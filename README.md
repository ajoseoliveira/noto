[English version](README.en.md)

# Noto

O Noto é um caderno de tarefas inteligente para Windows. Ele junta tarefas, lembretes, metas, rotinas, agenda e notas num só lugar, para quem quer organizar o dia e a cabeça sem abrir conta em lugar nenhum. Tudo fica salvo no seu computador.

## Como baixar

- **Página de download:** <https://ajoseoliveira.github.io/noto/>
- **Se a página não abrir:** <https://github.com/ajoseoliveira/noto/releases/latest>

O Noto é para Windows de 64 bits. Baixe o instalador e dê dois cliques.

O Windows pode mostrar um aviso azul, **O Windows protegeu o computador**. Ele aparece para programas que ainda não têm uma assinatura paga de empresa, e o Noto não tem. Para seguir, clique em **Mais informações** e depois em **Executar assim mesmo**. O passo a passo, com a explicação, está em [INSTALAR.md](INSTALAR.md).

Se você instalou o Noto antes, baixe esta versão uma vez; daqui em diante o Noto avisa quando houver versão nova.

## O que o Noto faz

### Tarefas e visões

- **Visões:** Hoje (com as atrasadas e o plano do dia), Entrada (tarefas sem projeto e sem data), Em breve (a partir de amanhã: 7 dias e "Mais adiante"), Concluídas, Projetos, Etiquetas e Busca (ignora acentos).
- **Hoje já traz o plano do dia**, sem IA e sem botão: o cartão **Comece por** mostra a próxima tarefa, com o motivo; abaixo ficam **Atrasadas**, **Com hora** (tarefas e compromissos, com a linha "agora") e **Depois, nesta ordem**. **Reordenar** mostra **Subir** e **Descer** em cada tarefa, e **Voltar à ordem sugerida** desfaz a sua escolha.
- **Adição rápida** (tecla `Q`), com linguagem natural em português:
  `Pagar conta amanhã às 10h p1 #Pessoal @casa`
  - Datas: `hoje`, `amanhã`, `depois de amanhã`, `sexta`, `próxima semana`, `20/11`, `25 de dezembro`, `dia 5`, `em 3 dias`.
  - Hora: `às 15h`, `15:30`, `ao meio-dia`.
  - Repetição: `todo dia`, `toda segunda`, `toda semana`, `todo mês`, `todo ano`, `a cada 2 semanas`.
  - `p1` a `p4` é a prioridade, `#Projeto` é um projeto que já existe e `@etiqueta` é uma etiqueta.
- **Tarefas:** descrição, data e hora, repetição, prioridade P1 a P4, etiquetas, subtarefas e mudança de projeto.
- **Concluir com Desfazer.** Uma tarefa que se repete pula para a próxima data.
- **Projetos:** criar, renomear, escolher a cor e excluir (com Desfazer).
- **Tema** claro, escuro ou o do Windows, e layout que se ajusta a janelas estreitas.

### Lembretes e atalho global

- **Lembrete por tarefa com hora:** "Na hora" é o padrão. No painel da tarefa dá para escolher 5, 10 ou 30 minutos antes, 1 hora antes, 1 dia antes ou "Sem lembrete".
- **Compromissos da agenda** avisam 10 minutos antes.
- O aviso chega como **notificação do Windows** (clicar abre a tarefa) e como **cartão no canto do Noto**, com **Concluir**, **Abrir** e **Adiar** (10 minutos, 1 hora ou amanhã às 9h).
- Um lembrete perdido, com o Noto fechado ou o computador suspenso, aparece quando você volta, se tiver até 2 horas.
- **Bandeja:** fechar a janela esconde o Noto, que continua perto do relógio para avisar. Para sair de verdade, clique com o botão direito no ícone e escolha **Sair do Noto**.
- **`Ctrl+Alt+N`** abre a Adição rápida de qualquer programa.

### Modo Foco e Progresso

- **Focar nesta:** botão no painel da tarefa e ícone de relógio que aparece ao passar o mouse na linha. Na tela **Progresso** dá para começar um **foco livre**, sem tarefa.
- **Pomodoro:** 25 minutos de foco, 5 de pausa curta e 15 de pausa longa a cada 4 focos. A pausa começa sozinha; o próximo foco espera o seu clique.
- **Barra de foco:** mostra a fase, a rodada, o tempo e a tarefa, com Pausar/Continuar, Pular e Parar. O tempo também aparece no título da janela.
- O fim de cada fase avisa com uma notificação do Windows e um aviso no Noto. O cronômetro continua certo com a janela escondida ou o computador suspenso.
- Os minutos de foco ficam guardados por tarefa. O painel mostra, por exemplo, "Foco: 50 min no total · 25 min hoje".
- **Progresso** (barra lateral) mostra os dias seguidos concluindo algo, com o recorde; as tarefas concluídas e o foco de hoje e dos últimos 7 dias; um gráfico dos últimos 7 dias; e as tarefas com mais foco na semana.
- O histórico de conclusões fica guardado à parte: tarefas que se repetem contam, reabrir desconta e excluir uma tarefa não apaga o histórico. Ele fica guardado por 2 anos.

