# Vertiefung der Kenntnisse in Docker (Bereitstellung Webserver  "Nginx")

* Bisher wurden PHP-Skripte über der PHP-CLI ausgeführt.
1. Welche Technologien sind notwendig um eine "HTML"-Website (keine PHP) über einen Browser anzeigen zu können?
1. Wie können komplexe Technologe-Stacks in Docker effizienter und übersichtlicher genutzt werden?
    1. Ziel: Identifizierung und Benennung des notwendigen Tools.  
1. Erarbeite eine Docker-Technologie-Stack aus den in 1. identifizierten Technologen mithilfe des in 2. benanten Tools.
    1. Ziel: Auslieferung eines einfachen "Hello Docker!" als <h1>
    
   docker run --name my-nginx -v "$PWD":/usr/share/nginx/html -p 80:80 -d nginx
   
* Ans.

* Welche Technologien sind notwendig um eine "HTML"-Website (keine PHP) über einen Browser anzeigen zu können?
Ans. Web server(Nginx)

* Wie können komplexe Technologe-Stacks in Docker effizienter und übersichtlicher genutzt werden?
      1. Ziel: Identifizierung und Benennung des notwendigen Tools.
docker-compose
* Tool for defeining and running multi-container docker applications
* use yaml files to configure application services(docker-compose.yml)
* Can start all services with a single command : docker-compose up
* Can stop all services with a single command : docker-compose down
* can scale up selected services when required