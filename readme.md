# LaslesVPN - Site Institucional

## Descrição do Projeto
LaslesVPN é um site institucional fictício que apresenta os serviços de uma empresa de VPN, oferecendo informações sobre planos, funcionalidades, estatísticas, depoimentos de usuários e formas de contato. O site foi desenvolvido utilizando **HTML semântico e CSS moderno**, com foco em **design responsivo, acessibilidade básica e organização de layout**.

O projeto tem como objetivo demonstrar habilidades em **front-end**, incluindo organização de seções, estilização avançada com CSS e implementação de elementos interativos básicos.

---

## Paleta de Cores
- **Cor Primária**: #F53838 (vermelho vibrante para CTAs e destaques)
- **Cor Secundária**: #4F5665 (cinza escuro para textos e elementos secundários)
- **Cor de Fundo**: #FFFFFF (branco para áreas principais)
- **Cor de Destaque**: #0B132A (azul escuro para cabeçalhos e rodapés)
- **Cor de Suporte**: #2C3333 (cinza médio para bordas e separadores)
- **Cor de Texto**: #000000 (preto para textos principais)

- **HTML5**: Estrutura semântica do site, incluindo header, nav, main, sections e footer.
- **CSS3**: Layout, responsividade, tipografia e interatividade visual (hover, cards ativos, botões estilizados).
- **Google Fonts**: Fonte Rubik para uma identidade visual moderna.
- **Iframes**: Integração com o Google Maps para exibição do mapa de localização.
- **Imagens e ícones**: Recursos gráficos para melhorar a experiência visual do usuário.

## Tecnologias Utilizadas

- **HTML5**: Estrutura semântica do site, incluindo header, nav, main, sections e footer.
- **CSS3**: Layout, responsividade, tipografia e interatividade visual (hover, cards ativos, botões estilizados).
- **Google Fonts**: Fonte Rubik para uma identidade visual moderna.
- **Iframes**: Integração com o Google Maps para exibição do mapa de localização.
- **Imagens e ícones**: Recursos gráficos para melhorar a experiência visual do usuário.

---

## Estrutura do Projeto

```├── index.html # Página principal
├── sobre.html # Página sobre a empresa
├── contato.html # Página de contato
├── auth/
│ ├── login.html # Tela de login
│ └── cadastro.html # Tela de cadastro
├── assets/
│ ├── style/
│ │ └── home.css # CSS principal
│ │ └── reset.css # CSS de reset
│ │ └── variaveis.css # CSS de variáveis
│ └── img/ # Imagens
```

---

## Funcionalidades Implementadas

### 1. Header e Navegação
- Logo da empresa com imagem.
- Menu de navegação com links para **Home, Sobre e Contato**.
- Área de login/cadastro com botões estilizados.

### 2. Hero Section
- Mensagem de destaque e chamada para ação (CTA).
- Imagem ilustrativa representando uso de VPN.
- Botão “Começar” com efeito hover.

### 3. Seção de Estatísticas
- Cards com informações chave: **Usuários, Localizações e Servidores**.
- Uso de ícones ilustrativos para melhorar a compreensão visual.

### 4. Seção de Recursos (Features)
- Lista de funcionalidades exclusivas:
  - Alta segurança de rede
  - Velocidade de conexão estável
  - Suporte em várias plataformas
  - Garantia de privacidade
- Layout em cards responsivos com imagem ilustrativa.

### 5. Planos
- Três tipos de planos:
  - Plano Grátis
  - Plano Padrão
  - Plano Premium
- Cards detalhando dispositivos permitidos, largura de banda, suporte e preço.
- Destaque visual no plano ativo.

### 6. Mapa
- Integração com Google Maps para mostrar localização global do serviço.
- Responsivo e ajustável para diferentes tamanhos de tela.

### 7. Depoimentos
- Cards com comentários de usuários, fotos e nomes.
- Design responsivo com flexbox para se ajustar em telas menores.

### 8. Footer
- Informações institucionais, links de produtos e engajamento.
- Formulário de newsletter.
- Layout organizado em colunas e adaptável a dispositivos móveis.

### 9. Meta dados extra sobre acessibilidade
```<meta name="description" content="Página Principal sobre LaslesVPN" />```
- A meta tag description ajuda a descrever o conteúdo da página, o que pode ser útil para usuários que dependem de tecnologias assistivas.

---

## Responsividade
O site foi construído com **media queries** para suportar diferentes tamanhos de tela, garantindo boa experiência em:

- Desktop
- Tablets
- Smartphones

Principais ajustes incluem:
- Flexbox para reorganizar seções (hero, planos, depoimentos) em coluna em telas pequenas.
- Botões e textos redimensionáveis.
- Ajuste de imagens e cards para caber na largura da tela.

---

## Observações Técnicas

- meta dados foram adicionados para melhorar SEO e acessibilidade.
- Uso de variáveis CSS para facilitar manutenção e consistência visual.
- Todos os botões e links têm **hover e transições suaves**.
- Estrutura semântica do HTML facilita SEO e acessibilidade.
- Ícones e imagens são otimizados para desempenho e carregamento rápido.
- A navegação entre login e cadastro é feita em páginas separadas (`auth/login.html` e `auth/cadastro.html`) para simplicidade e clareza do fluxo do usuário.

## 10. Checklist (colar no README e marcar)

- [x]  3 páginas mínimas (Home/Sobre/Contato) + links funcionando.
- [x]  `header`, `nav`, `main`, `footer` usados com propósito.
- [x]  Hero na página principal
- [x]  **Tabela** simples presente.
- [x]  Paleta no `:root` (variáveis CSS).
- [x]  Google Fonts.
- [x]  Imagens otimizadas com `alt` descritivo.
- [x]  README com papéis, paleta, fontes e decisões.
- [x]  Site no ar.
- [x]  Vídeo de demonstração.


|   <img width="120" src="https://github.com/alicessena.png">  |
|:----------------------------:|
|        **Alice Sena**        |
| **Desenvolvedora FullStack** |