### Inteligência artificial (opcional)

O Noto funciona inteiro sem IA. Se quiser conversar com ele, vá em **Ajustes › Inteligência**, escolha o provedor e conecte.

| Provedor | Custo | Como conecta |
|---|---|---|
| **Claude** (Anthropic) | Pago, o mais capaz | Chave de API |
| **ChatGPT** (OpenAI) | Pelo seu plano | Login na sua conta |
| **Groq** | Grátis, com limite por minuto e por dia | Chave de API |
| **Gemini** (Google AI Studio) | Grátis, com limite por minuto e por dia | Chave de API |

- **Troca automática:** com as chaves do Groq e do Gemini salvas, se o provedor em uso bater no limite grátis, o Noto usa o outro e avisa. Ele nunca passa sozinho para um provedor pago.
- **Gemini grátis:** pela página de preços do Google, o conteúdo enviado no plano grátis é usado para melhorar os produtos do Google. O Noto avisa isso na tela.
- Os modelos grátis são mais simples que os pagos. Para pedidos com várias ações, os pagos acertam mais.
- **Falar com o Noto** (botão na barra lateral ou tecla `K`) é uma conversa em português. Peça, responda às perguntas do agente e peça ajustes; ele mostra o que mudou, com Desfazer. Exemplos:
  - "joga tudo de hoje para amanhã"
  - "cria 3 tarefas para a mudança"
  - "conclui a do banco"
  - "a do relatório é P1"
- **Pedidos que não usam a IA** (rápidos e sem custo): "cria/anota/me lembra de … amanhã às 15h", "o que faço primeiro?" e "lembre que …".
- **Ordenar com a IA** (em Hoje, com uma IA conectada) grava a ordem do dia e mostra o motivo de cada tarefa; **Desfazer** volta à ordem de antes. O plano de Hoje funciona sem IA.
- **Quebrar em subtarefas com IA** (painel da tarefa) sugere passos, e você escolhe quais adicionar.
- **Memória:** "lembre que a reunião de equipe é toda segunda". A IA usa esses fatos, e dá para ver e apagar cada um nos Ajustes.

### O agente do Noto

Por trás do Falar com o Noto há um agente com arquivos próprios, que você pode ler e editar em **Ajustes › Avançado**:

| Arquivo | O que é |
|---|---|
| `prompt.md` | O que o agente é e como trabalha |
| `alma.md` | Personalidade: tom, jeito de cobrar, o que evita |
| `memoria.md` | Fatos sobre você, um por linha. "Lembre que…" grava aqui |
| `config.json` | Modo, integrações e horários da iniciativa |
| `skills/*.md` | Uma habilidade por arquivo, com nome, descrição, quando usar e o passo a passo |

- **Dois modos**, que você escolhe em **Ajustes › Como o Noto age** e também no topo da conversa:
  - **Propõe e eu aprovo** (o padrão): o agente monta tudo num plano; você revisa e escolhe **Aplicar o plano** ou **Descartar o plano**.
  - **Faz e me avisa:** faz na hora e mostra o que fez, com Desfazer.
- **Habilidades que já vêm prontas:** organizar atrasadas, montar o dia, planejar a semana, o mês e o trimestre, e revisar a semana, o mês e o trimestre.
- **O agente te procura:** em quatro momentos (bom dia, atrasadas, revisão da semana e revisão do mês e do trimestre) o agente começa a conversa sozinho, com uma notificação do Windows. Você liga, desliga e muda os horários em **Ajustes › Lembretes**. A mensagem é montada no próprio Noto, então funciona sem internet e não gasta a cota grátis; nada sai do computador até você responder.
- **Abrir com o Windows** (desligado por padrão): o Noto abre escondido na bandeja quando o Windows liga.

### Conversa de planejamento

