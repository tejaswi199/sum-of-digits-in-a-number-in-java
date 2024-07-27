# sum-of-digits-in-a-number-in-java
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int c=0;
        int s=0;
        while(a>0){
            s=a%10;
            a=a/10;
            c=c+s;
            
        }
        System.out.println(c);
       
      
    }
}
