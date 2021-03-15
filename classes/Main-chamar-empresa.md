**import** java.util.Scanner;

 

**public** **class** ChamarEmpresa {

 

   **public** **static** **void** main(String[] args) {

​            

​      Empresa e = **new** Empresa();

​      **int**[] lista = **new** **int** [10];

​      Scanner leitor = **new** Scanner(System.***in\***);

​      **int** i = 0;

​      

​      //preencher o array com os valores fornecido pelo usuário

​      **while**(i < lista.length-1){

​         System.out.println("Digite o valor da média de vendas da empresa.");

​         lista[i] = leitor.nextInt();

​         i++;       

​      }

​      

​      e.calculaMedia(lista);

​      

​      System.out.println("Empresa é classificar como:" + e.classificarEmpresa());

   }   

 

}