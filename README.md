import java.util.*;
class beg
{
public static void main(String args[])
{
int a[]=new int[args.length];
Arrays.sort(a);
if(a>1)
{
String s=a.length();
System.out.print(Arrays.sort(s-1) +Arrays.sort(s));
}
else
{
System.out.print(0);
}
}
}
