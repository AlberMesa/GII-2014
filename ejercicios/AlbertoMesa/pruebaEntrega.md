###Transparente-Servidor-UGR. Entrega de Práctica final.

- Enlace al **repositorio**: [repo de Github](https://github.com/TransparenciaUGR/Proyecto-IV).
- Enlace a la aplicación desplegada en **IAAS**: [Transparente en Azure](http://ugrtransparente.cloudapp.net:3000/).
- Enlace a la aplicación desplegada en **PAAS**: [Transparente en Heroku](https://transparente-ugr.herokuapp.com/).
- Build automatizado para despliegue local descargable desde [Docker](https://registry.hub.docker.com/u/am83/proyecto-iv/).
- Para detalles, instrucciones de uso, capturas y más info, ver el fichero **README**: [README.md](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/README.md).
- Publicado bajo **Licencia GNU**: [Licencia GNU](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/LICENSE).


-----------------------------------------------------------------------------------------------------------------------------

####Alberto Mesa Navarro
@AM83

**Ha hecho estos scripts de aprovisionamiento (enlace a los commits):**

- Script para Ansible: [transparente.yml](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/Ansible/transparente.yml) .  [Enlace commit] (https://github.com/TransparenciaUGR/Proyecto-IV/commit/f5341b490994d38f73520e639472c54963575092).

- Script básico para Vagrant, por si el usuario quisiera utilizar Vagrant: [Vagrantfile](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/vagrant/vagrantfile). [Enlace commit] (https://github.com/TransparenciaUGR/Proyecto-IV/commit/c0a1a5f4423d2737b97e74c8565f04051a4eecb3).


**Ha participado en estos tests (o issues):**

- Test timeout: [test.js] (https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/test/scenarios/timeoutOption/test.js).

- [Gruntfile.js] (https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/test/scenarios/timeoutOption/Gruntfile.js). 

- [grunt-mocha-test.js] (https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/test/tasks/grunt-mocha-test.js). <br /><br />
[Enlace commit] (https://github.com/TransparenciaUGR/Proyecto-IV/commit/6072118145501ada751f2ec426862177fac9e488#diff-b9221b9eb6cfaa61362b4c4c6eaea53d).

- Issues y test (resolución de problemas e intentos de mejora) relativos al uso de vnc, xvfb (falso display) y posibles configuraciones de GUI ligeras como Minimal Gnome Core para la plataforma. <br /> <br />
[Commit principal] (https://github.com/TransparenciaUGR/Proyecto-IV/commit/6702d317bf95e08908162649a5dd194162576102) y algunos otros como por ejemplo: [Enlace commit] (https://github.com/TransparenciaUGR/Proyecto-IV/commit/9a404bc103cfb8028851c24e3a6e960eb4c815c3) , [Enlace a commit] (https://github.com/TransparenciaUGR/Proyecto-IV/commit/8b79650503cce67cd39a876bbc3b9791b5dc3d35) , [Enlace a commit] (https://github.com/TransparenciaUGR/Proyecto-IV/commit/2055633d5d8d5593f4991492855bf3c3d19491c6) .

- Adición de extensibilidad postgresql-server-dev-X.Y para extensión server-side y libpq-dev para aplicación client-side. Son detalles importantes ya que con ello se facilita la extensibilidad deseable de este tipo de proyectos.<br />
[Enlace commit] (https://github.com/TransparenciaUGR/Proyecto-IV/commit/9d71758177735a3bb98807dfad735f6ed7a3bace) . 

- Puesta en marcha del servidor y funcionamiento consistente mediante solución de ejecución permanente del servidor y en segundo plano con multiplexor de terminales [tmux] (http://tmux.sourceforge.net/). [Enlace a ejemplo] (https://camo.githubusercontent.com/8b047ad7945797b7e9b1579b05bb329bb9717117/687474703a2f2f73392e706f7374696d672e6f72672f6d79357078396934662f417a7572655f576f726b696e672e706e67). 

- Pruebas de instalación y configuración de herramientas que luego implementé en los scripts de despliegue automático correspondientes. Pruebas, pruebas y más pruebas antes de integrar a la repo y de las que no hay commits.	

**Ha participado en esta integración continua y PaaS:**

- Realizado el despliegue integral en el PAAS Azure. Creación, configuración y despliegue de la máquina en Azure, apertura de extremos, ejecución permanente de servidor, pruebas y puesta en marcha del servicio hasta lograr que esté disponible. [Puede accederse desde su enlace en Azure] (http://ugrtransparente.cloudapp.net:3000/) . Más info en el [README.md](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/README.md).

- Integración en tiempo real y de manera totalmente automatizada a nuestra abstracción en Docker a través de la simbiosis Github - Docker para despliegues automáticos actualizados. Hacer el pull de am83/Proyecto-IV:latest .

- Aportaciones y modificaciones del fichero [shippable.yml] (https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/shippable.yml) . Ejemplo de [Enlace a commit] (https://github.com/TransparenciaUGR/Proyecto-IV/commit/bc4ae48f6fa88858558b336a91f0729d5c050521).


**Ha participado en esta configuración de despliegue automático** 
(Trabajamos en Azure pero es válido para cualquier otra infraestructura como servicio):

- Estudio, instalación, uso y configuración de herramientas Azure, Vagrant y Ansible.

- Script inicial para despliegue mediante scriptado seguro y paso de argumentos y ejecutables a la máquina Azure (o cualquier otra): [levantaAzure](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/scripts/levantaAzure).

- Script de despliegue automático mediante scriptado seguro en Azure (o cualquier otro PAAS): [maquinaNube](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/scripts/maquinaNube)

-**Nota**: los scripts de aprovisionamiento, como parte de la automatización, están en su sección correspondiente y por eso no se han incluido en este punto. 

- Automatización de despliegue con 1 solo comando desde Docker, listo para ejecutar y desplegar el servidor de forma totalmente automática: script [IniciarDespliegue](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/IniciarDespliegue) y [Dockerfile](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/Dockerfile). <br />

[Enlace a commit](https://github.com/TransparenciaUGR/Proyecto-IV/commit/e2288c48441a93092aaf7c4185202d4e96d16072#diff-c93bf64f0da08a198dce8900728ec5d0) y [Enlace a commit] (https://github.com/TransparenciaUGR/Proyecto-IV/commit/098e044944775c7f295a4c65a46c801f389a1ddb#diff-c93bf64f0da08a198dce8900728ec5d0) .

- Entre otras, scripts para "recoger la casa" de despligues locales: [EliminarImagenes](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/scripts/EliminarImagenes), [EliminarContainers](https://github.com/TransparenciaUGR/Proyecto-IV/blob/master/scripts/EliminarContainers). <br /> <br />
[Enlace a commit] (https://github.com/TransparenciaUGR/Proyecto-IV/commit/1d50febffa012ab3891e617ac2baf05527f326ce#diff-70bf79e207171206e221dd1e0209112f) .

-----------------------------------------------------------------------------------------------------------------------------
