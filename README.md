# Liga Sudamericana :soccer: :soccer:

Este repositorio contiene un sistema para la organización de la liga sudamericana de clubes generado con Golang y Angular 7 (Ngx-Admin) como prueba de microservicios para la Oficina Asesora de Sistemas. 

## Descripción

El presente repositorio tiene 1 directorio denominado Persistencia con los modelos de datos establecidos.

![Modelo de datos](https://github.com/macaguegi/campeonato_oas/blob/master/persistencia/sudamericana.png)
Además tiene 4 CRUD APIs denominadas

    - paises_crud
    - equipos_crud
    - partidos_crud
    - liga_sudamericana_crud
    
Las APIs mencionadas previamente se conectan a través de un MID API denominada sudamericana_mid . 

El MID API es quien interactua directamente con el cliente llamado sudamericana_cliente que está montado en Angular 7 con la plantilla ngx-admin .
## Ejecución :arrow_forward:
Clonar este repositorio
```sh
$ git clone https://github.com/macaguegi/campeonato_oas.git
$ cd campeonato_oas
```
Entrar a cada API que tiene el repositorio y dentro de cada uno de estos directorios (cada uno en una terminal diferente) ejecutar el comando 
```sh
$ bee run
```

## Licencia :heavy_check_mark:

This file is part of campeonato_oas.

campeonato_oas is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

Foobar is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with Foobar. If not, see https://www.gnu.org/licenses/.
