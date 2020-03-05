package com.company;

public class Main {

    public static void main(String[] args) {



int neOkudu = authorsAndLiterature( "fethi", 100, 3, 4, 6,1,
                                     5,9,2,1);
sonuc("fethi", neOkudu);

authorsAndLiterature("hilal", 15,13,15,17,12,
        37,8,22,16);
sonuc ( "hilal" , neOkudu);







    }


    public static void sonuc  (String student, int whatLiterature) {

        System.out.println(student + " en cok " + whatLiterature + " okudu.");


    }

    public static int authorsAndLiterature (String student, int dostoyevski , int tolstoy, int gogol,
                                              int saitFaik, int sabahttinAli , int peyamiSafa,
                                              int coelho, int neruda, int marquez) {

       int russian = dostoyevski + tolstoy + gogol;
        int turkish = saitFaik + sabahttinAli + peyamiSafa;
        int latin = coelho + neruda + marquez;

        if ((russian >= turkish) && (russian >= latin) ) {
            return russian;
        } else if ( ( latin >= turkish) && (latin > russian)){
            return latin;
        } else if (( turkish > russian) && (turkish > latin)) {
            return turkish;
        } else {
            return -1;

        }


    }



    }





