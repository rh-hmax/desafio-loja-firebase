# Criação de API
## História
Dentro de uma arquitetura de **micro-serviços** e **serverless**, precisamos de uma API para cadastro de produtos para uma loja.

### Requisitos funcionais
	- Como gerente gostaria de adicionar um novo produto ao catálogo da loja
	- Como gerente gostaria de editar um produto existente no catálogo
	- Como gerente gostaria de remover o produto do meu catálogo da loja
	- Como gerente gostaria de recuperar uma lista com os produtos disponíveis
	- Como gerente gostaria de buscar produtos pela sua descrição
	- Como gerente preciso que os resultados sejam páginados
	- Como gerente quero que apenas pessoas com permissão possam: adicionar, editar remover produtos
	- Como cliente quero visualizar um produto
### Requisitos não funcionais
	- A API precisa estar em uma estrutura serverless (Firebase ou GCP)
	- A API deve usar NodeJS com Typescript
	- A API deve seguir um padrão REST
	- Deve haver pelo menos 3 testes unitários com JEST
	- Deve haver tratamento centralizado de erros, usando os padrões HTTP
	- Os dados devem ser persistidos em um banco NoSQL, preferencialmente Firebase Firestore
### Entrega
	- Um repositório GitHub
	- Um ambiente rodando a aplicação
### Critérios de avaliação
	- Entendimento dos requisitos
	- Afinidade com a ferramenta utilizada
	- Testes unitários
	- Estrutura de arquivos
	- Padrão de escrita do código
	- Utilização de boas práticas
