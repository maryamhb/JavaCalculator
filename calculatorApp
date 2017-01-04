//CalculatorApp
//Maryam Habibollahi

import java.util.Scanner; //program uses Scanner

public class CalculatorApp {
    
    //global variables:
    static int x;
    static int y;
    static int m=10;
    static boolean k = false;
    
    
    public static void main(String args[]) {
        
        System.out.println("\n\nPlease choose one of the following:\n");

        while (m != 0) { //always goes back to menu
            
            System.out.println(" 1. Set numbers\n 2. Add numbers\n 3. Multiply numbers\n"); //menu
            
            Scanner scanIn = new Scanner(System.in); //creating a scanner
            m = scanIn.nextInt(); //take in the value
            
            
            //switch case for the three options:
            switch(m) {
                    
                case 1: //setNumbers
                    
                    Calculator num =new Calculator(); //create an object
                    
                    x = num.setFirst(); //call the method
                    y = num.setSecond();
                    
                    k = true; //to know numbers have been set
                    
                    break;
                    
                case 2: //addNumbers
                    
                    if(k) { //if numbers have been set
                        
                        //create an object and assign it to addtn
                        Calculator addtn = new Calculator();
                        
                        //call the method and print
                        System.out.println(x+"+"+y+" = "+ addtn.addNumbers(x,y) +"\n");
                    }
                    
                    else {
                        System.out.println("Set the numbers first\n");
                    }
                    
                    break;
                    
                case 3: //multiply numbers
                    
                    if(k) { //if numbers have been set
                        
                        //create an object and assign it to mltpctn
                        Calculator mltpctn = new Calculator();
                        
                        //call the method and print
                        System.out.println(x+"*"+y+" = " + mltpctn.multiplyNumbers(x,y)+"\n");
                    }
                    
                    else {
                        System.out.println("Set the numbers first\n");
                    }
            } //switch statement end
            
        } //while loop end
    } //main end
} //class end
