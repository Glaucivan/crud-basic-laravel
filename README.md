## Requisitos

* PHP 8.2 ou superior
* Composer
* GIT

## Como rodar o projeto baixado
Instalar as dependências
```
composer install
```

Duplicar o arquivo ".env.example" e renomear para ".env"

Gerar a chave
```
php artisan key:generate
```

Iniciar o projeto criado com Laravel
```
php artisan serve
```

Acessar o conteúdo padrão do Laravel
```
http://127.0.0.1:8000/
```
Executar as migration
```
php artisan migrate
```