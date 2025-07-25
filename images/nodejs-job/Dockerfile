# Gunakan Node.js sebagai base image
FROM node:18

# Buat direktori kerja
WORKDIR /app

# Copy file package.json dan install dependency
COPY package.json ./
RUN npm install

# Copy semua file ke dalam container
COPY . .

# Jalankan aplikasi
CMD ["npm", "start"]

# Ekspose port 3000
EXPOSE 3000
