# 🍲 MichiKay - Gestión de Pedidos (Cusco)

**MichiKay** es una startup enfocada en la gestión de pedidos de comida local en Cusco, Perú.  
Este sistema web permite conectar restaurantes tradicionales con clientes de forma eficiente.

---

## 🛠️ Stack Tecnológico

- **Frontend:** Next.js 14 (App Router) + TypeScript
- **UI:** Tailwind CSS + shadcn/ui
- **Backend:** API Routes de Next.js
- **Base de Datos:** PostgreSQL + Prisma ORM
- **Autenticación:** NextAuth.js

---

## 📁 Estructura del Proyecto

```text
/michikay
├── app/             # Rutas (Auth, Dashboard, Menú, Pedidos, API)
├── components/      # UI, Layout y lógica de componentes
├── lib/             # Prisma client, Auth config y utilidades
├── prisma/          # Modelos de base de datos
├── public/          # Recursos estáticos
└── types/           # Definiciones de TypeScript
```

---

## 🚀 Instalación y Configuración

### 1️⃣ Instalar dependencias

```bash
npm install
```

### 2️⃣ Configurar variables de entorno

Crea un archivo `.env` basado en `.env.example` y configura tu conexión a PostgreSQL.

```env
DATABASE_URL="postgresql://usuario:password@localhost:5432/michikay"
NEXTAUTH_SECRET="tu_secreto"
NEXTAUTH_URL="http://localhost:3000"
```

### 3️⃣ Sincronizar Base de Datos

```bash
npx prisma migrate dev --name init
```

### 4️⃣ Iniciar servidor de desarrollo

```bash
npm run dev
```

La aplicación estará disponible en:

```text
http://localhost:3000
```

---

## 📋 Modelos de Base de Datos

El sistema utiliza 5 modelos principales en Prisma:

### 👤 User
Gestión de usuarios y roles del sistema.

### 🍽️ Restaurant
Información de restaurantes afiliados.

### 🍛 MenuItem
Platos y productos disponibles en el menú.

### 🧾 Order
Gestión y seguimiento del estado de los pedidos.

### 📦 OrderItem
Detalle de productos incluidos en cada orden.

---

## 🔐 Funcionalidades Principales

- Registro e inicio de sesión
- Gestión de restaurantes
- Administración de menús
- Creación y seguimiento de pedidos
- Panel administrativo
- Gestión de usuarios y roles

---

## 🧑‍💻 Tecnologías Utilizadas

| Tecnología | Uso |
|---|---|
| Next.js 14 | Framework Full Stack |
| TypeScript | Tipado estático |
| Tailwind CSS | Estilos |
| shadcn/ui | Componentes UI |
| Prisma ORM | Acceso a base de datos |
| PostgreSQL | Base de datos |
| NextAuth.js | Autenticación |

---

## 📌 Estado del Proyecto

🚧 Proyecto en desarrollo.

---

## 📄 Licencia

Proyecto desarrollado para fines académicos y startup local en Cusco, Perú.

---

# Startup MichiKay - Cusco © 2026