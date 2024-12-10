# **Soundscape**

## **Descrição**

O **Soundscape** é um sistema de streaming e compartilhamento de áudio, desenvolvido para oferecer uma experiência intuitiva para os usuários. O sistema permite:

- Buscar e escutar músicas.
- Criar playlists personalizadas.
- Postar músicas próprias para que outros usuários possam ouvi-las.

O objetivo futuro da plataforma é evoluir para uma rede social focada em produção musical, facilitando a interação entre produtores que buscam inspiração e colaborações.

---

## **Tecnologias Utilizadas**

### **Frontend**
- **Framework:** React com TypeScript.
- **UI Library:** Material UI.
- **HTTP Client:** Axios.

### **Backend**
- **Linguagem:** Java 17.
- **Framework:** Spring Boot.
- **ORM:** Hibernate com JPA.
- **Gerenciador de Migração:** Liquibase.

### **Banco de Dados**
- PostgreSQL.

### **Serviços Externos**
- **Reconhecimento de Áudio:** [ACRCloud](https://www.acrcloud.com/).
- **Armazenamento de Arquivos:** AWS S3.

---

## **Requisitos Funcionais**

- **RF-1: Cadastrar usuário.**  
  Permitir que novos usuários se cadastrem utilizando e-mail, nome de usuário e senha.

- **RF-2: Autenticação de usuário.**  
  Exigir autenticação dos usuários cadastrados para acessar funcionalidades restritas, como criar postagens e interagir com conteúdos.

- **RF-3: Envio de arquivos de áudio.**  
  Permitir que usuários autenticados enviem arquivos de áudio.

- **RF-4: Validação de arquivos com copyright.**  
  Garantir que arquivos de áudio enviados sejam validados para evitar violação de direitos autorais.

- **RF-5: Download de arquivos de áudio.**  
  Permitir o download de qualquer arquivo de áudio publicado na plataforma.

- **RF-6: Reprodução de arquivos de áudio.**  
  Habilitar a reprodução de arquivos de áudio publicados diretamente na plataforma.

- **RF-7: Exibição do tamanho dos arquivos.**  
  Exibir o tamanho em disco dos arquivos de áudio antes de fazer o download.

- **RF-8: Curtidas em publicações.**  
  Permitir que usuários autenticados curtam publicações de outros usuários.

- **RF-9: Log Off.**  
  Permitir que o usuário encerre sua sessão na plataforma.

- **RF-10: Criar playlists.**  
  Permitir que usuários criem playlists personalizadas para organizar suas músicas.

- **RF-11: Excluir playlists.**  
  Permitir que os usuários excluam playlists criadas por eles.

- **RF-12: Gerenciar músicas em playlists.**  
  Permitir que os usuários adicionem ou removam músicas de suas playlists.

- **RF-13: Seguir usuários.**  
  Permitir que os usuários sigam o perfil de outros usuários para acompanhar suas publicações.

- **RF-14: Deixar de seguir usuários.**  
  Permitir que os usuários deixem de seguir outros perfis previamente seguidos.

---

## **Requisitos Não Funcionais**

- **RNF-1: Interface intuitiva.**  
  Garantir que o sistema tenha uma interface fácil de usar, com foco em visualização clara de respostas de publicações e músicas em reprodução.

---

## **Diagrama de Caso de Uso**
![caso de uso](https://github.com/user-attachments/assets/d1aecf84-00bb-4b15-90da-3e05121b35ff)

## **Diagrama de Contexto**
![Diagrama de contexto](https://github.com/user-attachments/assets/e15050ac-1040-42d0-9f6e-3bc1474b5b61)

---

## **Acesso à Aplicação**

- Link de acesso: [SoundScape](https://soundscape-project.tech/)

## **Repositórios Relacionados**

### **Frontend**
- Repositório: [Soundscape Frontend](https://github.com/J-Lembeck/soundscape-front)
- [SonarCloud Dashboard](https://sonarcloud.io/summary/overall?id=J-Lembeck_soundscape-front&branch=master)

### **Backend**
- Repositório: [Soundscape Backend](https://github.com/J-Lembeck/soundscape-back)
- [SonarCloud Dashboard](https://sonarcloud.io/summary/overall?id=J-Lembeck_soundscape-back&branch=master)

### **Design**
- **Figma:** [Soundscape Design](https://www.figma.com/design/ecYGRVUcnXh2Zn6PqvzSnL/SoundScape?node-id=3-11&node-type=CANVAS&t=nqD1d4L04pCiMFq3-0)

---

## **Monitoramento com Grafana**

- **Link de Acesso:** [Grafana Dashboard](http://3.13.122.161:3000/login)  
- **Credenciais de Acesso:**  
  - **Usuário:** `admin`  
  - **Senha:** `admin123`

---
