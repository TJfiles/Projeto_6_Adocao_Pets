# 🧩 **Projeto Adoção de Pets**


Uma aplicação web desenvolvida com **Flask**, **JSON** e a **API Resend**, que permite aos usuários visualizar animais disponíveis para adoção e enviar um formulário de interesse.  
As informações do formulário são salvas localmente em um arquivo **JSON** e também enviadas por **e-mail** ao proprietário do site.  

O front-end foi disponibilizado gratuitamente pelo site [HTML5 UP](https://html5up.net), adaptado para integração com o backend em Flask.


---
## 🧠 **Situação-Problema**

Você foi contratado por uma **ONG de proteção animal** para criar um site que facilite o processo de **adoção de pets**.  
O objetivo é permitir que visitantes visualizem os animais disponíveis e, caso se interessem, possam enviar uma solicitação de adoção de forma simples e rápida.  

A ONG precisa que o sistema:
- Mostre as fotos e informações dos pets disponíveis para adoção;  
- Permita o envio de um **formulário de adoção** com nome, e-mail e mensagem;  
- Armazene essas informações localmente em um **arquivo JSON**;  
- E envie automaticamente um **e-mail de notificação** ao responsável, utilizando a **API Resend**.  

Você, como desenvolvedor(a), utilizou **Python e Flask** para o backend, integrando um **template HTML responsivo** para criar uma interface bonita, leve e funcional.


---

## 🎯 **Objetivo Educacional**

- Praticar o desenvolvimento de **aplicações web com Flask**.  
- Entender o uso de **rotas**, **métodos HTTP (GET e POST)** e **formulários HTML**.  
- Aprender a **salvar dados em arquivos JSON** e enviar **e-mails via API REST**.  
- Compreender a integração entre **backend Python** e **frontend HTML/CSS**.  


---

## ⚙️ **Funcionalidades Principais**

✅ Exibição de pets disponíveis para adoção com imagens.  
✅ Formulário de adoção com campos de **nome**, **e-mail** e **mensagem**.  
✅ Salvamento das informações do formulário em um **arquivo JSON**.  
✅ Envio automático de **e-mail** para o proprietário do site via **API Resend**.  


---

## 💻 **Como Executar**

### 🧩 Pré-requisitos

- Python **3.8** ou superior instalado.  
- Instalar as bibliotecas necessárias (**Flask**, **resend**, etc.).  


### 🚀 Passos de execução
1. **Clone o repositório** ou baixe os arquivos do projeto:
   ```bash
   git clone https://github.com/seuusuario/projeto_adocao_pets.git
   cd projeto_adocao_pets
   ```
2. Instale as dependências:
    ```bash
    pip install flask resend
    ```

3. Execute o servidor Flask:

    ```bash
    flask run

    ```

4. Acesse no navegador:

    ```bash
    http://localhost:5000

    ```


# 🐶 Exemplo de Uso

- O usuário acessa o site e visualiza as imagens dos pets disponíveis.
- Clica em “Adotar” e preenche o formulário com nome, e-mail e mensagem.

Ao enviar, o sistema:

- Salva os dados em um arquivo dados.json;
- Envia um e-mail automático ao administrador com as mesmas informações.
- Uma mensagem de confirmação é exibida na tela, indicando que o envio foi realizado com sucesso. ✅


---

# 🧠 Conceitos Trabalhados
- Roteamento e métodos HTTP no Flask
- Manipulação de dados JSON em Python
- Integração com APIs externas (Resend)
- Envio de e-mails automatizados
- Integração entre backend Flask e frontend HTML
- Estrutura de formulários e tratamento de requisições POST


---

# 🧾 Licença

Este projeto está sob a licença MIT — sinta-se à vontade para usar, modificar e distribuir. ✨

--- 

# 🔧 Tecnologias Utilizadas
🐍 Python 3.x
🔥 Flask
📬 API Resend
📁 JSON
🎨 HTML5 UP (template de frontend)