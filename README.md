# Cardápio Online

Aplicação simples de cardápio online com carrinho de compras e checkout via WhatsApp. Feita com HTML, Tailwind CSS e JavaScript vanilla, usando Toastify para notificações e Font Awesome para ícones.

## Funcionalidades
- Listagem de produtos e bebidas com botão “adicionar ao carrinho”.
- Carrinho em modal: abre/fecha (inclui fechar ao clicar fora), lista itens, quantidade e preço unitário.
- Remoção de itens decrementa a quantidade; remove quando chega a zero.
- Total calculado e formatado em BRL (pt-BR).
- Contador no rodapé soma as quantidades totais do carrinho (não apenas itens únicos).
- Validação de endereço obrigatório antes do checkout, com feedback visual.
- Finalização via WhatsApp: abre conversa com a mensagem contendo itens e endereço.
- Indicador de funcionamento (18:00–22:00) altera a cor do selo automaticamente.

## Estrutura do Projeto
- `index.html`: marcação principal, menu, modal do carrinho e botão do rodapé.
- `script.js`: lógica do carrinho, modal, validação, formatação e checkout via WhatsApp.
- `styles/style.css`: ponto de entrada do Tailwind CSS (fonte do build).
- `styles/output.css`: CSS gerado pelo Tailwind (importado pelo HTML).
- `tailwind.config.js`: configuração do Tailwind.
- `assets/`: imagens do menu e assets de UI.

## Como Rodar
Opção 1 — Abrir diretamente no navegador:
- Basta abrir `index.html` no navegador.

Opção 2 — Ambiente de desenvolvimento (recompila o Tailwind em tempo real):
- Pré‑requisito: Node.js e npm instalados.
- Instalar dependências: `npm install`
- Rodar o watcher do Tailwind: `npm run dev`
- Abra `index.html` no navegador e edite os arquivos; o CSS será atualizado em `styles/output.css`.

## Tecnologias
- HTML5, JavaScript (vanilla)
- Tailwind CSS (via build local)
- Toastify (CDN)
- Font Awesome (CDN)
- Google Fonts (CDN)

## Licença
- ISC (veja `package.json`).

