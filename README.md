# FP_guion5
struct FrecuenciaCaracter{
    char caracter;
    int frecuencia=0;
};

int main(){
    const int TAM=200;
    char v[TAM];
    FrecuenciaCaracter letra;

    do{
        letra.caracter=cin.get();
        if (letra.caracter!='#'){
            v[letra.frecuencia++]=letra.caracter;
        }
    }while (letra.caracter !='#' && letra.frecuencia<TAM);
    cout <<letra.frecuencia;


}
