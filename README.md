# -Explorando-o-Rest-Assured-Para-a-Automa-o-de-Testes-de-API
Explorando o Rest Assured Para a Automação de Testes de API-projeto
import java.util.Scanner;

public class Main {

  public static void main(String[] args) {
    final int SLICE = 4;

    Scanner scanner = new Scanner(System.in);

    int T = scanner.nextInt();

    while (T-->0) {
      int amigos = scanner.nextInt();
      int fatias = scanner.nextInt();

      if ((amigos * fatias) % SLICE == 0) {
        System.out.println((amigos * fatias) / SLICE);
      } else {
        System.out.println((amigos * fatias) / SLICE + 1);
      }
    }
  }
}
