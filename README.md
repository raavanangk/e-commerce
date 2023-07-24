public class StringReverse{
public static String stringReverse(String name){
StringBuilder reversedstring =new StringBuilder(name).reverse();
return reversedstring.toString();
}

public static void main(String[]args){
String name ="gokulavasan";
String reversedstring=stringReverse(name);
System.out.println("orignialname :"+name);
System.out.println("reversed name :"+reversedstring);
}}

//////////////////////////////////////////////
public class ReverseNumber{
public static void main (String[]args){
int reversednumber=0;
Scanner scanner=new Scanner(System.in);
int number =scanner.nextInt();
System.out.println("ENTER THE NUMBER TO REVERSE :");
while(number!=0){
int lastdigit=number%10; // extract the last digit
reversednumber =reversednumber*10+lastdigit;
//lastdigit append with the reversed number
number /=10;
}
System.out.println("reversed number is :"+reversednumber);
}
//////////////////////////////////////////////////////////////

public class reversestring{
public static void main(String[]args){
Scanner scanner =new Scanner(System.in);
String inputstring=scanner.nextLine();
System.out.println("enter the string :");
String reversed="";
for(int i=0;i<inputstring.length();i++){
reversed =inputstring.charAt(i)+reversed;
}
System.out.println("reversedstring:"+reversed);




//String palindrome or not
public class reversestring{
public static void main(String[]args){
Scanner scanner =new Scanner(System.in);
String inputstring=scanner.nextLine();
System.out.println("enter the string :");
String reversed="";
for (int i=inputstring.length()-1;i>=0;i--){
reversed += inputstring.charAt(i);
}
If(inputstring.equals(reversed)){
System.out.println("Is palindrome");
}else{
System.out.println("is not a palindrome");
}
}
****//////////////////////////////////////////////////
// Reverse the word in a string
import java.util.Scanner;
public class reversewords{
public static void main (String [] args){
Scanner scanner= new Scanner(System.in);
String input = scanner.nextLine();
System.out.println("enter the words:");
String [] words=input.split(" ");
String reversed= "";
for(int i=words.length-1;i>=0;i--){
reversed+=words[i]+" ";
}
System.out.println(" reversed :"+reversed);
}

++++++++++±++++++++++++++++++±+++++±++++±+±———



