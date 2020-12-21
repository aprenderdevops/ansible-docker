# ansible-docker
Instalación de [Docker](https://www.docker.com/) con [Ansible](https://www.ansible.com/) utilizando el role [geerlingguy.docker](https://galaxy.ansible.com/geerlingguy/docker).

## Instalar el role geerlingguy.docker

Para instalar el role geerlingguy.docker, ejecutar el siguiente comando:
```bash
$ ansible-galaxy install -r roles/requirements.yml
```

## Inventario

El fichero `inventory` es un inventario de ejemplo que se deberá modificar en cada caso para indicar los hosts en los que se quiera instalar Docker.

## Ejecución del playbook

Para instalar Docker, ejecutar el playbook `install-docker.yml` mediante el siguiente comando:

```bash
$ ansible-playbook -i inventory install-docker.yml
```

---

Tags: ansible, ansible galaxy, configuration management, devops, docker