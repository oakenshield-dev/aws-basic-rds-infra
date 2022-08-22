# Infraestructura base para RDS

El objetivo de este proyecto es implementar la infraestructura base para montar una base de datos en RDS alojada en una red privada y lograr tener acceso a ella desde fuera.

La implementación será basada en el diagrama dispuesto en este mismo documento.

## Configuración de ambiente local de desarrollo

Los pre-requerimientos básicos para trabajar con el proyecto son:

- Git
- AWS CLI
- Configurar credenciales de cuenta de AWS 

### Contar con _git_ instalado.

1. Para ello hay que seguir la guia de instalación de cada S.O [Getting Started - Installing Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

2. Y posteriormente hay que configurar nuestra cuenta de git de forma locl, para hacer mas fácil el desarrollo y no tener que estar metiendo usuario y contraseña cada vez que sea necesario.

    Para ello  configuramos nuestro usuario localmente.

    ```bash
    $ git config --global user.name "User name"
    $ git config --global user.email email@example.com
    ```
3. Crear un Personal Access Token para no usar contraseña, esto se puede configurar siguiendo la siguiente guia [Creating a personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)

### Instalación de AWS CLI

El CLI de aws nos ayudara para realizar algunas operaciones con la cuenta sin tener que entrar a la consola de aws.

Para instalar es necesario seguir la guía de aws [Installing or updating the latest version of the AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)

Para MacOS existe otra alternativa mas simple usando Brew, para instalar el CLI

```install
brew install awscli
```

### Configurar credenciales de cuenta de AWS 

pruebas