- **É uma conversa:** cada mensagem leva as anteriores. O agente pode perguntar o que falta ("qual o objetivo da semana?") e você responde; "sim", "pode" e "troca para quinta" funcionam como resposta.
- **Fechar e abrir** o Falar com o Noto mantém a conversa; **Nova conversa** começa outra.
- **No modo "Propõe e eu aprovo"**, tudo o que o agente cria ou muda vai para um **plano**, que cresce ao longo da conversa. Nada muda nas suas listas até você aplicar.
  - O plano mostra metas, tarefas novas por dia, mudanças no que já existe e memória. Cada item tem uma caixa; desmarque o que não quer.
  - Para ajustar, peça na conversa ("tira a de sexta", "passa a de publicar para amanhã").
  - **Aplicar o plano** aplica só o que está marcado, com **Desfazer**. **Descartar o plano** não muda nada.
- **No modo "Faz e me avisa"**, cada mensagem age na hora. **Desfazer tudo o que o agente fez nesta conversa** volta a antes da primeira mudança.

### Metas

- A tela **Metas** (barra lateral) mostra o trimestre, com as metas de cada mês embaixo e as de cada semana embaixo delas. **Nova meta** cria uma.
- **Uma meta tem:** nome, nível (trimestre, mês ou semana), período, meta mãe (a do nível acima), indicador opcional ("3 de 10 clientes") e situação (ativa, concluída ou abandonada).
- **Progresso**, sempre em barra e em texto:
  - com indicador, é o feito dividido pelo alvo;
  - sem indicador, é a média das tarefas ligadas e das metas filhas (as abandonadas não contam);
  - uma tarefa que se repete conta se foi concluída dentro do período.
- **Tarefas ligadas:** pelo campo **Meta** nos detalhes da tarefa ou pelo painel da meta.
- **Excluir uma meta** mantém as tarefas e as metas filhas, com Desfazer.
- **Com o agente:** "planeje minha semana", "planeje o mês" e "planeje o trimestre" criam metas ligadas e tarefas com data; "fechei mais 2 clientes" atualiza o indicador.

### Rotinas e voz

- **Rotinas**, por exemplo "Bom dia" ou "Modo estudo": uma lista de tarefas, uma por linha, no formato da Adição rápida ("Revisar e-mails às 9h p2 #Trabalho"), com a opção de mostrar o plano em Hoje e começar um foco.
- **Como começar uma rotina:** pelo menu **Rotinas**, em Hoje, ou escrevendo o nome dela no Falar com o Noto ("bom dia"), sem IA. Ela cria as tarefas para hoje sem repetir as que já existem, com Desfazer.
- **Ditar por voz:** o botão de microfone abre a digitação por voz do Windows (`Win+H`) no campo. Não precisa de chave de IA; na primeira vez, o Windows pede um clique no microfone. O ditado usa os serviços de fala da Microsoft.

### Google Agenda

Em **Ajustes › Agenda**, cole o **"Endereço secreto no formato iCal"** da sua agenda. Para achá-lo: Google Agenda no computador, Configurações, clique na agenda e **Integrar agenda**.

- Só leitura: o Noto não altera nada no Google e não pede login.
- Dá para conectar várias agendas (pessoal, trabalho, compartilhadas, feriados), cada uma com nome e cor.
- Os compromissos aparecem em Hoje e Em breve, junto das tarefas.
- Atualiza ao abrir, a cada 15 minutos e quando o computador volta da suspensão. Sem internet, mostra a última cópia.
- O endereço fica criptografado com a sua conta do Windows.
- Entende eventos que se repetem (diário, semanal, mensal, anual), exceções, horários alterados e fusos.

### Cérebro (notas)

O **Cérebro** é o caderno de notas do Noto. As notas são arquivos de texto comuns (Markdown) na pasta de dados do Noto, e você pode abri-los em qualquer outro programa.

