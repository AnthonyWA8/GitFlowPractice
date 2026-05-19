# Nombre del Proyecto

API de Práctica Git Flow

## Descripción

Este proyecto es una mini API construida con Express para practicar Git Flow en una actividad guiada.

La API tiene un endpoint de estado que permite comprobar que el servidor está funcionando correctamente.

## Instalación

### Requisitos mínimos

- Node.js 20 o superior
- npm

### Pasos

~~~bash
git clone https://github.com/TU_USUARIO/NOMBRE_DEL_REPO.git
cd NOMBRE_DEL_REPO
npm install
~~~

## Uso

### Levantar el servidor local

~~~bash
npm start
~~~

### Probar el endpoint

~~~bash
curl http://localhost:3008/api/estado
~~~

### Respuesta esperada

~~~json
{
  "ok": true,
  "mensaje": "API de práctica Git Flow funcionando",
  "version": "1.0.0"
}
~~~

Si usas navegador, abre:

~~~text
http://localhost:3008/api/estado
~~~

## Autores

- Anthony — Desarrollador
- Camila — Analista

## Flujo de trabajo Git

Durante la práctica se utilizará Git Flow con las siguientes ramas:

- `main`: rama principal y estable.
- `develop`: rama de integración.
- `feature/readme-base`: rama para crear la primera versión del README.
- `feature/documentacion-extra`: rama para mejorar la documentación.
- `release/v1.0.0`: rama para preparar la entrega final.
- `hotfix/readme-typo`: rama para corregir un error menor.

La versión final se marcará con el tag `v1.0.0`.