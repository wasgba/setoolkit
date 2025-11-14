# 🛡️ Clonagem do Facebook com SEToolkit – Captura de Logins e Senhas
> Projeto documentando passo a passo a execução de um ataque **Credential Harvester + Site Cloner** usando o **SEToolkit** para clonar o Facebook e capturar credenciais.  
> Finalidade: estudo educacional e demonstração prática de engenharia social.

![Status](https://img.shields.io/badge/status-finalizado-brightgreen)
![Linux](https://img.shields.io/badge/OS-Linux-blue)
![Ferramenta](https://img.shields.io/badge/Tool-SEToolkit-red)
![Pentest](https://img.shields.io/badge/Ataque-Credential%20Harvester-orange)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

## 📚 Sumário
1. [Descrição do Projeto](#-descrição-do-projeto)
2. [Ferramentas e Ambiente](#-ferramentas-e-ambiente)
3. [Passo a Passo Completo](#-passo-a-passo-completo)
4. [Fluxo do Ataque](#-fluxo-do-ataque)
5. [Credenciais Capturadas](#-credenciais-capturadas)
6. [Ética e Uso Legal](#-ética-e-uso-legal)
7. [Autor](#-autor)
8. [Licença](#-licença)

---

## 📝 Descrição do Projeto
Este repositório contém a documentação completa da técnica utilizada para:

- Clonar a página de login do **Facebook**
- Hospedar a página falsa usando o SEToolkit
- Capturar **login e senha** digitados pela vítima
- Demonstrar como o ataque funciona de ponta a ponta

Este experimento foi feito **apenas para fins educacionais**, mostrando como ataques de engenharia social funcionam na prática.

---

## 🧰 Ferramentas e Ambiente

| Recurso | Descrição |
|---------|-----------|
| **Sistema Operacional** | Linux (Kali, Ubuntu, Parrot OS etc.) |
| **Ferramenta** | Social-Engineer Toolkit (SEToolkit) |
| **Modo de ataque** | Credential Harvester Attack Method |
| **Técnica** | Site Cloner |
| **Objetivo** | Capturar credenciais do Facebook |

---

## 🧪 Passo a Passo Completo

### **1️⃣ Abrindo o SEToolkit**
```bash
sudo setoolkit
Selecione:
1) Social-Engineering Attacks

📷 Adicione sua imagem aqui

2️⃣ Website Attack Vectors
Menu → 2) Website Attack Vectors

📷 Adicione sua imagem aqui

3️⃣ Credential Harvester Attack Method
Menu → 3) Credential Harvester Attack Method

Esse modo captura tudo que for digitado no formulário da página clonada.

📷 Adicione sua imagem aqui

4️⃣ Selecionar Site Cloner
Menu → 2) Site Cloner

O SET irá clonar automaticamente qualquer página que você indicar.

📷 Adicione sua imagem aqui

5️⃣ Informar o IP da máquina atacante
Descubra seu IP com:

bash
Copiar código
ip a
Insira seu IP.
Exemplo:

Copiar código
192.168.0.102
6️⃣ Inserir a URL do Facebook para clonar
Digite:

arduino
Copiar código
https://www.facebook.com
O SET irá:

Clonar a página do Facebook

Configurar servidor local

Preparar o ambiente para capturar credenciais

📷 Adicione sua imagem aqui

7️⃣ Página clonada rodando
O SET inicia um servidor hospedando a página falsa.
A vítima vê a mesma página do Facebook.

8️⃣ Vítima insere login e senha
Assim que a vítima tenta se logar:

✔ Login e senha aparecem no terminal
✔ O usuário é redirecionado ao Facebook oficial
✔ O ataque parece legítimo

📊 Credenciais Capturadas
Exemplo real:

yaml
Copiar código
[*] WE GOT A HIT! Printing the output:
PARAM: email=usuario_teste@gmail.com
PARAM: pass=senha123456
📷 Adicione a imagem da captura do terminal

🧭 Fluxo do Ataque
mermaid
Copiar código
flowchart TD
    A[Início do SEToolkit] --> B[Website Attack Vectors]
    B --> C[Credential Harvester]
    C --> D[Site Cloner]
    D --> E[Informar IP Local]
    E --> F[Clonar Facebook]
    F --> G[Vítima acessa link]
    G --> H[Captura de Login e Senha]
    H --> I[Redirecionamento ao Facebook real]
⚠️ Ética e Uso Legal
Proibido utilizar esta técnica para crimes digitais

Autorização é obrigatória para qualquer teste

Uso permitido apenas para estudo e pesquisa

Respeite toda lei de segurança da informação

👨‍💻 Autor
Walterlan Alves dos Santos
Estudante de Cibersegurança • Pentester em formação

📄 Licença
Este projeto está sob a licença MIT.

yaml
Copiar código

---

Se quiser, posso gerar também:

✅ **LICENSE.md (MIT)**  
✅ **Estrutura completa do repositório**  
/imgs
/src
README.md
LICENSE

css
Copiar código

Quer que eu gere a LICENÇA, a estrutura das pastas ou um PDF também?
