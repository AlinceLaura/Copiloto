# 🤖 Microsoft Copilot Studio – Guia Prático

Este repositório contém anotações e boas práticas para trabalhar com **Microsoft Copilot Studio**, incluindo criação e customização de copilots, fluxos de conversa, fallback e uso de IA generativa (GenAI).

---

## 📌 Sumário

* [Criar um Copilot em branco](#criar-um-copilot-em-branco)
* [Customizar um Tópico](#customizar-um-tópico)
* [Personalizar Mensagem de Erro (Fallback)](#personalizar-mensagem-de-erro-fallback)
* [Ajustar a Qualidade da Resposta com GenAI](#ajustar-a-qualidade-da-resposta-com-genai)

---

## 🧱 Criar um Copilot em branco

### ✅ O que é:

Criação de um chatbot do zero, totalmente personalizável.

### ▶️ Passo a passo:

1. Acesse o [Copilot Studio](https://copilotstudio.microsoft.com/).
2. Vá em **Copilots > Criar > Copilot em branco**.
3. Dê um nome ao seu projeto.
4. Clique em **Criar** para abrir o ambiente de edição.

---

## ✨ Customizar um Tópico

### ✅ O que é:

Tópicos definem como o chatbot responde a intenções específicas do usuário.

### ▶️ Passo a passo:

1. Vá em **Tópicos > Novo tópico**.
2. Defina:

   * Nome do tópico.
   * Palavras-chave de gatilho (ex: "ajuda", "pedir suporte").
3. Use o **editor visual** para:

   * Adicionar perguntas, mensagens e condições.
   * Criar ramificações com base em respostas do usuário.
   * Definir ou reutilizar variáveis.
   * Adicionar respostas generativas.

---

## ❗ Personalizar Mensagem de Erro (Fallback)

### ✅ O que é:

Respostas exibidas quando o chatbot não entende a entrada do usuário.

### ▶️ Passo a passo:

1. Vá em **Tópicos**.
2. Edite o tópico chamado **Fallback**.
3. Personalize a mensagem, por exemplo:

   ```text
   Desculpe, não entendi. Você pode reformular ou escolher uma opção abaixo.
   ```
4. Adicione ações úteis:

   * Redirecionar para tópicos gerais.
   * Oferecer opção de falar com um atendente humano.

---

## 🤖 Ajustar a Qualidade da Resposta com GenAI

### ✅ O que é:

Respostas geradas por inteligência artificial com base em prompts e contexto do usuário.

### ▶️ Passo a passo:

1. Dentro de um tópico, clique em **+ > Resposta com IA (generativa)**.
2. Escreva um prompt claro, como:

   ```text
   Explique como funciona o processo de reembolso de forma simples.
   ```
3. (Opcional) Use variáveis no prompt:

   ```text
   Informe a política de reembolso para o produto {{nomeProduto}}.
   ```
4. (Opcional) Ative **Knowledge Sources** para respostas com base em dados específicos.

### 🎯 Dicas para ajustar a qualidade:

* Para respostas mais **precisas**:

  * Use prompts detalhados.
  * Inclua restrições como “responda como especialista técnico”.
* Para respostas mais **genéricas**:

  * Use prompts amplos e curtos.

---
