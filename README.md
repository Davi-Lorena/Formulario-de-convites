# 🎉 Festivite

### Crie o convite digital do seu evento em poucos cliques.

Um formulário de criação de convites, **100% responsivo**, construído apenas com **HTML e CSS**.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Responsivo](https://img.shields.io/badge/Layout-Responsivo-2ECC71?style=flat-square)
![Deploy](https://img.shields.io/badge/Deploy-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

![Foto 1](https://github.com/user-attachments/assets/12c85253-6bcd-4d05-9450-b4168f79345c)

---

## ✨ Sobre o projeto

O **Festivite** é a interface de uma plataforma fictícia de convites digitais: a pessoa descreve o evento, escolhe um tema, define as cores e informa seus dados de contato, tudo numa única tela organizada e fácil de preencher.

O projeto nasceu como **desafio prático da trilha Fullstack da [Rocketseat](https://www.rocketseat.com.br/)** e virou um laboratório para treinar o que mais importa em um front-end sólido: **estrutura semântica de formulários, estilização com CSS puro e responsividade**.

> 💡 **Sem frameworks, sem bibliotecas, sem JavaScript.** Cada detalhe visual foi resolvido com HTML e CSS.

---

## 📱 Totalmente responsivo

A versão inicial do projeto era pensada para desktop. Agora o layout **se adapta a qualquer tela**:

| Dispositivo | Como o layout se comporta |
| :--- | :--- |
| 🖥️ **Desktop** | Painel lateral com a identidade do Festivite ao lado do formulário |
| 📲 **Tablet** | Espaçamentos e grades reorganizados para aproveitar a largura disponível |
| 📱 **Celular** | Campos empilhados em coluna única, pensados para o toque e a rolagem |

---

## 🧩 O que tem no formulário

O formulário é dividido em seções (`fieldset`), cada uma com seu ícone e propósito:

### 📅 Sobre o evento
- **Título** do evento
- **Início** e **fim** com seletor de data e hora (`datetime-local`)
- **Tipo**: presencial ou online
- **Local**: endereço ou link da reunião
- **Descrição** com os detalhes do evento

### 🎨 Personalização
- **Cor principal**: paleta com 11 opções
- **Tema do evento**: 12 cards ilustrados
  *Aniversário · Infantil · Formatura · Casamento · Chá de bebê · Chá de panela · Carnaval · Páscoa · São João · Halloween · Natal · Outro*
- **Estilo**: alternância entre modo claro e escuro do convite
- **Foto de capa**: envio de imagem pelo botão estilizado de upload

### 📇 Dados para contato
- **Nome completo** (obrigatório)
- **E-mail**
- **Telefone**

### ✅ Finalização
- Aceite de **Termos e Condições** e **Política de Privacidade**
- Opções para receber novidades por **e-mail** e por **SMS**
- Botão **Gerar convite**

---

## 🛠️ Tecnologias e recursos

- **HTML5** com marcação semântica (`aside`, `main`, `form`, `fieldset`, `legend`, `label`)
- **CSS3** com Grid e Flexbox para organizar o layout e as grades de cards
- **Media queries** para adaptar a interface a diferentes larguras de tela
- **Inputs variados**: `text`, `radio`, `checkbox`, `datetime-local`, `file`, `email`, `tel` e `textarea`
- **SVGs** para ícones e logotipo
- **Google Fonts**: *Leckerli One*, *Baloo 2* e *Open Sans*

---

## 🚀 Como rodar localmente

Não há dependências para instalar. Basta:

```bash
# 1. Clone o repositório
git clone https://github.com/Davi-Lorena/Formulario-de-convites.git

# 2. Entre na pasta
cd Formulario-de-convites

# 3. Abra o index.html no navegador
```

💡 Se preferir, use a extensão **Live Server** do VS Code para ver as alterações em tempo real.

---

## 🧠 O que eu pratiquei

- Construir formulários completos e bem estruturados com diferentes tipos de `input`
- Estilizar elementos nativos difíceis de customizar (radio, checkbox, upload de arquivo)
- Organizar o espaço da tela com Grid e Flexbox
- Criar um layout que se adapta de desktop a celular
- Manter consistência visual com paleta de cores, tipografia e ícones

---

## 🔭 Próximos passos

- [ ] Capturar os dados do formulário para gerar o convite de fato
- [ ] Validação personalizada com mensagens de erro nos campos
- [ ] Pré-visualização do convite em tempo real
- [ ] Compartilhamento do convite por link

---

## 👤 Autor

Feito com 💜 por **Davi Lorena**

[![GitHub](https://img.shields.io/badge/GitHub-Davi--Lorena-181717?style=flat-square&logo=github)](https://github.com/Davi-Lorena)

---

⭐ Gostou do projeto? Deixe uma estrela no repositório!
