
##  Instalação e Execução

Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:
   ```bash
   git clone git@github.com:sanca-flow/sancaflow-app.git
   ```

2. Entre na pasta do projeto:
   ```bash
   cd sancaflow
   ```

3. Instale as dependências:
   ```bash
   npm install
   ```

4. Execute a aplicação:
   
   Para desenvolvimento: 
   ```bash
   npx expo start --web 
   ```
---

## Build e regra pra deploy

1. Remova o dist/ antigo (se necessario, não é obrigatório e nem a melhor opção. O framework fará isso sozinho):
  ```bash
   rm -rf dist/  
   ```
No windows ou vscode pode ser feito manualmente. 

2. Após o desenvolvimento, no final do projeto (quando estiver pronto), deve ser feita a build para web do projeto (produção)
 ```bash
   npx expo export -p web // esse comando cria um arquivo chamado dist/ contendo o sistema em html, css
 e js.
   ```
3. Após isso pode ser feito normalmente o commit.


## Para acessar na web
Acesse esse site na web
https://sancaflow.netlify.app/
