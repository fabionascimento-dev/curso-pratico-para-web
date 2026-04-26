# 🎓 Curso Prático para WEB

> Destinado a estudantes e programadores que estão iniciando a carreira com foco em **Desenvolvimento Web**

---

## 📋 Como Usar Este Repositório

### Estrutura de Organização

1. **Realize os exercícios em módulo para correção**
2. **Dentro da pasta `aulas`, crie uma pasta com o seu nome:**
   - Exemplo: `Aulas/Eduardo` - Todas as aulas devem estar dentro dessa pasta
3. **Dentro da sua pasta, crie uma pasta com o número do módulo:**
   - Exemplo: `Aulas/Eduardo/01` - Indica que se trata do Módulo 01 - HTML
4. **Dentro da pasta do módulo, crie uma pasta de 2 dígitos com o número da aula:**
   - Exemplo: `Aulas/Eduardo/01/01` - Primeira aula do Módulo 01
5. **Crie os arquivos dentro dessa pasta para posterior correção**

### 📁 Estrutura Esperada
```
curso-pratico-para-web/
├── README.md
├── modulos/
│   └── 01-HTML/
│       ├── README.md (conteúdo teórico)
│       ├── exemplos/
│       └── exercicios/
├── aulas/
│   └── [seu-nome]/
│       ├── 01/
│       │   ├── 01/
│       │   ├── 02/
│       │   └── ...
│       ├── 02/
│       └── ...
└── ...
```

---

## 📚 Módulos

### ✅ Módulo 1 - HTML (Estruturas para Web)

**Objetivo:** Dominar os fundamentos de HTML e suas estruturas semânticas para desenvolvimento web profissional.

#### 📖 Conteúdo do Módulo 1

1. **Introdução ao HTML**
   - O que é HTML?
   - História e versões do HTML
   - Diferença entre HTML4 e HTML5
   - Ferramentas necessárias

2. **Estrutura Básica de um Documento HTML**
   - Declaração DOCTYPE
   - Tags meta (charset, viewport, etc.)
   - Estrutura semântica: `<html>`, `<head>`, `<body>`
   - Comentários

3. **Tags Semânticas HTML5**
   - `<header>` - Cabeçalho
   - `<nav>` - Navegação
   - `<main>` - Conteúdo principal
   - `<article>` - Artigo
   - `<section>` - Seção
   - `<aside>` - Conteúdo lateral
   - `<footer>` - Rodapé

4. **Formatação de Texto**
   - Títulos: `<h1>` a `<h6>`
   - Parágrafos: `<p>`
   - Ênfase: `<strong>`, `<em>`, `<b>`, `<i>`
   - Quebras de linha: `<br>`
   - Linhas horizontais: `<hr>`

5. **Listas**
   - Listas não ordenadas: `<ul>` e `<li>`
   - Listas ordenadas: `<ol>` e `<li>`
   - Listas de definição: `<dl>`, `<dt>`, `<dd>`

6. **Links e Navegação**
   - Tag `<a>` (links internos e externos)
   - Atributos href, target, rel
   - Links de âncora
   - Boas práticas de URL

7. **Imagens e Mídia**
   - Tag `<img>` (atributos src, alt, title)
   - Responsividade em imagens
   - `<picture>` para imagens responsivas
   - `<video>` e `<audio>`

8. **Formulários**
   - Tag `<form>`
   - Inputs: text, email, password, number, etc.
   - `<textarea>` e `<select>`
   - Validação básica
   - Atributos: name, id, required, placeholder

9. **Tabelas**
   - Estrutura: `<table>`, `<thead>`, `<tbody>`, `<tfoot>`
   - Linhas e células: `<tr>`, `<td>`, `<th>`
   - Atributos: colspan, rowspan

10. **Atributos Globais Importantes**
    - `id` e `class`
    - `data-*` (atributos customizados)
    - `title` e `alt`
    - `lang`

---

## 🎯 Exercícios por Aula

### Aula 01: Estrutura Básica e Tags Semânticas
- Criar documento HTML com estrutura completa
- Utilizar tags semânticas corretamente
- Validar o HTML

### Aula 02: Formatação de Texto
- Criar um documento com diferentes formatações
- Usar títulos, parágrafos e ênfases
- Praticar com quebras de linha e linhas horizontais

### Aula 03: Listas
- Criar listas não ordenadas
- Criar listas ordenadas
- Combinar listas em diferentes níveis

### Aula 04: Links e Navegação
- Criar múltiplos links internos e externos
- Usar links de âncora
- Praticar navegação entre páginas

### Aula 05: Imagens
- Inserir imagens com atributos corretos
- Usar imagens responsivas
- Trabalhar com `<picture>` para múltiplas resoluções

### Aula 06: Formulários
- Criar formulário com vários tipos de inputs
- Usar validação HTML
- Estruturar corretamente com labels

### Aula 07: Tabelas
- Criar tabelas simples
- Estruturar com thead, tbody, tfoot
- Usar colspan e rowspan

### Aula 08: Projeto Integrador - Página Web Completa
- Combinar todos os conceitos aprendidos
- Criar página com múltiplas seções semânticas
- Incluir links, imagens, formulários e tabelas

---

## 🔗 Recursos Úteis

### Documentação Oficial
- [MDN Web Docs - HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [W3C HTML Specification](https://www.w3.org/TR/html/)
- [HTML Validator](https://validator.w3.org/)

### Ferramentas Recomendadas
- **Editores de Código:** VS Code, Sublime Text, Atom
- **Validadores:** W3C Validator, HTML Hint
- **Inspetores:** DevTools (F12 no navegador)

### Boas Práticas
- ✅ Sempre use estrutura semântica adequada
- ✅ Inclua atributos `alt` em todas as imagens
- ✅ Use `<label>` associado a inputs de formulário
- ✅ Valide seu HTML regularmente
- ✅ Mantenha código limpo e indentado
- ✅ Use nomes descritivos para ids e classes

---

## 📝 Como Submeter Seus Exercícios

1. Crie uma branch com seu nome: `git checkout -b estudante/seu-nome`
2. Organize seus arquivos na pasta: `aulas/seu-nome/01/01`, `aulas/seu-nome/01/02`, etc.
3. Faça commit: `git commit -m "feat: aula 01 - exercício completado"`
4. Abra um Pull Request para revisão

---

## 🤝 Contribuições

Contribuições são bem-vindas! Se você encontrou erros, quer sugerir melhorias ou adicionar conteúdo, sinta-se à vontade para abrir uma issue ou pull request.

---

## 📄 Licença

Este repositório é de código aberto e disponibilizado para fins educacionais.

---

**Bom aprendizado! 🚀**

Criado com ❤️ para a comunidade de desenvolvedores web em desenvolvimento.
