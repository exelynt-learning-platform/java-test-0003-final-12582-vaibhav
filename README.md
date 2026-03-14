# java-test-0003-final-12582-vaibhav
Final Project Assignment - This repository contains the complete final project code and documentation.

class Pattern {
    
    public static void main(String args[])
    {
        int n = 6;

        for(int i = 1; i <= n; i++)
        {
            for(int j = 0;j<i;j++)
            {
                System.out.print((i+j)%2 + " ");
            }
            System.out.println();
        }
    }

}
