# Bot Studio — Painel de Controle SPA com Banco de Dados Real

Painel administrativo moderno construído como Single Page Application (SPA), integrado diretamente com banco de dados real em nuvem (**WLC.DB**), com suporte a autenticação, cadastro de novos usuários e gerenciamento persistente do módulo **Bot**.

## 🚀 Funcionalidades

- **Autenticação Real & Cadastro de Contas**:
  - Integração com o banco de dados via `window.wlcDb.collection('usuarios')`.
  - Abas de alternância rápida entre **"Entrar"** e **"Criar Conta"**.
  - Validação em tempo real (formato de e-mail, senha mínima e prevenção de e-mails duplicados no banco).
  - Inicialização automática de usuário administrador padrão para acesso imediato.
  - Alternância de visibilidade de senha (mostrar/ocultar senha com ícone interativo).
  - Notificações de *Toast* flutuantes e informativas com feedback visual de sucesso/erro.
  - Efeito visual com glassmorphism, grid dinâmico e iluminação radial.

- **Dashboard Integrada & Sidebar Moderna**:
  - Sidebar responsiva (recolhível com drawer retrátil em mobile e fixa em desktop).
  - Menu lateral dedicado exclusivamente ao módulo **Bot** com badge de status ativo em tempo real.
  - Card de status de conexão com o banco de dados (*WLC.DB Conectado*).
  - Header superior com breadcrumbs dinâmicos, ações rápidas de criação e botão de encerramento de sessão (*logout*).
  - Roteamento SPA resiliente baseado em hash (`#login` e `#dashboard`), redirecionando automaticamente acessos não autenticados.

- **Módulo Bot Dinâmico & Persistente**:
  - Integração com a coleção `bots` do banco de dados real.
  - Contador dinâmico de bots ativos no cabeçalho da dashboard.
  - **Estado Vazio (*Empty State*)**: exibido quando não há assistentes criados, com visual moderno e atalhos rápidos.
  - **Modal Completo de Criação de Bots**: permite cadastrar o nome do assistente, canal de atendimento (WhatsApp, Telegram, Webchat, Instagram) e modelo de IA (GPT-4o, Claude 3.5 Sonnet, etc.).
  - **Lista de Bots em Tempo Real**: exibe cards organizados com status online, canal, modelo e data de criação.

## 🛠️ Tecnologias Utilizadas

- **HTML5 Semântico & SPA Vanilla**: Roteamento leve baseado em `hashchange` sem dependência de build tools.
- **WLC.DB Cloud**: Banco de dados isolado em nuvem para persistência de usuários e bots com resiliência local.
- **Tailwind CSS (CDN)**: Design system moderno com paleta escura (slate/zinc) e acentos em índigo/violeta.
- **Lucide Icons**: Biblioteca de ícones modernos renderizados via SVG.
- **Google Fonts**: Tipografias *Inter* e *Plus Jakarta Sans*.

## 🔑 Credenciais Pré-configuradas

O banco de dados já inicializa com uma conta administrativa:
- **E-mail**: `admin@botstudio.com`
- **Senha**: `123456`

Você também pode clicar na aba **"Criar Conta"** na tela de login para cadastrar novos usuários com persistência real!
