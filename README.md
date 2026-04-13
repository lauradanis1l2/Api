# Servicio web para registro e inicio de sesión

**Evidencia:** GA7-220501096-AA5-EV01  
**Aprendiz:** Laura Daniela Hernandez Castro

## Descripción
Este proyecto implementa un servicio web para:
- Registrar usuarios
- Iniciar sesión
- Responder con mensaje de autenticación satisfactoria o error

## Endpoints

### POST /api/auth/register
Body:
```json
{
  "usuario": "laura",
  "contrasena": "123456"
}
```

### POST /api/auth/login
Body:
```json
{
  "usuario": "laura",
  "contrasena": "123456"
}
```

## Ejecución
```bash
npm install
npm start
```

## Observación
Se incluye el archivo `enlace_repositorio.txt` para pegar el enlace del repositorio remoto cuando se publique en GitHub o GitLab.
