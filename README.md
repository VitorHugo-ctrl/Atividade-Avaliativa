# Atividade-Avaliativa
Questão 1:
 letra d.

Questão 2:
letra a:

void main(){
int vitor=6;
int hugo=11;
String sobrenome='Soares';
print(vitor);
print(hugo);
print(sobrenome);
}

letra b:

void main(){
 positivo();
}
void positivo(){
  for(int i=1; i<=10; i++){
     print(i);
  }
}

letra c:

void main(){
int f=50;
positivo1(f);
}
void positivo1(int t){
  for(int i=1; i<=t; i++){
     print(i);
  }

letra d:

void main(){
 int g=4;
 Soma(g);
}
void Soma(int u){
  int som=0;
  for(int i=1; i<=u; i++){
    som=som+i;
  }
   print(som);
}

letra e:

void main(){
 Animal a=new Animal(2,'Elefante');
  print(a.idade);
  print(a.nome);
  a.latir();
  a.comer();
}
 
class Animal{
  int idade;
  String nome;
  Animal(int i, String n){
    this.idade=i;
    this.nome=n;
  }
  void latir(){
    print('Au Au!');
  }
  void comer(){
    print('Estou de barriga cheia!!');
  }
}
