Algoritmo "semnome"

Tipo Pessoa = Registro
  nome : caracter
  idade : inteiro
  peso : real
Fimregistro

Var
   paciente : vetor[1..5] de Pessoa
Inicio
    paciente[1].nome <- "João"
    paciente[1].idade <- 35
    paciente[1].peso <- 85
    
    Escreval("Paciente na posição 1 é :",paciente[1].nome)
    Escreval("Peso :", paciente[1].peso)
    Escreval("A idade é :", paciente[1].idade)
    
Fimalgoritmo
