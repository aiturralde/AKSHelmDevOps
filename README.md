# Introducción

<div style="text-align: justify">
 
En este laboratorio se realizará las tareas necesarias para efectuar un deployment de una aplicación de contenedores en Kubernetes en un ambiente de Azure Kubernetes Services (AKS).

Alguna de las cosas que se verán en este laboratorio serán:

- Deployment de Kubernetes

- Deploy de una aplicaciíon mediante Helm

- Construyendo un pipeline de CI/CD utilizando Azure DevOps y Azure Container Registry

## Pre requisitos
- Subscripción de Azure. Sí no posee una, obtenga un trial: [https://azure.microsoft.com/es-es/free/](https://azure.microsoft.com/es-es/free/)

- Cuenta de Azure DevOps, puede obtener una en [https://dev.azure.com](https://dev.azure.com)

- Para la ejecución de comandos puede utilizar el Azure Cloud Shell disponible en [https://shell.azure.com/](https://shell.azure.com/) una vez que inicie sesión con su subscripción de Azure. El Azure Cloud Shell tiene pre-instalado y configurado el Azure CLI para conectarse a su subscripción ded Azure así como tambien **kubectl** y **helm**.

## Conocimientos básicos de Kubernetes
Para este laboratorio se asume que se tiene conocimientos básicos sobre Kubernetes y sus conceptos generales.

Si es nuevo en Kubernetes, puede empezar con [Kubernetes Learning Path](https://aka.ms/LearnKubernetes "Kubernetes Learning Path") y luego avanzar con los conceptos sobre [qué es y qué no es Kubernetes.](https://aka.ms/k8sLearning "qué es y qué no es Kubernetes.") Si ya tiene mas experiencia como desarrollador o administrador de Kubernetes, puede revisar la [guía de mejores prácticas en Kubernetes](https://aka.ms/aks/bestpractices "guía de mejores prácticas en Kubernetes").

## Vistazo general de la aplicación
Se efectuará el deployment de la aplicación **Phippy and Friends**, la cual se encuentra en el repo: [https://github.com/Azure/phippyandfriends](https://github.com/Azure/phippyandfriends). Dicho repositorio tiene unos servicios, cada uno representa un personaje individual en la "Guía para Niños sobre Kubernetes y su nuevo amigo NodeBrady". Cada servicio esta construído en lenguaje de programación diferente, con lo cual se quiere mostrar como un cluster de AKS puede ejecutar cualquier tipo de aplicación. **Parrot** está en .NET Core, **CaptainKube** en GO, **Phippy** en PHP y **NodeBrady**  en Node.js.

# Ejercicio 1: Importando el código

1. En su subscripción de Azure DevOps cree un nuevo proyecto.
  
2. En su propio Azure Repo, del proyecto creado en el paso anterior, importe el contenido de [https://github.com/Azure/phippyandfriends](https://github.com/Azure/phippyandfriends).




</div>