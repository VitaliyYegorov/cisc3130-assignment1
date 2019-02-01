/******************************************************************************
 *  _Example commands for running this file_
 *  Compilation:  javac Assignment1.java
 *  Execution:    java Assignment1 < input.txt
 *
 *  Reads in a text file and for each line verifies whether the word has
 *  unique characters.
 *
 *  % cat input.txt
 *  Hello
 *  World
 *
 *  % java Assignment1 < input.txt
 *  False
 *  True
 *
 ******************************************************************************/
 
import java.util.*;

public class SortInput {

    private static boolean isUniqueChar(String s){
        // Fill this part out
        System.out.println(true);
        return true;
    }

    private static String sortWord(String s){
        char[] c = s.toCharArray();
        insertionSort(c);
        return "";
    }

    public static void insertionSort(char[] word) {
        if (word == null || word.length == 0)
            return;
        for (int i=0; i<word.length; i++) {
            char temp = word[i];
            int j = i;
            while (j>0 && word[j-1]>temp) {
                word[j] = word[j-1];
                j--;
            }
            word[j] = temp;
        }
        return;
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // read in words and determine whether it is composed of unique characters
        while (scanner.hasNextLine()) {
            String s = scanner.nextLine();
            isUniqueChar(s);
            sortWord(s);
        }

      scanner.close();
    }
}
