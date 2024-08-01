# US01 - Cadastro de Curso

- Como um usuário da aplicação
- Quero cadastrar um curso
- Para que eu possa ver a lista dos meus cursos disponíveis

## Critérios de Aceitação

1. O usuário deve acessar o formulário de cadastro de curso ao clicar no menu "Cadastrar curso"

2. O formulário de cadastro do curso deverá conter os seguintes campos obrigatórios:
- Nome do curso
- Descrição do curso
- Instrutor
- URL da imagem de capa
- Data de início
- Data de fim
- Número de vagas
- Tipo de cursos com as opções: Presencial e Online

3. O campo "Nome do curso" deve ter o limite de 50 caracteres

4. O campo "Descrição do curso" deve  ter o limite de 256 caracteres

5. O campo "Instrutor" deve ter o limite de 50 caracteres

6. O campo "URL da imagem de capa" deve ter validação para aceitar apenas URL

7. Os campos "Data início" e "Data fim" devem conter a opção de adicionar as datas pelo calendário

8. O campo "Data de fim" não deve aceitar data menor que "Data de início"

9. O campo "Número de vagas" deve ter o limite de 1000 vagas

10. O usuário deve ser alertado referente aos campos obrigatórios com a mensagem padrão abaixo de cada campo: "O campo é obrigatório"

11. O usuário não deve conseguir finalizar o cadastro se os campos obrigatórios não estiverem preenchidos

12. Após o cadastro ser realizado com sucesso, o usuário deve ser redirecionado para a lista de cursos