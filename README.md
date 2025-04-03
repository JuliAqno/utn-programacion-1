#include <stdio.h>

int main() {
	int n,resultado;
	printf("ingrese un numero: ");
	scanf("%d",&n);
	resultado=1;
	for ( int i=1; i<=n; i++){
		resultado=resultado*i;
	};
	printf(" \nel factorial de %d es %d",n,resultado);
	return 0;
}
