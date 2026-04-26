# 📖 Módulo 01 - HTML (Estruturas para Web)

> Estrutura de fundamentos de HTML para desenvolvimento web profissional

---

## 🎯 Objetivo do Módulo

Dominar os fundamentos de HTML5 e suas estruturas semânticas para criar documentos web bem estruturados, acessíveis e validados.

---

## 📚 Conteúdo Detalhado

### 1️⃣ Introdução ao HTML

#### O que é HTML?

HTML (HyperText Markup Language) é a linguagem padrão para criar páginas web. Ela usa **tags** para estruturar e marcar conteúdo.

```html
<!-- Exemplo básico de tag -->
<p>Este é um parágrafo</p>
```

#### História do HTML

- **HTML1 (1991)** - Primeira versão com tags básicas
- **HTML2 (1995)** - Adição de formulários
- **HTML3.2 (1997)** - Suporte a tabelas e applets
- **HTML4 (1999)** - Suporte a folhas de estilo (CSS)
- **XHTML (2000)** - HTML como XML
- **HTML5 (2014)** - Versão atual, mais semântica e com APIs

#### HTML4 vs HTML5

| Aspecto | HTML4 | HTML5 |
|--------|-------|-------|
| Declaração | `<!DOCTYPE html PUBLIC...>` | `<!DOCTYPE html>` |
| Validação | Mais complexa | Mais simples |
| Semântica | Limitada | Rica e completa |
| APIs | Nenhuma | Múltiplas (Canvas, Geolocation, etc.) |
| Acessibilidade | Básica | Avançada |

#### Ferramentas Necessárias

- ✅ **Editor de Texto:** VS Code, Sublime Text, Atom
- ✅ **Navegador Web:** Chrome, Firefox, Safari, Edge
- ✅ **Validador HTML:** https://validator.w3.org/
- ✅ **DevTools:** F12 em qualquer navegador

---

### 2️⃣ Estrutura Básica de um Documento HTML

#### Anatomia de um Documento HTML5 Completo

```html
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Descrição da página">
    <title>Título da Página</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <header>
      <h1>Bem-vindo!</h1>
    </header>
    
    <nav>
      <ul>
        <li><a href="#sobre">Sobre</a></li>
        <li><a href="#contato">Contato</a></li>
      </ul>
    </nav>
    
    <main>
      <article>
        <h2>Artigo Principal</h2>
        <p>Conteúdo do artigo...</p>
      </article>
    </main>
    
    <footer>
      <p>&copy; 2026 Todos os direitos reservados</p>
    </footer>
    
    <script src="script.js"></script>
  </body>
</html>
```

#### Explicação de Cada Parte

1. **`<!DOCTYPE html>`** - Declara que é um documento HTML5
2. **`<html lang="pt-BR">`** - Elemento raiz, define idioma
3. **`<head>`** - Contém metadados e configurações
4. **`<meta charset="UTF-8">`** - Define codificação de caracteres
5. **`<meta name="viewport">`** - Define responsividade mobile
6. **`<title>`** - Título mostrado na aba do navegador
7. **`<body>`** - Contém todo o conteúdo visível

---

### 3️⃣ Tags Semânticas HTML5

Semântica significa usar tags que descrevem corretamente o tipo de conteúdo.

```html
<!-- ❌ Evitar usar <div> para tudo -->
<div>
  <div>Menu</div>
  <div>Conteúdo</div>
</div>

<!-- ✅ Usar tags semânticas -->
<header>
  <nav>Menu</nav>
</header>
<main>
  Conteúdo
</main>
```

#### Tags Semânticas Principais

| Tag | Uso | Exemplo |
|-----|-----|---------|
| `<header>` | Cabeçalho da página/seção | Logo, título principal |
| `<nav>` | Navegação | Menu, links principais |
| `<main>` | Conteúdo principal | Único por página |
| `<article>` | Conteúdo independente | Blog post, notícia |
| `<section>` | Agrupamento temático | Capítulo de um artigo |
| `<aside>` | Conteúdo complementar | Sidebar, publicidade |
| `<footer>` | Rodapé | Copyright, links extras |

#### Exemplo de Layout Semântico

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Meu Blog</title>
</head>
<body>
  <header>
    <h1>Meu Blog Pessoal</h1>
    <nav>
      <ul>
        <li><a href="/">Início</a></li>
        <li><a href="/blog">Blog</a></li>
        <li><a href="/sobre">Sobre</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <article>
      <h2>Primeiro Post</h2>
      <p>Conteúdo do post...</p>
    </article>
    
    <article>
      <h2>Segundo Post</h2>
      <p>Conteúdo do post...</p>
    </article>
  </main>

  <aside>
    <h3>Posts Recentes</h3>
    <ul>
      <li><a href="#">Post 1</a></li>
      <li><a href="#">Post 2</a></li>
    </ul>
  </aside>

  <footer>
    <p>&copy; 2026 Meu Blog. Todos os direitos reservados.</p>
  </footer>
