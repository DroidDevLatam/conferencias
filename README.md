Conferencias
===========

Una lista de las conferencias para Desarrolladores Android en LatAm.


Agregar una conferencia
-------------------

Enviar un pull-request que añada un archivo al directorio `_conferences/` 
con un nuevo archivo representando la conferencia. El archivo debe llevar
el nombre de la conferencia, el año, y llevar la extensión `.md` (por
ejemplo, `my-cool-conference-2016.md`).

El contenido del archivo debería contener el siguiente formato:
```
---
name: "Droid4Droids"
website: http://co.d4d.com/2016/
location: Bogota, CO

date_start: 2015-10-29
date_end:   2015-10-30

cfp_start: 2015-06-16  # Optional
cfp_end:   2015-07-21  # Optional
cfp_site: http://co.d4d.com/2015/lineup-2015/ # Optional, will default to website
---
```

*Nota: No incluya la ubicación de la conferencia en el nombre. La conferencia listada en el ejemplo se refiere al "Droid4Droids Bogotá", sin embargo, encontramos que incluir la ubicación como parte del nombre se torna redundante.*


Ejecutar localmente
---------------

```
bundle install --path vendor/bundle
bundle exec jekyll serve
```

Una vez ejecutado el sitio web puede ser accedido desde http://localhost:4000.


License
-------

Esta lista está basada en el original https://github.com/AndroidStudyGroup/conferences
All content is [CC0][1].


 [1]: https://creativecommons.org/publicdomain/zero/1.0/
