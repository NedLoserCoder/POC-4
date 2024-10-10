# POC-4
## Sistemas de Informação, 02J L12
### Andreas Caycedo Martinez, 10435302
### Caio Takehiro Magnoli Igari, 10437809

Nesta POC, aplicamos o conceito de APIs, utilizando o método Fetch, para buscar a imagem de um gato. Aqui estão os detalhes do projeto:

- Endpoint
  
  Conforme dito acima, queremos a imagem de um gato, então utilizamos este endpoint para o consumo da API: https://api.thecatapi.com/v1/images/search

- Código HTML
  
  ![image](https://github.com/user-attachments/assets/6aa38815-9763-4bf2-8f07-d14867dd10fa)
  
  É uma estrutura típica de um código HTML, com seus respectivos links para os códigos CSS e JS, IDs e classes. Estrutura uma página visualmente simples. A imagem que provém da API   estará oculta até o usuário clicar no link, assim como uma mensagem de erro caso a API não funcione.

- Código CSS
  
  ![image](https://github.com/user-attachments/assets/b7a7f8c4-b31e-4883-a6dc-7a2f5de22fd5)
  
  A estilização é simples e prática, tendo em vista os poucos elementos em tela. Visa deixar o conteúdo centralizado e acessível, além do formato da imagem quando ela aparecer.

- Código Javascript
  
  ![image](https://github.com/user-attachments/assets/ae420aa1-adc1-42e7-8967-a6c9291cfd7a)
  
  E é aqui onde está o tal método Fetch, contida na função buscarGatoIMG, que por sua vez faz uma requisição assíncrona para a API de imagens de gatos. Ela retorna o URL da imagem    se a requisição for bem-sucedida, e exibe um erro caso falhe. Logo após, temos outra função, mostrarGatoIMG, que controla a exibição da imagem. Caso a imagem seja carregada com     sucesso, ela será exibida. Se houver um erro (ex.: falta de conexão), a imagem é ocultada e uma mensagem de erro é exibida. A constante botaoCat, atrelada ao ID "fetch-cat", fica   encarregada do evento "click", sob a função mostrarGatoIMG, que, como o próprio nome sugere, deverá mostrar uma imagem de gato ao ter o botão clicado.

- Resultados
  
  ![image](https://github.com/user-attachments/assets/233aeb56-a8d3-4930-ac7f-4865b3699e9f)
  
  Eis a página inicial. Ao pressionarmos o botão...

  ![image](https://github.com/user-attachments/assets/20f3d104-aa7f-46ea-bcad-60694bffb782)
  
  Voilá!

E isso foi a nossa POC envolvendo o uso do método Fetch para consumo de APIs





