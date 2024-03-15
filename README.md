import java.util.*;

public class main{
  public static void main(String[]args){
    Scanner sc=new Scanner(System.in);
    int num=sc.nextInt();
    int count=0;
    for(int i=1;i<=num;i++){
      if(num%i==0){
        count=count+1;
      }
    }
    if(count==2){
      System.out.println(num+"is a prime nunber");
    }
    else{
      System.out.println(num+"is not aprime number");
    }
  }
}
    
