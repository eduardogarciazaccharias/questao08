# questao08
int main(){
int vet[] = {4,9,13};
int i;                       **esta primeiro trecho imprime o conteudo de cada posição;
for(i=0;i<3;i++){
printf("%d ",*(vet+i));
}
}


int main(){
int vet[] = {4,9,13};
int i;                     **este segundo trecho imprime as posições de memória de cada conteudo; 
for(i=0;i<3;i++){
printf("%X ",vet+i);
}
}
