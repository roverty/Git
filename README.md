#  Curso git

```shell
Mayo 2021
Author : rhodfra@gmail.com
git  2.28.0 | gitub | gitlab | bitbucket
```
<p align="center">
    <img src="img/cover.jpg" alt=cover>
</p>

El objetivo de este curso es conocer las herramientas básicas de git. También se esbozará un panorama general de como funciona el desarrollo colaborativo (ya se para un proyecto público o privado) utilizando github, gitlab e inclusive bitbucket. Para poder desarrollar software con un equipo de trabajo es necesario conocer todas la buenas prácticas posibles, analizaremos eso y más.

No se requiere de ningún antecedente previo.

## Cheatsheet

### Configuración de editor

```sh
git --global core.editor nvim
```

### Git log en forma de grafo

```sh
git log --all --decorate --oneline --graph
```

### Cache credentials

Esta opción permite guardar temporalmente las credenciales del usuario para no ponerlas a cada rato. 

*Solo funciona con repositorio que usa HTTPS*

* Set git to use the credential memory cache

  ```sh
  git config --global credential.helper cache
  ```

* Set the cache to timeout after 1 hour (setting is in seconds)

  ```sh
  git config --global credential.helper 'cache --timeout=3600' 
  ```

## Temario

0. Instalación y configuración de git

1. Introducción

   1. ¿Qué es un CVS?
   2. Tipos de CVS

2. ¿Que es git?

   1. Arquitectura de git

3. Comandos básicos de git

4. Ramas

5. Repositorios remotos

6. Flujos de trabajo (workflows)

   1. Flujo de trabajo para proyecto *open source*
   2. Flujo de trabajo para proyecto *privados* 

7. Buenas prácticas

   1. Convenciones acerca de las ramas
   2. Convenciones para realizar un commit
   3. Convenciones de lenguaje
   4. Convenciones de nombrado de variables, funciones, constantes, etc.

8. Herramientas para integrar con git

## Bibliografía

* [The Definitive Guide to Forks and Branches in Git](https://blog.gitprime.com/the-definitive-guide-to-forks-and-branches-in-git/)

* [Consejos para el Código Abierto](https://eddiejaoude.github.io/book-open-source-tips/index-es.html#_god_pull_request)
* [under_scores, camelCase and PascalCase - Naming Conventions](https://dev.to/prahladyeri/underscores-camelcasing-and-pascalcasing-the-three-naming-conventions-every-programmer-should-be-aware-of-3aed) 

