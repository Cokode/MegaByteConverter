# MegaByteConverter
This is a coding exercise from a Java Master Class course I am taking that is supposed to print out "MB and KB" of any value inputed into int parameter called  kiloBytes when the method() is called. It was tough at first but I was able to crack it down after few hours of On and Off as I prepare our Xmass meal.  winks* 


public class MegaBytesConverter {

    public static void printMegaBytesAndKiloBytes(int kiloBytes) {

        if (kiloBytes < 0) {
            System.out.println("Invalid Value");
        } else {
            long megaBytes = (int) (kiloBytes * 0.0009765625);
            long remainder = Math.round(kiloBytes * 0.0009765625 % megaBytes);
            System.out.println(kiloBytes + " KB = " + megaBytes + " MB " + "and " + remainder + " KB");
        }
    }

    public static void main(String[] args) {
        MegaBytesConverter.printMegaBytesAndKiloBytes(2050);
    }
}

<img width="899" alt="Screenshot 2021-12-23 at 3 17 04 PM" src="https://user-images.githubusercontent.com/96517341/147259793-eb21839b-94dc-44d1-bd60-ab66200968c7.png">

<img width="793" alt="Screenshot 2021-12-23 at 3 19 45 PM" src="https://user-images.githubusercontent.com/96517341/147260625-1330132b-f34c-4b66-a95b-832a66f06333.png">
