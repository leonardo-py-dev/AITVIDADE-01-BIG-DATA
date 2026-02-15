# Walkthrough - Business Intelligence Presentation

Desenvolvemos uma apresentação web completa sobre Business Intelligence com design futurista e interações modernas.

## O Que Foi Implementado

### 1. Design System (`CSS/style.css`)

- **Paleta de Cores**: Fundo escuro (#020402) com acentos em verde neon (#00E676) e azul (#2979FF)
- **Tipografia**: Dual font system — **Oxanium** (títulos, futurista) + **Inter** (corpo, legível)
- **Glassmorphism**: Cards translúcidos com `backdrop-filter` e bordas semi-transparentes
- **Efeitos**: Brilhos ambientais, spotlight do mouse, animações de entrada suaves

### 2. Estrutura HTML (`HTML/index.html`)

#### Seções Principais

1. **Hero Section**: Título animado com gradiente e subtítulo
2. **Resumo Executivo**: Overview conciso do que é BI
3. **Conceito**: Definição clara e objetiva
4. **Impacto**: Cards mostrando os 3 pilares de valor do BI
5. **Ciclo de Vida dos Dados**: 5 etapas interativas (clique para expandir)
6. **Ecossistema**: Tabs interativas comparando BI vs Big Data, Data Science, Data Warehouse, Data Lake
7. **6 Vs do Big Data**: Flip-cards 3D com frente/verso (clique para girar)
   - **Destaque especial** para o 6º V (Visualização) com borda tracejada azul e badge de controvérsia
8. **Benefícios**: 5 cards com ícones grandes e textos diretos/objetivos
9. **Tipos de Análise**: 4 cards expansíveis (Descritiva → Diagnóstica → Preditiva → Prescritiva)
10. **Ferramentas de Mercado**: Categorias de ferramentas (Visualização, Armazenamento, ETL)
11. **Case Prático**: Comparação Antes ❌ vs Depois ✅ com métricas reais
12. **Referências**: Lista numerada com fontes confiáveis (Gartner, Nucleus Research, IBM, etc.)

### 3. Interatividade

- **Flip-Cards nos 6 Vs**: Rotação 3D ao clicar, mostrando conexão com BI no verso
- **Accordion nos Tipos de Análise**: Expande/contrai ao clicar
- **Tabs no Ecossistema**: Troca conteúdo sem reload
- **Ciclo Interativo**: Clique nas etapas para ver detalhes
- **Sidebar Dinâmica**: Links de navegação com highlight automático
- **Reveal on Scroll**: Elementos aparecem suavemente ao rolar a página

### 4. Responsividade

- **Desktop (>1024px)**: Grids de 3 e 5 colunas
- **Tablet (768-1024px)**: Grids de 2-3 colunas
- **Mobile (<768px)**: Layouts em coluna única, processos verticais

## Diferenciais

✨ **6º V Destacado**: Visualização tem estilo diferenciado (azul) + nota sobre Variabilidade  
🎨 **Design Premium**: Glassmorphism + gradientes + micro-animações  
📚 **Fontes Acadêmicas**: Seção de referências com 6 fontes confiáveis  
🔄 **Interações Modernas**: Flip-cards, accordions, tabs  
📱 **Totalmente Responsivo**: Funciona perfeitamente em todos os dispositivos

## Como Usar

1. Abra `HTML/index.html` no navegador
2. Navegue pelas seções usando a sidebar lateral
3. Clique nos cards dos 6 Vs para ver a conexão com BI
4. Expanda os tipos de análise para ver exemplos práticos
5. Explore as tabs do ecossistema para entender as diferenças conceituais
