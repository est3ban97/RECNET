# 🎬 RECNET - Sistema de Recomendación de Películas

Sistema inteligente de recomendación de películas basado en Machine Learning que utiliza técnicas de filtrado colaborativo y análisis de contenido para sugerir películas personalizadas.

## 📋 Descripción

RECNET es una aplicación web que proporciona recomendaciones de películas personalizadas utilizando algoritmos de aprendizaje automático. El sistema analiza preferencias de usuarios y características de películas para generar sugerencias relevantes.

## ✨ Características

- 🤖 Recomendaciones personalizadas basadas en ML
- 📊 Análisis de datos de películas
- 🎯 Filtrado colaborativo
- 💻 Interfaz web intuitiva
- 📈 Sistema de calificaciones

## 🛠️ Tecnologías Utilizadas

### Backend
- Python 3.x
- TensorFlow/Keras
- Pandas
- NumPy
- Scikit-learn

### Frontend
- React 19.2.0
- React Router DOM
- Axios (para peticiones HTTP)
- React Scripts

## 📦 Instalación

### Prerrequisitos

- Python 3.8 o superior
- pip (gestor de paquetes de Python)

### Pasos de instalación

1. **Clonar el repositorio**
```bash
git clone https://github.com/est3ban97/RECNET.git
cd RECNET
```

2. **Crear entorno virtual**
```bash
python -m venv backend
```

3. **Activar entorno virtual**

En Windows:
```bash
backend\Scripts\activate
```

En Linux/Mac:
```bash
source backend/bin/activate
```

4. **Instalar dependencias**
```bash
pip install -r requirements_fixed.txt
```

## 🚀 Uso

### Ejecutar el Backend

```bash
cd backend
python main.py
```

### Ejecutar el Frontend

```bash
cd frontend
npm install
npm start
```

El frontend se ejecutará en `http://localhost:3000`

## 📁 Estructura del Proyecto

```
RECNET/
│
├── datos/
│   └── movies_metadata.csv      # Dataset de películas
│
├── frontend/                     # Aplicación frontend
│
├── requirements_fixed.txt        # Dependencias Python
├── .gitignore                   # Archivos ignorados por Git
└── README.md                    # Este archivo
```

## 🧠 Modelo de Recomendación

El sistema utiliza:
- **Filtrado colaborativo**: Analiza patrones de comportamiento de usuarios similares
- **Análisis de contenido**: Evalúa características de las películas
- **Redes neuronales**: Implementadas con TensorFlow para predicciones precisas

## 📊 Dataset

El proyecto utiliza el dataset de películas que incluye información sobre:
- Títulos de películas
- Géneros
- Calificaciones
- Descripciones
- Metadatos adicionales

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para contribuir:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/NuevaCaracteristica`)
3. Commit tus cambios (`git commit -m 'Agregar nueva característica'`)
4. Push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto es de código abierto y está disponible bajo la [Licencia MIT](LICENSE).

## 👤 Autor

**Esteban**
- GitHub: [@est3ban97](https://github.com/est3ban97)

## 📧 Contacto

Si tienes preguntas o sugerencias, no dudes en contactarme o abrir un issue en el repositorio.

---

⭐ Si este proyecto te fue útil, considera darle una estrella en GitHub!
