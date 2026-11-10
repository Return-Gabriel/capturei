# Novidades do Capturei

## 1.4.0

- **Gravar tela com áudio:** grave em vídeo uma área, uma janela ou o monitor inteiro, **falando pelo microfone** enquanto grava.
  - Vídeo MP4 (H.264) no tamanho real da área, até 60 quadros por segundo, com qualidade visualmente idêntica à tela. Há também a opção "Máxima".
  - Áudio AAC de 48 kHz em estéreo a 192 kbps. Dá para gravar também o som do computador (vídeos, chamadas).
  - Contagem regressiva, moldura vermelha e barra com tempo, microfone em uso e os botões **Pausar**, **Parar** e **Descartar**. A barra e a moldura não aparecem no vídeo.
  - No fim: **Assistir**, **Abrir pasta** ou **Copiar arquivo** para colar direto no WhatsApp ou num e-mail.
  - Botão **Gravar tela** na janela principal, atalho `Ctrl+Alt+G` para iniciar e parar, e opções de microfone, qualidade e cursor em **Configurações → Gravação de tela**.
- **Enviar feedback:** dê uma nota, conte do que gostou e o que está faltando. A mensagem abre pronta no seu e-mail (ou no Gmail) para o desenvolvedor.
- Instalação em pasta (sem compressão), o que também ajuda a reduzir alertas de antivírus.

## 1.3.0

- **Captura com rolagem nas duas direções:** em conversas que abrem nas mensagens mais novas (WhatsApp, Teams, Telegram), a rolagem automática percebe que já está no fim e **sobe** sozinha. No modo "Rolar eu mesmo", você pode rolar para cima, para baixo e voltar, e tudo é emendado no lugar certo. Isso resolve os casos em que a captura parava com uma tela só.
- **Botão direito no editor:** clique com o botão direito em qualquer ponto da imagem para colocar ali um **texto, seta apontando para o ponto, marca-texto, retângulo, círculo, número ou pixelado**. Num item já desenhado, o botão direito também oferece editar, duplicar, trazer para frente, enviar para trás e excluir.
- **Forçar atalho em uso:** se a combinação de teclas já for usada por outro programa, clique em **Forçar** nas Configurações para o Capturei passar a ter prioridade. No Print Screen, o atalho da Ferramenta de Captura do Windows é desligado. Dá para **Desfazer**, e o original volta.
- **Sobre:** novo botão **Indique para um amigo**, que copia o link e abre a página do Capturei, e link para o GitHub do desenvolvedor.
- Ao clicar em **Nova captura** no editor, as telas do editor abertas são minimizadas.

## 1.2.1

- **Nova captura a partir do editor:** ao clicar em **Nova captura** (ou `Ctrl+N`), as telas do editor abertas são minimizadas. Elas não ficam mais na frente nem aparecem na captura nova, e continuam na barra de tarefas para você voltar a elas quando quiser.

## 1.2.0

- **Barra de opções na seleção:** depois de escolher a região ou a janela, a seleção fica na tela com uma barra: **Capturar · Com rolagem · Copiar · Salvar · Editar**.
  - Dá para **ajustar a seleção** antes de capturar: arraste as alças para redimensionar, arraste por dentro para mover, ou use as setas do teclado (Alt + setas muda o tamanho).
  - Atalhos: `Enter` captura, `S` captura com rolagem, `Ctrl+C` copia, `Ctrl+S` salva, `E` abre no editor e `Esc` cancela. Duplo clique dentro da seleção também captura.
  - Prefere a captura instantânea? Desligue em **Configurações → Captura**.
- **Duas formas de captura com rolagem:**
  - **Rolagem auto** (`S`): o Capturei rola sozinho até o fim.
  - **Rolar eu mesmo** (`M`): você rola com a roda do mouse no seu ritmo e o Capturei vai juntando. `Enter` ou **Concluir** termina. Se rolar rápido demais, ele avisa para voltar um pouco.
  - O modo padrão (para o bloco "Com rolagem" e o atalho) fica em **Configurações → Captura**.
- **Captura com rolagem mais confiável:**
  - Funciona com a barra de rolagem dentro da área selecionada, que antes podia fazer a captura parar no meio. A barra é removida da imagem final.
  - O cursor sai de cima do conteúdo na hora de cada print, então destaques de "passar o mouse" (como no WhatsApp Web) não atrapalham mais.
  - Tolera pequenas animações e mudanças na tela.
  - Durante a captura, `Esc` e `Enter` ficam só com o Capturei. Antes, o Esc também chegava ao app; no WhatsApp Web, por exemplo, ele fechava a conversa.

## 1.1.0

- **Captura com rolagem:** selecione um bloco que tem barra de rolagem (página, conversa, lista, documento) e o Capturei rola sozinho, tira as telas em sequência e junta tudo numa imagem só, comprida, sem perder qualidade.
  - Cabeçalhos e rodapés fixos aparecem uma vez só, no lugar certo.
  - Para sozinho no fim do conteúdo, ou quando você aperta **Esc** ou clica em **Concluir**.
  - Novo modo **Com rolagem** na janela principal, atalho `Ctrl+Alt+Print Screen` (configurável) e tecla **S** para ativar durante a seleção normal.
- Janela de atualização: o texto da versão instalada não fica mais cortado.

## 1.0.1

- **Atualização automática:** o Capturei avisa quando sai uma versão nova e atualiza com um clique. O download é conferido (SHA-256) antes de instalar e suas configurações e capturas são mantidas.
- Botão **Procurar atualizações** na janela Sobre e no menu da bandeja.
- Opção para desligar a verificação automática em Configurações.
- Novo instalador em português, com termos de uso e desinstalação completa pelo Windows.
- Política de Privacidade atualizada para explicar a verificação de atualizações.

## 1.0.0

Primeira versão.

- Captura de **região ou janela**, **forma livre** (qualquer formato, com o fundo transparente), **tela inteira** e **monitor atual**.
- **Desenhar na tela:** congela a tela para você rabiscar, destacar e apontar antes de capturar.
- **Editor sem perda de qualidade:** setas (com ponta dupla), linhas, retângulos, círculos, desenho livre, marca-texto, texto, numeração de passos, pixelar e recortar.
- Todos os itens continuam editáveis: arraste as pontas da seta, redimensione formas pelas alças e troque cor, tamanho e preenchimento quando quiser.
- Cores personalizadas, desfazer/refazer ilimitado e zoom pixel a pixel.
- **Atalhos de teclado configuráveis** para cada tipo de captura.
- Funciona com vários monitores e escalas diferentes (125%, 150%…).
- 100% offline: nenhum dado sai do seu computador.
