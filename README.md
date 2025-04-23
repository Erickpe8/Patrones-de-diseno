# 📁 Estructura de Proyecto Laravel con Patrones de Diseño 

## app/

- **Models/**
  - `User.php` → Modelo para MVC, Repository Pattern  
  - `Article.php` → Modelo para Eloquent Builder (Builder Pattern)

- **Http/**
  - **Controllers/**
    - `UserController.php` → MVC Pattern, Repository Pattern  
    - `MessageController.php` → Service Container / IoC  
    - `ArticleController.php` → Builder Pattern  
  - **Middleware/**
    - `ExampleMiddleware.php` → Strategy Pattern

- **Services/**
  - `MessageService.php` → Service Container / IoC  
  - `SingletonService.php` → Singleton Pattern

- **Repositories/**
  - `UserRepositoryInterface.php`
  - `UserRepository.php` → Repository Pattern

- **Factories/**
  - `UserFactory.php` → Factory Pattern

- **Providers/**
  - `RepositoryServiceProvider.php` → Vinculación del Repository Pattern

## resources/

- **views/**
  - **layouts/**
    - `app.blade.php` → Template Method Pattern (opcional)
