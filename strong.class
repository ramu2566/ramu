public class Strong
{
public static long factorial(int n)
{
if (n == 0 || n == 1)
{
return 1;
}
long fact = 1;
for (int i = 2; i <= n; i++)
{
fact *= i;
}
return fact;
}
public static boolean isStrong(int num) {
int originalNum = num;
long sumOfFactorials = 0;
while (num > 0)
{
int digit = num % 10;
sumOfFactorials += factorial(digit);
num /= 10;
}
return sumOfFactorials == originalNum;
}
public static void main(String[] args) {
System.out.println("Strong numbers from 1 to 5000:");
for (int i = 1; i <= 5000; i++)
{
if (isStrong(i)) {
System.out.println(i);
}
}
}
}