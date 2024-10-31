# UTN-FRA_SO_TP-Integral


## Descripcion:
> El siguiente TP tiene como finalidad recrear un equipo de trabajo. </br>
> Se encontraran y deberan resolver los diferentes inconvenientes que surjan en el camino.

## Descripción:
> El siguiente TP tiene como finalidad recrear un equipo de trabajo. </br>
> Se encontrarán y deberán resolver los diferentes inconvenientes que surjan en el camino.

- [ ] Funciones.
  - (R1) Líder:
  - (R2) Responsable de Arquitectura:
  - (R3) Responsable de Automatización Nivel 1:
  - (R4) Responsable de Automatización Nivel 2:
  - (R5) Responsable de Microservicios:
  - (R6) Responsable de Testing / Documentacion:
  
## Responsabilidades
- [ ] (R1) - Líder:
  - Dueño de la rama Master.
  - Acepta pull requests.
  - Realiza merges.
  - Responsable de producción.
  - Organiza reuniones regulares para revisar el progreso del proyecto.
  - Proporciona retroalimentación a los miembros del equipo.
  - Media en conflictos entre miembros del equipo.

- [ ] (R2) - Arquitectura:
  - Solo pushea contra dev.
  - Definición del hardware.
  - Scriptear la instalacion de todos los programas necesarios para el desarrollo del TP.
  - Estructura de discos / FS.
  - Realiza revisiones de diseño para asegurar alineación con los objetivos del proyecto.
  - Proporciona guías sobre mejores prácticas de arquitectura.

- [ ] (R3) - Automatización Nivel 1:
  - Solo pushea contra dev.
  - Creación de usuarios.
  - Monitoreo web.
  - Documenta los procesos de automatización y monitoreo.
  - Colabora con el responsable de Automatización Nivel 2 en herramientas de automatización.
  - Colabora con el responsable de Microservicios automatización.

- [ ] (R4) - Automatización Nivel 2:
  - Solo pushea contra dev.
  - Desarrollo de Playbooks de Ansible.
  - Desarrolla Roles de Ansible.
  - Desarrolla Playbook te testing unitarios dentro de los Roles de Ansible.

- [ ] (R5) - Microservicios:
  - Solo pushea contra dev.
  - Desarrollo de imágenes Docker / docker-compose.
  - Publicacion de la imagen en dockerhub
  - Responsable de la ejecución de las imágenes.
  - Documenta procesos de creación y despliegue de imágenes Docker.

- [ ] (R6) - Testing / Documentación:
  - Solo pushea contra dev.
  - Generación y verificación de issues.
  - Colabora con los distintos desarrollos






## Tareas: 
- [ ]   Preparacion del Repositorio de Git
  - Responsable: Lider
  - Tareas: Push contra master / Aceptar pull request
    - Seguridad: Rama Master -> Solo el lider puede pushear
    - Seguridad: Rama dev -> El esto de los integrantes pueden pushear
    - Seguridad: Cuando se requiera subir un cambio de dev a Master, El responsable de esa funcionalidad debe realizar un pull request al lider para que se realice el merge contra la rama master.
    - Metodologia:  Trunk-based development (TBD).
    - Cantidad de ramas aceptadas: master , dev


- [ ]   Preparacion de la VM
  - Responsable: Testing/Documentacion/Calidad
  - Tareas:
    - Generacion de vagrantfile
    - Ejecutar / Testear los diversos desarrollos de los demas integrantes.
    - Documentar la ejecucion, pruebas y bugs Encontrados. (crear issues, wiki ) 


- [ ]   LVM
  - Responsable: Arquitectura
  - Tareas: 
    - Indicar al responsable de la preparacion de la vm Discos a incorporar.
    - Scriptear / Documentar: Las tareas de particionamiento, creacion de PV, VG, LV, formateo y montajes persistentes segun el punto de LVM.


- [ ]   Bash-Scripting
  - Responsable: Automatizacion Nivel 1
  - Tareas: 
    - Scriptear / Documentar: Las tareas pedidas en el punto de Bash-Scripting 


- [ ]   Ansible
  - Responsable: Automatizacion Nivel 2
  - Tareas: 
    - Desarrollar Playbook Ansible / Documentar: Las tareas pedidas en el punto de Ansible.


- [ ]   Docker
  - Responsable: Microservicios.
  - Tareas: 
    - Desarrollar dockerfile, imagen / Documentar: Las tareas pedidas en el punto de Docker.
