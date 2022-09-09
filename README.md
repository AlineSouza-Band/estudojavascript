# estudojavascript

//Definição de variaveis e seus tipos
let meuTexto = "Meu texto"
let meuNumero = 200
let meuBooleano = true 
let meuObjeto = {
    nome: "Aline",
    idade:46
}

let meuArray = [meuTexto, meuNumero,meuBooleano,meuObjeto]



// 


function soma(numero1, numero2) {


return numero1 + numero2 

}

let subtracao = function(numero1, numero2) {
    return numero1 - numero2

}

const multiplica = (numero1,numero2) => {
    return numero1 * numero2

}



(() => {
    console.log("Mensagem")

})()

let veiculo = {
    marca: "toyota",
    modelo: "Etios",
    cor: "preto",
    placa: "ABC0910",
    potencia: 107,
    anda: function() {
        console.log("veiculo em movimento")
    }
}

veiculo.anda()
