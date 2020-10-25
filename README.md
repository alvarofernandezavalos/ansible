# Ansible Playbooks tests

## ami.yml
---

1. genera una imagen ami a partir de una instancia de AWS

## launch.yml
---

1. crea una instancia ec2
2. espera conexion con ssh
3. instala los paquetes
4. ejecuta un rol para instalar docker y docker-compose
5. clona un repositorio git
6. lanza un docker-compose
7. despues termina la instancia

## maven.yml
---

1. descarga de un artifactory el compilado