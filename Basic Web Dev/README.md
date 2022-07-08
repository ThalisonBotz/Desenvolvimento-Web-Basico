# Basic Web Developer
///////////////////////////////////////////////////////////////////////////////////////////////////////////////
# JAVASCRIPT

# Comentarios:
    "//" - Para comentar uma linha.
    "/*" - Para comentar até o fechamento "*/".
#

# Variaveis:
    "var" - Para variavel global.
    "let" - Para variavel no escopo.
    "const" - Para variavel constante, as mesmas não tem seus valores alterados.
    "bolean" - Para Variaveis do tipo boleano, as mesmas só retornam true ou false.
#

# Operadores:
    "+" - Adição.
    "-" - Subtração.
    "*" - Multiplicação.
    "**" - Exponenciação.
    "/" - Divisão.
    "%" - Resto da divisão.
    "++" - Aumentar.
    "--" - Diminuir.
#

# Operadores Logicos:
    == - Exatamente igual.
    != - Diferente.
    > - Maior que.
    < - Menor que.
    >= - Maior ou igual.
    <= - Menor ou igual.
    %% - And.
    || - Or.
#

# Funções:
    function test(){
        return a;
    }
#

# Objetos:
    var object = [{
        'nome':'Thalison',
        'idade':21,
        'profissão':'progamador'
    },
    {
        'nome':'Jõao',
        'idade':21,
        'profissão':'progamador'
    }];
#

# Condições:
    "if(Condição){Codigo}" - Se uma condição especificada for verdadeira.
    "else{Codigo}" - Se a mesma condição for falsa, faça outra coisa.
    "else if(Condição){Codigo}" - se a primeira condição for falsa, coloque outra etapa de validação.
    "switch(variavel){case 'conteudo': break;} " - Para especificar muitos blocos alternativos de código a serem executados.
#

# Laços de repetição:
    "while(Condição){Codigo}" - Usados para fazer laços menos precisos.
    "for(Condição){Codigo}" - Usado para fazer laços mais expecificos.
    "do{}while(Condição)" - Usado para que algo entre no laço antes de verificar a condição".
#

# Arreys:
    var nome = ['thalison','guilherme','joao'];

    Para acessar os dados dos arreys basta dizer a posição que está a variavel.
    console.log(nome[0])//thalison;

    É possivel alterar o conteudo do arrey
    nome[3] = "cleiton";

    Push é o comando pra empurrar outro conteudo dentro do arrey.
    nome.push("roberto");
#

///////////////////////////////////////////////////////////////////////////////////////////////////////////////
