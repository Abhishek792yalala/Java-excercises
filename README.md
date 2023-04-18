# Java-excercisesimport java.util.*;

class Java {

    public static void main(String... args) {

        System.out.println('\n'+ "*******************");

        System.out.println("Multiplication table of k");

        int k=5; int add=0;

        for(int t=1;t<=10;t++){

            System.out.printf('\n'+ "%dX%d=%d", k, t,k*t);

        }

        System.out.println('\n'+ "Sum of 5 multiplication table : ");

        for(int s=1;s<=10;s++){

            add+=(k*s);

        }

        System.out.println(add);

        System.out.println('\n'+ "*******************");

        System.out.println("Sum of first n even numbers");

        int n1=2; int sum=0;

        for(int i3=1; i3<=n1;i3++){

            sum=sum+(2*i3);

        }

        System.out.print("The sum of first n even numbers is : "+ sum);

        System.out.println('\n'+ "*******************");

        System.out.println('\n'+"Printing the patterns");

        int i1,j,n=6;

        for(i1=0; i1<n;i1++) {

            for (j=0; j<=i1; j++) {

                System.out.print('*');

            }

            System.out.println(" ");

        }

        System.out.println('\n'+ "*******************");

        for(int i2=n; i2>0; i2--){

            for(int j2=0; j2<i2; j2++){

                System.out.print('*');

            }

            System.out.println(" ");

        }

        System.out.println('\n'+ "*******************");

        int age;

        System.out.println("Please enter your age: ");

        Scanner s=new Scanner(System.in);

        byte r=s.nextByte();

        switch(r){

            case 18:

                System.out.println("You are eligible to register for the vote");

                break;

            case 21:

                System.out.println("You are eligible to marriage");

                break;

            case 65:

                System.out.println("You are eligible to register for pension");

                break;

            default:

                System.out.println("No data found regarding your age"+'\n'+" Please try on another portal" );

        }

        System.out.println('\n'+ "*******************");

        int i = 10;

        int a=12;

        int b=122;

        boolean a1=true;

        boolean a2=true;

        if(a1 && a2){

            System.out.println("correct");

        }

        else{

            System.out.println("incorrect");

        }

        System.out.printf("The value of a is %d and b is %d ", a, b);

        String name="Abhishek Yalala";

        System.out.println(name.replace('A','Y'));

        System.out.println(name.toLowerCase());

        System.out.println(name.substring(9, 15));

        System.out.println(name.substring(4));

        System.out.println(name.endsWith("la"));

        System.out.println(name.startsWith("Ab"));

        System.out.println(name.lastIndexOf('a'));

        System.out.println(name.indexOf('k'));

        System.out.println(name.equals("Abhishek Yalala"));

        System.out.println(name.equals("abhishek yalala"));

        while (true) {

            System.out.println('\n'+"Enter the number: ");

            Double d = s.nextDouble();

            if (d < i) {

                System.out.println("The number you entered is less than the required ");

            } else if (d > i) {

                System.out.println("The number you entered is more than the required ");

            } else {

                System.out.println("The number you entered matches the value");

                break;

            }

        }

    }

}

/* "C:\Users\user 33\.jdks\openjdk-20\bin\java.exe" "-javaagent:C:\Users\user 33\AppData\Local\JetBrains\IntelliJ IDEA Community Edition 2023.1\lib\idea_rt.jar=50272:C:\Users\user 33\AppData\Local\JetBrains\IntelliJ IDEA Community Edition 2023.1\bin" -Dfile.encoding=UTF-8 -Dsun.stdout.encoding=UTF-8 -Dsun.stderr.encoding=UTF-8 -classpath "C:\Users\user 33\IdeaProjects\Java\out\production\Java" Java

*******************

Multiplication table of k

5X1=5

5X2=10

5X3=15

5X4=20

5X5=25

5X6=30

5X7=35

5X8=40

5X9=45

5X10=50

Sum of 5 multiplication table : 

275

*******************

Sum of first n even numbers

The sum of first n even numbers is : 6

*******************

Printing the patterns

* 

** 

*** 

**** 

***** 

****** 

*******************

****** 

***** 

**** 

*** 

** 

* 

*******************

Please enter your age: 

21

You are eligible to marriage

*******************

correct

The value of a is 12 and b is 122 Ybhishek Yalala

abhishek yalala

Yalala

shek Yalala

true

true

14

7

true

false

Enter the number: 

12

The number you entered is more than the required 

Enter the number: 

10

The number you entered matches the value

Process finished with exit code 0

*/
