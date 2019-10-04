
## Functional Interface and ~Lamb chops~ Lambda

Functional Interafce - Contains only ONE abstract method
  - Lambda Expressions represent instances of Functional Interface


@FunctionalInterface <---- Needs to have @ Function
        
        interface Square 
        { 
         int calculate(int x); 
        } 
  
        class Test 
         { 
          public static void main(String args[]) 
         { 
        int a = 5; 
  
        // lambda expression to define the calculate method 
        Square s = (int x)->x*x; 
  
        // parameter passed and return type must be 
        // same as defined in the prototype 
        int ans = s.calculate(a); 
        System.out.println(ans); 
         } 
        } ANSWER = 25
  
  3 Types
  * Predicate
      - Abstract method test returns Boolean values
   
  * Bionary Operator
      - Abstract method apply which takes 2 arguements and returns value of the same Type
   
 * Function
      - Abstract method apply which takes arguements of type T and returns type R
      
                public interface Function 
                {
                 public R apply(T t);
                }
