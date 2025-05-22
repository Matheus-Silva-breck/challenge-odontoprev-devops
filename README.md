# DentalCare - Projeto DevOps Sprint 4
### Grupo: OdontoTech

## Integrantes
- Matheus Silva - RM 553180  
- Giovani Borba - RM 553724  
- Eduardo Rodrigues - RM 553705  

## Descrição da Solução
A aplicação DentalCare é uma API REST desenvolvida em Java (Spring Boot) com foco no gerenciamento de pacientes e consultas odontológicas. Utiliza banco de dados Oracle hospedado na Azure e adota práticas de CI/CD com Azure DevOps para automação do ciclo de vida da aplicação.

## Tecnologias utilizadas
- Java 17 + Spring Boot
- Maven
- Azure DevOps (Pipeline)
- Oracle Cloud Database (Azure)
- Azure App Service

## Executando o projeto
1. Clonar o repositório:
   ```bash
   git clone https://github.com/Matheus-Silva-breck/challenge-odontoprev-devops
   ```

2. Rodar localmente:
   ```bash
   ./mvnw spring-boot:run
   ```

3. Configurar o `application.properties` com os dados do Oracle DB (Azure):
   ```properties
   spring.datasource.url=jdbc:oracle:thin:@<SEU-HOST>:1521/<NOME_DB>
   spring.datasource.username=SEU_USUARIO
   spring.datasource.password=********
   ```

## Pipeline
A pipeline foi configurada para rodar automaticamente via Azure DevOps e executa:
- Build com Maven
- Testes automatizados
- Deploy contínuo (manual ou automático)

## Link do vídeo demonstrativo
: https://youtu.be/7b-fAs7jMwI
: https://youtu.be/Xs5JSb0sboM?feature=shared
