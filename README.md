# Exercicio-de-logica
Programa que calcule o status de aprovação do aluno 


Problema: 
Crie um programa que calcule o status de aprovação do aluno a partir da nota dele. O código deve seguir as instruções:
    • nota menor que 4: ele está reprovado;
    • nota menor que 7: ele está em recuperação;
    • nota maior que 7: ele está aprovado.


    Algoritmo 
    
    // Entrada da nota do aluno
    Escreva("Digite a nota do aluno: ")
    Leia(nota)

    // Verificação do status de aprovação
    Se nota < 4 Então
        Escreva("O aluno está reprovado.")
    Senão Se nota < 7 Então
        Escreva("O aluno está em recuperação.")
    Senão
        Escreva("O aluno está aprovado.")
    Fim Se

Fim Algoritmo
