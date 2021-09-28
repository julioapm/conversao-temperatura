# Estágio 1: compilar a app
# Obter imagem base
FROM node:14.17.5
# Definir diretório
WORKDIR /app
# Copiar arquivos de configuração
COPY package*.json ./
# Instalar as dependências
RUN npm install
# Copiar arquivos da app
COPY . .
# Expor a porta do servidor node
EXPOSE 8080
# Inicializar o container
CMD ["node", "server.js"]