import java.util.*;

import javax.sql.rowset.spi.SyncResolver;
public class avg_function {
    public static float average(float a,float b,float c){
        float average= (a+b+c)/3;
        return average;

    }
    public static void main(String arg[]){
    Scanner sc= new Scanner(System.in);
    float a= sc.nextFloat();
    float b= sc.nextFloat();
    float c= sc.nextFloat();
    System.out.println("avg of a,b,c is:"+average(a,b,c));
    
}
}

