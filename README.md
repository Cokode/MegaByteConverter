# MegaByteConverter
This is a coding exercise from a Java Master Class course I am taking that is supposed to print out "MB and KB" of any value inputed into int parameter called  kiloBytes when the method() is called. It was tough at first but I was able to crack it down after few hours of On and Off as I prepare our Xmass meal.  winks* 


public class MegaBytesConverter {

    public static void printMegaBytesAndKiloBytes(int kiloBytes) {

        if (kiloBytes < 0) {
            System.out.println("Invalid Value");
        } else {
            long megaBytes = kiloBytes / 1024;
            long remainder = Math.round(kiloBytes % 1024);
            System.out.println(kiloBytes + " KB = " + megaBytes + " MB " + "and " + remainder + " KB");
        }
    }
}

    public static void main(String[] args) {
        MegaBytesConverter.printMegaBytesAndKiloBytes(2050);
    }
}


<img width="1280" alt="Screenshot 2021-12-23 at 3 35 13 PM" src="https://user-images.githubusercontent.com/96517341/147262233-399c203e-b76b-49e3-92cf-dd6fdef22f86.png">
<img width="1279" alt="Screenshot 2021-12-23 at 3 37 08 PM" src="https://user-images.githubusercontent.com/96517341/147262250-b18415a3-7607-4a4b-be77-e43f7988db04.png">