</body>
</html>
```

---

### 4️⃣ Formatação de Texto

#### Títulos

```html
<h1>Título Principal (único por página)</h1>
<h2>Subtítulo</h2>
<h3>Sub-subtítulo</h3>
<h4>Nível 4</h4>
<h5>Nível 5</h5>
<h6>Nível 6</h6>
```

#### Parágrafos e Quebras

```html
<p>Este é um parágrafo.</p>
<p>Outro parágrafo após quebra de linha.</p>

<!-- Quebra de linha (raro usar) -->
<p>Primeira linha<br>Segunda linha</p>

<!-- Linha horizontal -->
<hr>
```

#### Ênfase e Negrito

```html
<!-- Semântico - preferir usar -->
<strong>Texto importante (negrito)</strong>
<em>Texto enfatizado (itálico)</em>

<!-- Apenas visual - evitar -->
<b>Apenas negrito</b>
<i>Apenas itálico</i>
```

#### Exemplo Completo

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Formatação de Texto</title>
</head>
<body>
  <h1>Formatação de Texto em HTML</h1>
  
  <p>Este é um parágrafo com <strong>texto importante</strong> 
     e <em>texto enfatizado</em>.</p>
  
  <h2>Exemplo de Sub-seção</h2>
  <p>Mais conteúdo aqui...</p>
  
  <hr>
  
  <p>Conteúdo após linha horizontal.</p>
</body>
</html>
```

---

### 5️⃣ Listas

#### Listas Não Ordenadas (com bullets)

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```

#### Listas Ordenadas (com números)

```html
<ol>
  <li>Primeiro passo</li>
  <li>Segundo passo</li>
  <li>Terceiro passo</li>
</ol>
```

#### Listas Aninhadas

```html
<ul>
  <li>Frutas
    <ul>
      <li>Maçã</li>
      <li>Banana</li>
    </ul>
  </li>
  <li>Legumes
    <ul>
      <li>Cenoura</li>
      <li>Brócolis</li>
    </ul>
  </li>
</ul>
```

#### Listas de Definição

```html
<dl>
  <dt>HTML</dt>
  <dd>Linguagem de marcação para web</dd>
  
  <dt>CSS</dt>
  <dd>Linguagem de estilos para web</dd>
  
  <dt>JavaScript</dt>
  <dd>Linguagem de programação para web</dd>
</dl>
```

---

### 6️⃣ Links e Navegação

#### Links Básicos

```html
<!-- Link externo -->
<a href="https://www.google.com">Ir para Google</a>

<!-- Link interno -->
<a href="sobre.html">Sobre nós</a>

<!-- Link com target (abre em nova aba) -->
<a href="https://www.github.com" target="_blank">GitHub</a>

<!-- Link de âncora (para seção da mesma página) -->
<a href="#secao1">Ir para Seção 1</a>

<!-- Definindo a âncora -->
<section id="secao1">
  <h2>Seção 1</h2>
</section>
```

#### Atributos Importantes de Links

| Atributo | Descrição |
|----------|-----------|
| `href` | URL do destino (obrigatório) |
| `target` | `_blank` (nova aba), `_self` (mesma aba) |
| `rel` | `noopener`, `noreferrer`, `external` |
| `title` | Texto que aparece ao passar o mouse |

---

### 7️⃣ Imagens e Mídia

#### Inserindo Imagens

```html
<!-- Forma básica -->
<img src="imagem.jpg" alt="Descrição da imagem">

<!-- Com atributos adicionais -->
<img 
  src="imagem.jpg" 
  alt="Descrição da imagem" 
  title="Passar mouse aqui"
  width="300"
  height="200"
>
```

#### Imagens Responsivas com `<picture>`

```html
<picture>
  <source media="(min-width: 1024px)" srcset="imagem-grande.jpg">
  <source media="(min-width: 768px)" srcset="imagem-media.jpg">
  <img src="imagem-pequena.jpg" alt="Descrição">
</picture>
```

#### Vídeos

```html
<video width="400" height="300" controls>
  <source src="video.mp4" type="video/mp4">
  <source src="video.webm" type="video/webm">
  Seu navegador não suporta vídeos HTML5
</video>
```

#### Áudio

```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  <source src="audio.ogg" type="audio/ogg">
  Seu navegador não suporta áudio HTML5
