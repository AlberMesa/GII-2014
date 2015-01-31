###Transparente-Servidor-UGR. Entrega de Práctica final.

- Enlace al **repositorio**: [repo de Github](https://github.com/TransparenciaUGR/Proyecto-IV).
- Enlace a la aplicación desplegada en **IAAS**: [Transparente en Azure](http://ugrtransparente.cloudapp.net:3000/).
- Enlace a la aplicación desplegada en **PAAS**: [Transparente en Heroku](https://transparente-ugr.herokuapp.com/).
- Build automatizado para despliegue local descargable desde [Docker](https://registry.hub.docker.com/u/am83/proyecto-iv/).
- Para detalles, instrucciones de uso, capturas y más info, ver el fichero **README**: [README.md](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/README.md).
- Publicado bajo **Licencia GNU**: [Licencia GNU](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/LICENSE).


-------------------------------------------------------------------------------------------------------------------

####Alberto Mesa Navarro
@AM83

**Ha participado en estos scripts de aprovisionamiento (enlace a los commits):**

- Script para Ansible: [transparente.yml](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/Ansible/transparente.yml) .  [Enlace commit] (https://github.com/TransparenciaUGR/Proyecto-IV/commit/f5341b490994d38f73520e639472c54963575092).

- Script básico para Vagrant, por si el usuario quisiera utilizar Vagrant: [Vagrantfile](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/vagrant/vagrantfile). [Enlace commit] (https://github.com/TransparenciaUGR/Proyecto-IV/commit/c0a1a5f4423d2737b97e74c8565f04051a4eecb3).


**Ha participado en estos tests (o issues):**

- Test timeout: [test.js] (https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/test/scenarios/timeoutOption/test.js).

- [Gruntfile.js] (https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/test/scenarios/timeoutOption/Gruntfile.js). 

- [grunt-mocha-test.js] (https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/test/tasks/grunt-mocha-test.js).

- Issues y test (resolución de problemas e intentos de mejora) relativos al uso de vnc, xvfb (falso display) y posibles configuraciones de GUI ligeras como Minimal Gnome Core para la plataforma.
	
- Adición de extensibilidad postgresql-server-dev-X.Y para extensión server-side y libpq-dev para aplicación client-side.

- Solución de ejecución permanente del servidor y en segundo plano con multiplexor de terminales [tmux] (http://tmux.sourceforge.net/).
	

**Ha participado en esta integración continua y PaaS:**

- Creación, configuración y despliegue de la máquina en Azure, apertura de extremos, ejecución permanente de servidor y puesta en marcha del servicio, accesible desde [su enlace] (http://ugrtransparente.cloudapp.net:3000/) .

- Integración en tiempo real y de manera totalmente automatizada a nuestra abstracción en Docker a través de la simbiosis Github - Docker para despliegues automáticos en local.

- Scripts para Azure mencionados anteriormente.

- Aportaciones y modificaciones del fichero [shippable.yml] (https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/shippable.yml) .


**Ha participado en esta configuración de despliegue automático** (trabajamos en Azure pero es válido para cualquier otra infraestructura como servicio):

- Instalación y configuración de herramientas Azure.

- Script inicial máquina Azure: [levantaAzure](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/scripts/levantaAzure).

- Script de despliegue automático en la nube (Azure): [maquinaNube](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/scripts/maquinaNube)

- Despliegue automático desde Docker a máquina local, listo para ejecutar y desplegar el servidor: script [IniciarDespliegue](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/IniciarDespliegue) y [Dockerfile](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/Dockerfile). 

- Scripts para "recoger la casa" de despligues locales: [EliminarImagenes](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/scripts/EliminarImagenes), [EliminarContainers](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/scripts/EliminarContainers).

-------------------------------------------------------------------------------------------------------------------------------------
