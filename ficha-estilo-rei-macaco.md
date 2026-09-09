# Ficha de Estilo — O Rei Macaco e a Grande Jornada

Guia de consistência visual pra colar em prompts de geração de imagem (ChatGPT, DALL-E, etc.)

---

## Técnica base

```
Aquarela tradicional, pintada à mão, pinceladas soltas e fluidas. As 
formas são definidas por camadas de cor e sombra — NUNCA por contorno de 
tinta preta ou linha de caneta. As bordas dos elementos se dissolvem 
naturalmente, sem silhueta "recortada". Sem textura granulada ou 
pontilhada tipo "glitter" espalhado pela pintura.
```

**Por que isso importa:** nas primeiras tentativas do projeto, saiu um estilo com contorno de tinta preta (tipo nanquim + aquarela) que destoou do resto do livro — teve que ser regenerado. Também apareceu, repetidamente, uma textura granulada/pontilhada indesejada em várias cenas até fixarmos essa instrução de forma explícita e reforçada.

---

## Paleta de cores

```
Dominante: tons terrosos e dourados — ocre, âmbar, laranja-queimado, 
marrom claro. 
Secundária: azul-acinzentado suave, usado quase exclusivamente em 
elementos distantes (montanhas ao fundo, névoa, água).
Uso de branco do papel: generoso, principalmente nas bordas — o papel 
"respira", não é tudo pintado até a borda.
```

**Exemplo que funcionou bem:** a cena do pêssego (Cap. 8) — céu em gradiente dourado/rosado de entardecer, com o personagem em primeiro plano em cores plenas e saturadas, contra um fundo mais diluído.

---

## Vinheta (bordas esmaecidas)

```
As bordas externas da imagem (topo, base, laterais) devem esmaecer 
suavemente até se dissolver no branco do papel, como uma vinheta suave e 
onírica, sem contorno retangular duro definido — o centro da composição 
permanece nítido, só as extremidades se dissipam.
```

**Quando usar:** cenas de introspecção, solidão, memória (ex: as três imagens do Cap. 9 — o spread do pássaro, a gota de chuva, a memória dos macaquinhos). Também usamos em encontros emocionalmente importantes (Guanyin com Mestre Tang).

**Quando NÃO é obrigatório:** cenas de ação/aventura mais "abertas" podem ter borda reta comum, sem vinheta — não é regra fixa pra 100% das imagens, é uma ferramenta pra cenas com peso emocional maior.

---

## Escala e proporção

```
Regra fixa: Sun Wukong é SEMPRE do tamanho de um macaco pequeno — 
visivelmente menor que qualquer humano adulto na mesma cena. Se ele 
precisar de destaque numa cena com multidão, resolver por POSIÇÃO 
(elevado numa pedra, em primeiro plano) — nunca aumentando o tamanho 
físico dele.
```

**Erro que já aconteceu:** numa cena de batalha, ele saiu do mesmo tamanho dos soldados humanos ao redor. Corrigido especificando "ele tem o tamanho físico de um macaco pequeno, bem menor que qualquer soldado humano adulto" e colocando-o em pé sobre uma pedra pra ganhar destaque sem crescer fisicamente.

**Demais personagens:** ver fichas de DNA individuais (alturas relativas descritas em cada uma — Sha Wujing é o mais alto do grupo humano, Zhu Bajie o mais largo/corpulento, Mestre Tang estatura média).

---

## Luz e atmosfera

```
Preferência geral: luz quente, de entardecer ou início de manhã (dourada, 
suave), mesmo em cenas de tensão — evitar contraste muito duro de luz e 
sombra, que puxa o tom pro "épico adulto" em vez de "livro infantil".
```

**Exceção deliberada:** cenas dentro da pedra onde Sun Wukong fica preso (Cap. 9) usam luz mais fria e cinzenta (dia chuvoso, pouca luz), pra reforçar o isolamento — mas mesmo aí, sem sombras dramáticas excessivas.

**Cuidado com composições muito "cinematográficas":** já tivemos um caso (a primeira tentativa do spread do Cap. 9, com pôr do sol saturado e alto contraste) que ficou bonita mas destoou do tom mais sereno do resto do livro. Prefira luz difusa a luz dramática.

---

## Composição

```
Evitar simetria perfeita/convergente quando a cena envolve espaços 
fechados (grutas, frestas) — pode criar leituras visuais indesejadas. 
Preferir ângulos levemente assimétricos, vistas laterais, câmera não 
centralizada.
```

**Para cenas de multidão/exército:** os personagens principais devem manter escala correta mesmo em meio a uma multidão — usar profundidade de campo e primeiro plano pra dar destaque, não aumentar o personagem.

---

## Composição de página inteira (texto integrado à ilustração)

Para páginas de **abertura de capítulo** e cenas principais: aquarela colorida 
cheia, seguindo a ficha de estilo acima (dourados, terrosos, luz quente).

Para páginas de **transição silenciosa ou contemplativa** (fechamentos de 
capítulo, partidas, momentos de reflexão): esboço a lápis 
puro, sem cor — linhas de construção visíveis, tom monocromático sobre o 
fundo creme da página. Funciona como uma "pausa respirada" antes do próximo 
capítulo começar, um registro visual deliberadamente mais silencioso que o 
resto do livro.

Regra de aplicação: usar o lápis em momentos de **transição silenciosa/contemplativa** 
— não só fechamentos literais de capítulo, mas qualquer cena de pausa emocional, 
partida, ou reflexão quieta, mesmo com volume de texto moderado (não precisa ser 
só "pouco texto"). Nunca usar nas ilustrações de ação principal de um capítulo, 
pra manter os dois registros (aquarela cheia vs. lápis) claros e intencionais.

---

## Resolução e formato de impressão

**Padrão oficial do livro**: 2400×3000px (proporção 0,8 — formato retrato 
8×10 polegadas / 20,3×25,4cm a 300 DPI). Esse é o tamanho de trim comum 
pra livros ilustrados coloridos em plataformas como Amazon KDP.

**Instrução de prompt pra sempre incluir** (composições de página inteira 
com texto integrado, geradas no ChatGPT):

```
Gere a imagem em exatamente 2400x3000 pixels (proporção retrato 4:5, 
formato 8x10 polegadas a 300 DPI) — não uma proporção aproximada, o 
tamanho exato importa pra impressão. 
```

**Nota sobre imagens já existentes**: várias composições já feitas usam 
proporções diferentes (0,65 a 0,88, variando por geração). Isso é aceitável 
como está — na hora de montar o livro final, cada uma vai precisar de um 
ajuste pequeno de recorte/margem pra caber no formato oficial, mas não 
precisam ser regeradas só por causa disso.

**Consistência de fonte**: como o tamanho da fonte no texto integrado 
também varia entre gerações (mesmo dentro do mesmo tamanho de canvas), 
incluir também no prompt:

```
O texto deve ocupar entre 45-55 caracteres por linha, com margens de 
aproximadamente 8% da largura da página em cada lado. Mantenha esse 
mesmo tamanho relativo de fonte em todas as páginas do livro.
```

---

## Checklist rápido antes de aceitar uma imagem

- [ ] Sem contorno de tinta preta?
- [ ] Sem textura granulada/pontilhada?
- [ ] Paleta dourada/terrosa com azul só no fundo?
- [ ] Escala de Sun Wukong correta (menor que humanos)?
- [ ] Se for cena íntima: tem vinheta esmaecida?
- [ ] Luz suave, não dramática/alto-contraste?
- [ ] Composição não força uma leitura visual estranha/indesejada?
