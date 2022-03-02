# Desafios-B-sicos---GFT-Start-4-Java---O-Filme

import java.io.IOException;
import java.util.Scanner;

public class Film {
  public static void main(String[] args) throws IOException {
  	Scanner leitor = new Scanner(System.in);
  	double A = leitor.nextDouble();
  	double B = leitor.nextDouble();
  	double diff = ((B-A)/A)*100;
  	System.out.printf("%.2f%%\n",diff);
  	leitor.close();
  }
}
