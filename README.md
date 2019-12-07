# WebAPI Raytracer
Um [raytracer](https://pt.wikipedia.org/wiki/Ray_tracing) para testes de carga e estresse de [WebAPIs](https://developer.mozilla.org/pt-BR/docs/WebAPI)

- Teste de sistemas/frameworks REST
- Uma requisição por pixel
- Resolução da imagem personalizável para refletir a extensão do teste
- WebAPI recebe a requisição de deve processar o raio segundo uma cena 3D salva em alguma estrutura de armazenamento de dados
- A estrutura de armazenamento de dados da cena 3D pode ser um arquivo ou um banco de dados
- O objetivo é testar a velocidade e o comportamento concorrente
- Espera-se que o teste demore até vários minutos
- A imagem final resultante pode ser formada em tempo real
- Um log pode mostrar as requisições que falharam
