# Packer & Docker

* Packer v0.7.1
* Docker 1.2.0
* Ansible 1.5.4 (in Docker container)

# Image in Docker Repo
https://registry.hub.docker.com/u/esacteksab/pyall/

# How-to

* Install Packer
* Install Docker
* Make any changes to Packer file -- **Make sure you update Tag in ``docker-import``!!!
* ``packer build docker-ubunt.json``
* ``docker push esacteksab/pyall:<version>``


# Python Versions:

```
root@b36681570b36:/# python2.6 --version
Python 2.6.9
root@b36681570b36:/# python2.7 --version
Python 2.7.6
root@b36681570b36:/# python3.1 --version
Python 3.1.5
root@b36681570b36:/# python3.2 --version
Python 3.2.5
root@b36681570b36:/# python3.3 --version
Python 3.3.5
root@b36681570b36:/# python3.4 --version
Python 3.4.0
root@b36681570b36:/# which python3    
/usr/bin/python3
root@b36681570b36:/# python3 --version
Python 3.4.0
root@b36681570b36:/# which python2
/usr/bin/python2
root@b36681570b36:/# python2 --version
Python 2.7.6

PyPy 2.4
```
