# Proyecto Angular Material

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.0.4.

## Instalación de Angular Material

Angular material es un conjunto de componentes e iconos diseñados bajo la guia de estilo de Material Design propuesta por Google para el desarrollo de aplicaciones móviles y web

- Visitar el sitio de [Angular Material](https://material.angular.io/) para obtener la información más actualizada
- Ejecutar el siguiente comando
```
ng add @angular/material
```
Esto instalará **Angular Material** sobre nuestro proyecto de Angular, así como el **CDK (Component Development Kit)** y **Angular Animation**.

Como parte de la instalación, el asistente preguntará sobre el tema (conjunto de estilos visuales) a usar en la aplicación, si se desea establecer la tipografía usada por Angular Material de forma global en la aplicación (fuente e iconos), así como configurar las animaciones del navegador para Angular Material; este último de suma importancia para poder proyectar los efectos visuales incorporados en la mayoría de los componentes de dicha librería.

#### Angular Material Schematics

Angular Material viene empaquetado con un generador automático de esquemas (scafolding) **Angular CLI schematics** para nuestras aplicaciones de Angular, son componentes preconstruidos a partir de componentes de Angular Material los cuales se pueden crear a traves del siguiente comando

```
ng generate @angular/material:tipo-esquema nombreComponente
```

Entre los esquemas que se pueden generar tenemos

- address-form, address-form, address-form, tree, table, address-form	

Por buenas prácticas, se recomienda agrupar este tipo de componentes bajo un módulo que gestione todo lo relacionado a Angular Material, e importarlo según corresponda en nuestra aplicación