# 🚀 Portal de Notícias Responsivo

## 📋 Descrição do Projeto

Este é um projeto de **Portal de Notícias Responsivo** desenvolvido durante a **Trilha Fullstack da Rocketseat**. O projeto foi recriado com foco em **responsividade**, utilizando **media queries**, **CSS Grid**, **Flexbox** e outras técnicas modernas de layout CSS.

### 🎯 Objetivos de Aprendizado

- **Media Queries**: Implementação de design responsivo para diferentes tamanhos de tela
- **CSS Grid**: Criação de layouts complexos e organizados
- **Flexbox**: Alinhamento e distribuição de elementos
- **Estrutura HTML Semântica**: Uso correto de tags HTML5
- **Design Responsivo**: Adaptação para dispositivos móveis e desktop

## 🎨 Design e Layout

### 📱 Figma Original
O projeto foi baseado no design do Figma disponível em:
[Portal de Notícias - Figma Community](https://www.figma.com/community/file/1392188698846698895)

### 🖥️ Layouts Implementados

#### **Header (Cabeçalho)**
- Menu hambúrguer para mobile
- Logo responsivo (versões mobile e desktop)
- Barra de navegação com categorias
- Barra de busca

#### **Seção Principal (Featured)**
- Card em destaque com imagem grande
- Grid de 2 colunas com cards menores
- Categorias com tags coloridas
- Gradientes sobrepostos nas imagens

#### **Seção Semanal (Weekly)**
- Lista de artigos mais lidos
- Cards horizontais com imagens
- Layout adaptativo para diferentes tamanhos

#### **Sidebar (Lateral)**
- Seção de Inteligência Artificial
- Seção de anúncios
- Cards com layout reverso (imagem à direita)

## 🛠️ Tecnologias e Bibliotecas

### **Fontes**
- **Google Fonts**: 
  - `Archivo` (família principal com pesos 100-900)
  - `Archivo Black` (para títulos especiais)

### **CSS Puro**
- **CSS Custom Properties** (variáveis CSS)
- **CSS Grid** para layouts complexos
- **Flexbox** para alinhamentos
- **Media Queries** para responsividade
- **CSS Gradients** para efeitos visuais
- **CSS Transitions** para animações suaves

### **Ferramentas de Desenvolvimento**
- **App Responsively**: Para visualização simultânea mobile/desktop
- **VS Code** com extensões de desenvolvimento web

## 📁 Estrutura do Projeto

```
portal-de-noticias-responsivo/
├── assets/
│   ├── icons/           # Ícones SVG
│   ├── logo.svg         # Logo desktop
│   ├── logo-sm.svg      # Logo mobile
│   └── Image 01-18.png  # Imagens dos artigos
├── styles/
│   ├── global.css       # Estilos globais e variáveis
│   ├── utility.css      # Classes utilitárias
│   ├── header.css       # Estilos do cabeçalho
│   ├── section.css      # Estilos das seções
│   └── index.css        # Arquivo principal (imports)
└── index.html           # Estrutura HTML principal
```

## 🎨 Sistema de Design

### **Paleta de Cores**
```css
--brand-color-light: #60A5FA    /* Azul claro */
--brand-color-dark: #1D4ED8     /* Azul escuro */
--bg-color: #0F172A             /* Fundo escuro */
--stroke-color: #1E293B         /* Bordas */
--text-color-primary: #F1F5F9   /* Texto principal */
--text-color-secondary: #CBD5E1 /* Texto secundário */
```

### **Tipografia**
- **Família**: Archivo (sans-serif)
- **Títulos**: Pesos 800 (extra-bold)
- **Texto**: Peso 400 (regular)
- **Tags**: Peso 600 (semi-bold)

### **Espaçamentos**
- Sistema de padding responsivo
- Breakpoint principal: `80em` (1280px)
- Adaptação automática de espaçamentos

## 📱 Responsividade

### **Breakpoints**
- **Mobile First**: Design baseado em dispositivos móveis
- **Desktop**: `width >= 80em` (1280px)

### **Classes Responsivas**
- `.mobile-only`: Visível apenas em mobile
- `.desktop-only`: Visível apenas em desktop
- `.grid-cols-2`: Grid de 2 colunas (desktop)

### **Adaptações**
- **Imagens**: Tamanhos diferentes para mobile/desktop
- **Textos**: Versões truncadas para mobile
- **Layouts**: Reorganização de elementos
- **Navegação**: Menu adaptativo

## 🚀 Como Executar

1. **Clone o repositório**
   ```bash
   git clone [url-do-repositorio]
   cd portal-de-noticias-responsivo
   ```

2. **Abra o projeto**
   - Use um servidor local (Live Server no VS Code)
   - Ou abra diretamente o `index.html` no navegador

3. **Visualização Responsiva**
   - Use o **App Responsively** para ver mobile e desktop simultaneamente
   - Ou redimensione a janela do navegador

## 📚 Conceitos CSS Aplicados

### **CSS Grid**
```css
.grid-cols-2 {
  grid-template-columns: 1fr 1fr;
}
```

### **Flexbox**
```css
.flex {
  display: flex;
}

.row-reverse {
  flex-direction: row-reverse;
}
```

### **Media Queries**
```css
@media (width >= 80em) {
  /* Estilos para desktop */
}
```

### **CSS Custom Properties**
```css
:root {
  --brand-color-light: #60A5FA;
  --py-md: 1rem;
}
```

## 🎯 Funcionalidades Implementadas

- ✅ **Header responsivo** com navegação adaptativa
- ✅ **Grid de cards** com layout responsivo
- ✅ **Sidebar lateral** com artigos em destaque
- ✅ **Sistema de categorias** com tags coloridas
- ✅ **Imagens responsivas** com diferentes tamanhos
- ✅ **Textos adaptativos** para mobile/desktop
- ✅ **Navegação mobile** com menu hambúrguer
- ✅ **Layouts flexíveis** usando CSS Grid e Flexbox

## 🔧 Desenvolvimento

### **Metodologia**
- **Mobile First**: Design iniciado para dispositivos móveis
- **Componentes Reutilizáveis**: Classes CSS modulares
- **Variáveis CSS**: Sistema de design consistente
- **Semântica HTML**: Estrutura semântica e acessível

### **Organização do CSS**
- **Separação por responsabilidade**: Cada arquivo tem uma função específica
- **Classes utilitárias**: Sistema de classes reutilizáveis
- **Variáveis globais**: Centralização de valores de design

## 📱 Compatibilidade

- ✅ **Chrome** (recomendado)
- ✅ **Firefox**
- ✅ **Safari**
- ✅ **Edge**
- ✅ **Dispositivos móveis**
- ✅ **Tablets**
- ✅ **Desktop**

## 🎓 Aprendizados da Trilha Fullstack

Este projeto foi desenvolvido durante a **Trilha Fullstack da Rocketseat**, focando em:

- **Frontend Fundamentals**: HTML semântico e CSS avançado
- **Responsive Design**: Media queries e layouts adaptativos
- **CSS Moderno**: Grid, Flexbox e Custom Properties
- **Boas Práticas**: Organização de código e estrutura de projeto

## 📄 Licença

Este projeto está sob a licença especificada no arquivo `LICENSE`.

---

**Desenvolvido com 💙 durante a Trilha Fullstack da Rocketseat**

