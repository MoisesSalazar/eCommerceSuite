# eCommerceSuite

eCommerceSuite es una solución integral que fusiona la potencia del comercio electrónico con la eficiencia de un sistema ERP, brindando una experiencia completa y sin fisuras para la gestión empresarial en línea.

## Requisitos del sistema
- Laravel v10.46.0
- PHP v8.2.13
- Composer

## Instalación

1. Instale PHP y Composer en su sistema. Puede encontrar las instrucciones de instalación en los sitios web oficiales de PHP y Composer.

2. Clone el repositorio en su máquina local.

    ```bash
    git clone https://github.com/your-repo/eCommerceSuite.git
    ```

3. Navegue hasta el directorio del proyecto.

    ```bash
    cd eCommerceSuite
    ```

4. Instale las dependencias de Laravel con Composer.

    ```bash
    composer install
    ```

5. Copie el archivo .env.example a un nuevo archivo llamado .env.

    ```bash
    cp .env.example .env
    ```

6. Genere una nueva clave de aplicación.

    ```bash
    php artisan key:generate
    ```

7. Inicie el servidor de desarrollo de Laravel.

    ```bash
    php artisan serve
    ```

Ahora debería poder acceder a la aplicación en su navegador en [http://localhost:8000](http://localhost:8000).
