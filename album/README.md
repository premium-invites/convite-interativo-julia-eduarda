# Álbum de teste — Julia Eduarda (V6)

**Não utilizar com fotos reais de convidados.** Esta versão utiliza upload anônimo para testes e versões decoradas em bucket público.

## Estrutura
- `album/index.html`: página do álbum, preservando o convite principal na raiz.
- `album/config.js`: Supabase Premium Invites, evento `julia-eduarda`.
- `album/assets/moldura.png`: **PENDENTE**. Enviar a moldura PNG RGBA 1080 × 1920, com transparência central real, para este caminho exato.

## Envio da moldura pelo GitHub
Abra a pasta `album` no repositório, entre em `Add file → Upload files`, e arraste a pasta local `assets` contendo `moldura.png` (ou crie a pasta `album/assets` e envie o PNG dentro dela). Confirme o caminho final no repositório: `album/assets/moldura.png`.

## Teste (somente imagem fictícia)
Em GitHub Pages com publicação da branch main e pasta /(root), o álbum estará em:
`https://premium-invites.github.io/convite-interativo-julia-eduarda/album/`
Use uma imagem de teste, envie e verifique:
- `originais-eventos/julia-eduarda/original` → arquivo sem moldura (bucket privado);
- `fotos-eventos/julia-eduarda/framed` → versão com moldura;
- `fotos-eventos/julia-eduarda/thumbs` → miniatura;
- tabela `public.fotos` → `evento_id=julia-eduarda` e caminhos preenchidos.

## Segurança antes da festa
A pasta por evento e o QR Code não são autenticação. Implementar controles de acesso por evento, proteção contra spam/upload abusivo, moderação e armazenamento privado para galeria antes de enviar a convidados reais. A chave pública do Supabase pode aparecer no JavaScript; chaves secretas nunca.
