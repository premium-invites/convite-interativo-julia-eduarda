# Convite Interativo — Julia Eduarda | Premium Invites

## Dados confirmados
- Julia Eduarda (SEM acento), XV anos
- 03/07/2027, 19h30 — horário de Brasília
- Abertura: carta + vídeo `assets/video.mp4` (arquivo enviado neste chat, convertido para H.264)
- Música: mantida do ZIP de Isadora, `assets/musica.mp3` (pode ser substituída por outro MP3 com mesmo nome)
- Cinco botões: confirmação, localização, manual, dress code, sugestões de presentes
- Contagem regressiva integrada à moldura da página principal
- Info acessível no manual e pop-up 9:16
- RSVP em duas etapas e mensagem preparada para WhatsApp

## IMPORTANTE — DADOS PENDENTES PARA PUBLICAÇÃO COMPLETA
1. `whatsappConfirmacao` em `config.js` está **vazio**. NÃO foi reutilizado o número da Isadora, Ágatha ou outro cliente. Sem ele a confirmação coleta dados mas NÃO envia ao WhatsApp.
2. `linkLocalizacao` em `config.js` está **vazio**. Sem a URL do evento o botão avisa que é preciso configurá-la.
3. `whatsappCriador` vem como referência do ZIP Isadora: confirmar antes de divulgação.
4. Capa JPEG de WhatsApp criada a partir da arte principal, não fornecida pelo usuário; revisar se quer outra composição.

## Publicação
Repositório recomendado: `convite-interativo-julia-eduarda`
URL prevista: `https://premium-invites.github.io/convite-interativo-julia-eduarda/`
Envie **index.html**, **config.js** e a pasta **assets/** para a RAIZ do repositório (não deixe subpasta externa do ZIP). Configure GitHub Pages em main / root.
Se mudar o nome do repositório ou usuário, altere as URLs absolutas dos metadados OG em `index.html`.

## Editor
Abra `?editor=1` no endereço publicado; escolha cada área e altere percentuais. As mudanças locais valem somente para seu navegador. Clique em Exportar e substitua o objeto `hotspots` no `config.js` para publicar as posições para todos. O editor usa campos numéricos em porcentagem, sem drag-and-drop.

## Testes necessários depois da publicação
- Imagens/MP3/MP4 acessíveis com caminho `assets/...` (cuidado com maiúsculas/minúsculas)
- Vídeo em H.264, abertura e transição automática
- A música começa após toque e mantém continuidade
- Confirmar presença: preencher, validar e abrir WhatsApp com nome e acompanhantes
- Localização: link exato
- Voltar em páginas, popup Info com botão X e contato
- Contagem regressiva na moldura da arte principal
- Compartilhar WhatsApp: prévia OG e JPEG 1200x630 (cache pode demorar)
- Testar em celular real Android + iPhone. O código foi construído e verificado estaticamente; ainda exige testes reais no GitHub Pages.
