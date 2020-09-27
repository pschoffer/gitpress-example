# GitPress Example

The objective here is to create example project for the ![Gitpress platform](https://github.com/pschoffer/gitpress).
Its very easy to install and you can try it easily home.

## Instalation

 ### Using Docker container
  You can start by fetching the example project.

 ```
  docker run -p 80:80 -d \
     --env "GITPRESS_MODE=FETCH" \
     --env "WORDPRESS_URL=http://localhost/" \
     --env "GIT_ORIGIN=github.com/pschoffer/gitpress-example.git" \
     pschoffer/gitpress
 ```

Docker compose version:

 ```
 version: '3.1'

 services:
   gitpress:
     image: pschoffer/gitpress
     ports:
       - 80:80
     environment:
       GITPRESS_MODE: FETCH
       WORDPRESS_URL: http://localhost/
       GIT_ORIGIN: github.com/pschoffer/gitpress-example.git
 ```

The admin login credentials are `gitpress:pass`		

## System Requirements

- ![Docker](https://www.docker.com/) 

## License
This is a GitPress example, GitPress is free software, and is released under the terms of the <abbr>GPL</abbr> (GNU General Public License) version 2 or (at your option) any later version. See ![license.txt](license.txt).




