# Variable_Arguments
public class VariableArguments {
    
    //static int sum(int a,int b){
      //  return a+b;
   // }
    
   // static int sum(int ...arr){
       // int result=0;
       // for(int a: arr){
       //     result += a;
      //  }
      //  return result;
   // }

     static int sum(int x,int ...arr){
        int result=0;
        for(int a:arr){
            result +=a;
        }
          return result; 
    }

    
    public static void main(String[] args) {
      //  System.out.println("The sum of 4 and 5 is:" + sum(4,5,6));
          //System.out.println("The sum of 4,5,6,7,8" +" " + sum(4,5,6,7,8));
          System.out.println("Sum of nothing is" + " " + sum(5));
          
        }
}
