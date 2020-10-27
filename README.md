# Java Recap

## Basics
1.      Boolean, String, Integer, Double, Long 

2. 		String h = "Harald";
		if (h.equals("Harald")) {
			h = "Deutsch";
		}

3. 		 x ++ x
		 y - x
		 x * y
		 y / x
		 x % y
		 a && b
		 a || b
		 a ^ b
		 a | b

4. 		 if is a contition that decide one instance 
	     if ( i < 7)

		 Switch alaows to run to more decisions and stop if a compared value is found
		 Switch 
		 a 
		break

5. 		 While lopp ( Head controlled loop)
		 in this loop you can iterate until you get a decision. 
		 This loop runs at least one time.
		 while( a < b)
		 =============================================
		 Do loop ( bottom controled loop)
		 runs until the decision on the bottom of the loop
		 Do (
		 until 
		 a < b)
		 =============================================
		 for loop ( the counter loop)
		 runs from a defined point and counts true the values
		 for ( int i ; i < y ; i++)
		 =============================================
		 for each loop ( repeat the values )
		 for ( int a : b)

6. 
		 for ( int i; i < values; i ++ ) -> simple to count true values
		 while ( i <= 10)
		 i + = 1  ->	for counting you need more synthax 
		
		 for is better for countin
          
		 while is better to run to a decision

7.    ``` java
        void oneToThen() {
		for (int x= 0; x <= 10; x++) {
			System.out.println(x);		
	    }
	    }
        ```

## Methods

1.      To keep the code simple
		 to save time in coding
		 don`t repeat yourself if isn`t nesecary


2.
	 * public or private  -> to define if you can use the method from outside
	 * int  -> to define witch value should go back void for no returns
	 * meth -> name of the methode to recall them in the main method
	 * int val -> to recieve a value from outside in the methode
	 * return -> to give a value back to the main

3.      return of null, int, String, double, float,     long

4.  ``` java
        	public String str () {
		return "Harald";
	}
	public float fl() {
		return 22;
	}
	public double dou() {
		return 2.0;
	}
	public long lo() {
		return 999;
	}
    ```

## Arrays

1.      Array is a goup of values

2.      Yes arrays are dinamic

3.      Yes at most arrays have one to three            dimensions
		 but they can have even more then 3


4.       yes the size of a array have to be defined during   the initialization

5.      principle a array can contain every type of datas

7.    ```java
        int[] arr = new int{1,2,3,4}
        int[ arr = new int [3]
        ```
8.    ```java
        		int[] arr = new int[10];
		int[][] arrs =  new int[2][4];
		int min;
		
		int[] aray = {6,3,8,5,7,2,9};
		for (int g= 0; g < aray.length; g++) {

			for (int h = 0; h < aray.length - 1; h++) {
				if (aray[h] > aray[h + 1]) {
					min = aray[h];
					aray[h] = aray[h +1];
					aray[h + 1] = min;		
					
				}
			}
		}
        ```
9.  ```java
        		System.out.println(Arrays.toString(aray));	
		for (int k = 0; k < 2; k++) {
			for (int l= 0; l < 4; l++) {
				arrs[k][l] = k+l;
				System.out.print(arrs[k][l] +  " ");
			}
			System.out.println("");
		}
        ```

        
