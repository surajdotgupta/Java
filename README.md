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

-------- Arithmatic Operators-------------

    int result = Math.round(5.58F);
    //System.out.println(result); //6

    int findFloor = (int)Math.floor(5.58F);
    //System.out.println(findFloor); //5

    int findCeil = (int)Math.ceil(5.58F);
    //System.out.println(findCeil); //6

    int findMax = (int)Math.max(5,10);
    //System.out.println(findMax); //10

    double findRandom = Math.random();
    //System.out.println(findRandom); //0.9819413464234525

    int findRand = (int) Math.round(Math.random()*100);
    //System.out.println(findRand); //52

    int findRand1 = (int) (Math.random()*100);
    System.out.println(findRand1); //78


    ------ Number Format($$,%)----------------

     NumberFormat iCurrency = NumberFormat.getCurrencyInstance();
    String result = iCurrency.format(1234567.8965);
    System.out.println(result); //$1,234,567.90

    NumberFormat iPercent = NumberFormat.getPercentInstance();
    String pResult = iPercent.format(0.5);
    System.out.println(pResult); //50%


    ---------- Inputs------------

    // Byte inpit
    Scanner scanner = new Scanner(System.in);
    System.out.print("Enter your age:");
    byte age = scanner.nextByte();
    System.out.println("Your age is :" + age);
    
    Scanner scanner = new Scanner(System.in);
    System.out.print("Name: ");
    String name = scanner.nextLine();
    System.out.println("Your name is :" + name); //Your name is :suraj gupta

    
