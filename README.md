

# Berta Rojas Project Site

La idea de este proyecto fue desarrollar un site, que partiendo de la información existente en el site oficial de la artista, nos permitiese tener una visión más moderna del mismo, sin perder la sobriedad y respeto que tan maravillosa guitarrista clásica se merece


## Uso de los fuentes


Descarga los fuentes.

Si deseas modificar los estilos del proyecto que estan en /css/styles.css, hay que habilitar SASS para que compile el /scss/main.scss y genere el /css/style.css.

Para ello hay que instalar node, que nos generará una carpeta node_modules.

Instalar SASS

y luego desde una consola bash o desde una terminal de Visual Code corriendo bash, ejecutar el siguiente comando para habilitar SASS. 

```bash
  npm run watch-css
```

de esta manera SASS estará esperando cambios para impactar en el archivo final /css/style.css, que es el que usa el portal.

| archivo SASS    | Función                                                                              |
|-----------------|-------------------------------------------------------------------------------------|
| main.scss       | en este scss se importan todos los demás que impactan sobre /css/style.css          |
| variables.scss  | definición de variables de SASS que usa el SCSS                                     |
| reset.scss      | resetear vsalores que por defecto ponen los navegadores como border y padding       |
| layout.scss     | estilos generales del site                                                          |
| footer.scss     | se define el estilo del footer                                                      |
| grids.scss      | en este se definen los estilos de grids que usa el site en versión mobile y desktop |
| cards.scss      | estilos propios de las cards                                                        |
| mixins.scss     | se usa para generar botones customizados                                            |
| extends.scss    | se usó porque lo pedía una entrega y se armaron estilo de flex                      |

    
## Links externos en Head de cada página

| Tool         | Para                                                             |
| -------------| ------------------------------------------------------------------ |
| Boostrap 5.0 | Para el navbar y formulario de contacto. a través de link en Head|
| Font-awesome | Iconos de redes sociales - usa link en head |
| GoogleFonts  | Famila de fonts especiales - usa link en head|
| Animate      | Para efectos de animación en página 404 - not found - usa link en página de error en head|

  
## Autor

- [@gaballester](https://github.com/gaballester)
- Los datos son extraidos desde la página oficial de Berta Rojas, esta es solo una prueba de un estilo diferente y el site está motivado por la profunda admiración que tengo por su trabajo y estilo de vida.