- **Editor.** O texto aparece formatado enquanto você escreve (títulos, negrito, itálico, listas, citações e código). Os símbolos do Markdown só aparecem na linha do cursor. `- [ ]` vira uma caixa: clique nela ou use `Ctrl+Enter` na linha. As notas salvam sozinhas depois de uma pausa curta, o indicador mostra **Salvando…**, **Salvo** ou **Não salvo**, e `Ctrl+S` salva na hora.
- **Links e tags.** Digite `[[` para escolher uma nota pelo nome, sem se preocupar com acentos. Um link para uma nota que ainda não existe aparece tracejado, e o clique oferece criá-la. Escreva `#tag` no texto para marcar a nota; a navegação conta as notas de cada tag e filtra pelo clique.
- **Conexões.** O botão **Conexões** mostra o mapa das suas notas: as ligadas ficam perto, e os grupos sem ligação se separam. Dá para arrastar um nó, usar o zoom e **Centralizar mapa**. As opções de mostrar ou ocultar as páginas do dia e as notas soltas ficam salvas, e **Ver como lista** mostra as mesmas notas em ordem, para usar pelo teclado. A nota aberta mostra quem liga para ela, os links dela, as tags e o grafo local.
- **Falar com o Noto no Cérebro.** O botão **Falar com o Noto** abre uma conversa ao lado da nota. Conte o que está pensando ou peça para organizar a nota aberta: o Noto propõe notas novas, ligações com o motivo, entradas nos mapas e tarefas. Nada muda antes de você aprovar o plano, e **Desfazer** tira o que entrou. O texto que você escreveu nunca é apagado nem reescrito: o Noto só acrescenta no fim.
- **Só IA paga e `#privado`.** A conversa do Cérebro só envia texto para o Claude (chave de API) ou o ChatGPT (login). Com Groq, Gemini ou sem IA, nada sai do computador. Uma nota com a tag `#privado` nunca vai para a IA.
- No menu do Cérebro ficam **Abrir pasta**, que mostra os arquivos das notas, e **Exportar cópia das notas**, que leva as notas a uma nova pasta.

### Atalhos

| Tecla | Ação |
|---|---|
| `Q` | Adicionar uma tarefa |
| `K` | Falar com o Noto |
| `/` | Buscar tarefas |
| `Esc` | Fechar o painel da tarefa ou a janela aberta |
| `Ctrl+N` | Começar uma conversa nova, na tela da conversa |
| `Ctrl+=` e `Ctrl+−` | Aumentar e diminuir o zoom (`Ctrl+0` volta ao normal) |
| `Ctrl+Alt+N` | Adicionar uma tarefa de qualquer programa, mesmo com o Noto fechado na bandeja |
| `Ctrl+S` | Salvar agora, numa nota ou num arquivo do agente |
| `Ctrl+Enter` | Marcar a tarefa da linha, numa nota |
| `Alt+Enter` | Abrir o link sob o cursor, numa nota |

## Seus dados e as cópias de segurança

- **Arquivo próprio:** as tarefas, projetos, etiquetas, metas, rotinas e históricos ficam num arquivo na pasta de dados do Noto (`%APPDATA%\Noto`), gravado a cada mudança. A gravação é segura: escreve num temporário, força o disco e só então troca, então o arquivo nunca fica pela metade.
- **Reserva:** a janela também guarda uma cópia no armazenamento interno dela.
- **Cópia por dia:** na primeira mudança de cada dia, a versão anterior vai para uma pasta de cópias. Ficam as 7 mais recentes.
- **Restaurar:** em **Ajustes › Dados e cópias**. A tela lista as cópias, com **Restaurar** (dá para desfazer) e **Abrir a pasta**.
- **Arquivo estragado:** se o arquivo de dados não puder ser lido ao abrir, o Noto o guarda à parte, abre a versão mais nova entre a cópia do dia e a reserva, e avisa.
- **Desinstalar não apaga as suas tarefas.**

## Privacidade

- **Não há conta nem servidor do Noto.** Seus dados ficam no seu computador.
- **IA:** o que você escreve só sai do computador quando você usa a IA, e vai para o provedor que você escolheu. Estão junto o seu pedido, as tarefas abertas, os projetos, a memória e os compromissos de hoje. As chaves ficam criptografadas com a sua conta do Windows.
- **Google Agenda:** só leitura, pelo endereço secreto que você colou.
- **Atualização:** o Noto consulta o GitHub para saber se há uma versão nova. Nada do que você escreve vai junto nessa consulta.
- **Ditado por voz:** usa os serviços de fala da Microsoft, pelo Windows.

## Atualização

Quando há uma versão nova, o Noto avisa, em português, com dois botões: **Atualizar agora** e **Depois**. **Depois** adia o aviso sem perder nada, e ele volta mais tarde. O Noto **nunca baixa nem instala nada sem você pedir**. Sem internet, ele funciona como sempre e não mostra erro.

## Licença

Você pode baixar e usar o Noto de graça. Não pode copiar, modificar, revender nem redistribuir o app ou o código.

Todos os direitos reservados. O texto completo está em [LICENSE](LICENSE), e os avisos das bibliotecas e da fonte que o Noto usa estão em [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).

## Encontrou um problema?

Conte pelos [Issues](https://github.com/ajoseoliveira/noto/issues), com a versão do Noto e o que apareceu na tela.
