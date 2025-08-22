# Mini Desafio CSS - Loja de Games Retro 🎮

## 📋 Descrição do Desafio

Você foi contratado para **estilizar** a página da **GameZone Retro** com um visual temático dos anos 80/90. A página HTML já existe - agora é hora de dar vida com CSS!

## 🎯 Objetivo

Criar um arquivo CSS de **no máximo 50 linhas** que transforme a página em uma experiência visual retro/arcade.

## 📝 Requisitos Principais

### ✅ Elementos CSS Essenciais
- **Tema Visual:** Cores neon e gradientes característicos dos arcades
- **Animações:** Pelo menos uma animação com @keyframes
- **Efeitos de Texto:** Text-shadow para efeito neon/glow
- **Hover Effects:** Interações em links e/ou tabela
- **Layout:** Centralização e espaçamento adequado

## 🎨 Requisitos de Design

### Paleta de Cores Sugerida:
- **Fundo:** Escuro (#0f0f23 ou similar)
- **Neon:** Magenta (#ff00ff), Ciano (#00ffff), Verde (#00ff00)
- **Destaque:** Amarelo (#ffff00)
- **Texto:** Branco com sombras coloridas

### Efeitos Obrigatórios:
- Título principal com efeito "neon piscante"
- Links com transformação no hover
- Tabela com visual "arcade screen"
- Bordas luminosas em elementos

## 🔧 Especificações Técnicas

- **Máximo:** 50 linhas de CSS
- **Arquivo:** `desafio5a.css` (externo)
- **Compatibilidade:** Chrome/Firefox modernos
- **Tema:** Visual arcade/retro anos 80
- **Foco:** Criatividade e impacto visual

## 🏆 Critérios de Avaliação

### Técnica (50 pontos)
- ✅ Uso correto de seletores (10pts)
- ✅ Implementação de animações (10pts)
- ✅ Gradientes e sombras (10pts)
- ✅ Hover effects funcionais (10pts)
- ✅ Código limpo e comentado (10pts)

### Criatividade (50 pontos)
- ✅ Fidelidade ao tema retro (15pts)
- ✅ Impacto visual "WOW" (15pts)
- ✅ Uso criativo de pseudo-elementos (10pts)
- ✅ Harmonia das cores (10pts)

## 💡 Dicas Avançadas

### Propriedades Recomendadas:
```css
/* Efeito neon */
text-shadow: 0 0 10px cor, 0 0 20px cor;

/* Animação */
@keyframes piscar {
    0%, 100% { opacity: 1; }
    50% { opacity: 0.5; }
}

/* Gradiente retro */
background: linear-gradient(angle, cor1, cor2);

/* Pseudo-elementos */
li::before { content: "▸"; }
```

### Inspirações:
- Máquinas de fliperama
- Telas de CRT antigas
- Estética Synthwave/Outrun
- Jogos como Pac-Man e Space Invaders

## 🚀 Desafios Extras (Opcional)

Se sobrar espaço nas 50 linhas:
1. **Cursor customizado** para feeling retro
2. **Fonte monoespaçada** estilo terminal
3. **Box-shadow animado** simulando brilho de tela
4. **Transform rotate** em elementos no hover

## 📚 Conceitos CSS Praticados

- Gradientes lineares
- Animações com @keyframes
- Text-shadow e box-shadow
- Pseudo-elementos (::before, ::after)
- Transforms e transitions
- Seletores de atributo e pseudo-classes

## ⚠️ Restrições

- NÃO usar frameworks CSS
- NÃO usar JavaScript
- NÃO modificar o HTML (apenas adicionar classes se necessário)
- MÁXIMO 50 linhas de CSS

## 🎮 Resultado Esperado

Uma página que:
- Transporta o usuário para os anos 80
- Tem elementos interativos e animados
- Usa cores vibrantes e contrastantes
- Demonstra domínio de CSS intermediário

---

**Que os jogos comecem! Mostre que você domina o CSS como um verdadeiro mestre dos arcades! 🕹️✨**

### 🔗 Arquivos Necessários:
- `desafio5a.html` (fornecido)
- `desafio5a.css` (você criará)
- `assets/retro.jpg` (imagem do tema)