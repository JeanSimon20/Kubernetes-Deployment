# Kubernetes-Deployment
What is Kubernetes?
Kubernetes, a menudo abreviado como "K8s", organiza aplicaciones en contenedores para que se ejecuten en un clúster de hosts. El sistema K8s automatiza la implementación y la gestión de aplicaciones nativas de la nube utilizando infraestructura local o plataformas de nube pública. Distribuye las cargas de trabajo de las aplicaciones en un clúster de Kubernetes y automatiza las necesidades dinámicas de redes de contenedores. Kubernetes también asigna volúmenes persistentes y de almacenamiento a contenedores en ejecución, proporciona escalado automático y trabaja continuamente para mantener el estado deseado de las aplicaciones, brindando resiliencia.

Deployment 
Las implementaciones representan un conjunto de varios pods idénticos sin identidades exclusivas. Una implementación ejecuta varias réplicas de tu aplicación y reemplaza automáticamente cualquier instancia que falle o deje de responder. De esta manera, las implementaciones ayudan a garantizar que una o más instancias de tu aplicación estén disponibles para entregar solicitudes de usuarios. El controlador de implementación de Kubernetes administra las implementaciones.

Scaling
El escalado en kubernetes se puede manejar utilizando las características integradas de los Deployment.
El escalado tiene la función de agregar recursos adicionales a una aplicación o sistema para manejar más trabajo. En k8s, esto a menudo significa ejecutar más copias (réplicas) de una aplicación en contenedores.
