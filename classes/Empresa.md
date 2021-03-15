**public** **class** Empresa {

   **int** soma;

   **double** media;

   String classificar;

   

   

   **public** **void** calculaMedia(**int** lista[]){

​      **for**(**int** i = 0; i <= lista.length-1; i++) {

​         soma += lista[i];

​      }

​      media = soma/lista.length-1;

   }

   

   **public** String classificarEmpresa(){

​      **if**(media < 10){

​         classificar = "Pequena";

​      }**else** **if**(media >= 10 && media <= 20){

​         classificar = "Media";

​      }**else** {

​         classificar = "Grande";

​      }

​      

​      **return** classificar;

   }

}