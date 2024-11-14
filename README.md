# Desafío Práctico con CDK

El objetivo de este desafío es introducir al estudiante al CDK a través de un ejercicio práctico. CDK es un framework de Infraestructura como Código diseñado para permitir a los arquitectos diseñar topologías de infraestructura complejas para la nube utilizando las abstracciones de lenguajes de programación comunes.

## Pasos del Desafío

Para completar el desafío con AWS-CLI, Cloudformation y CDK, el estudiante debe completar los siguientes pasos:

1. **Instalar CDK-CLI**: Sigue las instrucciones proporcionadas en la documentación oficial:
   [Introducción a AWS CDK](https://docs.aws.amazon.com/cdk/v2/guide/getting_started.html)

2. **Desarrollar una Aplicación Web Simple**: Utiliza una función lambda con CDK. Para completar este paso, sigue el tutorial en:
   [Tutorial Hello World de AWS CDK](https://docs.aws.amazon.com/cdk/v2/guide/hello_world.html)

3. **Subir a GitHub**: Sube la aplicación desarrollada a un repositorio en GitHub.

4. **Escribir un Informe**: Documenta tu experimento en el README del repositorio de GitHub. Asegúrate de agregar capturas de pantalla y evidencia de tus resultados.

¡Buena suerte!


## Creando el proyecto CDK

para crear un proyecto CDK nuevo, este debe tener su propio directorio, para esto ejecutaremos el siguiente comando, el cual le crea su propio directorio y nos deja en esta carpeta

```bash
mkdir hello-cdk && cd hello-cdk
```

![alt text](docs/imgs/01.png)


ahora para inicializar un proyecto cdk utilizaremos cdk init y en nuestro case lo haremos en base a java
```bash
cdk init app --language java
```

![alt text](docs/imgs/02.png)

si todo sale bien en nuestra carpeta se creo una estructura java como la siguiente

![alt text](docs/imgs/03.png)