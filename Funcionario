package Heranca;


public class Funcionario extends Pessoa {
   public String cargo;
   public double salario;


   public void trabalhar() {
       System.out.println("O funcionário " + nome + " está trabalhando como " + cargo);
   }


   public void aumentarSalario(double percentual) {
       salario += salario * (percentual / 100);
   }


   @Override
   public void apresentar() {
       super.apresentar();
       System.out.println("Cargo: " + cargo + "\nSalário: " + salario);
   }


   @Override
   public String toString() {
       return "Funcionario{nome='" + nome + "', idade=" + idade +
               ", cargo='" + cargo + "', salario=" + salario + "}";
   }
}

