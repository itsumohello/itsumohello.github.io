public class BuiltInFunctions {

    public static void main(String[] args) {

        /**
         * Scenario 1
         * 
         * Find a built-in function that prints the message on the console.
         * @param message (String)
         */
        String message = "Hello, World!" ;
        ;

        System.out.print(message);
        // Write your code here


        /**
         * Scenario 2
         * 
         * Find a built-in function that returns the length of a string.
         * @return length (int)
         */
        String example = "Java";
        int length = example.length();
        System.out.println(length);
        // Write your code here


        /**
         * Scenario 3
         * 
         * Find a built-in function that converts a string to lowercase.
         * @return lowerCase (String)
         */
        String upperCase = "JAVA";
        String lowerCase = upperCase.toLowerCase();
        System.out.println(lowerCase);
        // Write your code here


        /**
         * Scenario 4
         * 
         * Find a built-in function that checks if a string starts with a specified prefix.
         * @param prefix (String)
         * @return startsWithPrefix (boolean)
         */
        String programming = "Java programming";
        boolean doesStarts = programming.startsWith("Java");
        System.out.println("does it starts with Java? " + doesStarts );

        // Write your code here



        /**
         * Scenario 5
         * 
         * Find a built-in function that replaces all occurrences of a specified character in a string with another character.
         * @param oldChar (char)
         * @param newChar (char)
         * @return replacedString (String)
         */
        String original = "Java is fun!";
        String newOrginal = original.replace('a','o');
        System.out.println(newOrginal);
        // Write your code here

        
        /**
         * Scenario 6
         * 
         * Find a built-in function that calculates the square root of a number.
         * @param number (double)
         * @return squareRoot (double)
         */
        
        double number = 9;
        double squareRoot = Math.sqrt(number);
        System.out.println(squareRoot);

        // Write your code here


        /**
         * Scenario 7
         * 
         * Find a built-in function that calculates the power of a number.
         * @param base (double)
         * @param exponent (double)
         * @return power (double)
         */
        double base = 2;
        double exponent = 3;
        double power = Math.pow(base,exponent);
        System.out.println(power);
        // System.out.printlin(Math.pow(base,exponent); 가 정답)
        // Write your code here


        /**
         * Scenario 8
         * 
         * Find a built-in function that generates a random number between 0.0 (inclusive) and 1.0 (exclusive).
         * @return randomNumber (double)
         */
        // Write your code here
        double randomNumber = Math.random();
        System.out.println(randomNumber);



        /**
         * Scenario 9
         * 
         * Find a built-in function that returns the larger of two numbers.
         * @param number1 (int)
         * @param number2 (int)
         * @return maxNumber (int)
         */
        int number1 = 5;
        int number2 = 10;
        // Write your code here
        System.out.println(Math.max(number1,number2));


    }
}
