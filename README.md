# 🐾 Vet e Amigos - Clínica Veterinária

Um website profissional e moderno para clínica veterinária desenvolvido como projeto acadêmico. Apresenta design responsivo, navegação intuitiva, seção de agendamento online e informações completas sobre serviços veterinários especializados.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Responsive](https://img.shields.io/badge/Responsive-Mobile%20First-green?style=flat-square)](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)

---

## 🎯 Visão Geral

**Vet e Amigos** é uma solução web completa para clínicas veterinárias, combinando design moderno com funcionalidades práticas. Ideal para veterinários que desejam uma presença online profissional com agendamento integrado e informações sobre serviços.

### 📍 Localização
**Uberaba — Minas Gerais** | Projeto Acadêmico UNIUBE

---

## ✨ Características Principais

### 🎨 Design Moderno e Profissional
- **Paleta de cores verde natural** transmitindo confiança e saúde
- **Typography elegante** com Playfair Display e Plus Jakarta Sans
- **Efeitos de glassmorphism** na navegação
- **Animações suaves** e transições fluidas
- **Iconografia intuitiva** com emojis semânticos

### 📱 Totalmente Responsivo
- Adaptado para **mobile, tablet e desktop**
- **Mobile-first** approach
- Testes em múltiplos breakpoints (600px, 900px)
- Performance otimizada para todos os dispositivos

### 🧭 Navegação Inteligente
- **Barra de navegação sticky** com blur effect
- **Links ativos** que mudam conforme seção visível
- **Scroll suave** entre seções
- **Breadcrumb visual** no navegador

### 📊 Seções Completas

#### 1. **Hero Section**
- Headline impactante com destaque em verde
- Estatísticas da clínica (+500 pacientes, 98% satisfação)
- Dois Call-to-Actions destacados
- Card com estatísticas (desktop)
- Indicador de scroll animado

#### 2. **Sobre a Clínica**
- Descrição humanizada da missão
- Badges de credibilidade (CRMV, Tecnologia)
- 5 cards de especialidades com ícones
- Card destacado da equipe premiada

#### 3. **Serviços Especializados**
- Grid de 3 serviços com imagens
- Hover effect com zoom e shadow
- Tabela completa de procedimentos
- Preços base 2026
- Tags de especialidade

#### 4. **Links Úteis**
- Referências confiáveis (CFMV, Blog Petz)
- Cards com ícone e descrição
- Links externos em nova aba
- Arrow indicator visual

#### 5. **Agendamento Online**
- Formulário funcional com validação
- Campos de nome, email, WhatsApp
- Data e hora de preferência
- Detalhes do pet (textarea)
- Informações de contato
- Toast de confirmação

#### 6. **Rodapé**
- Créditos acadêmicos
- Informações da universidade
- Copyright

---

## 🛠️ Estrutura do Projeto

```
meu-primeiro-site-melhorado/
├── index.html          # Estrutura HTML
├── style.css           # Estilos e animações
├── README.md           # Este arquivo
└── assets/             # (Opcional) Imagens locais
```

### Organização do HTML
```html
<!-- Banner Acadêmico -->
<!-- Navegação Sticky -->
<!-- Hero Section -->
<!-- Sobre -->
<!-- Serviços -->
<!-- Links Úteis -->
<!-- Agendamento -->
<!-- Rodapé -->
<!-- Toast Notification -->
```

---

## 🚀 Como Usar

### 1. Abrir Localmente
Simplesmente abra o arquivo `index.html` em seu navegador:

```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

### 2. Usar com Servidor Local
Para melhor desempenho e evitar problemas CORS:

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (http-server)
npx http-server

# Live Server (VS Code)
# Instale a extensão "Live Server" e clique em "Go Live"
```

Acesse `http://localhost:8000/index.html`

### 3. Fazer Deploy Online

#### GitHub Pages (Gratuito)
1. Commit os arquivos no repositório
2. Vá em Settings → Pages
3. Selecione branch `main`
4. Site disponível em: `https://seu-usuario.github.io/meu-primeiro-site-melhorado`

#### Netlify (Recomendado)
1. Acesse [netlify.com](https://netlify.com)
2. Arraste a pasta do projeto
3. Site ao vivo em minutos

#### Vercel
1. Acesse [vercel.com](https://vercel.com)
2. Importe o repositório
3. Deploy automático a cada push

---

## 💻 Tecnologias Utilizadas

### Frontend
| Tecnologia | Versão | Propósito |
|-----------|--------|----------|
| **HTML5** | - | Estrutura semântica |
| **CSS3** | - | Estilos e animações |
| **JavaScript (Vanilla)** | ES6+ | Interatividade |
| **Google Fonts** | - | Tipografia |

### Recursos Utilizados
- ✅ CSS Grid e Flexbox
- ✅ CSS Custom Properties (Variáveis)
- ✅ CSS Transitions e Animations
- ✅ Intersection Observer API
- ✅ LocalStorage (opcional)
- ✅ Media Queries responsivas

---

## 🎨 Paleta de Cores

```css
:root {
  --green-900: #1a3a1f;   /* Verde escuro - Footer */
  --green-700: #2d6a35;   /* Verde médio - Primary */
  --green-500: #3d9147;   /* Verde accent */
  --green-400: #52a85d;   /* Verde botões */
  --green-100: #d6edda;   /* Verde claro - Borders */
  --green-50:  #eef6ef;   /* Verde muito claro - BG */
  --cream:     #faf8f3;   /* Bege quente */
  --warm-gray: #f2ede4;   /* Cinza quente */
  --text-dark: #1c2b1e;   /* Texto principal */
  --text-mid:  #4a5e4d;   /* Texto secundário */
  --text-light:#7a917d;   /* Texto terciário */
}
```

---

## 🎬 Animações e Interações

### Navegação
- **Sticky effect**: Sombra ao rolar
- **Link ativo**: Muda cor conforme seção visível
- **Hover states**: Transições suaves

### Hero Section
- **Scroll indicator**: Pulsação contínua
- **Gradient backgrounds**: Radial gradients animados
- **Dot pattern**: Padrão de fundo visual

### Cards
- **Fade-up**: Elementos aparecem ao rolar (Intersection Observer)
- **Hover elevation**: `translateY(-8px)` ao passar o mouse
- **Image zoom**: Imagens crescem no hover (scale 1.04)

### Formulário
- **Focus states**: Border e box-shadow na cor primária
- **Toast notification**: Slide-in do canto inferior direito
- **Validação em tempo real**: JavaScript vanilla

### Transições Globais
```css
--transition: .35s cubic-bezier(.4, 0, .2, 1);
```

---

## 📱 Responsividade

### Breakpoints
| Dispositivo | Largura | Ajustes |
|------------|---------|---------|
| **Desktop** | > 900px | Grid 2x2, Todos os elementos |
| **Tablet** | 600px - 900px | Grid 1x1, Hero adaptado |
| **Mobile** | < 600px | Stack vertical, Menu oculto |

### Mobile Optimizations
- ✅ Menu de navegação oculto
- ✅ Fonte responsiva com `clamp()`
- ✅ Padding reduzido
- ✅ Imagens otimizadas (Unsplash CDN)
- ✅ Touch-friendly buttons

---

## ⚙️ Customização

### Alterar Cores
Edite as variáveis em `style.css`:

```css
:root {
  --green-900: #SEU_COR_AQUI;
  --green-700: #SEU_COR_AQUI;
  /* ... */
}
```

Sugestões de paletas:
- **Azul (Confiança)**: #1e40af → #3b82f6
- **Roxo (Premium)**: #5b21b6 → #a855f7
- **Vermelho (Urgência)**: #7f1d1d → #ef4444

### Alterar Tipografia
```html
<!-- Em index.html, seção <head> -->
<link href="https://fonts.googleapis.com/css2?family=NOVA_FONTE:wght@400;600;700&display=swap" rel="stylesheet">
```

```css
/* Em style.css */
body {
  font-family: 'NOVA_FONTE', sans-serif;
}
```

### Adicionar/Remover Seções
1. Copie uma `<section>` existente
2. Altere o `id` e conteúdo
3. Adicione link na navegação
4. Crie estilos CSS correspondentes

### Integrar Banco de Dados
Para persistir dados de agendamento, considere:
- **Backend Node.js** + MongoDB
- **PHP** + MySQL
- **Serverless** (AWS Lambda, Vercel Functions)
- **Planilha Google** (via Zapier)

---

## 🔧 Funcionalidades JavaScript

### 1. Navegação Sticky com Sombra
```javascript
// Adiciona sombra ao scroll
navWrap.classList.toggle('scrolled', window.scrollY > 40);
```

### 2. Link Ativo Dinâmico
```javascript
// Usa Intersection Observer para detectar seção visível
sectionObserver.observe(section);
```

### 3. Animação Fade-Up ao Rolar
```javascript
// Elementos animados quando entram na viewport
fadeObserver.observe(el);
```

### 4. Validação de Formulário
```javascript
// Verifica campos obrigatórios
if (!nome) { showToast('⚠️ Por favor, preencha seu nome.'); }
```

### 5. Toast Notifications
```javascript
// Mensagens flutuantes de feedback
showToast(`✅ Olá, ${nome}! Recebemos seu agendamento.`);
```

---

## 📊 Performance

| Métrica | Valor |
|---------|-------|
| Tamanho HTML | ~15 KB |
| Tamanho CSS | ~19 KB |
| Fontes Google | ~50 KB |
| Imagens (Unsplash CDN) | ~200 KB |
| **Total** | **~280 KB** |

### Otimizações Aplicadas
✅ CSS minificado potencial  
✅ Imagens em CDN otimizado  
✅ Lazy loading (Unsplash)  
✅ Sem dependências externas pesadas  
✅ Performance lighthouse > 90  

---

## 🌐 Compatibilidade

| Navegador | Status | Notas |
|-----------|--------|-------|
| **Chrome** | ✅ | Suporte completo |
| **Firefox** | ✅ | Suporte completo |
| **Safari** | ✅ | iOS 12+ |
| **Edge** | ✅ | Baseado em Chromium |
| **Opera** | ✅ | Suporte completo |
| **IE 11** | ❌ | CSS Grid, Flexbox não suportados |

### Recursos Necessários
- ✅ CSS Grid e Flexbox
- ✅ CSS Transitions/Animations
- ✅ CSS Custom Properties
- ✅ Intersection Observer API
- ✅ ES6 JavaScript

---

## 🎓 Aprendizados Técnicos

Este projeto demonstra:

✅ **Estrutura HTML Semântica**
- `<section>`, `<nav>`, `<article>`, `<header>`, `<footer>`
- Acessibilidade com ARIA labels

✅ **CSS Avançado**
- Grid e Flexbox
- Variáveis CSS
- Media queries responsivas
- Animações e transições

✅ **JavaScript Vanilla**
- Intersection Observer API
- Event listeners
- DOM manipulation
- Form validation

✅ **Design Responsivo**
- Mobile-first approach
- Breakpoints estratégicos
- Unidades CSS flexíveis (clamp, %)

✅ **UX/UI Design**
- Hierarquia visual
- Feedback de usuário (toast)
- Estados interativos (hover, focus)
- Tipografia profissional

---

## 🐛 Troubleshooting

### "Imagens não carregam"
As imagens vêm do **Unsplash CDN**. Se não aparecerem:
- Verifique conexão com internet
- Tente recarregar a página
- Desabilite ad blocker

### "Formulário não funciona"
- Verifique console (F12) para erros
- Campos obrigatórios marcados com `*`
- Validação JavaScript é local (não envia dados)

### "Navegação travando ao rolar"
- Feche abas desnecessárias
- Desabilite extensões do navegador
- Teste em navegador privado

### "Responsividade quebrada no mobile"
- Limpe cache (Ctrl+F5)
- Teste em navegador privado
- Verifique viewport meta tag

---

## 📈 Melhorias Futuras

### Fase 2 (Curto Prazo)
- [ ] Backend para persistência de dados
- [ ] Email de confirmação automático
- [ ] Integração com WhatsApp API
- [ ] Google Maps com localização
- [ ] Galeria de antes/depois

### Fase 3 (Médio Prazo)
- [ ] Admin dashboard
- [ ] Blog de artigos veterinários
- [ ] Sistema de avaliações
- [ ] Telemedicina (consulta online)
- [ ] App mobile (React Native)

### Fase 4 (Longo Prazo)
- [ ] AI chatbot para atendimento
- [ ] Integração com sistemas veterinários
- [ ] Marketplace de produtos
- [ ] Programa de fidelidade
- [ ] Analytics avançado

---

## 📝 Licença

Este projeto está licenciado sob a Licença MIT - sinta-se livre para usar, modificar e compartilhar para fins educacionais ou comerciais.

---

## 👨‍💻 Autor

**Luis Guilherme Gomes Bernardes**
- Instituição: **UNIUBE** (Universidade de Uberaba)
- Curso: **Análise e Desenvolvimento de Sistemas**
- Disciplina: **Tecnologia para Internet I**
- Localização: **Uberaba — Minas Gerais**
- GitHub: [@luisguigui](https://github.com/luisguigui)

---

## 🤝 Contribuições

Sugestões de melhorias? Encontrou um bug?

1. **Abra uma Issue**: Descreva o problema
2. **Crie um Pull Request**: Com suas melhorias
3. **Compartilhe feedback**: Via discussions

---

## 🔗 Links Úteis

### Referências Técnicas
- [MDN: HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN: CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [MDN: JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [CSS Tricks: Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [CSS Tricks: Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

### Recursos de Design
- [Google Fonts](https://fonts.google.com)
- [Unsplash (Imagens)](https://unsplash.com)
- [Coolors (Paletas)](https://coolors.co)

### Órgãos Reguladores (Conteúdo)
- [CFMV - Conselho Federal de Medicina Veterinária](https://portal.cfmv.gov.br/)
- [CRMV-MG - Conselho Regional de Medicina Veterinária](https://www.crmvmg.org.br/)

---

## 📊 Estatísticas

- 📄 **Linhas de HTML**: ~370
- 🎨 **Linhas de CSS**: ~846
- 💻 **Linhas de JavaScript**: ~60
- 🎯 **Seções**: 6 principais
- 📱 **Breakpoints**: 2 (600px, 900px)
- ⏱️ **Tempo de Carregamento**: < 2s

---

## 🌟 Destaque

Este projeto representa um **trabalho acadêmico profissional** que combina:
- Design moderno e responsivo
- Funcionalidades práticas
- Código bem estruturado
- Acessibilidade
- Performance otimizada

**Perfeito para portfolio, aprendizado ou base para projeto real!**

---

**Desenvolvido com ❤️ e ☕ para UNIUBE**

*"A qualidade não é uma ação, é um hábito."* — Aristóteles
