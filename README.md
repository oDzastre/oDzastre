//saida
console.log('Hello world')
console.log('Hello world')
console.log("Hello world")


//Variaveis
var curso = 'javascript'
let nome = 'dzastre'
console.log(nome + ' esta fazendo curso de '+curso)


//Declarar
let sobrenome = undefined


sobrenome = 'vieira'


//tipos de dados
let numerointeiro = 10
let numerofloat = 10.0
let numerodouble = 10.0
let numerodecimal = 10.0


let caracter = 'c'
let texto = "texto"


let booleanos = false //false ou 0
let booleanos2 = true //true ou 1

let data = '2023-07-25 00:00:00' //Ano-mes-dia
//date, date, datetime, timestamp, time

//constantes
const PI = 3.14
//java = privete final double PI = 3.14;

//programação orientada objetos
//que é tranformar algo do mundo real
//em objeto computacional geralmente representado
//por classes

class Veiculo{
    constructor(marca, modelo, ano, chassi){
        this.marca = marca
        this.modelo = modelo
        this.ano = ano
        this.chassi = chassi
        

    }

    ligar(){
        console.log(`voce ligou o/a $(this.modelo)`)
    }

    desligar(){
        console.log(`voce desligou o/a $(this.modelo)`)
    }
}

let uno = new Veiculo('fiat','uno bala',2006,8778)
console.log(uno)


let carro = 'brasilia'
let marca = 'wolsvagem'
let ano = '1976'
let chassi = '1112'
let brasilia = new Veiculo(marca,carro,ano,chassi)
console.log(brasilia)

brasilia.ligar()
brasilia.desligar()

uno.ligar()
uno.desligar()

