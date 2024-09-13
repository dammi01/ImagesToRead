# ImagesToRead
Repository for testing text recognition of images

## Explorando os Recursos de IA Generativa

as instruções desse desafio eram as seguintes :

Como Entregar esse projeto?

Chegou a hora de você construir um portfólio ainda mais rico e impressionar futuros recrutadores, para isso é sempre importante mostrar os resultados do seu esforço e como você os obteve deixando claro o seu racional, para isso faça da seguinte maneira:

1. Crie um novo repositório no github com um nome a sua preferência
2. Crie uma pasta chamada 'inputs' e salve as imagens que você utilizou
3. Crie uma pasta chamado 'output' e salve os resultados de reconhecimento de texto nessas imagens
4. Crie um arquivo chamado readme.md , deixe alguns prints descreva o processo, alguns insights e possibilidades que você aprendeu durante o conteúdo.
5. Compartilhe conosco o link desse repositório através do botão 'entregar projeto'

## Como não tenho e-mail comercial e sem este não tem como se cadastrar no Serviços da Azure, tive que recorrer a uma solução manual alternativa.
Usei uma das IA's que tenho acesso (neste caso MORPHIC.SH) para tentar replicar o projeto proposto acima.

## Procedimento adotado:

- coletei via Google Images 12 imagens de setores diferentes, extensões diversas (JPG, WEBP, PNG) e com uma resolução mínima para que o reconhecimento de texto fosse possível
- elaborei um prompt para que a IA fosse
   a) analisar cada imagem,
   b) desse uma descrição dela,
   c) extraísse o texto contido e
   d) fizesse a tradução do texto extraído para o português.

## A primeira tentativa

Na primeira tentativa tentei deixar o bot da IA acessar o diretório aonde estão as imagens para executar o procedimento e me passar os resultados. 
Como foram 12 imagens suponho que em uma versão gratuita esse bot estava sendo sobrecarregado, porém trouxe já um resultado intermediário, como podemos ver a seguir:

Prompt:

eu quero que você como especialista de OCR e de imagens me faça a) um resumo descritivo sobre cada arquivo de imagem do diretório a seguir e b) também extraia o texto contido na imagem e c) traduza o mesmo texto para o português. Aqui o link : https://github.com/dammi01/ImagesToRead/tree/main/Inputs

Resposta:

Aqui está um resumo descritivo de cada arquivo de imagem no diretório Inputs do seu repositório, juntamente com a extração do texto contido nas imagens e a tradução para o português.

1. BookCover1.jpg
Descrição: Capa de um livro, provavelmente com título e autor visíveis.
Texto Extraído: (A ser extraído)
Tradução: (A ser traduzido)
2. BookCover2.webp
Descrição: Outra capa de livro, com design gráfico e texto.
Texto Extraído: (A ser extraído)
Tradução: (A ser traduzido)
3. HistoricalDocument1.jpg
Descrição: Documento histórico, possivelmente uma carta ou um registro.
Texto Extraído: (A ser extraído)
Tradução: (A ser traduzido)
4. HistoricalDocument2.webp
Descrição: Outro documento histórico, com texto manuscrito ou impresso.
Texto Extraído: (A ser extraído)
Tradução: (A ser traduzido)
5. InstructionManual.jpg
Descrição: Manual de instruções, possivelmente com diagramas e texto explicativo.
Texto Extraído: (A ser extraído)
Tradução: (A ser traduzido)
6. NewspaperHeadline.png
Descrição: Cabeçalho de um jornal, com título e data.
Texto Extraído: (A ser extraído)
Tradução: (A ser traduzido)
7. ProductLabel.webp
Descrição: Rótulo de um produto, com informações sobre o produto.
Texto Extraído: (A ser extraído)
Tradução: (A ser traduzido)
8. PublicAnnouncement.jpg
Descrição: Anúncio público, possivelmente um aviso ou comunicado.
Texto Extraído: (A ser extraído)
Tradução: (A ser traduzido)
9. StreetSign.webp
Descrição: Placa de rua, indicando direções ou informações de trânsito.
Texto Extraído: (A ser extraído)
Tradução: (A ser traduzido)
10. TouristMap1.png
Descrição: Mapa turístico, com pontos de interesse destacados.
Texto Extraído: (A ser extraído)
Tradução: (A ser traduzido)
11. TouristMap2.jpg
Descrição: Outro mapa turístico, com informações sobre a área.
Texto Extraído: (A ser extraído)
Tradução: (A ser traduzido)
12. WarningLabel.jpg
Descrição: Rótulo de aviso, possivelmente sobre segurança ou precauções.
Texto Extraído: (A ser extraído)
Tradução: (A ser traduzido)
Próximos Passos
Para prosseguir com a extração de texto e tradução, precisarei realizar o OCR (Reconhecimento Óptico de Caracteres) em cada uma das imagens. Isso pode levar algum tempo, então, por favor, aguarde enquanto eu realizo essa tarefa.

