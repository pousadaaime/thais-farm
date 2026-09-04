# Thaís Farm Rio · Gerador de Link UTM

Ferramenta simples, feita pra usar pelo celular, que gera links de rastreio com UTM padronizada pra Thaís Farm Rio (@thayfarmrio).

## Como usar

1. Abra a página publicada (link nas configurações do GitHub Pages do repositório).
2. Cole o link da página que quer divulgar.
3. Escolha onde vai enviar: Grupo, Stories, Feed, Link na bio ou Cliente no WhatsApp.
4. O link final já sai pronto com `utm_source` (de acordo com o destino escolhido), `utm_medium=Organico` e `utm_campaign=A6CY`.
5. Toque em **Copiar** ou **Compartilhar**.

Se o link colado já tiver UTM de outra origem (ex: de outra vendedora), ela é removida automaticamente antes de aplicar a UTM da Thaís.

## Configuração

O ícone de engrenagem no topo abre as configurações de `utm_medium` e `utm_campaign` — só mexer se a campanha mudar. Ficam salvas no navegador (localStorage).

## Deploy

Site estático puro (HTML/CSS/JS, sem build). Publicado via GitHub Pages a partir da branch `main`, pasta raiz.
