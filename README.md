# 🌟 Grin Care - Website

Bem-vindo ao repositório do **Grin Care**! Um site moderno e responsivo dedicado a produtos de design assistivo de alta qualidade para toda a família.

## 📋 Sobre o Projeto

**Grin Care** é uma empresa voltada ao **design assistivo**, dedicada a desenvolver soluções inovadoras que promovem **inclusão e autonomia** para pessoas com deficiência ou mobilidade reduzida.

Este website apresenta:

- ✨ Design moderno e elegante
- 📱 Responsivo para todos os dispositivos
- ♿ Acessível e inclusivo
- ⚡ Rápido e otimizado
- 🎨 Interface intuitiva

## 🚀 Características

### 🎯 Seções do Website

1. **Header Sticky**

   - Logo da marca
   - Navegação responsiva com menu hamburger em mobile
   - Menu dropdown animado

2. **Home (Início)**

   - Mensagem de boas-vindas
   - Descrição da empresa

3. **Sobre Nós**

   - Informações sobre as sócias (Lúcia e Denise)
   - Foto ao lado do texto
   - Layout flexível e responsivo

4. **Destaques (Carrossel)**

   - Carrossel interativo com 4 slides
   - Navegação com botões e indicadores
   - Auto-play a cada 5 segundos
   - Animações suaves

5. **Feedbacks (Carrossel Infinito)**

   - Carrossel infinito e contínuo
   - 5 depoimentos de clientes
   - Scroll automático sem pausa
   - Cards com avaliações (⭐⭐⭐⭐⭐)

6. **Contato**

   - Botão WhatsApp
   - Telefone clicável (tel:)
   - Links para redes sociais

7. **Footer**
   - Informações da empresa
   - Links rápidos de navegação
   - Contato direto (telefone e WhatsApp)
   - Redes sociais com ícone animado do Instagram
   - Copyright

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilos modernos com:
  - Flexbox e Grid
  - Gradientes e sombras
  - Animações e transições
  - Media queries para responsividade
- **JavaScript (Vanilla)** - Interatividade:
  - Menu dropdown com toggle
  - Carrossel interativo
  - Carrossel infinito
  - Eventos de mouse e clique

## 📁 Estrutura do Projeto

```
grin-website/
├── index.html          # Arquivo principal HTML
├── style.css          # Estilos CSS completos
├── script.js          # Scripts JavaScript
├── README.md          # Este arquivo
└── assets/            # Imagens e recursos
    ├── grinlogo.jpg
    ├── foto-socias.png
    ├── instagram.png
    ├── edredom.png
    ├── esmagador-triturador.png
    ├── mantas.png
    └── talheres.png
```

## 💻 Como Usar

### Instalação

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/grin-website.git
```

2. Abra o arquivo `index.html` no navegador:

```bash
# Opção 1: Abrir diretamente
open index.html

# Opção 2: Usar um servidor local (recomendado)
python -m http.server 8000
# Ou com Node.js
npx http-server
```

3. Acesse `http://localhost:8000` no navegador

## 🎨 Customização

### Cores

As cores principais estão definidas em variáveis CSS em `style.css`:

```css
:root {
  --primary-color: #f4b860; /* Ouro/Amarelo */
  --secondary-color: #6b9bd1; /* Azul */
  --accent-color: #e8a87c; /* Laranja claro */
  --dark-color: #2c3e50; /* Escuro */
  /* ... mais variáveis */
}
```

### Tempo do Carrossel

No arquivo `script.js`, altere o tempo de auto-play (em milissegundos):

```javascript
autoPlayInterval = setInterval(nextSlide, 5000); // Muda de 5000 para seu valor
```

### Adicionar Mais Feedbacks

Para adicionar mais feedbacks no carrossel infinito, adicione cards duplicados em `index.html`:

```html
<div class="feedback-card">
  <div class="stars">⭐⭐⭐⭐⭐</div>
  <p>"Seu feedback aqui"</p>
  <span class="feedback-author">- Seu Nome</span>
</div>
```

## 📱 Responsividade

O site é totalmente responsivo com breakpoints em:

- **Desktop**: Acima de 768px
- **Tablet**: Até 768px
- **Mobile**: Até 480px

### Recursos Responsivos:

- ✅ Menu hamburger em mobile
- ✅ Carrossel ajustável
- ✅ Fonte redimensionável
- ✅ Imagens otimizadas
- ✅ Spacing adaptável

## ♿ Acessibilidade

O projeto inclui:

- ✅ **Semântica HTML** adequada
- ✅ **aria-labels** em elementos interativos
- ✅ **Contraste de cores** suficiente
- ✅ **Focus states** para navegação por teclado
- ✅ **Respeita prefers-reduced-motion** para usuários sensíveis a animações
- ✅ **Links tel:** para contato telefônico

## 🔧 Funcionalidades JavaScript

### Menu Dropdown

- Toggle ao clicar no hamburger
- Fecha ao clicar em um link
- Fecha ao clicar fora do header
- Animações suaves

### Carrossel Interativo (Produtos)

- Navegação manual com botões
- Indicadores clicáveis
- Auto-play automático
- Pausa ao hover

### Carrossel Infinito (Feedbacks)

- Scroll contínuo sem pausa
- Seamless loop
- Efeito hover nos cards
- Cálculo dinâmico de animação

## 🎯 SEO e Performance

### Otimizações:

- Título descritivo
- Meta tags
- Viewport configurado
- Imagens otimizadas
- CSS e JS minificados (opcional)

## 📞 Contato e Links Úteis

- **WhatsApp**: [Enviar Mensagem](https://wa.me/5531988745307)
- **Telefone**: +55 31 98874-5307
- **Instagram**: [@grin.care](https://www.instagram.com/grin.care/)

## 📄 Licença

Este projeto é privado. Todos os direitos reservados © 2025 Grin Care.

## 🚀 Começar Agora

Para começar a usar o site localmente:

```bash
# 1. Navegue até o diretório do projeto
cd grin-website

# 2. Inicie um servidor local
python -m http.server 8000

# 3. Abra seu navegador
# http://localhost:8000
```
