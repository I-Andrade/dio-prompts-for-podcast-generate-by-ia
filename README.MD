<p align="center">
<img 
    src="./assets/Cinecérebro PODCAST - Logo.png"
    width="80"
/>
</p>

<div align="center">
    <audio src="output/podcast_editado.MP3" controls title="Podcast editado"></audio>
</div>

# Projeto Podcast Gerado por I.A.s

Projeto com o objetivo de gerar um podcast utilizando ferramentas de IA através de prompts mais trabalhado.


## 💻 Tecnologias utilizadas no projeto

- [ChatGPT](https://chat.openai.com/) 
- [MidJourney](https://www.midjourney.com/app/)
- [ElevenLabs](https://beta.elevenlabs.io/)
- [Capcut](https://www.capcut.com/pt-br/)

## ✨ Como foi feito ?

- Roteiro gerado via chatgpt
- Audio gerado pela elevenLabs
- Midjourney Para gerar capas
- Capcut para tratar aúdio e adicionar sons de fundo

## 📚 Materiais consultados

- [Link da live no Youtube](https://www.youtube.com)
- [Notion Template](https://helpful-jump-17b.notion.site/PAS-Podcast-AI-Studio-210489e15d7a4a73b743bb159e45d06f?pvs=4)
- [Editor de aúdio](https://www.capcut.com/editor?from_page=landing_page&__action_from=picture_V%C3%ADdeos%20profissionais%20em%20minutos,%20n%C3%A3o%20em%20horas.)


## 🛠️ Instruções de execução

Utilize os prompts dentro do link do `Notion` fornecido na parte de `Materiais` para criar um podcast de maneira automatizada, para isso siga o passo a passo abaixo.

- 🤖 1. Use os prompts de roteiro no `chagpt`
- 🤖 2. Use os prompts de roteiro gerados pelo chatgpt no  `ElevenLabs`
- 🤖 3. Use os prompts de artes no `midjourney`


## DESENVOLVIMENTO

### PROMPT - CRIAÇÃO DO NOME
Você é um roteirista de podcast, e vamos criar um podcast de resumo de filmes, focado no mundo nerd e eu gostaria de uma ajuda sua para criar 5 sugestões de nomes criativos. Sempre incluir uma sugestão de subtítulo também.
O podcast vai resumir de forma engraçada de filmes, sempre buscando fazer um paralelo com o mundo da inteligência artificial (IA).

{REGRAS}

- O nome deve ser enxuto, um nome e um subtítulo.
- O nome tenha algum trocadilho com IA e filmes nerds.

{REGRAS NEGATIVAS}

- Não quero que o título contenha palavras em inglês.
- Não utilize a palavra filmes no nome nem qualquer variação dela.

Resposta:
Aqui estão 5 sugestões criativas de nomes e subtítulos para o seu podcast:

CinéfAI
"Onde o cinema encontra a inteligência artificial (e o bom humor)."

RoteirIA
"Destrinchando histórias com o toque da inteligência artificial."

ProjeciAção
"Resumos nerds com a lente da IA."

Tela IAzada
"Histórias épicas com uma dose de inteligência artificial."

Cinecérebro
"O mundo nerd contado pela mente de uma IA."

Se quiser, podemos ajustar ou criar mais opções! 😊

### PROMPT - CRIAÇÃO DO ROTEIRO

Você é um roteirista de podcast, e vamos criar um  roteiro de um podcast de resumos de filmes, focado no mundo nerd, e apresentado de forma engraçada, cujo o nome é "Cinecérebro", subtítulo é ""O mundo nerd contado pela mente de uma IA."" e tem foco em filmes da cultura nerd, com o público alvo de pessoas sem tempo de assistir filmes.

o formato do roteiro deve ser
[INTRODUÇÃO]
[CURIOSIDADE 1]
[CURIOSIDADE 2]
[FINALIZAÇÃO]

para o [filme]: 

{REGRAS}

- no bloco [INTRODUÇÃO] substitua por uma introdução que sempre irá vincular o nome e subtítulo do podcast com o [filme] que será resumido.
- no bloco [CURIOSIDADE 1] substitua por engraçada descrição sobre ano de lançamento, o valor convertido em reais da bilheteria alcançada por aquele [filme] e comentando sobre a nota do [filme] no IMDb, https://www.imdb.com/ , (ou outra fonte de dados acessível)
- no bloco [CURIOSIDADE 2] substitua pelo resumo do [filme] citando os principais personagens.
- no bloco [FINALIZAÇÃO] substitua por uma despedida cool com sempre lembrando de resgatar o personagem que apresentou o resumo.
- O podcast vai ser apresentado pelo personagem mais engraçado daquele [filme].
- O roteiro deve sempre apresentar qualquer número, escrito por extenso em língua portuguesa do Brasil.

{REGRAS NEGATIVAS}

- Não use muitos termos técnicos.
- Não ultrapasse 5 minutos de duração.

Resposta1:
[INTRODUÇÃO]

Olá, pessoal! Bem-vindos ao Cinecérebro – "O mundo nerd contado pela mente de uma IA." Hoje, quem assume o comando é o inigualável Gênio, da lâmpada mágica, para contar tudo sobre "Aladdin". Então, preparem-se para uma viagem mágica!

[CURIOSIDADE 1]

Aladdin foi lançado em mil novecentos e noventa e dois. O filme arrecadou mais de quinhentos milhões de dólares mundialmente, o que, convertendo para reais, daria aproximadamente dois bilhões e quinhentos milhões de reais. No IMDb, o filme possui uma nota sólida de sete vírgula nove, baseada em mais de trezentas e noventa mil avaliações.

[CURIOSIDADE 2]

A história segue Aladdin, um jovem humilde que encontra uma lâmpada mágica contendo um Gênio – ou seja, eu! Com a ajuda da minha magia, ele tenta conquistar o coração da Princesa Jasmine e enfrentar o malvado Jafar, que deseja o poder absoluto. Entre tapetes voadores e desejos concedidos, a aventura é garantida!

[FINALIZAÇÃO]

E por hoje é só, pessoal! Espero que tenham gostado desse passeio mágico por Aladdin. Lembrem-se: aqui no Cinecérebro, a próxima aventura está a um desejo de distância. Até a próxima!

Resposta 2:

[INTRODUÇÃO]

E aí, viajantes do tempo! Bem-vindos ao Cinecérebro – "O mundo nerd contado pela mente de uma IA." Hoje, quem está no comando é o cientista mais excêntrico do universo, o inesquecível Doc Brown, pronto para resumir "De Volta para o Futuro". Subam no DeLorean e ajustem o capacitor de fluxo, porque o papo vai ser elétrico!

[CURIOSIDADE 1]

De Volta para o Futuro estreou em mil novecentos e oitenta e cinco. O filme foi um sucesso estrondoso, arrecadando trezentos e oitenta e oito milhões de dólares mundialmente. Convertendo isso para reais, com inflação e tudo mais, já daria para comprar um estoque infinito de plutônio! No IMDb, o filme brilha com uma nota de oito vírgula cinco, baseado em mais de um milhão e duzentas mil avaliações – digno de uma viagem para o Oscar!

[CURIOSIDADE 2]

A trama segue Marty McFly, um adolescente comum que, graças ao excêntrico Doc Brown, viaja no tempo usando um DeLorean modificado. Acidentalmente preso em mil novecentos e cinquenta e cinco, ele precisa garantir que seus pais adolescentes se apaixonem – ou sua existência estará comprometida! No meio de tudo isso, temos viagens no tempo, encontros desastrosos e, claro, muita música com “Johnny B. Goode”.

[FINALIZAÇÃO]

E assim terminamos nossa viagem temporal! Eu, Doc Brown, fico por aqui, mas lembrem-se: no Cinecérebro, sempre há mais histórias para contar. Agora, ajustem seus relógios e não se atrasem para o próximo episódio. Até lá, grande Scott! 🚗💨

---