Vou começar a extração de texto agora.

## API ERROR !!!!!!!!!!!

## A segunda tentativa

Agora o bot logo no começo me avisa que não poderia acessar o link para processar as imagens e pediu gentilmente para fazer o upload das mesmas para executar a tarefa proposta.

Resposta da IA:

O diretório Inputs do repositório ImagesToRead contém várias imagens que podem ser analisadas. Aqui estão os arquivos disponíveis:

BookCover1.jpg
BookCover2.webp
HistoricalDocument1.jpg
HistoricalDocument2.webp
InstructionManual.jpg
NewspaperHeadline.png
ProductLabel.webp
PublicAnnouncement.jpg
StreetSign.webp
TouristMap1.png
TouristMap2.jpg
WarningLabel.jpg

Próximos Passos

Para realizar a análise de OCR (Reconhecimento Óptico de Caracteres) e extrair o texto de cada uma dessas imagens, precisarei que você faça o download das imagens e as envie aqui, pois não consigo acessar diretamente os arquivos do GitHub para realizar a extração de texto.

Assim que você enviar as imagens, poderei:

a) Fazer um resumo descritivo sobre cada arquivo de imagem.
b) Extrair o texto contido nas imagens.
c) Traduzir o texto extraído para o português.

Por favor, faça o upload das imagens para que eu possa ajudar!

## A terceira tentativa

Agora modifiquei o prompt para não ter que repetir o procedimento inteiro em cada imagem, já que iria fazer o upload de cada imagem individualmente e para não correr mais riscos de interrupção. A seguir o prompt utilizado e alguns screenshots mostrando o procedimento final. 

### PROMPT:
eu quero que você como especialista de OCR e de imagens me faça até eu enviar a mensagem "PRONTO!" a) um descritivo sobre cada arquivo de imagem que eu encaminhar a seguir  b) extraia o texto contido na imagem e c) traduza o mesmo texto para o português. Aqui o primeiro arquivo: 

### Screenshots:
o Github alega que os arquivos de imagem dos screenshots estão vazios, então deixarei no diretório 'Output'
São : - Screenshot_Morphic_1(2)(3).png

### A análise da IA para cada imagem se encontra no diretório 'Output' com o mesmo nome só mudando a extensão do arquivo.
### Usei exatamente os nomes propostos (embora deve ser um erro cometido na digitação das instruções) então o nome dos diretórios é 'inputs' e 'output' e não 'outputs'

## Considerações finais

É realmente surpreendente como as IA's já conseguem interpretar imagens e reconhecer até uma escrita manual bem antiga como no caso da imagem com o 'certificado de dispensa' e a capa de livro com as letras em um estilo mais desenhado.

Colocando as ferramentas certas em ação com certeza tem como construir uma aplicação bem mais complexa, com uma pipeline ETL automatizada, alarme de texto não reconhecido para processamento posterior, etc.
