// Press Shift twice to open the Search Everywhere dialog and type `show whitespaces`,
// then press Enter. You can now see whitespace characters in your code.
public class Main {

    public static void main(String[] args) {
        // write your code here

        String diaSemana = "segunda-feira";

        switch (diaSemana) {
            case "segunda-feira":
                System.out.println("Hoje é segunda-feira");
                break;
            case "terça-feira":
                System.out.println("Hoje é terça-feira");
                break;
            case "quarta-feira":
                System.out.println("Hoje é quarta-feira");
                break;
            case "quinta-feira":
                System.out.println("Hoje é quinta-feira");
                break;
            case "sexta-feira":
                System.out.println("Hoje é sexta-feira");
                break;
            case "sábado":
                System.out.println("Hoje é sábado");
                break;
            case "domingo":
                System.out.println("Hoje é domingo");
                break;
            default:
                System.out.println("Dia da semana inválido");
        }
        }
    }
