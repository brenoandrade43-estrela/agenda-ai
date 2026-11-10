# Agenda AI — protótipo PWA v2

Interface em português, com identidade visual elegante e minimalista em preto, branco e cinza.

## Recursos desta versão
- Painel de hoje com totais, concluídos, pendentes e barra de progresso.
- Abas Hoje, Agenda, Tarefas e Assistente.
- Navegação por semana e seleção de dia.
- Cadastro e edição de compromissos, tarefas e lembretes.
- Marcação de concluído/pendente.
- Filtros de tarefas.
- Armazenamento local no navegador.
- Ditado experimental por SpeechRecognition, quando disponível.
- Manifesto, ícone e service worker para instalação como PWA.

## Limitações
Esta é uma demonstração local. Não possui ainda IA conversacional conectada, sincronização com iCloud/Calendário/Lembretes, notificações agendadas confiáveis, autenticação ou banco de dados remoto. Os dados ficam no armazenamento local do navegador e não sincronizam automaticamente com outros dispositivos.

## Instalação no iPhone
Hospede os arquivos em um endereço HTTPS. Abra o endereço no Safari, toque em Compartilhar e escolha “Adicionar à Tela de Início”. O suporte a PWA no iOS tem limitações específicas.

## Próximas etapas
1. Backend seguro e autenticação.
2. IA de voz com confirmação explícita de alterações.
3. Banco de dados e sincronização entre dispositivos.
4. Integração nativa com EventKit para Calendário e Lembretes Apple.
5. Notificações locais e/ou push.
6. Build iOS assinado e distribuição via TestFlight/App Store.
