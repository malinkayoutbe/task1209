package com.javarush.task.task12.task1210;

/* 
Три метода возвращают максимальное из двух переданных в него чисел
*/

public class Solution {
    public static void main(String[] args) {
        
        int x = max(500,600);
        
        
        long g = max(1000,600);
        
        
        double n = max(5.8,600.7);
        
        
    }
     public static int max(int a, int b){
         
         int c = Math.max(a,b);
         return c;
     }
    
     public static long max(long a, long b){
         
         long c = Math.max(a,b);
         return c;
     }
    
     public static double max(double a, double b){
         
         double c = Math.max(a,b);
         return c;
     }
    
    
    //Напишите тут  ваши методы
}
