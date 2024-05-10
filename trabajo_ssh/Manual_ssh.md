![Getting Started](img3.png)

# Manual de usuario para claves SSH en GitHub


## Introducción

Las claves SSH son una forma segura de autenticarse en GitHub y acceder a tus repositorios. Son una alternativa a las contraseñas, que pueden ser menos seguras y más engorrosas de usar.

Este manual te guiará a través del proceso de creación, uso e implementación de claves SSH en GitHub.

## Requisitos previos

- Tener una cuenta de GitHub
- Un ordenador con un terminal o línea de comandos

## Paso 1: Generar claves SSH

1. Abre un terminal o línea de comandos en tu ordenador.
2. Ejecuta el siguiente comando para generar un par de claves SSH: `ssh-keygen`
3. Se te pedirá que introduzcas un nombre de archivo para tus claves. El nombre por defecto es `id_rsa`, pero puedes elegir uno diferente.
4. Opcionalmente, puedes establecer una frase de contraseña para tus claves. Esto añadirá una capa adicional de seguridad, pero te pedirá que introduzcas la frase de contraseña cada vez que uses las claves.
5. Guarda las claves en un lugar seguro de tu ordenador.

## Paso 2: Agregar la clave pública a GitHub

1. Accede a tu cuenta de GitHub y ve a la sección "Configuración" > "Claves SSH y GPG".
2. Haz clic en el botón "Nueva clave SSH".
3. Pega la clave pública SSH en el campo "Clave". La clave pública es el archivo que termina con `.pub`.




![Logo de GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

![Getting Started](img5.png)