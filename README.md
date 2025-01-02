# NeuroFeed

NeuroFeed é um site de notícias alimentado por IA, projetado para oferecer uma experiência personalizada ao usuário, categorizando e apresentando notícias com base em seus interesses. O projeto utiliza tecnologias modernas como Java Spring, React, AWS, PostgreSQL, MongoDB, Python, Flask, Docker, Kubernetes e Redis para garantir uma arquitetura escalável e de alta performance.

## Tecnologias Utilizadas

- **Java Spring**: Para a construção do back-end e gerenciamento de APIs escaláveis.
- **React**: Para a construção do front-end dinâmico e interativo.
- **AWS**: Para hospedagem e escalabilidade em nuvem.
- **PostgreSQL**: Banco de dados relacional para armazenar dados estruturados.
- **MongoDB**: Banco de dados NoSQL para dados não estruturados.
- **Python & Flask**: Para implementação de funcionalidades relacionadas à IA e scraping de notícias.
- **Docker**: Para containerização e ambiente isolado de desenvolvimento.
- **Kubernetes**: Para orquestração de contêineres e escalabilidade.
- **Redis**: Para cache de dados e melhorar a performance.

## Funcionalidades

- Coleta e processamento de notícias em tempo real.
- Classificação de notícias em diferentes categorias utilizando IA.
- Sistema de recomendações personalizadas para os usuários com base em seu histórico de leitura.
- Interface de usuário interativa e responsiva com React.
- Sistema de login e gerenciamento de usuários.
- Integração com bancos de dados relacionais (PostgreSQL) e NoSQL (MongoDB).

## Como Rodar o Projeto

### Pré-requisitos

- Java 11 ou superior
- Node.js e npm
- Python 3.x
- Docker (opcional, para ambiente de produção)
- Banco de dados PostgreSQL e MongoDB (configuração local ou via Docker)

### Rodando o Back-end

1. Navegue até o diretório do back-end:
    ```bash
    cd backend
    ```

2. Instale as dependências do Spring:
    ```bash
    ./mvnw install
    ```

3. Execute o servidor:
    ```bash
    ./mvnw spring-boot:run
    ```

### Rodando o Front-end

1. Navegue até o diretório do front-end:
    ```bash
    cd frontend
    ```

2. Instale as dependências:
    ```bash
    npm install
    ```

3. Inicie o servidor de desenvolvimento:
    ```bash
    npm start
    ```

### Rodando a IA

1. Navegue até o diretório de IA:
    ```bash
    cd ai
    ```

2. Instale as dependências do Python:
    ```bash
    pip install -r requirements.txt
    ```

3. Execute o script de IA:
    ```bash
    python app.py
    ```

## Licença

Este projeto é **privado** e está sujeito a termos e condições internos. Não está disponível para distribuição ou modificação pública.

## Contato

Para dúvidas, sugestões ou feedbacks, entre em contato com [seu-email@dominio.com].
