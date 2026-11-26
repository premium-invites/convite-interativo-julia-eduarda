# Convite Interativo — Julia Eduarda | Premium Invites

## Dados confirmados
- Julia Eduarda (SEM acento), XV anos
- 03/07/2027, 19h30 — horário de Brasília
- Abertura: carta + vídeo `assets/video.mp4` (arquivo enviado neste chat, convertido para H.264)
- Música: mantida do ZIP de Isadora, `assets/musica.mp3` (pode ser substituída por outro MP3 com mesmo nome)
- Cinco botões: confirmação, localização, manual, dress code, sugestões de presentes
- Contagem regressiva integrada à moldura da página principal
- Info acessível no manual e pop-up 9:16
- Confirmação de presença com aviso da assessoria, sem formulário ou encaminhamento ao WhatsApp

## IMPORTANTE — DADOS PENDENTES PARA PUBLICAÇÃO COMPLETA
1. A confirmação de presença exibe a mensagem: **“A assessoria entrará em contato para realizar a confirmação de presença.”** Não solicita dados e não abre WhatsApp.
2. `linkLocalizacao` em `config.js` contém uma URL do espaço Monumentalle; confirme se é o local correto antes de compartilhar.
3. `whatsappCriador` vem como referência do ZIP Isadora: confirmar antes de divulgação.
4. Confira a capa JPEG de prévia para o WhatsApp e substitua caso queira usar outra composição.

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
- Confirmar presença: abrir aviso da assessoria e fechar em “Entendi”, pelo fundo ou pela tecla Esc
- Localização: link exato
- Voltar em páginas, popup Info com botão X e contato
- Contagem regressiva na moldura da arte principal
- Compartilhar WhatsApp: prévia OG e JPEG 1200x630 (cache pode demorar)
- Testar em celular real Android + iPhone. O código foi construído e verificado estaticamente; ainda exige testes reais no GitHub Pages.
