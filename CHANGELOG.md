# Changelog

Todas as mudanças relevantes do projeto são registradas neste arquivo.

O histórico utiliza uma convenção inspirada em [Semantic Versioning](https://semver.org/) e [Keep a Changelog](https://keepachangelog.com/).

## [1.3.6] - 2026-10-01

### Alterado
- Otimização da foto passou a preservar mais qualidade antes de reduzir compressão.
- Qualidade e resolução da foto são ajustadas de forma progressiva conforme o espaço disponível.
- Contatos foram reorganizados em linhas independentes para melhorar leitura em telas menores.
- Largura da assinatura foi reduzida para maior estabilidade em dispositivos móveis.

### Validado
- Teste real de salvamento no Gmail.
- Teste de envio e visualização em dispositivo móvel.

## [1.3.5] - 2026-10-01

### Adicionado
- Processamento local de imagens usando Canvas API.
- Recorte quadrado e compressão automática da foto enviada pelo computador.
- Foto otimizada passou a ser utilizada também na assinatura final, sem exigir hospedagem externa.

## [1.3.4] - 2026-10-01

### Adicionado
- Compactação do HTML antes da exportação.
- Indicador aproximado do tamanho do HTML em relação ao limite do Gmail.

### Alterado
- Em uma primeira abordagem, fotos locais foram limitadas à pré-visualização e a exportação com foto exigia URL pública HTTPS.

### Observação
- Essa estratégia foi substituída na versão `1.3.5` por otimização local automática da imagem para simplificar a experiência do usuário.

## [1.3.3] - 2026-10-01

### Alterado
- Foto da assinatura aumentada para `100 × 100 px`.
- Centralização vertical da foto em relação ao corpo da assinatura.

## [1.3.2] - 2026-10-01

### Corrigido
- Validador de e-mail corrigido para aceitar corretamente endereços válidos.
- Testes realizados com domínios simples e compostos, incluindo `.com.br`.

## [1.3.1] - 2026-10-01

### Corrigido
- Restauradas funções auxiliares que impediam a pré-visualização e o painel de HTML de funcionar corretamente.

## [1.3.0] - 2026-10-01

### Adicionado
- Máscara de telefone no padrão `(xx) xxxxx-xxxx`.
- Validação de telefone.
- Validação de e-mail.
- Mensagens visuais de erro para campos inválidos.
- Bloqueio da exportação quando os dados de contato obrigatórios estão inválidos.
- Opção de escolher a cor dos hyperlinks entre a cor de destaque e preto.
- Exemplos exibidos como placeholders em cinza.

### Alterado
- Dados digitados pelo usuário passam a aparecer em preto, diferenciando-se dos exemplos.

## [1.2.0] - 2026-10-01

### Alterado
- Painel de HTML passou a ficar recolhido por padrão em **Opções avançadas**.
- Pré-visualização ganhou maior destaque na interface.

## [1.1.0] - 2026-10-01

### Adicionado
- Perfis fictícios de demonstração para diferentes áreas profissionais.
- Demo criativa inspirada em John Stewart.
- Exemplos para Tecnologia, Administrativo/Negócios, Engenharia, Design/Criativo e Saúde.
- Textos de ajuda contextuais nos campos.

## [1.0.0] - 2026-10-01

### Adicionado
- Primeira versão funcional do Gerador de Assinatura Profissional.
- Formulário para dados pessoais e profissionais.
- Personalização de cores.
- Pré-visualização em tempo real.
- Geração automática de links para WhatsApp, e-mail e LinkedIn.
- Opção de copiar assinatura formatada.
- Opção de copiar e baixar o HTML gerado.
- Foto opcional.
