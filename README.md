# Java

--sout then tab will print  System.out.println in Intellij

    ------ Java Primitive Types-----------
    int myAge = 30;
    int herAge = myAge;
    long viewsCount = 3_123_466_789L;
    float price = 10.99F;
    char letter = 'A';
    boolean isEligible = false;

    ------ Reference Types-----------
    Date now = new Date();
    //System.out.println(now);


------ Arrays-----------   
//Array Declaration - Type1
    int [] numbers = new int[5];
    numbers[0] = 10;
    numbers[1] = 15;
    System.out.println(Arrays.toString(numbers));

    //Array Declaration - Type2
    int [] myNumbers = {10,30,20};
    System.out.println(Arrays.toString(myNumbers));
    System.out.println(myNumbers.length);
    Arrays.sort(myNumbers);
    System.out.println(Arrays.toString(myNumbers));

// Multi-demensional array
     int[][] numbers = new int[2][3];
    numbers[0][1] = 5;
    System.out.println(Arrays.deepToString(numbers));

    int[][] myNumbers = { {1,2,3}, {4,5,6}};
    System.out.println(Arrays.deepToString(myNumbers));

----------- Constants(final vairable)------------
final float pi = 3.14F;
    System.out.println(pi);


------ Explicit casting--------
double x = 1.5;
    int y= (int)x+2;
    System.out.println(y); -- 3



    
