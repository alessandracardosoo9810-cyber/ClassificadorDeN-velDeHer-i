# Classificador De Nível de Herói
Desafio Felipão DIO
// Oque deve ser utilizado:
//variáveis, operadores, laços de repetição e estruturas de decisão
// Objetivo:
// Crie uma variável para armazenar o nome e a quantidade de experiência
// desse herói (XP), depois utilize uma estrutura de decisão para apresentar
// alguma das mensagens abaixo:
// Se for menor que 1.000 = Ferro
// Se for entre 1.001 e 2.000 = Bronze
// Se for entre 2.001 e 5.000 = Prata
// Se for entre 5.001 e 7.000 = Ouro
// Se for entre 7.001 e 8.000 = Platina
// Se for entre 8.001 e 9.000 = Ascendente
// Se for entre 9.001 e 10.000 = Imortal
// Se XP for maior ou igual a 10.001 = Radiante
// Saída:
// Ao final deve ser exibir uma mensagem:]
// "O Herói de nome "(nome)" está no nível de "(nível)"

let nomeDoHeroi = "Alê";
let xp = 8500; // Altere o valor para testar outros níveis
let nivel = "";

// Estrutura de decisão para determinar o nível
if (xp < 1000) {
    nivel = "Ferro";
} else if (xp >= 1001 && xp <= 2000) {
    nivel = "Bronze";
} else if (xp >= 2001 && xp <= 5000) {
    nivel = "Prata";
} else if (xp >= 5001 && xp <= 7000) {
    nivel = "Ouro";
} else if (xp >= 7001 && xp <= 8000) {
    nivel = "Platina";
} else if (xp >= 8001 && xp <= 9000) {
    nivel = "Ascendente";
} else if (xp >= 9001 && xp <= 10000) {
    nivel = "Imortal";
} else {
    nivel = "Radiante";
}

console.log("O Herói de nome " + nomeDoHeroi + " está no nível de " + nivel);

