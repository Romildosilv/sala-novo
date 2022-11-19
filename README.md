# sala-novo
Novo salário 
#include<stdio.h>
int i=0,n;
float sal,aum;



int main(){
	printf("quantos func voce quer verificar: ");
	scanf("%d",&n);
	while(i<n){
printf("\ndigite o seu salario: ");
scanf("%f",&sal);
	if(sal<1000){
	aum=sal*0.30;
	printf("\no aumento do salario e de 30 porcento e o valor final e de: %.2f",sal+aum);
}
	else{
	printf("\n funcionario nao tem direito ao aumento");
	}
i++;
}

return 0;
}
