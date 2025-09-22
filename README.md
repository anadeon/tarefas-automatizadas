# ☁️ Módulo 11 - Anotações do Curso Santander Code Girls

Este repositório faz parte do módulo **Executando Tarefas Automatizadas** do curso **Santander - Code Girls**.  
O desafio consistia em criar um repositório contendo **anotações feitas durante o módulo**, consolidando os conhecimentos adquiridos sobre a **Tarefas Automatizadas** e suas ferramentas.

## ⚙️ Tarefas Automatizadas com Amazon S3 e Lambda

Neste módulo, aprendemos como **automatizar tarefas na nuvem** utilizando os serviços **Amazon S3** e **AWS Lambda**, além de como simular esses recursos localmente com o **LocalStack** para desenvolvimento e testes.


## 🗂 Entendendo o Amazon S3

O **Amazon S3 (Simple Storage Service)** é um serviço de **armazenamento em nuvem** da AWS.  
Ele **suporta qualquer tipo de arquivo**, sendo ideal para:

- **Backup de dados**
- **Armazenamento de objetos**, como imagens, vídeos, documentos e muito mais.

> 💡 **Exemplo prático:**  
> Você pode armazenar imagens enviadas por usuários em um bucket do S3 e acessá-las diretamente via URL.


## 💻 Entendendo o AWS Lambda

O **AWS Lambda** é um serviço que permite **executar códigos em resposta a eventos**, sem a necessidade de gerenciar servidores (modelo **serverless**).

### **Vantagens do AWS Lambda**
- **Execução sob demanda:** código só roda quando necessário.  
- **Escalabilidade automática:** ajusta a capacidade automaticamente conforme a demanda.  
- **Custo eficiente:** você paga apenas pelo tempo de execução do código.  
- **Integração com outros serviços AWS:** como S3, DynamoDB, API Gateway, entre outros.

> 💡 **Exemplo prático:**  
> Quando um arquivo é enviado para um bucket do S3, o Lambda pode ser acionado automaticamente para processá-lo, como redimensionar uma imagem ou validar dados.


## 🧪 Configurando AWS Localmente com LocalStack

O **LocalStack** é um projeto **open source** que permite **simular serviços da AWS localmente**.  
Ele é útil para **desenvolvimento**, **testes** e **integração**, evitando a necessidade de acessar a AWS real durante o processo inicial.

### **Principais características:**
- Suporte a diversos serviços AWS (S3, Lambda, DynamoDB, etc.).
- Versão **Pro** e **Enterprise**, que oferecem funcionalidades extras, como suporte a **endpoints de rede personalizados**.

> 💡 **Vantagem:**  
> Desenvolvedores podem criar, testar e validar suas aplicações **sem custos** e **sem depender da internet**.

## 🛠 Criando os Recursos

Ao trabalhar com **Amazon S3**, **Lambda** e **LocalStack**, é possível:

1. Criar **buckets no S3** localmente.  
2. Configurar **funções Lambda** para responder a eventos, como upload de arquivos.  
3. Integrar esses serviços, simulando o ambiente real da AWS.

## 📂 Trabalhando Arquivos Localmente com LocalStack

Com o **LocalStack**, você pode manipular arquivos localmente como se estivesse usando o **S3 real**, incluindo:

- Upload de arquivos para buckets.
- Leitura e exclusão de objetos.
- Testes de eventos que acionam funções Lambda.

> 💡 **Exemplo prático:**  
> Fazer upload de uma imagem em um bucket local e disparar automaticamente uma função Lambda que redimensiona essa imagem.

## 📚 Benefícios de Usar Essa Abordagem

- **Redução de custos**: evita gastos durante a fase de desenvolvimento.  
- **Segurança**: dados sensíveis não são enviados diretamente para a nuvem durante os testes.  
- **Agilidade**: testes rápidos sem depender da conectividade com a AWS real.  
- **Simulação realista**: comportamento próximo ao ambiente de produção.
---
Feito por Ana Gabriela Deon ✨👩🏻‍💻
