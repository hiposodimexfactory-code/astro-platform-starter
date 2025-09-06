# 🚀 Guía paso a paso: Despliega tu web Astro en Vercel

---

## 1. Crea tu cuenta en Vercel

Ve a [https://vercel.com/signup](https://vercel.com/signup) y regístrate (puedes usar tu cuenta de GitHub para mayor facilidad).

![Registro en Vercel](https://user-images.githubusercontent.com/6740217/228404833-21eafc98-6e6d-46e1-9fa6-3d3d2ce1b4f9.png)

---

## 2. Sube tu proyecto a GitHub

Si ya tienes tu repo en GitHub, ¡sigue al paso 3!

Si no, abre una terminal y ejecuta:
```bash
git init
git add .
git commit -m "Versión inicial"
git branch -M main
git remote add origin https://github.com/hiposodimexfactory-code/astro-platform-starter.git
git push -u origin main
```
![Push a GitHub](https://user-images.githubusercontent.com/6740217/228405038-e4a7d718-0e1a-46e6-b3e2-4f6e7c7b5b5b.png)

---

## 3. Importa tu repositorio en Vercel

### a) Haz clic en **Add New Project** o **New Project**  
![Add Project](https://user-images.githubusercontent.com/6740217/228405245-1f6c8c7e-4e2a-4f23-8cb3-9a6498dc12c3.png)

### b) Selecciona tu repositorio  
Busca y haz clic en `astro-platform-starter`  
![Selecciona repo](https://user-images.githubusercontent.com/6740217/228405334-4090b42e-4d94-4c3e-a9d8-1c3f5a4c1f2b.png)

---

## 4. Configura el proyecto (opcional)

Vercel detectará Astro, pero si te lo pregunta:
- **Framework Preset:** Astro
- **Build Command:** `npm run build`
- **Output Directory:** `dist`

![Configuración Astro](https://user-images.githubusercontent.com/6740217/228406016-8ecb2a0b-7a2a-4d6e-8192-9b9a6f8f4c4a.png)

---

## 5. Haz clic en **Deploy**

![Deploy button](https://user-images.githubusercontent.com/6740217/228406079-3ec7c0d6-0b1f-47c6-8e4d-4ac1f4ea6f0c.png)

---

## 6. ¡Listo! Tu web estará disponible en una URL pública

Ejemplo:  
`https://astro-platform-starter.vercel.app`

![Proyecto desplegado](https://user-images.githubusercontent.com/6740217/228406234-5d7f0b3d-2d5c-4f7a-8c2d-0e9d4c8f970b.png)

---

## 7. Actualiza tu web fácilmente

Cada vez que hagas cambios y los subas a GitHub (`git push`), Vercel los desplegará automáticamente.

---

¿Tienes dudas o algún error?  
- Revisa los logs en Vercel (“View Build Logs”).
- Asegúrate de tener las imágenes en `/public` y todo tu código en el repo.
- Si necesitas más ayuda, ¡dímelo!