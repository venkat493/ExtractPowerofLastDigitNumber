# ExtractPowerofLastDigitNumber
import java.util.Scanner;
 public class swap{
    public static void main(String[]args){
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        int lastdigit=printmatrix(a,b);
        System.out.print(lastdigit);
    }
    static int printmatrix(int a,int b){
        int ans=1;
        for(int i=1;i<=b;i++){
            ans=ans*a;
        }
        int lastdigit=(ans%10);
        return(lastdigit);
    }
    
 }
