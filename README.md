# fileReader
import java.io.FileReader; 
public class PatikaDev { public static void main(String[] args) { 

try { FileReader input = new FileReader("input.txt"); 
int data = input.read(); while (data != -1) {

System.out.print((char) data);                
data = input.read();
}

input.close();
} catch (Exception e) {            
e.getStackTrace();

        }
    }
}


