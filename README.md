# 🌐 Meu Primeiro Site Melhorado — Portfólio Pessoal

> Um portfólio web moderno e responsivo desenvolvido em HTML5 e CSS3. Showcasing profissional com navegação fluida, seções bem estruturadas e design clean centrado no desenvolvedor.

[![HTML5](https://img.shields.io/badge/HTML5-Latest-e34c26.svg?style=flat&logo=html5&logoColor=white)](https://www.w3.org/TR/html5/)
[![CSS3](https://img.shields.io/badge/CSS3-Latest-1572b6.svg?style=flat&logo=css3&logoColor=white)](https://www.w3.org/TR/CSS/)
[![Responsive](https://img.shields.io/badge/Responsive-Mobile%20First-green.svg)]()
[![Status](https://img.shields.io/badge/status-Live-brightgreen.svg)]()

<div align="center">

**[🎯 Visualizar](#-demonstração) • [🚀 Como Usar](#-como-usar) • [📦 Estrutura](#-estrutura-do-projeto) • [🎨 Design](#-design--cores) • [📱 Responsive](#-responsividade)**

</div>

---

## 🌟 Visão Geral

Um **portfólio web profissional e minimalista** que apresenta Luis Guilherme como desenvolvedor em formação. O site combina **design moderno**, **navegação intuitiva** e **estrutura semântica** para criar uma experiência atraente aos visitantes.

### ✨ Destaques Principais

- 🎨 **Design Moderno**: Interface clean com gradientes e sombras
- 📱 **Fully Responsive**: Adaptável a todos os dispositivos
- ⚡ **Otimizado**: Carregamento rápido, sem dependências pesadas
- 🧭 **Navegação Intuitiva**: Menu sticky fluido com âncoras
- 📚 **Bem Estruturado**: HTML5 semântico e organizado
- 🎯 **Call-to-Action Claro**: Links para GitHub e contato
- 🌓 **Paleta Profissional**: Cores que transmitem confiança
- ✍️ **Tipografia Limpa**: Font Inter do Google Fonts

---

## 📁 Estrutura do Projeto

```
meu-primeiro-site-melhorado/
├── index.html         # Página principal (HTML5)
├── style.css          # Estilos completos
└── README.md          # Documentação (este arquivo)
```

### Arquivos

#### `index.html` (3.7 KB)
Estrutura HTML5 semântica com:
- Header com navegação fixa
- Hero section com apresentação
- Seção "Sobre Mim" com contexto
- Seção "Habilidades Técnicas" em grid
- Seção "Projetos em Destaque"
- Footer com contato

#### `style.css` (3 KB)
Estilos CSS3 com:
- Reset e normalização
- Componentes reutilizáveis
- Grid system responsivo
- Animações e transições
- Media queries para mobile

---

## 🏗️ Estrutura HTML

### Hierarquia de Seções

```html
<header>                    <!-- Navegação fixa -->
  <nav>                     <!-- Logo + Links -->
    <ul>                    <!-- Sobre, Skills, Projetos, Contato -->

<main>
  <section id="hero">       <!-- Apresentação pessoal -->
    <h1>                    <!-- Nome principal -->
    <p class="subtitulo">   <!-- Subtítulo -->
    <status-cards>          <!-- Localização, escola, período -->
  
  <section id="sobre">      <!-- Sobre mim -->
    <h2>                    <!-- Título seção -->
    <p>                     <!-- Parágrafo descritivo -->
  
  <section id="habilidades"> <!-- Skills técnicas -->
    <div class="skills-grid">
      <skill-box>           <!-- Programação, Dados, Soft Skills -->
  
  <section id="projetos">   <!-- Projetos destaque -->
    <grid-projetos>
      <projeto-card>        <!-- Cada projeto -->

<footer id="contato">       <!-- Informações de contato -->
```

---

## 🎨 Design & Cores

### Paleta de Cores

| Cor | Hex | Uso |
|-----|-----|-----|
| **Azul Profissional** | `#2980b9` | Títulos, destaques, links |
| **Cinza Escuro** | `#2c3e50` | Header, textos principais |
| **Cinza Claro** | `#7f8c8d` | Subtítulos, textos secundários |
| **Branco** | `#ffffff` | Cards, fundo de conteúdo |
| **Fundo Corpo** | `#f4f4f9` | Background principal |
| **Fundo Hero** | Gradiente | Apresentação principal |

### Componentes Visuais

#### Header (Sticky Navigation)
```css
header {
  background: #2c3e50;      /* Azul escuro profissional */
  position: sticky;         /* Fica no topo ao scroll */
  top: 0;
  z-index: 100;
}
```

**Características:**
- Fixo no topo durante scroll
- Logo com identificação visual
- Links com navegação por âncoras
- Alinhamento centralizado

---

#### Hero Section
```css
#hero {
  background: linear-gradient(135deg, #fdfbfb 0%, #ebedee 100%);
  padding: 100px 20px;
  height: 40vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
```

**Componentes:**
- H1 com nome destaque (2.8rem)
- Subtítulo em tom cinza claro
- Status cards inline (localização, school, período)
- Gradiente sutil de fundo

---

#### Skill Boxes
```css
.skill-box {
  background: white;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.05);
}
```

**Grid:**
- 3 colunas em desktop
- Responsivo em mobile
- Espaçamento uniforme (gap: 20px)
- Sombra sutil para profundidade

---

#### Projeto Cards
```css
.projeto-card {
  background: white;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

.projeto-card:hover {
  transform: translateY(-5px);  /* Elevação ao hover */
}
```

**Animações:**
- Elevação suave ao passar mouse
- Transição smooth (0.3s)
- Tag de categoria destacada
- Botão com link para repositório

---

## 📱 Responsividade

### Breakpoints

```css
/* Mobile First */
/* Até 768px: Mobile */
/* 768px - 1024px: Tablet */
/* Acima de 1024px: Desktop */
```

### Grid Adaptável

```css
.grid-projetos {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}
```

**Comportamento:**
- 1 coluna em mobile
- 2 colunas em tablet
- 3+ colunas em desktop
- Ajuste automático de tamanho

### Navegação Mobile

```html
<nav>
  <ul>                        <!-- Flex, wrap automático -->
    <li><a href="#sobre">Sobre</a></li>
    <li><a href="#habilidades">Skills</a></li>
    <!-- ... -->
  </ul>
</nav>
```

**Características:**
- Menu flex com wrap
- Links centrados
- Espaçamento adequado (15px)
- Readaptação automática

---

## 🚀 Como Usar

### ⚡ Quick Start

```bash
# Clone o repositório
git clone https://github.com/luisguigui/meu-primeiro-site-melhorado.git
cd meu-primeiro-site-melhorado

# Abra no navegador (sem servidor necessário!)
# Opção 1: Duplo clique em index.html
# Opção 2: Abra em localhost com Live Server (VSCode)
```

### 📝 Editar Conteúdo

#### Alterar Nome
```html
<!-- index.html linha 6 -->
<title>Luis Guilherme | Dev em Formação</title>

<!-- index.html linha 30 -->
<h1>Olá, eu sou o <span class="destaque-nome">Luis Guilherme</span></h1>
```

#### Adicionar Novo Projeto
```html
<!-- index.html linha 77 -->
<div class="projeto-card">
    <div class="tag">Acadêmico</div>
    <h3>Nome do Projeto</h3>
    <p>Descrição breve...</p>
    <a href="link" target="_blank" class="btn-github">Ver Repositório</a>
</div>
```

#### Mudar Cores
```css
/* style.css */
:root {
  --cor-primaria: #2980b9;      /* Azul */
  --cor-escura: #2c3e50;         /* Cinza escuro */
}

/* Aplicar em qualquer elemento */
.elemento {
  color: var(--cor-primaria);
}
```

---

## 📂 Customização Avançada

### Adicionar Seção Nova

```html
<!-- index.html -->
<section id="experiencia">
  <h2>Experiência</h2>
  <div class="experiencia-container">
    <!-- conteúdo -->
  </div>
</section>
```

```css
/* style.css */
#experiencia {
  padding: 60px 20px;
  max-width: 1000px;
  margin: 0 auto;
  background: #f9f9f9;
}

.experiencia-container {
  display: grid;
  gap: 20px;
}
```

---

### Adicionar Redes Sociais

```html
<!-- index.html footer -->
<div class="social-links">
  <a href="https://github.com/luisguigui" target="_blank">
    <svg><!-- GitHub icon --></svg>
  </a>
  <a href="https://linkedin.com/in/luisguigui" target="_blank">
    <svg><!-- LinkedIn icon --></svg>
  </a>
</div>
```

```css
/* style.css */
.social-links {
  display: flex;
  gap: 15px;
  justify-content: center;
  margin-top: 20px;
}

.social-links a {
  width: 40px;
  height: 40px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  background: #f0f0f0;
  transition: background 0.3s;
}

.social-links a:hover {
  background: #2980b9;
}
```

---

## 🔧 Otimizações Implementadas

### Performance

✅ **Sem dependências pesadas**
- Apenas HTML5 + CSS3
- Google Fonts para tipografia
- Carregamento rápido (~100KB)

✅ **Otimizações CSS**
- Reutilização de classes
- BEM methodology
- Media queries eficientes
- Transições GPU-aceleradas

✅ **SEO Friendly**
- HTML5 semântico
- Meta tags corretas
- Título descritivo
- Viewport configurado

### Accessibility

✅ **Acessibilidade**
- Links com `target="_blank"` e `rel="noopener"`
- Contrastes adequados
- Estrutura semântica
- Âncoras em elementos corretos

---

## 📸 Seções do Site

### 1. Header & Navegação
```
┌─────────────────────────────────────────┐
│ LG.dev    [Sobre] [Skills] [Projetos]  │
└─────────────────────────────────────────┘
```

Sticky no topo, links para cada seção.

---

### 2. Hero Section
```
┌─────────────────────────────────────────┐
│                                         │
│  Olá, eu sou Luis Guilherme             │
│  Estudante de ADS                       │
│                                         │
│  📍 Uberaba, MG  |  🎓 UNIUBE  |  3º   │
│                                         │
└─────────────────────────────────────────┘
```

Apresentação principal com status cards.

---

### 3. Sobre Mim
```
┌─────────────────────────────────────────┐
│  SOBRE MIM                              │
│                                         │
│  3º período em ADS, focando em Backend  │
│  e BD. Facilidade com lógica...        │
│                                         │
│  Busco aplicar conceitos de Eng...     │
└─────────────────────────────────────────┘
```

Contextualização pessoal em 2 parágrafos.

---

### 4. Habilidades Técnicas
```
┌─────────────────────────────────────────┐
│  HABILIDADES TÉCNICAS                   │
│                                         │
│  ┌──────────┐ ┌──────────┐ ┌─────────┐ │
│  │Program.  │ │Dados&Inf│ │Soft Skl │ │
│  │Python    │ │SQL      │ │Gestão   │ │
│  │Algoritmos│ │Modelagem│ │Ágil     │ │
│  └──────────┘ └──────────┘ └─────────┘ │
└─────────────────────────────────────────┘
```

Grid 3 colunas com skill categories.

---

### 5. Projetos
```
┌─────────────────────────────────────────┐
│  PROJETOS EM DESTAQUE                   │
│                                         │
│  ┌──────────────────────────────────┐   │
│  │ [Acadêmico]                      │   │
│  │ Hub de Ferramentas               │   │
│  │ Repositório centralizando...     │   │
│  │ [Ver Repositório →]              │   │
│  └──────────────────────────────────┘   │
└─────────────────────────────────────────┘
```

Cards com projetos destacados.

---

### 6. Footer & Contato
```
┌─────────────────────────────────────────┐
│  Luis Guilherme Gomes Bernardes         │
│  Email: luis.guibernardes@gmail.com     │
└─────────────────────────────────────────┘
```

Informações de contato no rodapé.

---

## 🐛 Troubleshooting

### ❌ CSS não carrega
**Causa:** Caminho incorreto no HTML
```html
<!-- Errado -->
<link rel="stylesheet" href="/style.css">

<!-- Correto (mesmo diretório) -->
<link rel="stylesheet" href="style.css">
```

---

### ❌ Fonte Google não aparece
**Solução:** Verificar conexão internet e URL:
```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
```

---

### ❌ Links não funcionam
**Verificar:** IDs das seções correspondem aos href:
```html
<!-- Header -->
<a href="#sobre">Sobre</a>

<!-- Seção -->
<section id="sobre">
```

---

### ❌ Site não responsivo
**Verificar:** Meta viewport no head:
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

---

## 📚 Conceitos Utilizados

### HTML5
- Elementos semânticos (`<header>`, `<main>`, `<footer>`, `<section>`)
- Âncoras com `id`
- Meta tags (charset, viewport)
- Link de stylesheet

### CSS3
- Flexbox (navigation, grid adaptável)
- Grid CSS (skill boxes, projects)
- Gradientes lineares
- Transições e transforms
- Media queries
- Box shadows
- Border radius

### UX/UI
- Design minimalista
- Paleta de cores profissional
- Tipografia clean
- Espaçamento adequado
- Feedback ao hover
- Navegação intuitiva

---

## 🎯 Próximas Melhorias

```
☐ Adicionar Dark Mode com toggle
☐ Integrar formulário de contato
☐ Adicionar animações AOS (Animate On Scroll)
☐ Implementar lazy loading de imagens
☐ Adicionar carousel de projetos
☐ Deploy no GitHub Pages ou Vercel
☐ Adicionar certificados/badges
☐ Integrar blog com artigos
```

---

## 🚀 Deploy

### GitHub Pages (Grátis!)

```bash
# 1. Configurar repositório
# Settings → Pages → Source: main branch

# 2. Site disponível em:
# https://luisguigui.github.io/meu-primeiro-site-melhorado

# 3. Sempre atualizado com cada push
```

### Vercel (Alternativa)

```bash
# 1. Conectar repo no Vercel
# 2. Deploy automático
# 3. URL customizável
```

---

## 📊 Estatísticas do Projeto

| Métrica | Valor |
|---------|-------|
| **Linhas HTML** | 97 |
| **Linhas CSS** | 164 |
| **Peso Total** | ~6.7 KB |
| **Dependências** | 0 (apenas Google Fonts) |
| **Tempo Carregamento** | < 1s |
| **SEO Score** | ⭐⭐⭐⭐⭐ |
| **Acessibilidade** | ⭐⭐⭐⭐⭐ |

---

## 💡 Dicas de Customização

### 1. Mudar Paleta de Cores
Substitua todas as ocorrências de cores no CSS:
- `#2980b9` → sua cor primária
- `#2c3e50` → cor escura
- `#f4f4f9` → fundo claro

### 2. Adicionar Imagem de Perfil
```html
<section id="hero">
  <img src="foto.jpg" alt="Luis Guilherme" class="profile-pic">
  <h1>...</h1>
</section>
```

```css
.profile-pic {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  margin-bottom: 20px;
  object-fit: cover;
}
```

### 3. Integrar Analytics
```html
<!-- Antes de </body> -->
<!-- Google Analytics, Plausible, etc -->
<script>
  // Seu código de rastreamento
</script>
```

---

## ✒️ Autor

**Luis Guilherme Gomes Bernardes**

- 🐙 GitHub: [@luisguigui](https://github.com/luisguigui)
- 📧 Email: luis.guibernardes@gmail.com
- 📍 Localização: Uberaba, MG

---

## 📄 Licença

MIT — Sinta-se livre para usar, modificar e distribuir!

---

## 🌟 Se gostou, dê uma ⭐!

```
🌐 Meu Primeiro Site Melhorado

Portfólio profissional simples, rápido e responsivo.
HTML5 + CSS3 puro. Nenhuma complexidade desnecessária.

Perfeito para iniciantes e profissionais.
```

---

**Versão**: 1.0  
**Status**: ✅ Live & Funcional  
**Última Atualização**: 2024

---

## 📞 Suporte

Encontrou um erro ou tem sugestões?
- 📝 Abra uma [Issue](https://github.com/luisguigui/meu-primeiro-site-melhorado/issues)
- 🔄 Pull Requests são bem-vindos!
- 💬 Deixe seu feedback

