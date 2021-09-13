# Haywood-cop3330-ex01
/*
 *  UCF COP3330 Fall 2021 Assignment 1 Solution
 *  Copyright 2021 Kaylah Haywood
 *  Exercise 1 - Saying Hello
 */

package stringvars;
import java.util.scanner;

public class StringVariables {
  public static void main(String[] args) {
  
    Scanner user_input = new Scanner(System.in);
    System.out.print("What is your name? ");
    first_name = user_input.next();
    
    String user_name;
    user_name = first_name;
    
    System.out.println("Hello " + user_name + nice to meet you);
  }
}
