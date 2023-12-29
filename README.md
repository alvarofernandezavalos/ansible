# Ansible Playbooks tests

## ami.yml

1. genera una imagen ami a partir de una instancia de AWS

## launch.yml

Antes de ejecutar este playbook, se deben de instalar dos módulos.
```
ansible-galaxy collection install community.docker
ansible-galaxy collection install amazon.aws
```

1. crea una instancia ec2
2. espera conexion con ssh
3. instala los paquetes
4. ejecuta un rol para instalar docker
5. clona un repositorio git
6. lanza docker compose
7. despues destruye la instancia

## maven.yml

1. descarga de un artifactory