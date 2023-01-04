# Título primario

## Título secundario

texto...

* Lista

Escribir **Negritas**

Escribir *Cursivas*

Para escribir código:
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FrontEnd Store</title>
</head>
<body>
    
</body>
</html>
```

# FrontEnd Store

## Crear y definir variables de colores:
--NombreColor: (#color en hexadecimal) - (color en rgb());
```css
--primario: #9c27b0;
```

## Crear y definir variables de fuentes de letra:
--NombreFuente: fuente;
```css
--fuentePrincipal: 'Montserrat', sans-serif;
```

## Pdding y border pasen a formar parte del calculo del ancho de la caja y no lo suman posteriormente
```css
html {
    box-sizing: border-box;
}
*, *:before, *:after {
    box-sizing: inherit;
}
```