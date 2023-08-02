//Arrays
let arr = [0,1,2,3,4,5]
let arr2 = ['uva', 'maça','pera']
//let arr2 = [0, 1, 2]
let arr3 = ['Joâo',50,'Casado',3, true]
//Tuplas
let tup =(0,1,2,3,4,5)
let tup2 = ('gabiroba','gavirova','guabiroba','guavirova')
let tup3 = ("João", 45,'Casado',3, true )
//Dicionarios
let pessoa = {
    nome : 'João',
    idade : 45 ,
    estado_civil : 'Casado',
    filhos : 3,
    Registrado : true
}
console.log(pessoa)
let pessoa2 = {
    nome : 'João',
    idade : 45,
    estado_civil : 'Casado',
    filhos : 3,
    Registrado : true
}
console.log(pessoa2)

//Array
console.log(arr3[3])
arr3[0] = 'Jose'
arr3[1] = 25
arr3[2] = 'solteiro'
console.log(arr3)

//Laço de repetiçao
//Enquanto - while
//while quando não sei o tamanho dos dados
let indice = 0
let parar = true
while(indice < 100){
console.log(indice)
indice++
}
//Para ou Até ou Faça - for
//indice = i
for (let index = 0; index < arr3.length; index++) {
    const element = arr3[index];
    console.log(element)
}
//é possivel simplificar usando o forEach
arr3.forEach(element => console.log(element))

let arr4 = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
arr4.forEach(element => console.log(element))

const arr5 = arr4.map(x => x * 2)
console.log(arr5)

//Recapitulando
//Array = é uma coleçao de dados, varios tipos, e podem
//ser alterados conforme a necessidade
//voce pode consultar usando o indice, a partir de 0 ate
//o tamanho do array, e pode alterar tambem cada indice
//é definido pelo [] (colchetes)
//Unidirecional = [0]
let uni = [0, 1, 2]
//Bidirecional = [0][0]
let bid = [
    [0, 1, 2]
    [0, 1, 2]
]
//Tridimensional = [0][0][0]
let tri = [
    [
        [0, 1, 2],
        [0, 1, 3]
],
[
    [0, 1, 2],
    [0, 1, 3]
]]

//Array vazio
let vazio = []

vazio.push(1)//0
vazio.push(2)//1
vazio.push(3)//2
vazio.push(5)//3
vazio.push(7)//4
vazio.push(12)//5

console.log(vazio)
vazio.pop(3) //Remove o ultimo elemento
console.log(vazio)
vazio.shift() // Remove o primeiro elemento
console.log(vazio)

let p1 = {nome: 'Paula', Idade: 45, estado_civil: 'casada'}
let p2 = {nome: 'Ana', Idade: 40, estado_civil: 'casada'}
let p3 = {nome: 'Maria', Idade: 20, estado_civil: 'Solteira'}
//Quando eu quero acessar o tributo eu pego a variavel e
//chamo pelo nome
console.log(p2.nome)

let lista = [p1, p2, p3]
console.log(lista)
//Remover por indice e total de registros apos este indice
lista.splice(1,1)
console.log(lista)
