# NOME DO REPOSITÓRIO/SERVIÇO AQUI

[BREVE RESUMO DO QUE SE TRATA ESSA CODEBASE, DE FORMA OBJETIVA E SIMPLES DE ENTENDER]

## Indice da Documentação

- [Responsáveis](docs/responsaveis.md)
- [Tecnologias Utilizadas](docs/tecnologias-utilizadas.md)
- [Padrões e Políticas dessa codebase](docs/padroes-e-politicas-dessa-codebase.md)
- [Endpoints e Acessos](docs/endpoints-e-acessos.md)
- [Documentação API](docs/documentacao-api.md)

## Instalação e Setup Local

[COLOCAR TODA CONFIGURAÇÃO NECESSÁRIA QUE ESSE SERVIÇO NECESSITA PARA SER RODADO LOCALMENTE AQUI]

1. Clone o repositório

   ```
   git clone https://github.com/company/todo-api-clean-architecture-boilerplate
   ```

2. Instale as dependências utilizando:

   ```
   npm install
   ```

3. Defina as variáveis de ambiente em um novo arquivo chamado `.env`, conforme o arquivo `.env.example`
   - Peça para seu tech-lead ou colegas de trabalho te mandaram uma cópia do .env deles, para execução local, caso necessário
4. Suba os serviços docker necessários:

   ```
   sudo docker-compose up -d
   ```

5. Pegue o IP address do serviço postgres do docker:

   ```
   docker inspect -f '{{range.NetworkSettings.Networks}}{{.IPAddress}}{{end}}' todo_postgres
   ```

6. Atualize o servidor da variável de ambiente DATABASE_URL no arquivo `.env`, como no exemplo abaixo:

   ```
   DATABASE_URL="postgresql://postgres:postgres@172.29.0.2:5432/todo_api?schema=public"
   ```

7. Gere o client do prisma:

   ```
   npx prisma generate
   ```

8. Rode as migrations do Prisma:

   ```
   npx prisma migrate dev
   ```

9. Suba o servidor localmente:

   ```
   npm run dev
   ```

10. Cheque o Prettier e o ESLint antes de enviar uma PR:

   ```
   npm run precommit
   ```

11. Cheque também se todos os testes continuam passando, antes de enviar uma PR:

   ```
   npm run test
   ```

12. Lembre-se de verificar outros comandos úteis no arquivo `package.json`
