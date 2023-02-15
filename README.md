# basic_java_question

#Basic Java Program

#### calculate the sum of first N natural numbers.
```
static int printSum(int N){
        //sum= sum +i
		int sum=0;
		for(int i =0 ; i<= N; i++){
			sum = sum + i;
		}
		return sum;
    }

```
#### To check the number is even or odd
```
//this will return output in boolean

	 public static boolean evenodd(int num) {
         if(num%2==0){
             return true;
         }
     return false;
    }

```
####  Check the sum of a cubed of two binomial is valid or not
```
// (a+b)^3 = a^3 + b^3 + 3a^2b + 3ab^2.

 public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
        long a = sc.nextLong();
        long b = sc.nextLong();
        sc.close();
        long LHS = (a + b) * (a + b) * (a + b);
        long RHS = (a * a * a) + (b * b * b) + (3 * a * b * b) + (3 * a * a * b);
        System.out.println(lhs);
        System.out.println(rhs);
        if (LHS == RHS)
            System.out.println("valid");
        else
            System.out.println("not valid");
 }

```

