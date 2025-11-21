🌍 Mercantilix — Plataforma de Comercio Mercantilista entre Países

Mercantilix es una plataforma web experimental que simula dinámicas mercantilistas entre países, permitiendo analizar flujos comerciales, balanzas económicas, políticas arancelarias y estrategias competitivas.
Este proyecto combina visualización de datos, simulación económica y análisis comparativo en tiempo real.

🚀 Características principales

Simulación económica en tiempo real:
Modelos simplificados basados en teorías mercantilistas clásicas y neomercantilistas.

Tablero interactivo:
Visualización de:

Exportaciones e importaciones

Balanza comercial

Acuerdos bilaterales

Materias primas estratégicas

Motor de políticas comerciales:
Los países pueden:

Modificar aranceles

Establecer monopolios

Administrar reservas de oro

Crear tratados económicos

API REST para acceso a datos internacionales generados por la simulación.

Sistema de roles (investigador, analista, administrador).

🛠️ Tecnologías utilizadas

Frontend: React + Vite + TailwindCSS

Backend: Node.js + Express

Base de datos: PostgreSQL

Visualización: D3.js

Autenticación: JWT + OAuth opcional

Infraestructura: Docker + Railway/Render (deployment)

📦 Instalación
git clone https://github.com/tuusuario/mercantilix.git
cd mercantilix

Backend
cd server
npm install
npm run dev

Frontend
cd client
npm install
npm run dev

🔧 Configuración

Crea un archivo .env en el servidor:

DATABASE_URL=postgres://usuario:password@localhost:5432/mercantilix
JWT_SECRET=supersecreto
PORT=4000


Y otro en el cliente:

VITE_API_URL=http://localhost:4000

🧪 Tests
npm test


Incluye tests unitarios y de integración mediante Jest y Supertest.

📈 Próximas mejoras

🤖 Integración de modelos predictivos con IA

🔗 Comercio multilateral complejo

📊 Nuevos dashboards para índices geopolíticos

🌐 Traducción multilingüe

🤝 Contribuciones

¡Las contribuciones son bienvenidas!
Haz un fork, crea una rama y abre un pull request.

📄 Licencia

Este proyecto está bajo la licencia MIT.
