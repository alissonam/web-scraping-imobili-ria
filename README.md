# web-scraping-imobiliaria

Aqui vai uma breve descrição sobre o funcionamento do código...

Primeiramente realizamos as importações das libs e recursos que iremos utilizar no 1º bloco.

Após isso no 2º bloco realizamos a ponte(declaração do agent um parametro necessário para uso da rota web) que fará com que consigamos enviar e receber os dados atraves de nossa requisição.

Nos dois blocos(3 e 4) seguintes realizamos a lógica para pegar a ultima página tanto de aluguel como de vendas, para sabermos até onde nosso scraping irá pegar os dados.

O Bloco 5 e 6 declaram as funções de buscar e trazer os links dos imoveis que iremos analisar das respectivas urls que definimos(Venda e Aluguel).

O Bloco 7 chama uma das funções para extração dos links, no caso a de venda.

Bloco 8 é printada na tela os resultados dessa busca de links

Bloco 9 é somente para printar o tamanho de nosso array de links, para sabermos se a requisição dos dados será muito grande ou não.

Bloco 10 é um print para exemplo de um dos links armazenados em nossa variável que mantém os mesmos.

Bloco 11 até 13 é onde pegamos cada link e os tranformamos, requisitando os dados que cada um contém como, valor, tamanho do terreno, endereço, entre outros, como também já nos printa na tela o resultado de nossa extração de dados de um link especifico. 

Ao final, juntando todos esses blocos, podemos perceber que agora temos acesso a uma base de dados de uma imobiliária e com esses dados podemos fazer diversas coisas como: médias de preço, previsões de venda e aluguel, extração de dados de anunciantes do imóvel, entre outros.
