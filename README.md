# Reverse-string-in-java
public class Revers {
    public static void main(String[] args)
    {
        String st="tata";
        int le=st.length();
        String re="";
        for(int i=le-1;i>=0;i--)
        {
            re=re+st.charAt(i);
        }
        System.out.println(re);
    }
    
}
