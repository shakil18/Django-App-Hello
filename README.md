
## Table of Contents

- [Django Hello-World with Docker <a name = "about_the_project"></a>](#django-hello-)
- [Requirements <a name = "requirements"></a>](#requirements-)
- [Directory Structure <a name = "directory_structure"></a>](#directory-structure-)
- [Usage Example <a name = "usage_example"></a>](#usage-example-)
- [Contact <a name = "contact"></a>](#contact-)
- [Acknowledgement <a name = "references"></a>](#acknowledgement-)
---


<!-- ABOUT THE PROJECT -->
## Django Hello-World with Docker <a name = "about_the_project"></a>

This repository contains a deployment template for Dockerized Django with Postgres, Gunicorn, and Nginx. The docker-compose file comprised of several container services. 

<!-- DIRECTORY STRUCTURE -->
## Directory Structure <a name = "directory_structure"></a>

Here's a project's directory structure:

```text
django-app-hello
├── app
│   ├── Dockerfile                   # Dockerfile for App(hello_djago)
│   ├── entrypoint.sh                # Check Postgres runtime
│   ├── hello_django                 # App
│   │   └── ...
│   ├── manage.py
│   ├── requirements.txt             # dependency list
│   └── upload
│       ├── admin.py
│       ├── apps.py                  
│       ├── __init__.py
│       ├── migrations
│       │   └── __init__.py
│       ├── models.py                
│       ├── templates
│       │   └── upload.html          # front-end
│       ├── tests.py
│       └── views.py                 
├── docker-compose.yml               # Docker-compose
├── nginx
│   ├── Dockerfile                   # Dockerfile for Nginx
│   └── nginx.conf                   # Nginx config file
└── README.md                        # Documentation
```

<!-- REQUIREMENTS -->
## Requirements <a name = "requirements"></a>

- [Docker <a href="https://docs.docker.com/get-docker/"> </a>](docker_download)
- [Docker Compose <a href="https://docs.docker.com/compose/install/"> </a>](docker_compose_download)

<!-- DEVELOPMENT -->
## Development <a name = "development_setup"></a>
Run:
```shell
$ cd django-hello
$ docker-compose up
```

<!-- CONTACT -->
## Contact <a name = "contact"></a>

**Azizul Hakim Shakil** - [@ShakilAzizul](https://twitter.com/ShakilAzizul) - azizulhakim.shakil18@gmail.com

Project Link: [https://github.com/shakil18/django-app-hello](https://github.com/shakil18/django-app-hello)



<!-- REFERENCES -->
## Acknowledgement <a name = "references"></a>
* [Michael Herman](https://testdriven.io/blog/dockerizing-django-with-postgres-gunicorn-and-nginx/)
