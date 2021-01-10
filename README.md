<!--
*** Thanks for checking out the my README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->


<!-- PROJECT READY MADE -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->



## Table of Contents

- [Table of Contents](#table-of-contents)
- [DJANGO-HELLO <a name = "about_the_project"></a>](#django-hello-)
- [Installation <a name = "installation"></a>](#installation-)
- [Development Setup <a name = "development_setup"></a>](#development-setup-)
- [Directory Structure <a name = "directory_structure"></a>](#directory-structure-)
- [Usage Example <a name = "usage_example"></a>](#usage-example-)
- [Contact <a name = "contact"></a>](#contact-)
- [Acknowledgement <a name = "references"></a>](#acknowledgement-)



<!-- ABOUT THE PROJECT -->
## DJANGO-HELLO <a name = "about_the_project"></a>

Template for Dockerized Django with Postgres, Gunicorn, and Nginx.



<!-- INSTALLATION -->
## Installation <a name = "installation"></a>

Install docker & docker-compose



<!-- DEVELOPMENT -->
## Development Setup <a name = "development_setup"></a>

Setup development environment:

```shell
cd django-hello
docker-compose up
```



<!-- DIRECTORY STRUCTURE -->
## Directory Structure <a name = "directory_structure"></a>

Here's a project's directory structure:

```text
DJANGO-HELLO
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



<!-- USAGE EXAMPLE -->
## Usage Example <a name = "usage_example"></a>

A few motivating and useful examples of how this product can be used. Spice this up with code blocks and potentially more screenshots.



<!-- CONTACT -->
## Contact <a name = "contact"></a>

**Azizul Hakim Shakil** - [@ShakilAzizul](https://twitter.com/ShakilAzizul) - azizulhakim.shakil18@gmail.com

Project Link: [https://github.com/shakil18/django-hello](https://github.com/shakil18/django-hello)



<!-- REFERENCES -->
## Acknowledgement <a name = "references"></a>
* [Michael Herman](https://testdriven.io/blog/dockerizing-django-with-postgres-gunicorn-and-nginx/)


