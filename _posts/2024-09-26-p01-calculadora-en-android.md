---
layout: post
title: P01 - Calculadora en Android
date: 2024-09-26 11:12 +0200
categories: [Desarrollo de Aplicaciones Multiplataforma, Programación Multimedia y Dispositivos móviles]
tags: [desarrollo de aplicaciones multiplataforma, Programación Multimedia y Dispositivos móviles, dam2, lmsgi]
---
## APP NATIVA CALCULADORA  

La primera práctica que vamos a realizar este curso va a ser una calculadora. La App contiene los mismos tipos de vistas que hemos realizado en la de la Edad Canina. El resultado final que se pide es el siguiente:  

### A. UI en el XML  

1. Lo primero que tendrás que hacer es el diseño de la `Activity Principal`. Al igual que en la App canina, has de usar un `LinearLayout` vertical. Lo único “nuevo” es que dentro de ese `LinearLayout` deberás introducir otro (horizontal) para la línea de los botones.  

### B. Archivo.kt  

1. Tienes que configurar los `Views` que has necesitado y necesitarás para crear la lógica de la App.
2. A `boton1`, `boton2`, `boton3`, y `boton4` les tendrás que dar la lógica correspondiente en el evento `onClick` para que resuelvan la operación.  
3. Usa `DataBinding`.

![App Calculadora](/assets/img/pmdm/practicas/P01-AppCalculadora.png)

---

## 2. ASPECTOS A TENER EN CUENTA  

Los aspectos a tener en cuenta para la valoración de la práctica serán los mismos que en la aplicación del perrito. Son los siguientes:  

- La app debe realizar los cálculos correctamente y mostrar el resultado en el lugar correspondiente.  
- Deben tenerse en cuenta los errores a la hora de introducir los caracteres numéricos.  
- En ese caso se debe indicar mediante un mensaje `Toast`.  
- La app será multilenguaje: en inglés y español.  
- La app tendrá un icono.

---

## 3. ENTREGA DE LA PRÁCTICA  

El tiempo máximo para presentar la App será el **Lunes 30 de Septiembre**.  
La entrega de la app la realizaréis por `Github-Classroom`.