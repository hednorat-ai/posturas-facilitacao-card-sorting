# Card Sorting — Posturas de Facilitadores

Acervo didático com **20 situações** para o curso **Formação de Instrutores, Multiplicadores e Tutores**.

## Situação dos arquivos
- `cards.json` contém nomes, descrições, classificações, textos alternativos e caminhos das 20 imagens.
- `index.html` apresenta uma galeria responsiva. Quando as imagens forem enviadas, aparecerão automaticamente.
- **As imagens JPG precisam ser adicionadas na pasta `images/`**. O manifesto está publicado, mas as 20 fotos ainda não foram transferidas ao repositório.

## Como enviar as 20 imagens
1. Baixe o ZIP fornecido na conversa com o ChatGPT e **extraia** os arquivos.
2. Abra o repositório no GitHub e clique em **Add file → Upload files**.
3. Envie a pasta `images` com os arquivos `postura-01.jpg` até `postura-20.jpg`. Se a interface não preservar a pasta, primeiro crie o diretório `images` e faça o upload a partir dele.
4. Conclua com **Commit changes**.
5. Abra o arquivo `cards.json` e confira os campos `imagem`: todos esperam `images/postura-NN.jpg`.

## Como usar no Gemini
Link de dados JSON (público):
https://raw.githubusercontent.com/hednorat-ai/posturas-facilitacao-card-sorting/main/cards.json

Exemplo de URL de imagem (funciona somente depois de enviar os JPG):
https://raw.githubusercontent.com/hednorat-ai/posturas-facilitacao-card-sorting/main/images/postura-01.jpg

Peça: "Crie um app de card sorting para classificar 20 posturas de facilitação em 'Posturas recomendadas' e 'Posturas a evitar'. Leia o JSON do link acima, use `imagem_url` de cada carta e embaralhe as cartas. Inclua arrastar e soltar, acessibilidade por teclado e feedback formativo. Ao terminar, mostre acertos e explicações. Não deduza intenção ou personalidade a partir de um gesto isolado."

## Habilitar galeria por GitHub Pages
Em **Settings → Pages**, selecione **Deploy from a branch**, `main` e `/(root)`. Depois acesse o endereço gerado pelo GitHub.

## Nota pedagógica
Não rotule pessoas como agressivas, simpáticas ou despreparadas em função do gênero ou de um único gesto. O julgamento deve se referir à **conduta observada dentro do contexto da cena**, levando em conta acessibilidade, cultura, situação e frequência.
