# Tipos primitivos
```yaml
ciudad: Madrid
pais: "Mexico"
edad: 23
temperatura: 23.4
activo: true
verificado: yes
descripcion: null
```

# Lista
```yaml
colores: 
	- rojo
	- azul
	- verde
```

# Mapas
```yaml
persona: 
	nombre: juan
	edad: 32
```

# Listas de valores
```yaml
usuarios:
	- nombre: juan
		edad: 33
	- nombre: pedro
		edad: 44
```

# Modificadores de strings
```yaml
mensaje: |
	Hola, 
	Mundo
	
mensaje: >
	Hola, 
	Mundo
```

# Herencia
```yaml
item0: &item0
	color: blue
	size: sm

item1:
	<<: *item0
	color: red
	
item2:
	<<: *item0
	size: lg
```

	