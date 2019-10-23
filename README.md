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

# Atividade de 4 Pontos:
void main() {
 double din=200;
 double saldo=0;
 double v=100;
 Banco b=new Banco(123,'Pessoa Física','Vitor',a:333);
 b.Criaconta();
 b.Deposito(v);
 double r=b.Saldoat(v,saldo);
 print('O saldo atual é de: $r reais!');
 double u=b.Transferencia(r,din);
 print('O seu novo saldo após a Transferência é de: $u reais!');
 }
class Banco{
  int nconta;
  String tipo;
  String nome;
  int ag;
  Banco(int n,String t, String no, {int a}){
    this.nconta=n;
    this.tipo=t;
    this.nome=no;
    this.ag=a;
  }
  void Criaconta(){
    print('$nome sua conta foi criada!');
  }
  void Deposito(double valor){
       print('$nome você recebeu o valor de: $valor reais de um deposito em sua conta!');
  }
  double Saldoat(double f,double valor)=>valor+f;
  double Transferencia(double s,double t){
   if(s>0){
      print('$nome você recebeu uma transferência de $t reais!');
      return s+t;
   }
    else{
      print('Transferência inválida, pois sua conta está sem saldo!');
      return 0;
    }
  
  }
}


