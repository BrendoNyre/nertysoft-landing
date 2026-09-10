# NertySoft — Landing Page & Plataforma

> Landing page institucional da **NertySoft**, focada em serviços de desenvolvimento de software sob medida, plataformas web, automações com IA e visão computacional (LPR).

## 🚀 Tecnologias

- **HTML5 & Tailwind CSS**
- **Lucide Icons**
- **Docker & Docker Compose**
- **Nginx (Alpine)**

## 📦 Como rodar localmente com Docker

```bash
docker compose up -d
```

Acesse em `http://localhost:8081`.

## 🌐 Produção

- **Subdomínio:** `nertsoft.nerty.com.br`
- **Ambiente:** Servidor Nginx Reverse Proxy com Docker Compose.

## 🎬 Adicionando fotos e vídeos reais dos cases

A seção "Projetos Reais" (`#cases`) já vem com a estrutura pronta para receber
mídia real — veja `assets/cases/README.md` para a convenção de nomes de arquivo.
Basta salvar os arquivos na pasta do case correspondente (`lpr/`, `erp-oficina/`,
`agendamento/` ou `pdv/`); o site detecta e exibe automaticamente, sem alterar código.

## ⚠️ Antes de publicar

- Troque o número de WhatsApp placeholder em `index.html` (variável `SEU_WHATSAPP`, `const SEU_WHATSAPP = "5500000000000"`) pelo número real da NertySoft.
- Preencha o campo "Cliente" de cada case (ou deixe como "Confidencial" quando houver NDA).
