# GeoLab — Brasil: Terra, Poder e Mundo

Site educacional interativo desenvolvido para o Seminário Bimestral da turma INFO2V.

## Conteúdo do repositório

- `index.html` — livro digital vivo completo
- `assets/media/debate-concentracao-fundiaria-agronegocio.mp3` — podcast/debate de apoio
- `assets/media/videoaula-brasil-terra-poder-mundo.mp4` — videoaula de apoio
- `assets/media/videoaula-poster.jpg` — capa do player de vídeo
- `.nojekyll` — evita processamento do Jekyll
- `404.html` — fallback simples
- `README.md` — este arquivo

## Publicar no GitHub Pages

### Opção recomendada: Git / GitHub Desktop
Os dois arquivos de mídia estão abaixo do limite de 100 MB por arquivo do GitHub, mas são grandes demais para alguns fluxos de upload individual pelo navegador. Use GitHub Desktop ou `git push`.

1. Crie um repositório vazio no GitHub.
2. Coloque **todo o conteúdo desta pasta na raiz** do repositório.
3. Faça commit e push.
4. Abra **Settings > Pages**.
5. Em **Build and deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
6. Salve e aguarde a publicação.

## Observações

- O site é estático; não precisa de backend.
- Progresso, Caderno, revisões e preferências são armazenados em `localStorage`.
- O podcast foi convertido para MP3 e a videoaula foi otimizada para reduzir o tamanho do repositório e facilitar a hospedagem no GitHub Pages.
- Os players usam controles nativos do navegador e os materiais também podem ser baixados pela própria página.


## Favicon e identidade

A identidade do GeoLab já está configurada no `index.html`.

Arquivos:
- `assets/images/favicon.ico`
- `assets/images/favicon-32x32.png`
- `assets/images/favicon-48x48.png`
- `assets/images/apple-touch-icon.png`
- `assets/images/android-chrome-192x192.png`
- `assets/images/android-chrome-512x512.png`
- `site.webmanifest`

Não é necessário editar os caminhos: ao publicar a raiz do projeto no GitHub Pages, o favicon já será carregado automaticamente.
