# Instalación de Docker

> **Importante**
>
> Tenga en cuenta que aquí asumimos que ya está familiarizado con Docker

Para descubrir Jeedom, también puedes rotarlo en un contenedor Docker :

## Instalación de Docker

Docker ahora está disponible en todas las distribuciones recientes.
Para instalarlo en una distribución

-   a base de ``rpm``

````
yum install docker
````

-   a base de ``deb``

````
apt-gy update
apt-gy install docker
apt-gy install docker.io
````

## Instalar una imagen Jeedom

Instalación de imagen :

``docker pull jeedom/jeedom:latest``

Luego inicie el :

``sudo docker run --name jeedom-server --privileged -v /opt/jeedom/www:/var/www/html -v /opt/jeedom/mysql:/var/lib/mysql -e ROOT_PASSWORD=your-root-password -p 9080:80 jeedom/jeedom``

Con :

-   ``jeedom-server`` : Se busca el nombre de Jeedom Docker
-   ``/opt/jeedom/www`` y ``/opt/jeedom/mysql`` : directorio donde los datos de Jeedom se colocan en el host
-   ``your-root-password`` : contraseña de root para acceder a Jeedom en SSH

Entonces necesita instalar Jeedom yendo a : ``IP_DOCKER:9080``

Por lo demás, puedes seguir la documentación [Primer paso con Jeedom](https://doc.jeedom.com/es_ES/premiers-pas/index)
