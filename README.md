# Tutorial de Listas HTML para Iniciantes

## Sumário
1. [Introdução](#introdução)
2. [Listas Não Ordenadas (ul)](#listas-não-ordenadas-ul)
3. [Listas Ordenadas (ol)](#listas-ordenadas-ol)
4. [Listas de Definição (dl)](#listas-de-definição-dl)
5. [Listas Aninhadas](#listas-aninhadas)
6. [Atributos Especiais](#atributos-especiais)
7. [Exemplo Completo](#exemplo-completo)

---

## Introdução

Listas são elementos fundamentais em HTML, usadas para agrupar e organizar informações de forma estruturada. Existem três tipos principais de listas em HTML:
- **Listas não ordenadas** (`<ul>`) - para itens sem ordem específica
- **Listas ordenadas** (`<ol>`) - para itens com sequência numérica ou alfabética
- **Listas de definição** (`<dl>`) - para pares de termo e descrição

---

## Listas Não Ordenadas (ul)

As listas não ordenadas são usadas quando a ordem dos itens não é importante. Cada item é marcado com um símbolo (geralmente um marcador circular).

### Sintaxe Básica
```html
<ul>
  <li>Primeiro item</li>
  <li>Segundo item</li>
  <li>Terceiro item</li>
</ul>
```

### Exemplo Prático
```html
<h3>Frutas Preferidas</h3>
<ul>
  <li>Maçã</li>
  <li>Banana</li>
  <li>Laranja</li>
  <li>Morango</li>
</ul>
```

**Resultado:**
- Maçã
- Banana
- Laranja
- Morango

---

## Listas Ordenadas (ol)

As listas ordenadas são usadas quando a ordem dos itens é importante. Cada item é numerado automaticamente.

### Sintaxe Básica
```html
<ol>
  <li>Primeiro item</li>
  <li>Segundo item</li>
  <li>Terceiro item</li>
</ol>
```

### Exemplo Prático
```html
<h3>Passo a passo para fazer café</h3>
<ol>
  <li>Ferva a água</li>
  <li>Coloque o pó de café no filtro</li>
  <li>Despeje a água quente sobre o pó</li>
  <li>Aguarde o café passar</li>
  <li>Sirva em uma xícara</li>
</ol>
```

**Resultado:**
1. Ferva a água
2. Coloque o pó de café no filtro
3. Despeje a água quente sobre o pó
4. Aguarde o café passar
5. Sirva em uma xícara

---

## Listas de Definição (dl)

As listas de definição são usadas para apresentar pares de termo e descrição, como glossários ou definições.

### Sintaxe Básica
```html
<dl>
  <dt>Termo 1</dt>
  <dd>Descrição do termo 1</dd>
  
  <dt>Termo 2</dt>
  <dd>Descrição do termo 2</dd>
</dl>
```

### Exemplo Prático
```html
<h3>Glossário de HTML</h3>
<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language - Linguagem de marcação para criar páginas web</dd>
  
  <dt>CSS</dt>
  <dd>Cascading Style Sheets - Linguagem para estilizar páginas web</dd>
  
  <dt>JavaScript</dt>
  <dd>Linguagem de programação para adicionar interatividade às páginas web</dd>
</dl>
```

**Resultado:**

**HTML**
: HyperText Markup Language - Linguagem de marcação para criar páginas web

**CSS**
: Cascading Style Sheets - Linguagem para estilizar páginas web

**JavaScript**
: Linguagem de programação para adicionar interatividade às páginas web

---

## Listas Aninhadas

Você pode criar listas dentro de outras listas para organizar informações hierárquicas.

### Exemplo com Lista Não Ordenada Aninhada
```html
<h3>Estrutura de um Site</h3>
<ul>
  <li>Home
    <ul>
      <li>Banner principal</li>
      <li>Seção de destaques</li>
    </ul>
  </li>
  <li>Sobre
    <ul>
      <li>História</li>
      <li>Equipe</li>
      <li>Missão e Visão</li>
    </ul>
  </li>
  <li>Contato</li>
</ul>
```

### Exemplo com Lista Ordenada Aninhada
```html
<h3>Plano de Estudos</h3>
<ol>
  <li>HTML
    <ol>
      <li>Tags básicas</li>
      <li>Formulários</li>
      <li>Tabelas</li>
    </ol>
  </li>
  <li>CSS
    <ol>
      <li>Seletores</li>
      <li>Box model</li>
      <li>Flexbox</li>
    </ol>
  </li>
</ol>
```

---

## Atributos Especiais

### Atributo `type` para Listas Ordenadas

O atributo `type` permite alterar o estilo de numeração:

```html
<!-- Letras maiúsculas -->
<ol type="A">
  <li>Primeiro item</li>
  <li>Segundo item</li>
</ol>

<!-- Letras minúsculas -->
<ol type="a">
  <li>Primeiro item</li>
  <li>Segundo item</li>
</ol>

<!-- Números romanos maiúsculos -->
<ol type="I">
  <li>Primeiro item</li>
  <li>Segundo item</li>
</ol>

<!-- Números romanos minúsculos -->
<ol type="i">
  <li>Primeiro item</li>
  <li>Segundo item</li>
</ol>
```

### Atributo `start` para Listas Ordenadas

O atributo `start` define o número inicial da lista:

```html
<ol start="5">
  <li>Este é o item 5</li>
  <li>Este é o item 6</li>
  <li>Este é o item 7</li>
</ol>
```

### Atributo `reversed` para Listas Ordenadas

O atributo `reversed` inverte a ordem da numeração:

```html
<ol reversed>
  <li>Terceiro</li>
  <li>Segundo</li>
  <li>Primeiro</li>
</ol>
```

---

## Exemplo Completo

Para ver todos os tipos de listas em ação, confira o arquivo [exemplo.html](exemplo.html) neste repositório. O arquivo contém exemplos práticos de todas as listas abordadas neste tutorial em um documento HTML5 válido.
