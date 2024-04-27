---
theme: dracula
layout: cover
transition: fade
---
# O software livre e o sentido das liberdades

Quer saber por que o software é *livre* e o não-livre é *proprietário*? Bora conversar sobre **liberdade** =D

---
layout: author
---

<img src="https://avatars.githubusercontent.com/u/24627793?v=4" size="65" alt="foto de perfil do GitHub de @cannudo"><br/>

# @cannudo (luan)

Mulher, eu fazia Redes, né. Mas era chato.

[http://github.com/cannudo/](http://github.com/cannudo/)

---
layout: section
---

# A escolha do tema

---
layout: center
---
# [cannudo] Quem tem interesse em palestrar sobre software livre na FLISOL? 😁

---
layout: center
---

# [colega] Tenho interesse em tentar ouvir sobre 🤓

---
layout: center
---

# [cannudo] Certo. Sobre qual aspecto, especificamente? 📝

---
layout: center
---

# [colega] Ué, essa parada aí 🤷‍♂️

---
layout: center
---

<img src="assets/img/gnu-logo.png" size="75" alt="logotipo do sistema GNU">

---
layout: intro
---

# Perguntas

<v-click>

- O que é software?

</v-click>

<v-click>

- O que é distribuição?

</v-click>

<v-click>

- O que é software livre?

</v-click>

<v-click>

- O que é software proprietário?

</v-click>

<v-click>

- Quais exemplos temos disso no mundo real?

</v-click>


---
layout: section
---

# Software

---
layout: quote
---

# “Software é uma **sentença** escrita em uma **linguagem computável**, para a qual existe uma **máquina** capaz de **interpretá-la**.”

Fernandes (2002)

---
layout: fact
---

# ou seja

---
layout: center
---

# isso é software

```python
def somar(a, b):
    return a + b

print("0 + 1 = {}".format(somar(0, 1)))

```

---
layout: center
---

# isso também

<img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/0a100087-f121-4b86-98a1-068a138e9150/deu65o3-6e950be4-4c57-4b94-b651-c8f256b37a4c.png/v1/fill/w_512,h_512,q_80,strp/resident_evil_4_hd_icon_by_loganquest_deu65o3-fullview.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9NTEyIiwicGF0aCI6IlwvZlwvMGExMDAwODctZjEyMS00Yjg2LTk4YTEtMDY4YTEzOGU5MTUwXC9kZXU2NW8zLTZlOTUwYmU0LTRjNTctNGI5NC1iNjUxLWM4ZjI1NmIzN2E0Yy5wbmciLCJ3aWR0aCI6Ijw9NTEyIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmltYWdlLm9wZXJhdGlvbnMiXX0.J3fttEuaw7brfM02nWzNbKaRyZTu6joKJmnrqndUrcU" size="45" alt="ícone do lançador do jogo Resident Evil 4"><br/>

---
layout: quote
---

# e também isso

<br/>

## Instalação local do Potigol

As instruções a seguir permitem que você instale o Potigol localmente em um ambiente Debian GNU/Linux, usando a linha de comandos do sistema. Ocasionalmente, são incluídas alternativas de comandos para Windows.

Ao final, você deve conseguir escrever códigos Potigol e executá-los localmente.

[...]

---
layout: section
---

# Distribuição

---

Nesse contexto, *distribuição* diz respeitos às formas as quais outras pessoas dispõem para obter o software.

<v-click>

- Ele é distribuido pela **internet**?
- É um **CD** que faz a instalação?
- É um **executável** no pen-drive?
- É um sistema **online**?

</v-click>

<v-click>

Dentre outras coisas, *um software pode ser classificado como livre ou proprietário* dependendo de como é *distribuido e sob quais condições ele pode ser acessado*.

</v-click>

---
layout: section
---

# Software livre

---

é um software que respeita *quatro pírincpios essenciais*, conhecidos como *liberdades*.

---
layout: fact
---

Mas antes

---
layout: fact
---

# 1984

---
layout: image
image: https://www.fsf.org/history/img/event/00300printer.jpg
---

---
layout: center
---

<img src="assets/img/gnu-logo.png" size="75" alt="logotipo do sistema GNU">

---
layout: image-left
image: https://i.giphy.com/oUVFtt6s74HLy.webp
---

# Liberdade #0: executar o software, como desejar

<v-click>

Essa liberdade quebra uma restrição que muitos **softwares proprietários** impõem em seus contratos de uso: *este software deve ser usado exclusivamente por <code>tal grupo de pessoas</code>*, *<code>tais empresas</code> não podem executá-lo* ou *o software não pode ser executado em <code>tal cenário</code>*.

Ela define que qualquer pessoa ou empresa pode executar o software em qualquer sistema operacional e em qualquer ambiente, para qualquer trabalho ou finalidade.

</v-click>

---
layout: image-left
image: https://i.giphy.com/11JTxkrmq4bGE0.webp
---

# Liberdade #1: estudar e adaptar o software

<v-click>

A liberdade #1 inclui o direito de executar versões modificadas no lugar original. Se o software é entregue em um sistema que só rode versão `x` e se recuse a rodar a sua versão, essa liberdade se torna apenas uma pretensão vazia ao invés de uma realidade prática. Esses binários não são software-livre,  mesmo que o codigo-fonte a partir do qual foi compilado seja livre.


</v-click>

---
layout: image-left
image: https://i.giphy.com/gEKaPwIDiZffnhmVII.webp
---

# Liberdade #2: resdistribuir cópias do software

<v-click>

Essa liberdade e a próxima (liberdade #3) significam que o usuário é livre para redistribuir copias, sejam modificadas ou não, gratuitamente ou não, a qualquer um e em qualquer lugar sem ter que pedir uma autorização formal dos autores ou pagar para poder fazê-lo.

O usuário também tem o direito de modificar o software para uso privado, sem ter que publicar sua versão. E se publicá-la, não deve ser obrigado a avisar a ninguém que o fez.

</v-click>

---
layout: image-left
image: https://i.giphy.com/gEKaPwIDiZffnhmVII.webp
---

# Liberdade #3: distribuir versões modificadas do software

<v-click>

Essas duas últimas liberdades devem incluir o software em formato executável ou binárias, bem como o código-fonte.

Não há nenhum problema se o software não oferecer a versão executável, pois certas linguagens não suportam este recurso, mas a liberdade para incluí-la na distribuição deve ser concedida.

</v-click>

---

# E o software proprietário?

```python
def eh_livre(software):
    if software.permissoes == ('executar', 'estudar', 'modificar', 'redistribuir'):
        return True
    
    return False
```

---
layout: section
---

# Exemplos

---

Esta apresentação está hospedada no [GitHub](http://github.com/cannudo/apresentacao-flisol) e o repositório de distribuição usa a licença GPL. Você pode acessar o link, baixar o código-fonte do projeto, estudar como eu a fiz, modificá-la, usá-la para qualquer fim e distribuir suas versões modificadas e até vendê-las.

<v-click>

Ela foi  usando o [slidev](http://sli.dev/), uma biblioteca JavaScript que permite que tem como premissa ser uma alternativa de apresentação de slides para desenvolvedores.

</v-click>

<v-click>

O slidev se junta ao [Vue.js](https://vuejs.org) para colocar componentes reativos dentro da apresentação.

</v-click>

<v-click>

Usa [Markdown](https://www.rfc-editor.org/rfc/rfc7763.html) para renderizar textos.

</v-click>

---
layout: section
---

# Limitações de comunicação

---

*Livre* é interpretado no sentido de *liberdade* mesmo. Está correto!

<v-click>

Mas em países que falam Inglês, o termo é traduzido como *free software*. A palavra *free* é polissêmica, podendo se referir a algo que ofereça *liberdade* ou até mesmo que seja *grátis*.

</v-click>

<v-click>

Por esse motivo, as publicações oficiais da FSF quase sempre são acompanhadas de links para uma desambiguação:

> *Free* as in *freedom*, not *free beer*.
> (Livre no sentido de liberdade, não no sentido de cerveja grátis.)

</v-click>

<v-click>

Mesmo com a linguagem ao nosso lado, muitos estudantes novatos associam software livre com software grátis.

O software pode ser livre mesmo que você tenha cobrado por ele. Para o software ser livre, ele deve garantir as quatro liberdades essenciais.

Quando falamos de *software grátis*, estamos nos referindo àpenas uma vantagem de mercado. **Distribuir o software gratuitamente não fornece liberdade suficiente para que o software seja livre!**

</v-click>

<v-click>

E talvez por consumirmos muito conteúdo em Inglês, às vezes até trocamos *free software* por *open source software*. Novamente, estamos nos referindo àpenas uma vantagem competitiva. **Código aberto não fornece liberdade suficiente para que o software seja livre!**

</v-click>

---
layout: end
---

# Um de cada vez

Obrigado pela atenção, pessoal =D