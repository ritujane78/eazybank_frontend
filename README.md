# BankAppUi

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.3.

# Backend
The backend code in Spring Boot (https://github.com/ritujane78/eazybank_backend) runs at `http:localhost:8080`.

# Authorization Server
Keycloak authorization server runs on docker with command
  
  docker run -p 127.0.0.1:8081:8080 -d \
  -e KC_BOOTSTRAP_ADMIN_USERNAME=admin \
  -e KC_BOOTSTRAP_ADMIN_PASSWORD=admin \
  quay.io/keycloak/keycloak:26.5.0 start-dev


  Keycloak will be available at:
    
    http://127.0.0.1:8081

  ## Keycloak Configuration Steps

        Create a new Realm

        Create Clients

        Create Users

        Create and assign Roles (USER / ADMIN)

        Configure and enable the required Grant Types for each client
  
## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
