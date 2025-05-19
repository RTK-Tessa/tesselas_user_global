# 🌐 Tesselas User Global

Este repositório faz parte do projeto **RTK (Rede Tesselar de Conhecimento)** e armazena tesselas criadas por usuários de forma colaborativa.

## 📖 O que são Tesselas?

Tesselas são unidades de conhecimento em formato `.md` (Markdown), utilizadas por assistentes pessoais (como o **RTKServer**) para armazenar e compartilhar informações estruturadas sobre temas variados.

## 📁 Estrutura

Cada arquivo `.md` contém informações sobre um assunto específico, por exemplo:

- `tessela_padarias_bm_rj.md` — Lista de padarias em Barra Mansa - RJ
- `tessela_pontos_turisticos_paris.md` — Dicas sobre pontos turísticos de Paris
- `tessela_melhores_cafes_sp.md` — Melhores cafeterias em São Paulo

## 🧠 Uso

O sistema **RTKServer** pode sincronizar automaticamente estas tesselas para a pasta local do usuário (`TESSELAS_users_local`) se uma tessela for acessada e não estiver presente localmente.

## 👥 Como contribuir

1. Faça um fork deste repositório.
2. Crie ou edite tesselas (formato `.md`) com conteúdo útil.
3. Envie um pull request.

> Todas as tesselas devem ter títulos, conteúdo útil e podem conter seções com listas, tabelas, links, etc.

## ✍️ Exemplo de Tessela

```markdown
# Padarias em Barra Mansa - RJ

- **Padaria Central**
  - Endereço: Rua A, nº 100
  - Telefone: (24) 99999-0000
  - Especialidades: Pão francês, Sonho, Donuts

- **Doce Massa**
  - Endereço: Av. das Flores, nº 250
  - Telefone: (24) 88888-1111
  - Wi-Fi gratuito, aceita Pix
