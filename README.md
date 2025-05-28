
# 🎯 Integração do Azure Data Factory com Azure DevOps

Este projeto faz parte do curso **Microsoft AI | Azure Databricks** da **DIO**. O objetivo é realizar a integração do Azure Data Factory com o Azure DevOps, permitindo versionamento de código, controle de alterações e backups dos pipelines.

## 🚀 Tecnologias e Serviços Utilizados

- ☁️ Microsoft Azure (Data Factory, DevOps)
- 🔧 Git (Controle de Versionamento)
- 📄 Markdown para documentação

## 🔗 Pré-requisitos

- Conta ativa no **Microsoft Azure**
- Conta no **Azure DevOps** vinculada ao mesmo diretório do Azure

## 🛠️ Passo a Passo da Integração

### ✅ 1º Passo: Criação do Data Factory
> Data Factory criado no projeto anterior.
🔗 [Acesse Aqui o Passo a Passo da Criação do Data Factory](https://github.com/AstriPrado/Projeto-Azure-Data-Factory)

---

### ✅ 2º Passo: Criação da Organização e Projeto no Azure DevOps
 1. Acesse: https://dev.azure.com/
 2. Crie uma nova organização vinculada ao mesmo diretório do seu Azure.
 3. Crie um projeto dentro dessa organização.

![Criação do Azure DevOps](./imagens/print-1.png)

---

### ✅ 3º Passo: Configuração do Git no Data Factory

1. Acesse **Gerenciar** no menu do Data Factory.
2. Clique em **Configuração do Git** e depois em **Configurar**.

![Configuração do Git](./imagens/print-2.png)

3. Defina o tipo de repositório (**Azure DevOps Git** ou **GitHub**).

![Escolha do repositório](./imagens/print-3.png)

4. Configure o repositório com os dados da sua organização e projeto.

![Configuração do repositório](./imagens/print-4.png)

5. Confirme o repositório configurado.

![Repositório configurado](./imagens/print-5.png)

---

### 🔗 Verificando no Azure DevOps

- No Azure DevOps, acesse **Repos > Files** para visualizar os artefatos sincronizados.

![Verificação no DevOps](./imagens/print-6.png)

---

## 💡 Conclusão

A integração permite versionamento, governança e rastreabilidade sobre os pipelines do Data Factory.

## ✍️ Autor

- 👩‍💻 **Astri Prado**  
🔗 [LinkedIn](https://www.linkedin.com/in/astri-prado) | [GitHub](https://github.com/AstriPrado)

