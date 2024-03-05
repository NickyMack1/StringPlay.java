# StringPlay.java

public class StringPlay
{
    public static void main (String[] args)
    {
        String college = "Leeds Beckett University";
        String town = "Anytown, UK"; // part (a)

        int stringLength;
        String change3;

        stringLength = college.length(); // part (b)

        System.out.println (college + " contains " + stringLength + " characters.");

        change3 = college.concat(town); // part (e)

        System.out.println ("The final string is " + change3);
    }
}
