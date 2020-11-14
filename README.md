# myqr
## QR Code scanner for login hotspot MikroTik

### Cómo utilizar

1. Agregar un botón en login.html
```html
<button onclick="window.location='https://jmanuelhk.github.io/myqr';">QR Code</button>
```
2. Agregue el siguiente script en MikroTik via Terminal.
```
/ip hotspot walled-garden ip

add action=accept comment="Mikhmon QR Code Scanner" disabled=no dst-host=laksa19.github.io
```

### Powered by webqr.com
