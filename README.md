# section-filemanager-react
Section FileManager es una forma rapida de generar un gestor de archivos en react, es muy simple de parametrizarlo desde API.

### Requiere
Para utilizar este paquete es necesario implementar el API escrito en cualquiera de los siguietes lenguajes:
- PHP/Laravel [section-file-manager-laravel](https://github.com/ivanfretes/section-filemanager-laravel) 
- Python/Django [section-file-manager-django](#) 
- Ruby/Rails [section-file-manager-rails](#) 

### Instalación

Importar Componente
```sh
  $ npm install section-filemanager-react
```


### Ejemplo

Importar Componente
```js
  import SectionFileManager from SectionFileManager
```

Implementación básica

```html
  <SectionFileManager
      urlGetOption="..."
      urlGetFileUpload="..."                  
  />
```

### Etiqueta \<SectionFileManager\/\>
<table>
  <tr>
    <th>Atributo</th>
    <th>Descripción</th>
    <th>Tipo de Parametro</th>
    <th>Tipo de Atributo</th>
    <th>Valor por defecto</th>
    <th>Requerido</th>
  </tr>
  <tr>
    <th>urlGetOption</th>
    <th>Listado de opciones disponibles definidas en API</th>
    <th>String</th>
    <th>Simple</th>
    <th>--</th>
    <th>No</th>
  </tr>
  <tr>
    <th>urlGetFileUpload</th>
    <th>Url para consultar los archivos</th>
    <th>String</th>
    <th>Simple</th>
    <th>--</th>
    <th>No</th>
  </tr>
    <tr>
    <th>urlPostFileUpload</th>
    <th>Url a donde subir el archivo</th>
    <th>String</th>
    <th>Simple</th>
    <th>--</th>
    <th>No</th>
  </tr>
    <tr>
    <th>sectionId</th>
    <th>Si la subida corresponde a solo a una sección en particular</th>
    <th>String|id</th>
    <th>Simple</th>
    <th>--</th>
    <th>No</th>
  </tr>
</table>

### Por hacer
- Agregar atributo typeOption="select|row|listFormat:image|listFormat:table" (Para indicar el formato de salida/vista del componente)
- Paquete para django y ruby
- Para otros frameworks
- Agregar Test
