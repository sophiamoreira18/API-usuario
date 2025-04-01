## Requisitos

Antes de rodar a aplicação, é necessário ter o seguinte instalado em seu ambiente:

- PHP 7.4 ou superior
- Composer
- Servidor web (como Apache ou Nginx) ou usar o servidor embutido do PHP

## Instalação

1. Clone este repositório:

   ```bash
   git clone https://seurepositorio.com

   
## Endpoints
 
### 1. `GET /usuarios`
Retorna uma lista de 5 usuários.
 
### 2. `POST /usuarios`
Cria um novo usuário. Campos obrigatórios:
- `login`
- `senha`
 
### 3. `PUT /usuarios/{id}`
Atualiza os dados de um usuário pelo ID.
 
### 4. `DELETE /usuarios/{id}`
Exclui um usuário pelo ID.