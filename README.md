<div align="center">
      <img src="./_assets/logo.png" alt="Climatempo" width="300px"/>
</div>

---

## Sobre

Teste técnico para Desenvolvedor Full Stack na Climatempo, empresa de serviços meteorológicos.

### O Projeto

-  [Protótipo da interface](https://www.figma.com/file/t9fJqD8uh0yuXEeHvKsgm1/Layout---Climatempo-app?node-id=0%3A1&t=KzGQzecOwTi9SJlK-1) no Figma.

-  [Documentação da API](https://documenter.getpostman.com/view/14419670/2s8YzMXQhT) no Postman.

#### Tecnologias utilizadas

-  Typescript
-  Node.js, Express.js, Cors
-  React.js, Styled-components, Phosphor-react, Zod, React-hook-form, Axios

### O Desafio

Um usuário quer saber como vai ficar o
tempo para os próximos dias em Osasco e São Paulo utilizando seu smartphone.

Requisitos:

-  Frontend:

   -  Uma página responsiva;
   -  Um campo autocomplete para buscar localidades;
   -  Um card para cada dia de previsão;

-  Backend:

   -  Uma API rest ou graphql para obter localidades e dados de previsão;
   -  Validação de entradas do usuário;

Diferenciais:

-  Utilizar cache;
-  Utilizar Elasticsearch ou algum outro software de **full-text search** para busca de localidades;
-  Configurar ambiente docker para rodar a aplicação;

### Desafio Extra (opcional)

Permita que o usuário selecione em qual unidade de temperatura e chuva (precipitação) ele quer visualizar os dados.

#### Conversão dos valores:

-  Temperatura:
   -  de **°C** pra **°F**: (`valor` \* 1.8) + 32
   -  de **°F** pra **°C**: (`valor` - 32) / 1.8
-  Chuva:
   -  de **mm** pra **inch**: (`valor` / 25.4)
   -  de **inch** pra **mm**: (`valor` \* 25.4)

### Critérios de Avaliação

-  Performance de busca e renderização;
-  Segurança;
-  Testes;
-  Manutenibilidade;
-  Usabilidade;
-  Boas práticas;
