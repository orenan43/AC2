# Sistema de Agendamento de Treinamento

Este sistema foi desenvolvido para a empresa XYZ, especializada em capacitações no ramo da fisioterapia. Ele tem como objetivo organizar e gerenciar a agenda de treinamentos, substituindo o uso de planilhas do Excel por uma solução mais eficiente e moderna.

## Funcionalidades Principais:


### Cadastro de Professores:

- Nome
- CPF
- RG
- Endereço
- Celular

### Cadastro de Cursos:

- Descrição
- Carga horária
- Objetivos
- Ementa

### Relacionamento entre Professores e Cursos:

- Associação de professores às suas especializações

### Cadastro de Agenda de Treinamentos:

- Curso
- Data e horário
- Professor responsável
- Local (Cidade, Estado, CEP)

### Validações durante o cadastro de Agenda:

- Restrição de professores apenas com especialização no curso selecionado
- Verificação de conflitos de agenda para o mesmo professor

### Acesso do Professor:

- Visualização da própria agenda
- Impressão da agenda
- Cadastro de resumo do treinamento (ocorrências)

## Tecnologias Utilizadas:

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- HTML
- CSS
- JavaScript

## Como Executar:

1. Clone este repositório: `git clone <link_do_repositorio>`
2. Importe o projeto em sua IDE
3. Configure o banco de dados de acordo com as configurações do arquivo `application.properties`
4. Execute o projeto
5. Acesse a aplicação através do navegador web: `http://localhost:8080`

Este sistema proporcionará à empresa XYZ uma gestão mais eficiente e organizada de seus treinamentos, permitindo um acompanhamento detalhado da agenda dos professores e dos cursos oferecidos.
