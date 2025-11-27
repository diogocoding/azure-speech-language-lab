# Análise de Sentimentos com Language Studio e Azure Speech Studio

## 📌 Objetivo do Projeto

Este repositório documenta minha prática no laboratório da DIO utilizando **Azure Speech Studio** e **Language Studio**, com foco em:
- Reconhecimento e síntese de fala (Speech).
- Análise de texto e linguagem natural (Language).
- Criação de bases de conhecimento para bots e análise de sentimentos.

---

## 🧩 Tecnologias Utilizadas

- Microsoft Azure
  - Azure Speech Studio
    - Fala para texto (speech-to-text)
    - Texto para fala (text-to-speech)
  - Azure Language Studio
    - Detecção de idioma
    - Análise de sentimentos / opinião
    - Extração de frases‑chave
    - Detecção de entidades
    - Question Answering (base de conhecimento)
- GitHub para versionamento e documentação (este repositório)

---

## 🔊 Experiência com o Azure Speech Studio

### 1. Reconhecimento de fala (Speech-to-Text)

Atividades realizadas:
- Criação de um recurso de Fala no Azure.
- Uso do Speech Studio para transcrever áudio em texto.
- Observação de como o serviço:
  - Converte áudio em texto automaticamente.
  - Lida com sotaque e qualidade do áudio.

Principais aprendizados:
- A entrada é sempre áudio; a saída é texto.
- Ideal para legendas automáticas, transcrição de reuniões, assistentes virtuais etc.

### 2. Síntese de fala (Text-to-Speech)

Atividades realizadas:
- Geração de fala audível a partir de texto.
- Teste com diferentes vozes e idiomas.

Principais aprendizados:
- A entrada é texto; a saída é áudio.
- Pode ser usada para acessibilidade, leitura automática de conteúdos e bots.

> (Opcional) Adicione aqui prints em uma pasta `/images` e referencie:
> `![Exemplo Speech Studio](./images/speech-studio.png)`

---

## 📝 Experiência com o Azure Language Studio

### 1. Detecção de idioma

- Testei textos em português e outros idiomas.
- O serviço identifica automaticamente o idioma predominante.

### 2. Análise de Sentimentos

Exemplo usado:
> "Passei férias maravilhosas na França."

Resultados observados:
- Idioma: Português  
- Sentimento: fortemente positivo (ex.: 0,88)  
- Frases‑chave: “férias maravilhosas”  
- Entidades: “França”

Aprendizado:
- Útil para analisar feedback de clientes, redes sociais, reviews etc.

### 3. Extração de frases‑chave

- Identifica os **principais pontos** de um texto.
- Diferente de:
  - Detecção de entidade (foca em nomes próprios).
  - Análise de sentimento (foca em positivo/negativo).

### 4. Entidades e Question Answering

- Entidades: o serviço reconhece pessoas, lugares, organizações etc.
- Question Answering:
  - Criação de uma base de conhecimento com pares de pergunta e resposta.
  - Útil para bots que respondem FAQs automaticamente.

---

## 🤖 Integração com Bot Service e Compreensão de Linguagem

Conceitos vistos:
- **Serviço de Bot do Azure**: plataforma em nuvem para criar e gerenciar bots, com integração a vários canais.
- **Compreensão da linguagem coloquial (CLU/LUIS):**
  - Identificação de intenções (o que o usuário quer).
  - Identificação de entidades (informações importantes na frase).

Uso em conjunto:
- Language Studio para entender texto.
- Bot Service para orquestrar conversas.
- Speech Studio para entrada/saída de voz.

---

## 🧠 Conceitos de IA Reforçados

Durante o curso/lab, também revisei:

- Fundamentos de **IA e aprendizado de máquina**:
  - Regressão × Classificação (binária e multiclasse).
  - Aprendizado supervisionado × não supervisionado.
- **Processamento de Linguagem Natural (PLN)**:
  - Tokenização, embeddings, modelos de linguagem.
- Conceitos de **IA generativa**:
  - Modelos de linguagem grandes (LLMs).
  - Engenharia de prompts (ser específico, usar contexto, exemplos e dados de fundamentação).
- **Princípios de IA Responsável**:
  - Imparcialidade, privacidade, segurança, transparência e responsabilidade.

---
## ✅ Conclusões e Aprendizados

- Entendi na prática a diferença entre:
  - Serviços de **Fala** (voz ↔ texto),
  - Serviços de **Linguagem** (análise e compreensão de texto),
  - Serviços de **Tradução** e **Bots**.
- O laboratório ajudou a visualizar aplicações reais:
  - Atendimento automatizado,
  - Análise de feedback em massa,
  - Assistentes de voz integrados com bots.

Este repositório serve como base de estudo e como parte do meu portfólio em soluções de IA no Azure.
