### Troca-comigo
### Install
Instale as dependências do projeto (Necessário ter instalado na sua máquina o Composer e o Node.js):

```
composer install
npm install
```
Duplicar arquivo `.env.example` para `.env`: 
```
cp .env.example .env
```
Configure nome do projeto, banco de dados e outras informações no `.env`
Gere um novo APP_KEY: 
```
php artisan key:generate
```

Configure o Laravel mix
```
npm run dev

```
Pronto! O projeto foi instalado com sucesso.
