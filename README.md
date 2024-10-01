# Gestión de bases de datos relacionales en R
Este repositorio contiene el código fuente de la presentación "Gestión de bases de datos relacionales en R" presentada en el [Meetup de R-Ladies Barranquilla](https://www.meetup.com/es-ES/rladies-barranquilla/events/302078872/).

Para poder correr el código de la presentación, es necesario instalar las siguientes librerías:  
- `RSQLite`  
- `DBI`  
- `readr`
- `dplyr`

Para instalar las librerías, se puede correr el siguiente código en R: 
`install.packages(c("RSQLite", "DBI", "readr", "dplyr"))`.

Recuerda que es necesario también instalar un program de SQL en tu computador. Aquí utilicé [MariaDB](https://mariadb.org/download/?t=mariadb&p=mariadb&r=11.4.2&os=windows&cpu=x86_64&pkg=msi&mirror=realworldgroup) que es una versión libre, pero puedes utilizar cualquier otro programa de SQL como MySQL, PostgreSQL, etc.

En este repositorio usamos datos de distribución de *Mycteroperca olfax* o bacalao desde GBIF, los cuales puedes descargar [aquí](https://doi.org/10.15468/dl.wychnv). Incluimos una pequeña versión de los datos descargados en la carpeta `data`.

