# Política de Privacidade — Capturei

**Última atualização:** 09/11/2026
**Desenvolvedor:** GhostDev

> **Resumo:** o Capturei funciona no seu computador. Ele não coleta, não envia, não vende e não compartilha nenhuma informação sua. Não existe conta, anúncio ou rastreamento. A única conexão com a internet é a verificação de atualizações, que não envia dados pessoais e pode ser desligada.

## 1. Quem somos

O Capturei é um aplicativo de captura e edição de tela para Windows, desenvolvido por GhostDev.

## 2. Quais dados o aplicativo manipula

Todos os dados abaixo ficam somente no seu computador:

- **Capturas de tela e imagens editadas:** ficam na pasta que você escolher (padrão: `Imagens\Capturei`). Só são criadas quando você faz uma captura ou salva uma imagem.
- **Área de transferência:** o Capturei só copia imagens para ela quando você clica em Copiar ou ativa "Copiar automaticamente". Ele nunca lê o que você copiou de outros programas.
- **Gravações de tela:** só acontecem quando você clica em "Gravar tela". A contagem regressiva, a moldura vermelha e a barra de controle ficam sempre visíveis. Os vídeos ficam no seu computador, em `Vídeos\Capturei`.
- **Microfone e som do computador:** são usados apenas durante uma gravação que você iniciou, e só se estiverem ligados nas Configurações. O áudio vai somente para o arquivo de vídeo no seu computador.
- **Configurações:** atalhos, pasta, formato e preferências ficam em `%APPDATA%\Capturei\settings.json`.
- **Registro de erros:** se algo falhar, o Capturei grava detalhes técnicos em `%APPDATA%\Capturei\erros.log`. O arquivo não contém imagens nem dados pessoais e nunca é enviado a ninguém.
- **Inicialização com o Windows:** se você ativar essa opção, o Capturei cria uma entrada `Run` no registro do seu usuário. Ela é removida quando você desativa a opção.

## 3. Conexão com a internet (verificação de atualizações)

A única conexão que o Capturei faz é para saber se existe uma versão nova. Uma vez por dia, ou quando você clica em "Procurar atualizações", ele consulta a página de versões do Capturei no GitHub (`api.github.com`). Se você escolher atualizar, o instalador é baixado do GitHub e só é executado depois de conferido o seu código de segurança (SHA-256).

Nessa consulta não vai nenhum dado pessoal, imagem ou informação sobre o seu uso. Vai apenas a requisição padrão da internet, que identifica o aplicativo como "Capturei" e a versão instalada. Como em qualquer acesso a um site, o GitHub recebe o endereço IP da conexão, conforme a política de privacidade do próprio GitHub.

Você pode desligar a verificação automática em *Configurações → Procurar atualizações automaticamente*. Não há telemetria, estatísticas de uso, anúncios nem outros serviços de terceiros.

## Feedback

Se você usar "Enviar feedback", o Capturei apenas monta a mensagem e abre o **seu** programa de e-mail (ou o Gmail no navegador), endereçada a alves.santos.biel@gmail.com. Nada é enviado sem você clicar em Enviar, e só vai o que você escreveu. Se você marcar a opção, vão também a versão do Capturei e do Windows. As mensagens são usadas apenas para melhorar o aplicativo e para responder você, se pedir.

## 4. Compartilhamento com terceiros

Nenhum dado é compartilhado com terceiros. As imagens só saem do seu computador se você mesmo enviá-las.

## 5. Conteúdo sensível nas capturas

Uma captura de tela pode mostrar informações pessoais, senhas, conversas ou dados de outras pessoas. Antes de compartilhar, revise a imagem e use a ferramenta **Pixelar** para esconder o que for sensível. Você é responsável pelo uso que fizer das imagens e por respeitar a privacidade de terceiros e a legislação aplicável, como a LGPD (Lei nº 13.709/2018).

## 6. Como apagar seus dados

- **Capturas:** apague os arquivos da pasta de capturas.
- **Configurações e registro de erros:** apague a pasta `%APPDATA%\Capturei`.
- **Aplicativo:** desinstale em *Configurações → Aplicativos → Aplicativos instalados → Capturei*. A desinstalação mantém suas capturas, para você não perder nada sem querer.

## 7. Alterações nesta política

Se uma versão futura mudar a forma como o aplicativo trata dados, esta política será atualizada junto com o aplicativo, com nova data no topo.

## 8. Contato

Mande suas dúvidas ao desenvolvedor, GhostDev, pelo e-mail alves.santos.biel@gmail.com.
