import javax.swing.JOptionPane;

public class SistemaAvaliacao {
    public static void main(String[] args) {
        // Receber as notas das provas e do trabalho
        String notaProva1Input = JOptionPane.showInputDialog(null, "Digite a nota da primeira prova:");
        double notaProva1 = Double.parseDouble(notaProva1Input);

        String notaProva2Input = JOptionPane.showInputDialog(null, "Digite a nota da segunda prova:");
        double notaProva2 = Double.parseDouble(notaProva2Input);

        String notaTrabalhoInput = JOptionPane.showInputDialog(null, "Digite a nota do trabalho:");
        double notaTrabalho = Double.parseDouble(notaTrabalhoInput);

        // Calcular a média
        double media = (notaProva1 + notaProva2 + notaTrabalho) / 3;

        // Verificar se o aluno está aprovado ou reprovado
        String mensagem;
        if (media >= 6) {
            mensagem = "Aprovado! Média: " + media;
        } else {
            mensagem = "Reprovado! Média: " + media;
        }

        // Exibir o resultado usando JOptionPane
        JOptionPane.showMessageDialog(null, mensagem);
    }
}
