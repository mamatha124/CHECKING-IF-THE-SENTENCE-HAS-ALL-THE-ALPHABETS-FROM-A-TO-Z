# CHECKING-IF-THE-SENTENCE-HAS-ALL-THE-ALPHABETS-FROM-A-TO-Z
import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        String s1="the quick brown fox jumps over lazy dog";
        s1=s1.toUpperCase();
        int n=s1.length();
        int k=0;
        char a[]=s1.toCharArray();
        for(int p=65;p<91;p++){
            char ch=(char)p;
            k=0;
        for(int i=0;i<n;i++){
            if(ch==a[i]||ch==32){
                k=1;
                break;
            }
        }
        if(k!=1){
            System.out.println("False");
            break;
        }
        }
        if (k==1){
            System.out.println("True");
        }
    }
}
