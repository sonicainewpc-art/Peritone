# PeritOne — website estático

## Estrutura
- `index.html` — página inicial
- `peritagem.html` — peritagem técnica + termografia
- `fiscalizacao.html` — fiscalização de obras
- `style.css` — estilos
- `script.js` — ano automático no rodapé
- `assets/` — imagens

## Cloudflare Pages
1. Criar um repositório no GitHub e carregar todo o conteúdo desta pasta.
2. No Cloudflare: Workers & Pages → Create → Pages → Connect to Git.
3. Selecionar o repositório.
4. Framework preset: None.
5. Build command: deixar vazio (ou `exit 0` se a interface exigir).
6. Output directory: `/` ou o diretório raiz do projeto.
7. Fazer o deploy.

O site não precisa de servidor, base de dados ou backend.

## Antes de publicar
- Substituir o placeholder do email quando o email da PeritOne estiver definido.
- Confirmar telefone e área de atuação.
- Ligar o domínio personalizado no Cloudflare, se existir.
