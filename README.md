# Quem eu quero ser hoje?

Apresentação interativa de cartas anonimizadas, com estética de manuscritos medievais e iluminação de velas.

## Como abrir

Extraia o ZIP e abra `index.html` no navegador. Não há dependências nem necessidade de internet, servidor, cadastro ou API. Para ativar o áudio, clique em **Som** (navegadores restringem reprodução automática). Use **Tela cheia** para projetar em sala.

## Funcionalidades

- Navegação com setas, teclado, indicadores ou gesto horizontal no celular.
- Destaque de palavras ao passar sobre a carta; clique ou Enter para abrir a nuvem individual.
- Cloud: animação das cartas sendo reunidas, seguida da nuvem global. Passe sobre as palavras para revelar a contagem.
- Inspire: síntese editorial afetiva, em primeira pessoa, escrita a partir dos temas legíveis das cartas. Não utiliza IA externa nem inventa uma fala atribuída a um estudante específico; é um texto coletivo preparado para esta coleção.
- Configurações: filtro de palavras comuns, lista personalizada de exclusão, comprimento mínimo, limite de palavras e volume. Preferências salvas localmente.
- Feche a nuvem por X, Escape ou clique fora.

## Arquivos

- `cartas.md`: transcrição de leitura provisória de 24 páginas; nomes, assinaturas e turmas removidos. Trechos incertos ou suprimidos indicados. A página 23 não tem conteúdo suficientemente legível e seguro para exibir; conserva-se a entrada para manter a correspondência com o original.
- `cartas.js`: dados utilizados pelo site. Caso revise `cartas.md`, atualize também os textos correspondentes neste arquivo. Nenhuma imagem do manuscrito original acompanha o projeto.
- `index.html`, `style.css`, `app.js`: código do site.
- `assets/`: pergaminho, recortes laterais do cenário, trilha instrumental original sintetizada em loop de 40 segundos.

## Privacidade e revisão

Apesar de omitirmos identificadores explícitos, narrativas pessoais podem ser reconhecíveis por pessoas próximas. Revise antes de apresentar ou publicar; prefira exibição local e obtenha as autorizações pertinentes. Não publique em endereço aberto sem avaliar a confidencialidade. A transcrição manuscrita tem trechos cuja leitura permanece incerta. A carta 23 não entra na contagem de palavras. A síntese Inspire não é uma transcrição.

## Vercel

Importe `MicamAmorim/lettersfromheart` em https://vercel.com/new após enviar os arquivos. Use Framework Preset **Other**, diretório raiz e nenhum comando de instalação ou build. O `vercel.json` configura hospedagem estática e cabeçalhos contra indexação. Não são necessários tokens nem variáveis de ambiente. Os cabeçalhos e robots.txt não restringem o acesso; se necessário, configure proteção de acesso no Vercel antes de publicar.
