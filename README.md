Este es un proyecto en Next.js con el fin de explicar cómo desplegar una tienda con su respectiva base de datos desde vercel y poder hacer la reportería desde Grafana.

## Requerimientos:
- Tener instalado Node.js versión 18 o superior.
- Tener cuenta en GitHub
- Tener cuenta en Vercel.com
- Tener cuenta en Grafana

## Pasos:
1. Forkear este repositorio en GitHub a tu propio repo de GitHub 
2. Crear una cuenta en Vercel.com
3. Conectar tu cuenta de Github a Vercel.com
4. Importar el Proyecto la-tienda a tu cuenta de Vercel
5. No te preocupes, te va a dar un error cuando se te esté desplegando la aplicación.  :)
6. Ir a STORAGE y conectar una base de datos en POSTGRES
7. Conectar el proyecto la-tienda a la base de datos de POSTGRES
8. Clonar el proyecto a tu computador local 
```bash
git clone $URL
cd la-tienda
npm install
export POSTGRES_URL= $DATABASE
npx prisma migrate dev
npx prisma db seed
```
9. Volver a Vercel, a DEPLOYMENTS y re-deployar la aplicación
10. Ahora en la aplicación se puede utilizar, tocando el boton VISIT.
11. FELICITACIONES! Puedes probar la aplicación.

## Reportería con Grafana

1. Ir a Grafana y crearse una cuenta conectando tu cuenta de GitHub.
2. Instanciar un Grafana
3. Crear un datasource 
4. Agregar la configuración que venga desde el storage de Vercel
5. Crear Graficos.

## Consultas de SQL 
