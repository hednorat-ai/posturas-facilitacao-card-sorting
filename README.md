# Card Sorting — Posturas de Facilitadores

**Projeto completo:** 20 imagens publicadas e disponíveis para o curso **Formação de Instrutores, Multiplicadores e Tutores**.

## Links principais
- [Galeria de imagens (pasta images)](https://github.com/hednorat-ai/posturas-facilitacao-card-sorting/tree/main/images)
- [Arquivo de dados cards.json](https://raw.githubusercontent.com/hednorat-ai/posturas-facilitacao-card-sorting/main/cards.json)
- [Primeira imagem](https://raw.githubusercontent.com/hednorat-ai/posturas-facilitacao-card-sorting/main/images/postura-01.png)
- [Última imagem](https://raw.githubusercontent.com/hednorat-ai/posturas-facilitacao-card-sorting/main/images/postura-20.png)

## Estrutura
- `images/postura-01.png` até `images/postura-20.png`.
- `cards.json`: dados de cada carta, categoria, legenda, descrição e URL pública.
- `index.html`: galeria de referência; para publicar como website, habilite GitHub Pages em **Settings → Pages**, branch `main`, diretório raiz.

## Instrução para o Gemini
> Crie um aplicativo de card sorting para a formação de instrutores, multiplicadores e tutores. Carregue as cartas de https://raw.githubusercontent.com/hednorat-ai/posturas-facilitacao-card-sorting/main/cards.json. Use os URLs do campo `imagem_url`. Embaralhe os cartões, permita classificá-los em "Posturas recomendadas" e "Posturas a evitar", inclua suporte a arrastar/soltar e teclado, feedback pedagógico por carta, placar e reinício. Não infira caráter ou intenção a partir de um gesto isolado; avalie os comportamentos no contexto da situação.

**Nota:** as imagens das posturas 11 a 20 foram extraídas das páginas correspondentes do PDF original já presente no repositório. Isso significa que podem incluir título e legenda da página, diferentemente dos arquivos de foto isolada.
