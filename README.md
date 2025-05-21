No JavaScript, XMLHTTPREQUEST é uma API utilizada para realizar requisições(buscar dados no servidor), HTTP 
de forma assíncrona que significa que o código é executado em paralelo sem bloquear a execução, funciona da seguinte forma: 
você cria um objeto, abre uma requisição, evia essa requisição e processa a resposta, não é mais tão utilizado por não ser
moderno nem fácil

FETCH tambem é uma API que realiza requisições HTTP de forma assícrona, é considerada mais moderna, fácil e usa promises,
funciona da seguinte forma: recebe a URL da informação a ser buscada e retorna uma promise, a promise retornada por fetch
pode ser resolvida ou rejeitada,você pode usar then ou async/await para processar a resposta da requisição e depois
acessar os dados da resposta como por exemplo, um JSON

PROMISES é um objeto que representa a conclusão ou falha (resultado) de uma operação assíncrona e  pode estar em três estados: 
pendente,resolvida ou rejeitada, tambem é considerada moderna e organizada e usa then para lidar com o valor de
resolvida da promise e catch para lidar com o motivo de falha da promise

ASYNC/AWAIT é a forma mais moderna e legível de lidar com códigos assíncronos, construída sobre o conceito de promises,
funciona da seguinte forma: async torna uma função assíncrona, colocando async na frente de uma função você pode usar await dentro dela
e essa função sempre retorna uma promise, await espera a promise terminar, pausa a execução da função até o valor estar pronto
e depois continua normalmente, por fim pega o resultado com JSON e mostra no console

Alunos: Gabriel Ferreira, Gabriel Republica, Ana Julia França, Clara Beatriz, Jeronimo.
