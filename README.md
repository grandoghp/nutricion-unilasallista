# NutriSalud Unilasallista

## Descripción del Proyecto

NutriSalud Unilasallista es un sitio web interactivo diseñado para abordar la problemática de la desinformación nutricional y los malos hábitos alimenticios entre los estudiantes universitarios de Unilasallista. 

En el contexto actual, donde el avance tecnológico ha contribuido al sedentarismo y a la proliferación de información poco fiable sobre nutrición, muchos estudiantes enfrentan dificultades para mantener una alimentación equilibrada, lo que puede afectar negativamente su rendimiento académico y bienestar general.

Este proyecto proporciona una plataforma digital que ofrece información validada, recomendaciones personalizadas y herramientas de seguimiento nutricional, permitiendo a los estudiantes mejorar sus hábitos alimenticios de manera informada y efectiva.

## Problemática

El avance tecnológico ha transformado la vida cotidiana de las personas, facilitando el acceso a información y recursos digitales. Sin embargo, también ha contribuido a:

- Aumento del sedentarismo
- Proliferación de información poco fiable sobre hábitos alimenticios
- Alta tasa de desinformación sobre nutrición
- Dificultades para adoptar hábitos alimenticios saludables
- Falta de acceso a asesoramiento nutricional confiable
- Problemas de salud derivados de una mala alimentación

Estos factores pueden repercutir negativamente en la salud de los estudiantes, afectando su bienestar general y su rendimiento académico.

## Objetivos

- Desarrollar un sitio web interactivo que proporcione información nutricional validada
- Ofrecer recomendaciones personalizadas basadas en perfiles de usuarios
- Proporcionar herramientas de seguimiento para hábitos alimenticios
- Fomentar una comunidad de apoyo entre estudiantes
- Mejorar el bienestar general de los estudiantes universitarios
- Contribuir positivamente al rendimiento académico a través de una mejor nutrición

## Características Principales

- **Perfil de Usuario Personalizado**: Registro y creación de perfiles con información relevante (edad, peso, altura, preferencias alimenticias, restricciones dietéticas, etc.)
- **Evaluación Nutricional**: Herramienta de evaluación inicial para determinar necesidades específicas
- **Recomendaciones Personalizadas**: Sugerencias de alimentación basadas en el perfil
- **Planificador de Comidas**: Herramienta para crear y gestionar planes alimenticios semanales
- **Seguimiento de Nutrición**: Registro diario de consumo de alimentos y nutrientes
- **Biblioteca de Recetas Saludables**: Colección de recetas nutritivas adaptadas a estudiantes
- **Blog Informativo**: Artículos validados por profesionales sobre nutrición y salud
- **Comunidad de Usuarios**: Foro para compartir experiencias y consejos
- **Sistema de Notificaciones**: Recordatorios para mantener hábitos alimenticios
- **Dashboard de Progreso**: Visualización gráfica del progreso nutricional

## Tecnologías

### Frontend
- HTML5, CSS3, JavaScript
- React.js
- Bootstrap/Tailwind CSS
- Chart.js (para visualizaciones)

### Backend
- Node.js con Express
- API RESTful
- Autenticación JWT

### Base de Datos
- MongoDB (para perfiles de usuarios y datos no estructurados)
- MySQL (para datos relacionales como recetas e ingredientes)

### Otras Herramientas
- Git y GitHub para control de versiones
- Docker para despliegue
- Firebase para autenticación de usuarios
- AWS/Heroku para hosting

## Estructura del Proyecto

```
nutricion-unilasallista/
│
├── client/                  # Frontend (React)
│   ├── public/
│   ├── src/
│   │   ├── components/      # Componentes reutilizables
│   │   ├── pages/           # Páginas de la aplicación
│   │   ├── assets/          # Imágenes, iconos, etc.
│   │   ├── hooks/           # Custom React hooks
│   │   ├── utils/           # Utilidades y funciones auxiliares
│   │   ├── context/         # Context API para estado global
│   │   ├── services/        # Servicios para API calls
│   │   └── App.js           # Componente principal
│
├── server/                  # Backend (Node.js + Express)
│   ├── config/              # Configuración de la aplicación
│   ├── controllers/         # Controladores para rutas
│   ├── models/              # Modelos de datos
│   ├── routes/              # Definición de rutas API
│   ├── middleware/          # Middleware personalizado
│   ├── utils/               # Utilidades y funciones auxiliares
│   └── server.js            # Punto de entrada del servidor
│
├── database/                # Scripts para la base de datos
│   ├── migrations/
│   └── seeds/
│
├── docs/                    # Documentación
│
├── tests/                   # Tests unitarios y de integración
│
├── .github/                 # Configuración de CI/CD
│
├── .gitignore               # Archivos ignorados por Git
├── package.json             # Dependencias del proyecto
├── docker-compose.yml       # Configuración de Docker
└── README.md                # Documentación principal
```

## Instalación y Configuración

### Prerrequisitos
- Node.js (v14 o superior)
- npm o yarn
- MongoDB
- MySQL
- Git

### Pasos para Instalación Local

1. Clonar el repositorio:
```bash
git clone https://github.com/grandoghp/nutricion-unilasallista.git
cd nutricion-unilasallista
```

2. Instalar dependencias del servidor:
```bash
cd server
npm install
```

3. Configurar variables de entorno:
```bash
cp .env.example .env
# Editar .env con tus configuraciones
```

4. Instalar dependencias del cliente:
```bash
cd ../client
npm install
```

5. Iniciar el servidor de desarrollo:
```bash
# En una terminal (desde la raíz)
cd server
npm run dev

# En otra terminal (desde la raíz)
cd client
npm start
```

## Contribución

Estamos abiertos a contribuciones. Por favor, sigue estos pasos:

1. Haz fork del repositorio
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`)
3. Haz commit de tus cambios (`git commit -m 'Agregar nueva funcionalidad'`)
4. Haz push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

## Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## Equipo de Desarrollo

- [Tu Nombre](https://github.com/tuusuario) - Desarrollador Principal
- [Colaborador 1](https://github.com/colaborador1) - Frontend Developer
- [Colaborador 2](https://github.com/colaborador2) - Backend Developer
- [Colaborador 3](https://github.com/colaborador3) - UI/UX Designer

## Contacto

Para preguntas o colaboraciones, por favor contacta a: [tucorreo@example.com](mailto:tucorreo@example.com)

---

Desarrollado con ❤️ para mejorar la salud nutricional de los estudiantes de Unilasallista.
