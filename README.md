# Bot Studio — Painel de Controle SPA

Painel administrativo moderno construído como Single Page Application (SPA), com tela de login estilizada, validação de acesso e dashboard responsiva com menu lateral contendo o módulo **Bot**.

## 🚀 Funcionalidades

- **Tela de Login Moderna**:
  - Efeito glassmorphism e iluminação de fundo (radial glow / grid background).
  - Validação de campos (e-mail e senha) com mensagens de erro reativas.
  - Alternância de visibilidade de senha (mostrar/ocultar senha).
  - Animação de carregamento (spinner) no botão de autenticação.
  - Notificações por Toast flutuante com feedback visual de sucesso/erro.
  - Credenciais de demonstração pré-configuradas.

- **Dashboard Integrada**:
  - Sidebar lateral responsiva (drawer retrátil em telas móveis e fixa em desktop).
  - Menu lateral dedicado ao módulo **Bot** com badge de status ativo em tempo real.
  - Header superior com breadcrumbs dinâmicos, ações rápidas e botão de encerramento de sessão (*logout*).
  - Controle de sessão persistente no `localStorage`.
  - Roteamento SPA seguro por hash (`#login` e `#dashboard`), redirecionando automaticamente usuários não autenticados.

- **Módulo Bot (Estado Vazio Elegante)**:
  - Cabeçalho de módulo com contadores e botão de criação de agentes.
  - Empty state com ícone iluminado com efeito pulse-ring, chamada de ação clara e cartões de prévia de recursos (Canais, Automações e IA).
  - Modais interativos para criação de assistentes e acesso à documentação.

## 🛠️ Tecnologias Utilizadas

- **HTML5 Semântico & SPA Vanilla**: Roteamento leve baseado em `hashchange` sem dependência de build tools.
- **Tailwind CSS (CDN)**: Design system com paleta zinc/slate e acentos violeta/índigo.
- **Lucide Icons**: Biblioteca de ícones modernos renderizados via SVG limpo.
- **Google Fonts**: Tipografias *Inter* e *Plus Jakarta Sans*.

## 🔑 Credenciais de Demonstração

Para acessar imediatamente o painel:
- **E-mail**: `admin@botstudio.com`
- **Senha**: `123456`

*(Também é possível utilizar qualquer outro e-mail e senha válidos com pelo menos 4 caracteres).*
