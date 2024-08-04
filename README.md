# Sorteador de Números
Este projeto é um sorteador de números simples desenvolvido em JavaScript. Ele permite ao usuário sortear uma quantidade específica de números dentro de um intervalo definido. A interface do usuário é construída em HTML e estilizada com CSS.

## Funcionalidades
- Sorteio de números aleatórios dentro de um intervalo definido pelo usuário.
- Prevenção de números duplicados no sorteio.
- Interface intuitiva com campos de entrada para definir a quantidade de números a serem sorteados e o intervalo.
- Botão para reiniciar o sorteio e limpar os campos de entrada e resultados.
## Estrutura do Projeto
### Arquivos Principais
- index.html: Contém a estrutura HTML da aplicação.
- style.css: Contém os estilos CSS para a interface do usuário.
- app.js: Contém a lógica JavaScript para o sorteio de números.
### HTML (index.html)
A estrutura HTML inclui:

- Campos de entrada para a quantidade de números a serem sorteados e o intervalo (de e até).
- Botões para iniciar o sorteio e reiniciar o formulário.
- Área para exibir os resultados do sorteio.
### CSS (style.css)
O arquivo CSS define os estilos para os elementos da interface, incluindo os campos de entrada, botões e a área de resultados.

### JavaScript (app.js)
O arquivo JavaScript contém as seguintes funções:

- sortear(): Realiza o sorteio dos números, garantindo que não haja números duplicados, e exibe os resultados.
- obterNumerosAleatorios(min, max): Gera um número aleatório entre os valores min e max.
- alterarStatusBotao(): Alterna o estado do botão de reinício entre habilitado e desabilitado.
- reiniciar(): Limpa os campos de entrada e os resultados, e redefine o estado do botão de reinício.
## Como Usar
1. Abra o arquivo index.html em um navegador.
2. Insira a quantidade de números a serem sorteados no campo "Quantidade de números".
3. Defina o intervalo inserindo os valores nos campos "Do número" e "Até o número".
4. Clique no botão "Sortear" para gerar os números aleatórios.
5. Para realizar um novo sorteio, clique no botão "Reiniciar" para limpar os campos e os resultados.
## Exemplo de Uso
Se você inserir 5 no campo "Quantidade de números", 1 no campo "Do número" e 10 no campo "Até o número", ao clicar em "Sortear", cinco números aleatórios entre 1 e 10 serão exibidos, sem repetição.

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para fazer um fork deste repositório e enviar pull requests.
