# [Voltar para o caso Loja de CDs](https://github.com/tmenegaz/db_dendezeiros/blob/master/assunto/ansRequisitos.md#loja-de-cds)

## [Voltar para o enunciado da prática do catálogo de CDs](https://github.com/tmenegaz/db_dendezeiros/blob/master/assunto/ansRequisitos.md#pratique)

> Nomo do projeto: **Católodo de CDs**
>
> Contratante: **Maria**
>
> Entidades identificadas:
>
> 1. CD - produto da venda
> 2. Musica - conteúdo do CD
> 3. Gravadora - fornecedor do CD
> 4. Autor - cria a música
> 5. Faixa - forma de organização das músucas no CD
> 6. Preço - valor da venda do produto CD
> 7. Artista - conteúdo do CD
> 8. Banda - conteúdo do CD
>
> ![diagrama do catálogo de CDs com alguns atributos](img/entidadesProjetoCatCDs.png "Diagrama do catálogo de CDs")

## [Voltar para o enunciado do relacionamentos do catálogo de CDs](https://github.com/tmenegaz/db_dendezeiros/blob/master/assunto/ansRequisitos.md#relacionamento)

> - **Cada** *CD* **deve ser** *gravado* por **uma única** *gravadora*.
> - **Cada** *gravadora* **deve ter** *gravado* **um ou mais** *CDs*.
>
> ![cd_x_gravadora](img/cd_x_gravadora.png "cd_x_gravadora")
> 
> - **Cada** *CD* **deve ter** *precificado* **um único** *Preço*.
> - **Cada** *Preço* **deve estar** *precificado* em **um ou mais** *CDs*.
> 
> - **Cada** *CD* **deve ter** *garavado* **uma ou mais** *músicas*.
> - **Cada** *música* **deve estar** *garavada* em **um ou mais** *CDs*.
> 
> **OBS**
> Cd tem relação com música ou tem relação  com faixa?
> Se a música tem relação com faixa então a música não precisa ter relação com CD?
> o que acham?
> 
> - **Cada** *Faixa* **deve estar** *incluida* em **uma ou mais** *CD*.
> - **Cada** *CD* **deve ter** *incluido* **um ou mais** *Faixa*.m
> 
> - **Cada** *Faixa* **deve ter** *referenciado* **uma única** *músicas*.
> - **Cada** *música* **deve estar** *referenciada* em **uma única** *Faixa*.
> 
> - **Cada** *Autor* **deve ter** *composta* **uma ou mais** *músicas*.
> - **Cada** *música* **deve ser** *composta* por **um ou mais** *Autores*.
> 
> - **Cada** *Artista* **deve ter** *cantado* **uma ou mais** *músicas*.
> - **Cada** *música* **deve ser** *cantada* por **um ou mais** *Artistas*
> 
> - **Cada** *Música* **deve ser** *tocada* por **uma ou mais** *Bandas*.
> - **Cada** *Banda* **deve ter** *tocado* **um ou mais** *Música*.
> 
> - **Cada** *Banda* **deve ter** *elencado* **um ou mais** *Artistas*.
> - **Cada** *Artista* **deve ser** *elencado* em **uma ou mais** *Bandas*.


[Localize-se: lista das aulas](https://github.com/tmenegaz/db_dendezeiros/blob/master/assunto/lista.md#lista-de-aulas)