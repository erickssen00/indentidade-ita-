# Guia de Estilo Visual — Itaú

Este documento é um **Design System / Style Guide** simples para o projeto do Itaú, servindo como referência prática para desenvolvedores, designers e profissionais de UX/UI[cite: 1]. O objetivo é garantir **consistência visual**, **acessibilidade** e **padronização** de componentes em todas as telas da aplicação[cite: 1].

---

## 🎨 Paleta de Cores e Aplicação

A paleta foi dividida de acordo com a função e o grau de contraste/ênfase (com variações `-1` para tons mais escuros/saturados e `+1` para tons mais claros)[cite: 1].

### 1. Cores Primárias (Identidade Visual)
Utilizadas nos elementos de maior destaque da marca, como botões de ação principal (*Primary Call to Action*), cabeçalhos de destaque e elementos institucionais[cite: 1].
* **Primário -1 (`#CC4E00`):** Indicado para estados de *hover* ou *press* do botão primário[cite: 1].
* **Primário Base (`#FF6200`):** Cor principal da marca[cite: 1]. Usada em botões e destaques primários[cite: 1].
* **Primário +1 (`#FF8133`):** Indicado para fundos suaves ou elementos secundários da cor de marca[cite: 1].

### 2. Cores Secundárias (Apoio e Interação)
Cor complementar para dar contraste aos elementos alaranjados e organizar diferentes fluxos[cite: 1].
* **Secundário -1 (`#1866BE`):** Estado ativo/pressionado de links ou botões azuis[cite: 1].
* **Secundário Base (`#267FE3`):** Usado em links, botões secundários, ícones informativos e elementos interativos[cite: 1].
* **Secundário +1 (`#539AE9`):** Estado de *hover* leve ou superfícies com fundo azul suave[cite: 1].

### 3. Neutras Escuras (Dark Mode / Tipografia)
Dedicadas principalmente ao contraste de textos, títulos e bordas escuras[cite: 1].
* **Dark -1 (`#0B0A0A`):** Cor máxima de contraste, ideal para textos principais em fundos brancos[cite: 1].
* **Dark Base (`#262323`):** Usada para títulos (`H1` a `H5`) e textos de corpo de leitura[cite: 1].
* **Dark +1 (`#403B3B`):** Usada em textos secundários, legendas (*captions*) ou ícones desabilitados[cite: 1].

### 4. Neutras Claras (Light Mode / Fundos)
Servem de base de fundo para telas, cards, containers e áreas de conteúdo[cite: 1].
* **Light -1 (`#D3DDE4`):** Ideal para bordas, divisores (`dividers`) e linhas estruturais[cite: 1].
* **Light Base (`#F2F5F7`):** Cor de fundo padrão da aplicação (canvas/background)[cite: 1].
* **Light +1 (`#FFFFFF`):** Branco puro, ideal para o interior de cartões (cards), modais e caixas de texto[cite: 1].

### 5. Cores de Feedback (Status da Interface)
Cores semânticas para comunicar o resultado das ações dos usuários[cite: 1].

#### 🟢 Sucesso (Success)
Utilizadas em mensagens de confirmação, estados concluídos ou indicadores positivos[cite: 1].
* **Success -1 (`#2FC63E`):** Tom escuro para bordas ou textos[cite: 1].
* **Success Base (`#52D65F`):** Cor principal de ícones e botões de confirmação[cite: 1].
* **Success +1 (`#7BE085`):** Fundo claro para caixas de alerta positivo[cite: 1].

#### 🔴 Perigo / Erro (Danger)
Utilizadas para avisos críticos, validação de formulários com erro, exclusões ou alertas de perigo[cite: 1].
* **Danger -1 (`#FF2705`):** Alerta vibrante e chamativo[cite: 1].
* **Danger Base (`#D11C00`):** Texto de erro ou botão destrutivo[cite: 1].
* **Danger +1 (`#9E1500`):** Tom escuro para estados ativos de erro[cite: 1].

---

## 🔤 Tipografia e Hierarquia Visual

* **Família Tipográfica Padrão:** `Poppins` (Google Fonts)[cite: 1]  
  *A fonte **Poppins** foi escolhida por sua excelente legibilidade em telas digitais (desktop e mobile), possuindo formas geométricas bem definidas.*

### Escala Tipográfica (Font Scale)
Siga esta escala para definir tamanhos de fonte no CSS, mantendo o ritmo vertical da página e uma hierarquia clara de leitura[cite: 1]:

| Nível / Tag | Tamanho (px) | Função e Recomendação de Uso |
| :--- | :---: | :--- |
| **Small** | `14px` | Textos auxiliares, legendas, rodapés e notas de rodapé (*captions*)[cite: 1]. |
| **Parágrafo (Body)** | `16px` | Tamanho padrão para corpo de texto, descrições e inputs de formulário[cite: 1]. |
| **H5** | `18px` | Subtítulos pequenos, títulos de cards e itens de lista em destaque[cite: 1]. |
| **H4** | `24px` | Títulos de seções intermediárias e cabeçalhos de modais[cite: 1]. |
| **H3** | `28px` | Títulos de grandes seções na página[cite: 1]. |
| **H2** | `34px` | Títulos principais de páginas internas e painéis[cite: 1]. |
| **H1** | `40px` | Título principal (*Hero Title*) ou telas de boas-vindas[cite: 1]. |

---

## 🏷️ Marca e Logo

* **Aplicação da Marca:** Itaú[cite: 1]  
* Certifique-se de manter o contraste adequado do logotipo sobre as cores da paleta, aplicando o logo em fundo **Light +1 (`#FFFFFF`)** ou **Primário Base (`#FF6200`)** conforme as regras de aplicação da marca[cite: 1].
