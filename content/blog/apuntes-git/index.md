---
title: Mis apuntes git, conceptos y comandos
date: "2021-12-02T22:12:03.284Z"
description: 'Mis apuntes git, conceptos y comandos'
inHome: true
---

## Introducción

Aprender Git es fundamental en el desarrollo de software, no importa qué tecnología utilices, o si trabajas de forma individual o en grupo.

Usualmente Git trabaja de una manera formidable si es orientado al código, porque Git va a poder analizar los archivos, determinar qué cambió, hacer uniones de código, y todo de manera automática.

Ahora, va a llegar un punto donde Git no lo va a poder hacer de manera automática, como cuando dos personas tocan el mismo código, se produce un conflicto y en esos casos Git necesita que ese conflicto se resuelva manualmente.

Enfrentarse a conflictos es algo normal, no hay que asustarse, e incluso existen técnicas para evitar tener una gran cantidad de conflictos.

Solo veremos la utilización de Git a través de comando de consola, para poder abarcar todos los conceptos necesarios, luego con esa información aprendida es sencillo que cada quien elija el gestor gráfico de repositorios Git que más le guste.


## Conceptos

.

## Comandos


#### Conocer la versión instalada de Git

```
git --version
```

#### Visualizar el contenido de ayuda del comando de Git

Ver la ayuda general:

```
git help
```

Ver la ayuda de un subcomando específico:

```
git help commit
```

#### Configuración inicial de Git

Configurar el nombre del usuario:

```
git config --global user.name = "Fabian Karaben"
```

Configurar el nombre del usuario:

```
git config --global user.email = "fabian@example.com"
```

Ver y opcionalmente editar la configuración actual del usuario:

```
git config --global -e
```