</audio>
```

---

### 8️⃣ Formulários

#### Estrutura Básica de Formulário

```html
<form action="/enviar" method="POST">
  <!-- Inputs de texto -->
  <label for="nome">Nome:</label>
  <input type="text" id="nome" name="nome" required>
  
  <!-- Email -->
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required>
  
  <!-- Senha -->
  <label for="senha">Senha:</label>
  <input type="password" id="senha" name="senha" required>
  
  <!-- Número -->
  <label for="idade">Idade:</label>
  <input type="number" id="idade" name="idade" min="0" max="120">
  
  <!-- Data -->
  <label for="data">Data:</label>
  <input type="date" id="data" name="data">
  
  <!-- Checkbox -->
  <input type="checkbox" id="termos" name="termos" required>
  <label for="termos">Concordo com os termos</label>
  
  <!-- Radio -->
  <fieldset>
    <legend>Escolha uma opção:</legend>
    <input type="radio" id="opcao1" name="opcao" value="1">
    <label for="opcao1">Opção 1</label>
    
    <input type="radio" id="opcao2" name="opcao" value="2">
    <label for="opcao2">Opção 2</label>
  </fieldset>
  
  <!-- Select (dropdown) -->
  <label for="pais">País:</label>
  <select id="pais" name="pais">
    <option value="">Selecione um país</option>
    <option value="br">Brasil</option>
    <option value="us">EUA</option>
    <option value="ca">Canadá</option>
  </select>
  
  <!-- Textarea -->
  <label for="mensagem">Mensagem:</label>
  <textarea id="mensagem" name="mensagem" rows="5" cols="40"></textarea>
  
  <!-- Botões -->
  <button type="submit">Enviar</button>
  <button type="reset">Limpar</button>
</form>
```

#### Tipos de Input HTML5

| Tipo | Descrição |
|------|-----------|
| `text` | Texto simples |
| `email` | Email com validação |
| `password` | Campo oculto |
| `number` | Número com spinners |
| `date` | Seletor de data |
| `time` | Seletor de hora |
| `color` | Seletor de cor |
| `range` | Slider |
| `checkbox` | Múltiplas seleções |
| `radio` | Uma única seleção |
| `file` | Upload de arquivo |

---

### 9️⃣ Tabelas

#### Estrutura Básica

```html
<table border="1">
  <thead>
    <tr>
      <th>Nome</th>
      <th>Idade</th>
      <th>Profissão</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>João</td>
      <td>28</td>
      <td>Programador</td>
    </tr>
    <tr>
      <td>Maria</td>
      <td>32</td>
      <td>Designer</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td colspan="3">Total: 2 pessoas</td>
    </tr>
  </tfoot>
</table>
```

#### Atributos de Tabela

```html
<!-- colspan (estende em coluna) -->
<td colspan="2">Célula que ocupa 2 colunas</td>

<!-- rowspan (estende em linha) -->
<td rowspan="3">Célula que ocupa 3 linhas</td>
```

---

### 🔟 Atributos Globais Importantes

```html
<!-- id (identificador único) -->
<div id="principal">Conteúdo principal</div>

<!-- class (classe para estilo) -->
<div class="container destaque">Conteúdo</div>

<!-- data-* (atributos customizados) -->
<div data-usuario-id="123" data-tipo="admin">Admin</div>

<!-- title (tooltip) -->
<p title="Passe o mouse aqui">Texto com tooltip</p>

<!-- lang (idioma) -->
<p lang="en">This is English text</p>

<!-- hidden (oculta elemento) -->
<div hidden>Este elemento está oculto</div>
```

---

## ✅ Checklist de Conclusão

Antes de passar para o próximo módulo, certifique-se de que você:

- [ ] Compreende a estrutura básica de um documento HTML5
- [ ] Usa tags semânticas corretamente
- [ ] Sabe a diferença entre `<strong>` e `<b>`, `<em>` e `<i>`
- [ ] Consegue criar listas em diferentes tipos
- [ ] Domina links internos e externos
- [ ] Sabe inserir e otimizar imagens
- [ ] Consegue criar formulários funcionais
- [ ] Entende estrutura de tabelas
- [ ] Valida seu HTML em validator.w3.org
- [ ] Escreve código limpo e bem indentado

---

## 🎓 Próximos Passos

Após concluir este módulo, você estará pronto para:
- ✅ Aprender CSS (Módulo 2)
- ✅ Entender JavaScript (Módulo 3)
- ✅ Trabalhar com frameworks e bibliotecas

---

**Bom aprendizado! 🚀**
