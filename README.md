# Frontend para Projeto front-api-pessoas

Este é o frontend do front-api-pessoas, desenvolvido em Angular. O frontend é responsável pela interface do usuário e interação com o backend fornecido pelo projeto .NET.

## Configuração e Execução

1. **Instalação de Dependências:**
   - Execute o comando a seguir para instalar as dependências:
     ```bash
     npm install
     ```

2. **Executar o Servidor de Desenvolvimento:**
   - Execute o seguinte comando para iniciar o servidor de desenvolvimento:
     ```bash
     ng serve
     ```
   - Acesse a aplicação em `http://localhost:4200/pessoas` no navegador.

## Tecnologias Utilizadas

- Angular
- Angular CLI
- ngx-bootstrap para componentes Bootstrap no Angular
- Outras dependências do npm

## Estrutura do Projeto

- `src/app`: Contém os componentes, serviços e módulos da aplicação.

## Componente Pessoas

O componente `Pessoas` é responsável por exibir e interagir com a entidade de Pessoa. Ele possui funcionalidades de listagem, adição, atualização e exclusão de pessoas.

### Componente Pessoas (pessoas.component)

O código-fonte do componente `Pessoas` está localizado em `src/app/components/pessoas/pessoas.component.ts`.

### Modelo de Pessoa (Pessoa.ts)

O modelo de dados para a entidade Pessoa está em `src/app/Pessoa.ts`.
