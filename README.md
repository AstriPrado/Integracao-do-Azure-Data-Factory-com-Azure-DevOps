
# 🎯 Integração do Azure Data Factory com Azure DevOps

Este projeto faz parte do curso **Microsoft AI | Azure Databricks** da **DIO**. O objetivo é realizar a integração do Azure Data Factory com o Azure DevOps, permitindo versionamento de código, controle de alterações e backups dos pipelines.

## 🚀 Tecnologias e Serviços Utilizados

- ☁️ Microsoft Azure (Data Factory, DevOps)
- 🔧 Git (Controle de Versionamento)
- 📄 Markdown

## 🔗 Pré-requisitos

- Conta ativa no **Microsoft Azure**
- Conta no **Azure DevOps** vinculada ao mesmo diretório do Azure
- Data Factory criado

## 🛠️ Passo a Passo da Integração

### ✅ 1º Passo: Criação do Data Factory
> Data Factory criado no projeto anterior.

---

### ✅ 2º Passo: Criação da Organização e Projeto no Azure DevOps

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

## 🧠 Conceitos Importantes

- **Branch:** Ramificação de código para desenvolvimento isolado.
- **Commit:** Registro de alteração.
- **Publish:** Publicação dos artefatos no ambiente do Data Factory.

## 💡 Conclusão

A integração permite versionamento, governança e rastreabilidade sobre os pipelines do Data Factory.

## ✍️ Autor

- 👩‍💻 **Astri Prado**  
🔗 [LinkedIn](https://www.linkedin.com) | [GitHub](https://github.com)

## 🚀 Licença

Projeto sob licença MIT.

## 📦 Estrutura dos Arquivos

```
📂 projeto-ADF-AzureDevOps
│
├── 📁 imagens
│   ├── print-1.png
│   ├── print-2.png
│   ├── print-3.png
│   ├── print-4.png
│   ├── print-5.png
│   └── print-6.png
│
├── README.md
└── (outros arquivos)
```
