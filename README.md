# Clonar repositorio
git clone https://github.com/tu-usuario/backend-gestor.git
cd backend-gestor

# Instalar dependencias
npm install

# Crear archivo .env con la conexión a MongoDB
echo MONGO_URI=mongodb://localhost:27017/gestor > .env

# Ejecutar el servidor
npm run dev
