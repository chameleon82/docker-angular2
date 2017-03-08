# docker-angular2

## Run as quickstart preview
Run container for preview angular quickstart
``docker run -d -p 8080:8080 -p 3000:3000 -p 3001:30001 chameleon82/angular2``

- localhost:3000 - your application
- localhost:3001 - BrowserSync panel
- localhost:8080 - weinre debugger

## Run as development app

Mount host path with angular app sources on /var/www/angular/src, for example ``-v //c/dev/angular/src:/var/www/angular/src``
