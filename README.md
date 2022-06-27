# calculo_media
média da quantidade de alunos inseridos pelo usuário em cada sala

public class media_alunos_vet{
    public static void main(String[] args){
        //Declara a variável i
        int i;
        //Declara a Array Q e atribuilo o tamanho 6
        double Q[] = new double[6]; 
        //Declarar os valores de cada 
        Q[0] = 35;
        Q[1] = 4;
        Q[2] = 22;
        Q[3] = 20;
        Q[4] = 36; 
        Q[5] = 30;
        Q[6] = 32;
        Q[7] = 40;
        // Calculo da média da sala
        double media = ((Q[0] + Q[1] + Q[2] + Q[3] + Q[4] + Q[5]) + Q[6] + Q[7] + Q[8] / 6);
        //Demonstra aos usuários a média de alunos da sala
        System.out.println("A media de alunos é: " + media);
        
        //Faz o uso da estrutura de repetição do For
        for (i=0; i<6; i++){
            //Condicional If para determinar as informações correspondentes
            if (Q[i] > media)
            //Demonstrar ao usuário qual a sala  que possui a quantia de alunos acima da média e também  o informando o número de alunos da sala
            System.out.println("A sala " + (i+1) + " tem " + Q[i] + " alunos e tem mais alunos do que a media");
        }

    }
}
