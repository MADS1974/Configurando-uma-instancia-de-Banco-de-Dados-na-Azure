# ☁️ Desafio: Configuração de uma Instância de Banco de Dados no Microsoft Azure

Este repositório foi criado como parte do desafio proposto pela DIO, com o objetivo de praticar a configuração de uma instância de banco de dados na plataforma **Microsoft Azure**. Aqui você encontrará resumos, anotações e dicas sobre o uso do Azure, servindo como material de apoio para estudos e futuras implementações.

## 📝 Descrição

Nesse projeto, você irá descobrir como configurar uma instância de banco de dados no Azure, explorando conceitos básicos de **bancos de dados gerenciados** e **nuvem**. Este desafio é voltado para profissionais e entusiastas que desejam aprender práticas essenciais para iniciantes.

**Nível:** Básico  
**Especialista:** Valéria Baptista  
**Cargo:** Head of Cloud and Cybersecurity, CloudData Tech & DevOps  
[LinkedIn](https://www.linkedin.com/in/valeria-baptista)

## 🚀 Objetivos do Desafio

- **Aplicar conceitos aprendidos** em um ambiente prático.
- **Documentar processos técnicos** de forma clara e estruturada.
- **Utilizar o GitHub** como ferramenta para compartilhamento de documentação técnica.

## 📋 Requisitos do Desafio

Para concluir este desafio, você deverá:

1. **Assistir a todas as vídeo-aulas**:
   - Não pule nenhuma etapa! As aulas contêm informações essenciais para o sucesso do seu projeto.

2. **Criar um repositório público no GitHub** contendo:
   - Um arquivo `README.md` detalhado.
   - Quaisquer arquivos adicionais que sejam relevantes para documentar sua experiência.
   - Opcionalmente, capturas de tela relevantes organizadas em uma pasta.

3. **Enviar o link do repositório** e uma breve descrição clicando no botão “Entregar Projeto”.

## 🎯 Estrutura do Repositório

- **README.md**: Este arquivo contém a documentação principal do desafio.
- **/screenshots**: Pasta opcional para armazenar capturas de tela relevantes.
- **/notes**: Arquivos adicionais com resumos e anotações sobre o uso do Azure.

## 🖥️ Passos para Configurar uma Instância de Banco de Dados no Azure

1. **Acessar o Portal do Azure**  
   Acesse o [Portal do Azure](https://portal.azure.com/) com sua conta Microsoft. Certifique-se de que você possui uma assinatura ativa para criar recursos.

2. **Criar um Recurso de Banco de Dados**  
   - No menu lateral, clique em **"Criar um recurso"**.
   - Na barra de pesquisa, digite o tipo de banco de dados que deseja criar, como:
     - **Azure SQL Database**
     - **Azure Database for MySQL**
     - **Azure Database for PostgreSQL**
   - Selecione o serviço desejado e clique em **"Criar"**.

3. **Configurar a Instância do Banco de Dados**  
   Preencha os campos obrigatórios para configurar sua instância:
   - **Assinatura**: Escolha a assinatura ativa.
   - **Grupo de Recursos**: Crie um novo grupo ou selecione um existente.
   - **Nome do Servidor**: Defina um nome único para o servidor (exemplo: `meu-banco-dados`).
   - **Região**: Escolha a região mais próxima para reduzir a latência.
   - **Usuário Administrador**: Configure o nome de usuário para o administrador do banco de dados.
   - **Senha**: Defina uma senha forte para o administrador.
   - **Plano de Serviço**: Escolha o plano de serviço com base no desempenho necessário (exemplo: Básico, Standard, Premium).
   - **Tamanho do Banco de Dados**: Defina o tamanho máximo de armazenamento (exemplo: 5 GB, 10 GB, etc.).

4. **Configurar a Rede**  
   - Configure o acesso à rede, permitindo conexões de endereços IP específicos ou habilitando o acesso público.
   - Adicione regras de firewall para permitir conexões seguras.

5. **Revisar e Criar**  
   - Revise todas as configurações feitas.
   - Clique em **"Criar"** para iniciar a implantação.
   - Aguarde a conclusão da implantação.

6. **Conectar ao Banco de Dados**  
   - Utilize ferramentas como **Azure Data Studio**, **MySQL Workbench** ou **pgAdmin** para se conectar ao banco de dados.
   - Copie a string de conexão fornecida no portal do Azure e configure-a em sua aplicação.

## 🌐 Interface do Portal do Microsoft Azure

A interface do portal do Microsoft Azure oferece uma visão centralizada de todos os serviços disponíveis. Na seção "Todos os serviços", é possível explorar categorias como **IA + Machine Learning**, **Computação**, **Contêineres**, **Bancos de dados**, entre outras. Além disso, serviços populares como **Máquinas virtuais**, **Grupos de recursos**, **Serviços de Aplicativos** e **Bancos de dados SQL** estão facilmente acessíveis, permitindo o gerenciamento eficiente de recursos na nuvem.

## 📚 Recursos Úteis

- **Documentações Oficiais**:
  - [Azure SQL Database](https://learn.microsoft.com/pt-br/azure/azure-sql/)
  - [Azure Database for MySQL](https://learn.microsoft.com/pt-br/azure/mysql/)
  - [Azure Database for PostgreSQL](https://learn.microsoft.com/pt-br/azure/postgresql/)

- **Materiais Complementares sobre GitHub**:
  - [GitHub Quick Start](https://github.com/github/quickstart).
  - [GitBook: Formação GitHub Certification](https://git-scm.com/book/en/v2).
  - [Documentação do GitHub](https://docs.github.com/).
  - [GitHub Markdown](https://guides.github.com/features/mastering-markdown/).

## ✅ Toda implementação deste código foi feita seguindo as orientações da especialista Valéria Baptista 
em www.dio.me

### Follow me

- [MARCIO ADRIANO DA SILVA | LinkedIn](https://www.linkedin.com/in/mads1974/)
