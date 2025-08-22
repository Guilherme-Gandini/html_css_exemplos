# Mini Desafio CSS Avançado - Portal de Notícias Tech 📱

## 📋 Descrição do Desafio

Você foi contratado para **criar o design visual** do **TechNews Today** com CSS moderno e profissional. O HTML semântico já existe - agora transforme-o em um portal visualmente impressionante!

## 🎯 Objetivo

Criar um arquivo CSS de **no máximo 50 linhas** que transforme a página em um portal de notícias moderno com técnicas avançadas de design.

## 📝 Requisitos Principais

### ✅ Elementos CSS Essenciais
- **Layout Responsivo:** CSS Grid ou Flexbox para estrutura
- **Design Moderno:** Glassmorphism ou Neumorphism
- **Gradientes Avançados:** Em backgrounds e/ou textos
- **Interações:** Transições suaves e hover effects
- **Dark Mode:** Paleta escura profissional

## 🎨 Requisitos de Design

### Técnicas Obrigatórias:
- **Glassmorphism:** `backdrop-filter: blur()` em pelo menos um elemento
- **Gradiente em Texto:** `-webkit-background-clip: text`
- **CSS Grid:** Para layout principal
- **Position Sticky:** Header fixo ao rolar
- **Media Query:** Responsividade básica

### Paleta de Cores Sugerida:
```css
/* Dark Mode Moderno */
--bg-dark: #0a0e27;
--card-bg: linear-gradient(135deg, #1e293b, #334155);
--accent: #6366f1;
--text: #e4e4e7;
--muted: #64748b;
```

## 🔧 Especificações Técnicas

- **Máximo:** 50 linhas de CSS
- **Arquivo:** `desafio10a.css` (externo)
- **Técnicas:** CSS3 moderno (Grid, Flexbox, Filters)
- **Tema:** Tech/Futurista/Profissional
- **Foco:** Layout avançado e efeitos modernos

## 🏆 Critérios de Avaliação

### Layout & Responsividade (40 pontos)
- ✅ CSS Grid implementado (15pts)
- ✅ Media query funcional (10pts)
- ✅ Position sticky no header (10pts)
- ✅ Espaçamento consistente (5pts)

### Design Moderno (35 pontos)
- ✅ Glassmorphism aplicado (10pts)
- ✅ Gradientes criativos (10pts)
- ✅ Transições suaves (10pts)
- ✅ Paleta de cores harmônica (5pts)

### Técnica & Código (25 pontos)
- ✅ CSS limpo e organizado (10pts)
- ✅ Uso de variáveis CSS (5pts)
- ✅ Seletores eficientes (5pts)
- ✅ Comentários úteis (5pts)

## 💡 Técnicas Avançadas

### Glassmorphism:
```css
.elemento {
    background: rgba(255,255,255,0.1);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255,255,255,0.2);
}
```

### Gradiente em Texto:
```css
.titulo {
    background: linear-gradient(90deg, #6366f1, #db2777);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
```

### Grid Responsivo:
```css
.container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
}
```

## 🚀 Desafios Extras (Opcional)

Se sobrar espaço nas 50 linhas:
1. **Custom Properties** para tema dinâmico
2. **Scroll Snap** para seções
3. **Container Queries** (se suportado)
4. **Animação de entrada** com @keyframes

## 📚 Conceitos CSS Praticados

### Nível Avançado:
- CSS Grid Layout
- Backdrop-filter
- Background-clip
- Position sticky
- Media queries
- Custom properties
- Transform 3D
- Grid areas

### Técnicas Modernas:
- Glassmorphism
- Dark mode design
- Responsive design
- Micro-interactions
- Design system basics

## ⚠️ Restrições

- NÃO usar frameworks CSS
- NÃO usar JavaScript
- NÃO modificar estrutura HTML
- MÁXIMO 50 linhas de CSS
- DEVE funcionar em Chrome/Firefox modernos

## 🎯 Resultado Esperado

Um portal que:
- Impressiona visualmente ao primeiro olhar
- Funciona perfeitamente em mobile e desktop
- Demonstra técnicas CSS de nível profissional
- Tem interações suaves e naturais
- Segue tendências de design 2024/2025

## 📊 Comparação com Desafio 5a

| Aspecto | Desafio 5a (GameZone) | Desafio 10a (TechNews) |
|---------|------------------------|------------------------|
| **Nível** | Intermediário | Avançado |
| **Foco** | Criatividade/Diversão | Profissionalismo |
| **Técnicas** | Animações, Neon | Grid, Glassmorphism |
| **Estilo** | Retro/Arcade | Moderno/Minimalista |
| **Layout** | Simples | Complexo/Responsivo |

---

**Hora de mostrar que você domina CSS moderno! Crie um portal que impressione recrutadores e clientes! 💻✨**

### 🔗 Arquivos Necessários:
- `desafio10a.html` (fornecido)
- `desafio10a.css` (você criará)
- Navegador moderno para testar