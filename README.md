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

## Sequencia para criar no projeto

Criar a migration
```
php artisan make:migrate create_NOMEDATABELA_table
```
```
php artisan make:migrate create_crudlaravel_table
```
Executar as migration
```
php artisan migrate
```

Criar Controller
```
php artisan make:controller CrudController
```

Criar a VIEW e a pasta
```
php artisan make:view crud/index
```

Criar Models
```
php artisan make:model Crud
```