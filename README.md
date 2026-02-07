# DIOUX-LL-mediafidelidade

Este projeto é a implementação em **HTML e CSS** de um layout baseado em um wireframe de média fidelidade. O objetivo é representar visualmente a estrutura de uma interface de listagem de produtos, priorizando organização, hierarquia visual e responsividade básica.

O foco está na **estrutura e no layout**, não em design final, identidade visual ou funcionalidades dinâmicas.

---

## 📌 Objetivo do Projeto

Este código foi criado para:

- Traduzir um wireframe em uma estrutura real de interface
- Servir como base para evolução visual (cores, tipografia, imagens reais)
- Facilitar a implementação futura com JavaScript ou frameworks
- Demonstrar organização de layout com boas práticas de HTML e CSS

---

## 🧱 Estrutura da Interface

A página é composta por quatro partes principais:

### 1. Cabeçalho (Header)

Contém:
- Espaço para logotipo
- Nome do aplicativo
- Subtítulo

Função: Identificação da aplicação e introdução visual.

---

### 2. Barra de Destaque

Blocos horizontais cinza que representam áreas de destaque visual no wireframe.

Função: Separar seções e sugerir áreas para banners, filtros ou chamadas importantes.

---

### 3. Lista de Produtos (Cards Horizontais)

Dois cartões de produto em formato horizontal, contendo:

- Espaço para imagem
- Título do produto
- Texto descritivo

Função: Exibir produtos com mais informações resumidas.

---

### 4. Grade de Produtos (Cards Verticais)

Uma grade responsiva com quatro cartões verticais, cada um contendo:

- Espaço para imagem grande
- Placeholder para botão ou ação

Função: Exibir itens de forma mais visual e exploratória.

---

## 🗂 Estrutura de Arquivos
/projeto
│── index.html
│── styles.css

---

## 🧾 Tecnologias Utilizadas

- **HTML5** — Estrutura semântica da página
- **CSS3** — Estilização, layout, responsividade
- **Flexbox** — Layout da lista horizontal e header
- **CSS Grid** — Layout da grade de produtos
- **Media Queries** — Ajustes para telas menores

---

## 🧩 Conceitos de Layout Aplicados

### Organização em Componentes
O layout foi dividido em blocos reutilizáveis como:
- `.product-card`
- `.image`
- `.content`

Isso facilita a futura transformação em componentes de frameworks (React, Vue, etc.).

### Responsividade Básica
A interface se adapta a telas menores:
- Cards horizontais se tornam verticais em telas pequenas
- A grade usa `auto-fit` para ajustar o número de colunas automaticamente

### Separação de Responsabilidades
- HTML define estrutura e significado
- CSS define aparência e layout

---

## ▶️ Como Executar

1. Salve os arquivos `index.html` e `styles.css` na mesma pasta
2. Abra o arquivo `index.html` em qualquer navegador moderno

Não é necessário servidor ou instalação de dependências.

---

## 🔄 Próximos Passos Sugeridos

Este projeto representa apenas a base estrutural. Evoluções possíveis incluem:

### Visual
- Aplicar paleta de cores
- Definir tipografia oficial
- Substituir blocos cinza por imagens reais
- Criar estados de botão (hover, active)

### Funcional
- Transformar os cards em links clicáveis
- Adicionar navegação
- Integrar dados dinâmicos (API ou JSON)

### Estrutural
- Separar CSS em módulos
- Converter para SCSS ou outro pré-processador
- Migrar para um framework (React, Vue, Angular)

---

## Limitações

- Não há interatividade ou JavaScript
- Não há acessibilidade avançada implementada
- Não representa design final, apenas estrutura
- Não inclui sistema de componentes real (apenas organização visual)

---

## Licença

Este projeto é livre para uso educacional e como base para novos projetos.



