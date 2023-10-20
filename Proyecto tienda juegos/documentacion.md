# Proyecto tienda (GameStonks)
## Tienda de videojuegos 
Enlace de pagina de [GAME](https://www.game.es/) para referencia.

La página tratara de abarcar de forma minimalista, la venta de juegos nuevos y de segunda mano, entre otros artículos.

## Wireframe
[Boceto](/Proyecto%20tienda%20juegos/img/boceto.png)

[Boceto Movil](/Proyecto%20tienda%20juegos/img/boceto_movil.png)

[Login PC](/Proyecto%20tienda%20juegos/img/login_pc.png)

[Login Movil](/Proyecto%20tienda%20juegos/img/login_movil.png)

[Producto PC](/Proyecto%20tienda%20juegos/img/producto_pc.png)

[Producto Movil](/Proyecto%20tienda%20juegos/img/producto_movil.png)

En el boceto hay que destacar una cosa:
- El carrito de la compra no apareceria hasta que el usuario se registrara o iniciara sesión (en la versión de movil, para verlo tendría que darle desde el submenu de su cuenta).

## Logo
![logo](./img/logo.png)

## Colores

- Los colores utilizados para el proyecto van a ser tonos naranja pastel, los cuales presentaremos en el siguiente HTML

```
<!DOCTYPE html>
<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	
	<title>Colores</title>
	

<style type="text/css">

.primary-1 { background-color: #FFC398 }
.primary-2 { background-color: #FCA86C }
.primary-0 { background-color: #DF8443 }
.primary-3 { background-color: #C36320 }
.primary-4 { background-color: #9B470B }

.secondary-1-1 { background-color: #FFD098 }
.secondary-1-2 { background-color: #FCBA6C }
.secondary-1-0 { background-color: #DF9843 }
.secondary-1-3 { background-color: #C37820 }
.secondary-1-4 { background-color: #9B590B }

.secondary-2-1 { background-color: #FFAF98 }
.secondary-2-2 { background-color: #FC8D6C }
.secondary-2-0 { background-color: #DF6643 }
.secondary-2-3 { background-color: #C34420 }
.secondary-2-4 { background-color: #9B2B0B }

body {
	margin:0; padding: 2em;
	background: #fff;
	color: #000;
	font: 12px/1.33 "Segoe UI", "Helvetica Neue", Helvetica, sans-serif;
	text-align:left;
	}
h1 {
	margin: 0.5em 0;
	font-size: 200%;
	}
p {
	margin: 0.5em 0;
	}

.color-table {
	margin: 2em 2em 5em;
	border-collapse:collapse;
	border:none;
	border-spacing:0;
	font-size:100%;
	}
.color-table th {
	padding: 0 1em 0 0;
	text-align: right;
	vertical-align: middle;
	font-size: 100%;
	font-weight: normal;
	border: none;
	}
.color-table td.sample {
	width:6em; height:6em;
	padding: 10px;
	text-align:center;
	vertical-align:middle;
	font-size:90%;
	border: 1px solid white;
	white-space:nowrap;
	}
.color-table td.sample-0 {
	width:18em;
	}
.color-table.small td.sample {
	width:3em; height:3em;
	padding:0;
	border:none;
	}
.color-table.small td.sample-0 {
	width:9em;
	}
.color-table .white { margin-bottom:0.2em; color:white }
.color-table .black { margin-top:0.2em; color:black }

hr {
	margin: 2em 0 1em 0;
	border:none;
	border-bottom:1px solid silver;
	}
#footer {
	padding:1em;
	text-align:center;
	font-size:80%;
	}

</style>

</head>
<body>

<h1>Colores utilizados para "GameStonks"</h1>
<br>
<h2>Se ha utilizado el sistema de colores adyacentes al primario</h2>

<table class="color-table">
	<tbody><tr>
		<th><b>Colores primarios:</b></th>
		<td class="sample sample-1 primary-1">
			<div class="white">#FFC398</div>
			<div class="black">#FFC398</div>
		</td>
		<td class="sample sample-2 primary-2">
			<div class="white">#FCA86C</div>
			<div class="black">#FCA86C</div>
		</td>
		<td class="sample sample-0 primary-0">
			<div class="white">#DF8443</div>
			<div class="black">#DF8443</div>
		</td>
		<td class="sample sample-3 primary-3">
			<div class="white">#C36320</div>
			<div class="black">#C36320</div>
		</td>
		<td class="sample sample-4 primary-4">
			<div class="white">#9B470B</div>
			<div class="black">#9B470B</div>
		</td>
	</tr>
	<tr>
		<th><b>Colores secundarios 1:</b></th>
		<td class="sample sample-1 secondary-1-1">
			<div class="white">#FFD098</div>
			<div class="black">#FFD098</div>
		</td>
		<td class="sample sample-2 secondary-1-2">
			<div class="white">#FCBA6C</div>
			<div class="black">#FCBA6C</div>
		</td>
		<td class="sample sample-0 secondary-1-0">
			<div class="white">#DF9843</div>
			<div class="black">#DF9843</div>
		</td>
		<td class="sample sample-3 secondary-1-3">
			<div class="white">#C37820</div>
			<div class="black">#C37820</div>
		</td>
		<td class="sample sample-4 secondary-1-4">
			<div class="white">#9B590B</div>
			<div class="black">#9B590B</div>
		</td>
	</tr>
	<tr>
		<th><b>Colores secundarios 2:</b></th>
		<td class="sample sample-1 secondary-2-1">
			<div class="white">#FFAF98</div>
			<div class="black">#FFAF98</div>
		</td>
		<td class="sample sample-2 secondary-2-2">
			<div class="white">#FC8D6C</div>
			<div class="black">#FC8D6C</div>
		</td>
		<td class="sample sample-0 secondary-2-0">
			<div class="white">#DF6643</div>
			<div class="black">#DF6643</div>
		</td>
		<td class="sample sample-3 secondary-2-3">
			<div class="white">#C34420</div>
			<div class="black">#C34420</div>
		</td>
		<td class="sample sample-4 secondary-2-4">
			<div class="white">#9B2B0B</div>
			<div class="black">#9B2B0B</div>
		</td>
	</tr>
</tbody>
</table>
<h2>Se han utilizado estos colores ya que son cálidos y reconfortantes, transmitiendo espíritu y confianza. </h2>
</body>
</html>
```


