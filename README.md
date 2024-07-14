### README.md para o Plugin Slotlauch Provedor

---

# Slotlauch Provedor

## Descrição

O **Slotlauch Provedor** é um plugin WordPress desenvolvido para facilitar a integração de provedores de jogos de cassino ao seu site. Com este plugin, você pode adicionar e gerenciar jogos de slots diretamente do painel do WordPress, proporcionando uma experiência de jogo rica e envolvente para seus usuários.

## Funcionalidades

- **Integração Simplificada**: Adicione e configure jogos de slots facilmente, sem a necessidade de conhecimentos técnicos avançados.
- **Gerenciamento Centralizado**: Administre todos os jogos a partir de um painel único e intuitivo.
- **Compatibilidade**: Compatível com uma ampla gama de temas e plugins WordPress.
- **Segurança**: Autenticação segura para garantir a integridade dos dados.

## Instalação

1. **Baixe o Plugin**:
   - Obtenha o arquivo ZIP do plugin a partir do repositório oficial.

2. **Instale o Plugin**:
   - No painel administrativo do WordPress, vá para **Plugins > Adicionar Novo**.
   - Clique em **Enviar Plugin** e selecione o arquivo ZIP do Slotlauch Provedor.
   - Clique em **Instalar Agora** e, em seguida, ative o plugin.

3. **Configuração Inicial**:
   - Acesse o menu **Slotlauch Provedor** no painel do WordPress.
   - Forneça as chaves de API do provedor de jogos conforme solicitado.
   - Adicione e configure os jogos de slots conforme necessário.

## Configuração

1. **Configurações Gerais**:
   - Vá para **Slotlauch Provedor > Configurações**.
   - Insira as informações da API do provedor de jogos.
   - Ajuste as configurações de segurança e autenticação conforme necessário.

2. **Adicionando Jogos**:
   - Acesse **Slotlauch Provedor > Jogos**.
   - Clique em **Adicionar Novo Jogo** e preencha as informações solicitadas.
   - Configure as opções de cada jogo, como temas e limites de apostas.

## Arquitetura do Plugin

O plugin é estruturado da seguinte forma:

- **includes/**: Contém as classes principais e funções auxiliares.
  - `class-slotslaunch-license.php`: Gerencia as licenças do plugin.
  - `class-slotslaunch-slots.php`: Responsável pela lógica dos jogos de slots.
  - `class-slotslaunch-ajax.php`: Lida com requisições AJAX.
  - `class-slotslaunch-cpt.php`: Define os Custom Post Types.
  - `class-slotslaunch-activator.php`: Ações a serem executadas na ativação do plugin.
  - `class-slotslaunch-widget.php`: Criação de widgets do plugin.
  - `class-slotslaunch.php`: Classe principal do plugin.
  - `class-slotslaunch-i18n.php`: Internacionalização do plugin.
  - `class-slotslaunch-client.php`: Gerenciamento do cliente.
  - `class-slotslaunch-deactivator.php`: Ações a serem executadas na desativação do plugin.

- **admin/**: Contém os arquivos relacionados ao painel administrativo.
  - `class-slotslaunch-settings.php`: Gerencia as configurações do plugin.
  - `class-slotslaunch-importer.php`: Importação de dados.
  - `class-slotslaunch-wizard.php`: Assistente de configuração.
  - `class-slotslaunch-updates.php`: Gerencia atualizações do plugin.
  - `wizard/`: Arquivos relacionados ao assistente de configuração inicial.

- **vendor/**: Dependências externas necessárias para o funcionamento do plugin.

## Suporte

Para suporte técnico, visite [link de suporte] ou envie um e-mail para suporte@slotlauch.com.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests no repositório do GitHub.

## Licença

Este projeto está licenciado sob a [Nome da Licença].

---

Este README foi projetado para fornecer uma visão geral detalhada do plugin Slotlauch Provedor, incluindo instruções de instalação, configuração e uma descrição da arquitetura do plugin.