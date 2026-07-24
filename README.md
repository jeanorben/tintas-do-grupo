# Tintas do Grupo

Lista de tintas de miniatura do Jean e do Felipe. Página publicada em: https://jeanorben.github.io/tintas-do-grupo/

## Como editar (Felipe, é contigo)

1. Faça login no GitHub (crie conta se não tiver, é grátis).
2. Peça pro Jean te adicionar como colaborador (Settings > Collaborators do repositório).
3. Abra o arquivo `index.html` aqui no GitHub e clique no lápis (Edit) no canto direito.
4. Ache a seção da cor certa (Brancos, Azuis, Verdes...) e copie uma linha existente como modelo:

```html
<div class="row"><span class="sw" style="background:#8a4b26"></span><span class="nome">NOME DA TINTA</span><span class="marca">MARCA</span><span class="tipo">base</span><span class="dono df">Felipe</span></div>
```

5. Troque:
   - `background:#8a4b26` pela cor aproximada em hex (joga o nome da tinta no Google Imagens e pega o tom com um color picker qualquer, ex.: https://imagecolorpicker.com)
   - `NOME DA TINTA` e `MARCA` (Citadel, IONIC, AK, Vallejo, Acrilex...)
   - `tipo`: base, layer, wash, contrast, metálica, textura, verniz ou medium
   - dono: `class="dono df"` + `Felipe`, ou `class="dono dj"` + `Jean`
   - Tinta metálica: use `class="sw metal"` no quadradinho. Verniz/medium sem cor: `class="sw medium"` e sem background.
6. Atualize o contador de potes no topo da página (linha "Acervo combinado · NN potes").
7. Desça a página, escreva uma mensagem curta de commit (ex.: "adiciona IONIC Sky Blue") e clique em **Commit changes**.
8. Em 1-2 minutos o site atualiza sozinho no mesmo link.

Errou algo? Sem drama: todo commit fica no histórico e dá pra reverter.
