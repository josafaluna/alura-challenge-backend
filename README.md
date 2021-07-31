<img src="https://github.com/josafaluna/alura-challenge-backend/blob/2b675d4963c6c77b89817641761ec326ebc63f91/logo.svg" width="160px" id="titulo">



# AluraFlix
A REST-API deve permitir ao usuário montar playlists com links para seus vídeos preferidos, separados por categorias. Este projeto foi desenvolvido durante a **[Alura Challenges](https://www.alura.com.br/challenges/back-end)**.
<br/>

### :rocket: Tecnologias
Esse projeto foi desenvolvido com as seguintes tecnologias:



<a href="https://developers.redhat.com/products/openjdk/download"><img src="https://img.shields.io/badge/JAVA-11-red"></a> <a href="https://spring.io/"><img src="https://img.shields.io/badge/Spring%20Boot-2.5.3-green"></a> <a href="https://mariadb.org/"><img src="https://img.shields.io/badge/MariaDB-10.6-blueviolet"></a> <a href="https://projectlombok.org/"><img src="https://img.shields.io/badge/Lombok-1.18.20-blue"></a> <a href="https://maven.apache.org/download.cgi"><img src="https://img.shields.io/badge/Maven-3.8.1-ff69b4"></a> <a href="http://modelmapper.org/"><img src="https://img.shields.io/badge/ModelMapper-2.3.8-black"></a> <a href="https://spring.io/guides/gs/accessing-data-jpa/"><img src="https://img.shields.io/badge/JPA- -white"></a> <a href="https://hibernate.org/"><img src="https://img.shields.io/badge/Hibernate- -white"></a>
<br/>

### 💻 Pré-requisitos
Antes de começar, verifique se você atendeu aos seguintes requisitos:
* Você tem uma máquina `Windows`.
* Você instalou a versão:
  *  `Java 11+ / MariaDB 10.6+ / Maven / IDE: Eclipse / Git for windows`.
* Variáveis de Ambiente:
  * `JAVA_HOME: caminho do Java - exemplo: C:\Program Files\java-11`.
  * `MAVEN_HOME: caminho do Mavem - exemplo: D:\Sistemas\apache-maven-3.8.1`.
  * `Path: inserir no final: %JAVA_HOME%\bin %MAVEN_HOME%\bin`
<br/>

### 🚀 Clonando
Para clonar o AluraFlix, siga estas etapas:
Clone o repositório

```bash
# Entre no repositório pelo git bash
$ cd nome-do-seu-diretório

# Clone o repositório
$ git clone https://github.com/josafaluna/alura-challenge-backend.git

# Abra a sua IDE e import o projeto
File > Import... > Existing Maven Project > encontre o projeto > Finish

# Iniciar o projeto
Run as > Spring Boot App
```
<br/>

## ☕ Testando
Para testar AluraFlix, siga estas etapas:

```bash
# Web ou Postman
A API estará disponível no endereço http://localhost:8081/videos.

#GET - Todos os Vídeos
  http://localhost:8081/aluraflix/videos

#GET - Apenas 1 Video
  http://localhost:8081/aluraflix/videos/1

#POST - Cria um novo Video
  http://localhost:8081/aluraflix/videos
  Corpo:
    {
      "titulo": "titulo do video",
      "descricao": "descrição do video",
      "url": "endereço do video"
    }

#PUT - Atualiza um video
  http://localhost:8081/aluraflix/videos/1
  Body
    {
      "id": 1,
      "titulo": "titulo do video",
      "descricao": "descrição do video",
      "url": "endereço do video"
    }

#DELETE
  http://localhost:8081/aluraflix/videos/1

```
<br/>

### Ajustes e melhorias

O projeto ainda está em desenvolvimento e as próximas atualizações serão voltadas nas seguintes tarefas:

- [x] API com rotas implementadas segundo o padrão REST;
- [x] Validações feitas conforme as regras de negócio;
- [x] Implementação de base de dados para persistência das informações;
- [ ] Serviço de autenticação para acesso às rotas GET, POST, PUT e DELETE.
<br/>


### :memo: Licença
Copyright © 2021 - [Josafá Luna](https://github.com/josafaluna)

A permissão é concedida, gratuitamente, a qualquer pessoa que obtenha uma cópia deste arquivo, com restrição de publicar como SEU repositório. Porém, sem restrição nos direitos de usar, copiar, modificar e mesclar.
<br/>

### Autor

<img style="border-radius: 10%;" src="https://github.com/josafaluna/alura-challenge-backend/blob/2b675d4963c6c77b89817641761ec326ebc63f91/josafa.JPG" width="100px;" alt=""/>
<br />

Feito com ❤️ por Josafá Luna 👋🏽 Entre em contato!

[![Linkedin Badge](https://img.shields.io/badge/-Josafa-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/josafaluna/)](https://www.linkedin.com/in/josafaluna/) 
[![Gmail Badge](https://img.shields.io/badge/-josafaluna@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:josafaluna@gmail.com)](mailto:josafaluna@gmail.com)


[⬆ Voltar ao topo](#titulo)<br>
