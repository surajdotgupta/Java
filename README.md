# Java

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


    
