import java.util.*;
public class Main{
     public static void main(String []args){
        Scanner ms=new Scanner(System.in);
        System.out.println("Number of items in the cart");
        int a=ms.nextInt();
        if(a==0)
        System.out.println("cart is empty");
        else{
            int arr[]=new int[a];
            int bill=0;
            System.out.println("Enter price for each item");
            for(int i=0;i<a;i++){
                arr[i]=ms.nextInt();
                bill+=arr[i];
              
            }
            System.out.println("Your total bill is: " + bill);
        }
     }
}
