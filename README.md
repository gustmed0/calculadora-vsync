# Calculadora VSYNC

Calculadora da facção VSYNC (FiveM): vendas de itens com e sem parceria, comissão do vendedor e serviços (lavagem, desmanche, secagem).

## Arquivos
- `index.html` — a página inteira
- `vsync.jpg` — arte da facção (topo e fundo)

## Publicar no GitHub Pages
1. Crie um repositório novo no GitHub (ex.: `calculadora-vsync`), público.
2. Clique em **Add file → Upload files** e envie `index.html` e `vsync.jpg`.
3. Vá em **Settings → Pages**.
4. Em **Source**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)` e clique em **Save**.
5. Em 1–2 minutos o link aparece no topo dessa tela:
   `https://SEU-USUARIO.github.io/calculadora-vsync/`

## Mudar valores
Abra `index.html` e edite o bloco `CONFIG` no começo do arquivo:
- `comissaoVendedor` — % de quem vendeu
- `itens` — nome, preço `com` parceria e `sem` parceria
- `servicos` — porcentagens de cliente e facção

Depois envie o `index.html` de novo para o repositório (o site atualiza sozinho).
