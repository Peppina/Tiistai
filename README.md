Tiistai
=======

Ohja3

import java.util.Scanner;
public class Lukija {
    
    private Scanner lukija;
    
    public Lukija(){
        this.lukija = new Scanner(System.in);
    }
    
    public String lueMerkkijono(){
        String merkkijono = lukija.nextLine();
        return merkkijono;
    }
    public int lueKokonaisluku() {
        int kokonaisluku = Integer.parseInt(lukija.nextLine());
        return kokonaisluku;
    }

    
}