# Skill: Design System para Automação Visual (Estilo Designer/Founder)

Esta Skill define as regras e a lógica para um agente de IA gerar e manter a consistência visual do conteúdo do Instagram no estilo "Designer/Founder", utilizando os templates e elementos visuais pré-definidos.

---

## 1. Elementos Visuais Fundamentais (Brand Kit)

Todo o design é construído sobre estes pilares, que devem ser configurados no Brand Kit do Canva ou em qualquer ferramenta de design.

### 1.1. Paleta de Cores

| Cor | Código Hexadecimal | Uso Principal |
| :-- | :----------------- | :------------ |
| Preto | `#000000` | Fundo principal, texto de alto contraste |
| Branco | `#FFFFFF` | Texto principal, fundo de contraste |
| Verde Neon | `#DFFF00` | Destaques, palavras-chave, ícones, elementos gráficos de atenção |
| Cinza Escuro | `#1A1A1A` | Fundo secundário, sombras sutis |
| Cinza Claro | `#CCCCCC` | Linhas de grade, elementos de fundo com baixa opacidade |

### 1.2. Tipografia

| Tipo | Família de Fonte | Uso Principal | Peso | Estilo |
| :--- | :--------------- | :------------ | :--- | :----- |
| **Serif** | `Cormorant Garamond` (ou similar elegante) | Títulos principais, frases de impacto, quotes | Regular, Bold | Normal, Itálico |
| **Sans-Serif** | `Inter`, `Montserrat` (ou similar técnica) | Corpo de texto, subtítulos, listas, CTAs | Regular, Bold | Normal |

### 1.3. Elementos Gráficos
*   **Grades (Grid):** Linhas finas (1px) em cinza claro, com baixa opacidade (5-10%), sobrepostas ao fundo para um toque técnico.
*   **Orbes/Brilhos:** Círculos desfocados em Verde Neon, usados para criar profundidade ou destacar pontos focais.
*   **Linhas de Conexão:** Linhas finas (1px) em branco ou verde neon, usadas para guiar o olhar em diagramas ou posts de contraste.
*   **Ícones:** Minimalistas, preferencialmente em Verde Neon para checkmarks ou setas.

---

## 2. Mapeamento de Conteúdo para Template Visual

Esta seção define qual template visual deve ser usado com base no tipo de conteúdo ou na função do slide/post.

| Tipo de Conteúdo / Função | Template Visual Sugerido | Elementos Chave | Observações |
| :----------------------- | :----------------------- | :-------------- | :---------- |
| **Capa de Carrossel (Gancho)** | `template_matt_gray_style.png` | Fundo preto, título Serif, orbe neon | Foco em impacto e curiosidade. |
| **Página Interna (Detalhe)** | `template_interna_matt_gray.png` | Fundo preto, título Sans-Serif, listas | Clareza e legibilidade. |
| **Checklist (Valor Rápido)** | `template_checklist.png` | Fundo preto, checkmarks neon | Conteúdo acionável e salvável. |
| **Diagrama (Sistema)** | `template_diagrama.png` | Fundo preto, linhas técnicas | Visualização de processos complexos. |
| **Quote Card (Autoridade)** | `template_quote.png` | Fundo preto, frase Serif | Compartilhável e inspirador. |
| **Contraste (Prisão vs. Liberdade)** | `template_contraste.png` | Fundo preto, divisão vertical | Mostrar transformação. |
| **Contraste (Fundo Branco)** | `template_minimalista_branco.png` | Fundo branco, texto Serif itálico | Clareza e sofisticação. |
| **Híbrido (Foto + Texto)** | `template_hibrido_estudio.png` | Foto de estúdio, texto Serif | Humanização e autoridade. |
| **Gráfico de Ondas (Insight)** | `template_ondas_autoridade.png` | Fundo preto, ondas neon, texto Serif | Conceitos abstratos e técnicos. |
| **Capa de Reels (Autoridade)** | `capa_reels_autoridade.png` | Foto de estúdio, título Serif | Impacto no feed e curiosidade. |
| **Capa de Reels (Gancho Visual)** | `capa_reels_gancho.png` | Fundo preto, diagrama técnico | Atração para conteúdo técnico. |

---

## 3. Regras de Aplicação Visual (Lógica para o Agente)

Estas regras guiam a aplicação dos elementos visuais e a escolha dos templates.

### 3.1. Prioridade de Fundo
*   **Padrão:** Fundo preto (`#000000`).
*   **Exceções:** Usar fundo branco (`#FFFFFF`) para posts de contraste ou quando a mensagem exige máxima clareza e minimalismo (ex: `template_minimalista_branco.png`).

### 3.2. Uso de Fotos Pessoais
*   **Condição:** Se o conteúdo for sobre "você" (sua jornada, sua experiência, seu sistema pessoal).
*   **Aplicação:** Usar templates híbridos (`template_hibrido_estudio.png`, `capa_reels_autoridade.png`, etc.). A foto deve ter fundo removido e ser de alta qualidade, com iluminação de estúdio.
*   **Interação:** O texto pode estar à frente ou atrás da pessoa, criando profundidade.

### 3.3. Destaque de Palavras-Chave
*   **Regra:** Palavras-chave ou conceitos importantes devem ser destacados em **Verde Neon** (`#DFFF00`) e, opcionalmente, em itálico ou negrito.
*   **Frequência:** Usar com moderação para não saturar o visual. Máximo de 1-3 palavras por frase.

### 3.4. Hierarquia Tipográfica
*   **Títulos Principais:** `Cormorant Garamond` (Serif), tamanho grande, branco.
*   **Subtítulos/Corpo:** `Inter` ou `Montserrat` (Sans-Serif), tamanho médio, branco.
*   **CTAs:** `Inter` ou `Montserrat` (Sans-Serif), negrito, verde neon ou branco.

### 3.5. Elementos de Grid e Linhas
*   **Presença:** O grid de 1px deve estar presente em quase todos os designs, com baixa opacidade.
*   **Função:** Linhas devem ser usadas para dividir seções, conectar ideias em diagramas ou guiar o olhar. Devem ser finas e minimalistas.

### 3.6. Consistência de Layout
*   **Carrosséis:** A capa (`template_matt_gray_style.png`) deve ser sempre impactante. As páginas internas (`template_interna_matt_gray.png`) devem manter a mesma estrutura de cabeçalho e rodapé, alterando apenas o conteúdo central.
*   **Reels:** As capas (`capa_reels_autoridade.png`, etc.) devem ser pensadas para o feed (quadrado central) e para o clique (título claro).

---

## 4. Lógica de Decisão para o Agente

Ao receber um roteiro de carrossel (do Content GPS), o agente deve:
1.  **Analisar a Função do Slide:** Identificar se é um gancho, problema, solução, CTA, etc.
2.  **Consultar o Mapeamento:** Usar a tabela do item 2 para selecionar o `Template Visual Sugerido`.
3.  **Aplicar Regras:** Preencher o template com o texto e elementos gráficos, seguindo as `Regras de Aplicação Visual` (item 3).
4.  **Gerar Imagem:** Criar a imagem final do slide, garantindo que todos os elementos do Brand Kit sejam respeitados.

Esta Skill, combinada com o Content GPS, forma a base para a automação visual do seu Instagram, garantindo que cada peça de conteúdo seja uma extensão autêntica e de alta qualidade do seu brand.
