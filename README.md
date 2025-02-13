# Zalando Auto Buy

Zalando Auto Buy es una extensión de Chrome que permite comprar zapatillas de manera automática en Zalando con un solo clic, mostrando las tallas disponibles directamente en la página de listado de productos.

## Características
✅ Muestra las tallas disponibles sin necesidad de entrar en la página del producto.  
✅ Compra automática al hacer clic en una talla.  
✅ Utiliza los datos guardados en la cuenta de Zalando para una compra rápida.  
✅ Interfaz minimalista que no interfiere con la experiencia del usuario.  

## Instalación
1. Clona este repositorio:
   ```sh
   git clone https://github.com/tuusuario/zalando-auto-buy.git
   ```
2. Abre Google Chrome y ve a `chrome://extensions/`.
3. Activa el **modo desarrollador**.
4. Haz clic en **Cargar extensión sin empaquetar** y selecciona la carpeta del proyecto.
5. La extensión se instalará y estará lista para usarse.

## Uso
1. Navega a Zalando.
2. La extensión inyectará las tallas disponibles en la página principal de productos.
3. Haz clic en una talla para proceder automáticamente a la compra.

## Estructura del Proyecto
```
/zalando-auto-buy
│── /src
│   ├── background.js       # Procesos en segundo plano
│   ├── content.js          # Inyecta tallas y maneja la compra
│   ├── ui.js               # Lógica de la interfaz
│   ├── purchase.js         # Compra automática
│── /popup
│   ├── popup.html          # Interfaz emergente
│   ├── popup.js            # Lógica de la UI del popup
│── /icons
│   ├── icon.png            # Icono de la extensión
│── manifest.json           # Configuración de la extensión
│── README.md               # Documentación
│── main.js                 # Punto de entrada
```

## Contribución
¡Las contribuciones son bienvenidas! Para mejorar la extensión:
1. Haz un fork del repositorio.
2. Crea una rama (`git checkout -b feature-nueva`).
3. Haz tus cambios y confirma (`git commit -m 'Añadir nueva funcionalidad'`).
4. Sube los cambios (`git push origin feature-nueva`).
5. Abre un Pull Request.

## Licencia
Este proyecto está bajo la licencia MIT.
