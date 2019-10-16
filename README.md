QUESTÃO 1

resposta= d;

QUESTÃO 2

#letra a)

void main() {

 int num1=10;
 
 int num2=12;
 
 String text='Aula de topicos especiais';
  
  print('o primeiro valor e $num1 o segundo valor e $num2 e o texto e $text');
}

letra b)

void numeros(){
  
  for(int i=1; i<=10;i++){
  
    print(i);
  }
  
}
void main(){
  
  numeros();
  
}

letra c)

void numeros(int a){
  
  for(int i=1; i<=a;i++){
  
    print(i);
  }
  
}
void main(){

  int num=50;
  
  numeros(num);
  
}

letra d)
 
int numeros(int a){

   int soma=0;
   
  for(int i=0;i<=a;i++){
  
    soma=soma+i;
  
  }
  print(soma);
  
 return soma; 
}

void main(){

  int num=10;
  
  numeros(num);
  
}

letra e)

class coelho{

  String nome; 
  
   String raca;
  
    coelho( String nome, String raca){
    
      this.nome=nome;
      
      this.raca=raca;
    }
  
  void pular(){
    
    print('O coelhinho $nome pulou!!');
  }
  
  void comer(){
    
    print('O coelinho $nome gosta de comer alface');
  }
  
}
void main(){

 coelho coelhinho= new coelho('fofo','nao definida');
 
  print('A raca do coelhinho e :');
  
  print(coelhinho.raca);
  
  print(coelhinho.nome);
  
  coelhinho.pular();
  
  coelhinho.comer();
}
