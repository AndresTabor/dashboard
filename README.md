# Next.js Dashboard

Este proyecto es un dashboard construido con Next.js, TypeScript y TailwindCSS. Incluye autenticación, manejo de usuarios, clientes, facturas y reportes de ingresos, utilizando una base de datos PostgreSQL.

## Características

- **Next.js App Router**
- **Autenticación con NextAuth**
- **Estilos con TailwindCSS**
- **Conexión a PostgreSQL**
- **Seed de base de datos vía endpoint `/seed`**
- **Componentes reutilizables y diseño responsivo**

## Instalación

1. Clona el repositorio:
   ```sh
   git clone <url-del-repo>
   cd nextjs-dashboard
   ```
2. Instala las dependencias:
   ```sh
   npm install
   ```
3. Configura las variables de entorno en un archivo `.env` basado en el archivo `.env.example`.
4. Ejecuta el seed de la base de datos:
   ```sh
   npm run seed
   ```
5. Inicia el servidor de desarrollo:
   ```sh
   npm run dev
   ```
   Accede a `http://localhost:3000` en tu navegador.

## Uso

- Regístrate como nuevo usuario o inicia sesión con las credenciales de prueba:
  - Email: `admin@admin.com`
  - Contraseña: `admin`
- Navega por las diferentes secciones del dashboard: usuarios, clientes, facturas e ingresos.
- Utiliza el formulario de contacto para enviar mensajes.
- Despliega el menú de usuario para acceder a la configuración y cerrar sesión.

## Contribución

Las contribuciones son bienvenidas. Por favor, sigue estos pasos:

1. Crea un fork del repositorio.
2. Crea una rama para tu característica o arreglo de bug:
   ```sh
   git checkout -b mi-caracteristica
   ```
3. Realiza tus cambios y haz commit:
   ```sh
   git commit -m "Agrega mi caracteristica"
   ```
4. Sube tus cambios a tu fork:
   ```sh
   git push origin mi-caracteristica
   ```
5. Crea un Pull Request en el repositorio original.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

Este README fue generado con ayuda de ChatGPT.

