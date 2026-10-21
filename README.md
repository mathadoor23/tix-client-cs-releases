# T1x Game Client

Biblioteca de jogos e configurações locais para Windows, com perfis por jogo, prévias e aplicação revisada com backup.

Baixe o **Setup** na [última versão](https://github.com/mathadoor23/tix-client-cs-releases/releases/latest). Instalação por usuário, sem exigir administrador. Requer Windows 10/11 x64 com .NET Framework 4.8. A versão 0.5.1 corrige o ícone do atalho e mantém o diagnóstico local para jogos da 0.5.0. O T1x Game Client amplia o antigo Tix Client CS; o canal de atualização mantém o endereço anterior por compatibilidade.

## Recursos

- Biblioteca Steam em várias unidades e inclusão manual de jogos pelo executável.
- Leitura de CPU, RAM e memória dedicada de GPU; perfil com meta de FPS e preferência visual para cada jogo.
- **Perfil do PC:** sistema, driver de vídeo, plano de energia, armazenamento, prontidão por jogo e teste curto de latência/jitter/perda.
- Exportação de relatório HTML/JSON sem usuário, nome do computador, números de série ou caminhos de arquivos.
- Prioridade e energia opcionais de sessão, com registro e restauração. O processo é identificado pelo caminho e pela hora de criação.
- **CS2:** editor visual de mira, HUD, radar e viewmodel, CFG própria, vídeo, presets, atalhos e arranque.
- **Deadlock:** mira base no arquivo KV3 nativo, preservando ajustes por herói, editor de vídeo e CFG própria para HUD/FPS.
- **GTA V Enhanced:** campos gráficos existentes no XML com preservação dos demais dados.

Em **Perfil do PC**, confira os limites básicos do computador e exporte o diagnóstico. Em **Configuração**, gere uma recomendação e prepare a sugestão no editor. Revise o conteúdo antes de aplicar. Recomendações são heurísticas iniciais: não prometem atingir o alvo de FPS nem substituem uma medição no seu jogo. Para outros títulos, use os recursos gerais e ajuste os gráficos no próprio jogo até existir um módulo específico.

## Arquivos e recuperação

O cliente preserva o autoexec do CS2 e usa sua própria CFG. Vídeo, mira nativa do Deadlock e XML do GTA exigem o jogo fechado. Antes de escrever, o programa salva backup e recibo; a restauração recusa sobrescrever mudanças posteriores. Restaurar um arquivo não reverte automaticamente comandos já carregados no jogo. Falha abrupta de energia pode exigir recuperação manual do backup.

O desinstalador remove os arquivos conhecidos do aplicativo e preserva perfis, configurações e backups.

## Atualizações

Em **Preferências**, consulte, baixe e instale versões explicitamente. O cliente confere assinatura do manifesto, versão, origem, tamanho e SHA-256. O canal tem assinatura própria e não substitui um certificado Authenticode do Windows; o instalador não possui certificado comercial.

## Limites atuais

As prévias são ilustrativas. Ainda não há ganho de FPS demonstrado, ajuste automático medido para qualquer jogo, separação adaptativa de aplicativos ou garantia de compatibilidade com todo build. O módulo completo do GTA Legacy ainda não está disponível. As capacidades específicas de cada jogo aparecem separadas na interface.

Este repositório contém somente instaladores, metadados de atualização e documentos públicos.
