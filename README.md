# Tutorial Django API

This tutorial will go throw some steps of how to create a simple Rest API using Django. You can follow the [slides here.](https://rencesar.github.io/create-api-django-rest/)


## Setup

1. Clone this repository
    ```
    $ git clone https://github.com/rencesar/supermarket-djangoapi-tutorial.git
    ```
  
1. Generate your Django Secret Key
    * Access this [link](https://www.miniwebtool.com/django-secret-key-generator/) and generate your secret key

1. Add environment variables
    * You can add them permanently
        ```
        $ echo 'export DJANGO_SECRET_KEY=[PUT YOUR SECRET KEY HERE WITHOUT THE SQUARED BRACKETS]' >> ~/.bashrc
        ```

    * or temporarily
        ```
        $ export DJANGO_SECRET_KEY=[PUT YOUR SECRET KEY HERE WITHOUT THE SQUARED BRACKETS
        ```
1. Change file permissions
    ```
    $ chmod +x entrypoint.sh
    ```
1. Install Docker and Docker-compose
    * Follow this [tutorial](https://docs.docker.com/install/)
1. Running applications
    ```
    $ docker-compose up --build
    ```
1. References

    https://blog.restcase.com/restful-api-authentication-basics/  
    https://www.django-rest-framework.org/  
    https://tableless.com.br/entendendo-tokens-jwt/  
    https://testdriven.io/dockerizing-django-with-postgres-gunicorn-and-nginx  
    https://www.getpostman.com/  
    https://medium.com/@marcosrabaioli/django-rest-framework-e-django-oauth-toolkit-c71f8920db08
