var lado = prompt("Digite o lado do quadro em cm")
var perimetro = lado * 4

alert("O perimetro do quadro é:" + perimetro + "cm")

// num: 4

var numero = prompt("Digite um número")
var quadrado = 

// num 5

var horas = prompt("Digite um valor em horas")

// num 6

var idade = prompt("Digite um numero")

if (idade <= 10) {
  alert("Você é uma criança.")
} else if (idade <= 15) {
  alert("Você é adolescente")
} else if (idade <= 18) {
  alert("Você é jovem")
  
// Escreva um programa que receba a velocidade do carro em km/h e calcule a multa recebida pelo motorista. A regra é a segunte, o limite da via é 60 km/h, para cada km excedido o motorista irá receber R$ 3,99 de multa.

const MAXIMO_VIA = 60
const MULTA_POR_KM_EXCEDENTE = 3.99

var velocidade = prompt("Digite um valor em km/h")
var excedente = velocidade - MAXIMO_VIA
var multa = excedente * MULTA_POR_KM_EXCEDENTE

if (velocidade > MAXIMO_VIA) {
  alert("O valor da sua multa é: " + multa.toFixed(2))
} else {
  alert("Você não teve multa")
}

// Escreva um programa que receba a quantidade de litros que um motorista abasteceu o carro dele e calcule o valor que ele irá pagar. Ele poderá escolher entre álcool e gasolina. O valor do álcool é R$ 4,01 por litro e o valor da gasolina é R$ 5,99 por litro.

const LITRO_GASOLINA = 5.99
const LITRO_ALCOOL = 4.01

var combustível = prompt("Digite o tipo de combustível. [1] para gasolina, [2] para alcool:")
var litros = prompt("Digite a quantidade de litros desejada: ")
var valor = 0

if (combustivel == 1) {
  valor = litros * LITRO_GASOLINA
} else if (combustivel == 2){
} else {
  alert ("Você não digitou um tipo válido")
}

// Escreva um programa que receba dois valores. Após isso, o usuário deverá escolher se deseja somar, subtrair, dividir ou multiplicar esses valores. O resultado final deverá ser exibido.

var valor1 = parFloat(prompt("Digite um valor: "))
var valor2 = parFloat(prompt("Digite um valor: "))

var operacao = prompt("Digite a operação que você deseja realizar: [1] para soma, [2] para subtração, [3] para multiplicação, [4] para divisão")
