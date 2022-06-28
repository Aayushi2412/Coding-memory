# Coding-memory
// Best Time to Buy and Sell Stock
/*
Problem Statement
You are given an array/list 'prices' where the elements of the array represent the prices of the stock as they were yesterday and indices of the array represent minutes. Your task is to find and return the maximum profit you can make by buying and selling the stock. You can buy and sell the stock only once.
*/



import java.util.* ;
import java.io.*; 
import java.util.ArrayList;

public class Solution{
    public static int maximumProfit(ArrayList<Integer> prices){
        // Write your code here.
        
        int max=0,Pmin=prices.get(0);
        for(int i=1;i<prices.size();i++)
        {
            if(Pmin<prices.get(i))
                max=Math.max(prices.get(i)-Pmin,max);
            else
                Pmin=prices.get(i);
        }
        return max;
    }
}
