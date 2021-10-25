# JS Functions

Atividade 6 - Tópicos em Computação

Considere o array a seguir:

//----------------------------------------------------------------------------------------------------------------------------------------------------------------

const funcionarios = [
{
id: 11,
nome: 'joao da silva',
cpf: '111.222.333-44',
categoria: 'tecnico'
},
{
id: 22,
nome: 'joana da silva',
cpf: '111.222.333-55',
categoria: 'tecnico'
},
{
id: 23,
nome: 'joana da Mata',
cpf: '111.222.333-66',
categoria: 'analista'
},
{
id: 24,
nome: 'joana da Mata',
cpf: '23456789-00',
categoria: 'gerente'
},
{
id: 45,
nome: 'joana da Mata',
cpf: '111222333-44',
categoria: 'gerente'
},
{
id: 36,
nome: 'joana da Mata',
cpf: '654321987-23',
categoria: 'gerente'
},
{
id: 27,
nome: 'joana da Mata',
cpf: '098876654-99',
categoria: 'gerente'
}
];

//----------------------------------------------------------------------------------------------------------------------------------------------------------------

Implemente e envie um código em JS usando Node.js que:

- 1º commit: Use o filter() para recuperar um array apenas com objetos da categoria 'gerente'
- 2º commit: Use o reduce() para retornar o objeto com o menor id
- 3º commit: Use o map() para colocar todos os nomes no formato UpperCase. 
