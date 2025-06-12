# QrCodeGenerator
QR Code Generator com AWS S3 e Docker


📦 QR Code Generator com AWS S3 e Docker
Este projeto é uma aplicação Java Spring Boot desenvolvida para gerar códigos QR dinâmicos com armazenamento em nuvem. Utiliza o serviço AWS S3 para armazenar os QR Codes gerados e o Docker para facilitar a construção e execução da aplicação em qualquer ambiente.

🚀 Funcionalidades
✅ Geração de QR Code a partir de uma URL ou texto informado

☁️ Upload automático do QR Code para um bucket S3 da AWS

🔗 Retorno da URL pública do QR Code armazenado

🐳 Containerização da aplicação com Docker

🛠️ Tecnologias Utilizadas
Java 17 + Spring Boot

AWS SDK (S3)

Docker

Gradle

Lombok



🧪 Como executar
bash
Copiar
Editar
# Build da imagem
docker build -t qrcode-generator .

# Executar o container
docker run -p 8080:8080 qrcode-generator

📂 Exemplo de Requisição
{
  "text": "https://github.com/MeloAri"
}
