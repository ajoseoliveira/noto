[English version](INSTALL.md)

# Como instalar o Noto

Este guia é para quem nunca instalou um programa. Leia na ordem. Leva uns cinco minutos.

O Noto é um caderno de tarefas. Ele fica no seu computador com Windows de 64 bits, e as suas tarefas ficam guardadas só nele.

## 1. Baixe o instalador

Abra a página de download, <https://ajoseoliveira.github.io/noto/>, e clique no botão de baixar. Se a página não abrir, o mesmo arquivo está em <https://github.com/ajoseoliveira/noto/releases/latest>, na lista de arquivos da versão mais nova.

O arquivo se chama **Noto-Instalador** e termina em `.exe`. O navegador o guarda na pasta **Downloads**.

Ao baixar, o Chrome ou o Edge podem mostrar um aviso dizendo que o arquivo não é baixado com frequência. É normal para um programa novo. Clique nos três pontinhos ao lado do aviso e em **Manter**. Se aparecer outra pergunta, clique em **Manter assim mesmo**.

**Quer conferir que o arquivo é o certo?** A página mostra a soma de verificação (SHA-256) do instalador, ao lado do botão. No PowerShell, na pasta Downloads, o comando abaixo mostra a soma do arquivo que você baixou. Se for igual à da página, o arquivo está inteiro e é o mesmo que foi publicado.

```text
Get-FileHash .\Noto-Instalador-*.exe -Algorithm SHA256
```

## 2. Instale com dois cliques

1. Dê **dois cliques** no arquivo **Noto-Instalador**.
2. O Windows vai mostrar um aviso azul: **O Windows protegeu o computador**. Isso é esperado.
3. Clique em **Mais informações**.
4. Clique em **Executar assim mesmo**.

Pronto. Não há mais perguntas: nada de pasta, licença ou "próximo". A instalação leva alguns segundos.

**Por que o aviso aparece?** O Windows mostra esse aviso para todo programa que não tem uma assinatura paga de empresa. O Noto não tem essa assinatura. O aviso não quer dizer que o arquivo é perigoso: ele só diz que o Windows ainda não conhece o programa. Para ter certeza de que o arquivo é o que foi publicado, use a soma de verificação do item 1.

Se o antivírus bloquear o arquivo, ou ele sumir da pasta Downloads, **não tente de novo por conta própria**. Conte o que aconteceu pelos Issues (veja o item 8).

## 3. O que acontece depois

O Noto abre sozinho. Na primeira vez, ele mostra um **tutorial curto**. Leia no seu ritmo. Você pode usar **Próximo** e **Voltar**, ou **Pular** para ver depois.

Se quiser ver o tutorial outra vez, clique em **Ajustes**, o botão com a engrenagem, embaixo da barra do lado esquerdo. Escolha **Ajuda e atalhos** e, ali, **Ver o tutorial de novo** (o caminho todo é **Ajustes › Ajuda e atalhos › Ver o tutorial de novo**).

A IA é opcional: o Noto funciona inteiro sem ela. Se um dia quiser conversar com o Noto, o tutorial mostra como conectar.

## 4. Onde achar o Noto depois

O Noto cria dois atalhos com o nome **Noto**:

- na **Área de Trabalho** (a tela inicial do computador);
- no **menu Iniciar** (o botão do Windows, no canto de baixo). Digite "Noto" para achar mais rápido.

## 5. Fechar a janela não fecha o Noto

Quando você fecha a janela do Noto, ele **continua aberto perto do relógio**. É de propósito: assim ele consegue avisar os seus lembretes na hora marcada.

O ícone do Noto fica na barra de tarefas, perto do relógio. Às vezes ele fica escondido atrás da setinha **^**. Clique na setinha para ver.

Para **sair de verdade**, clique com o **botão direito** no ícone do Noto e escolha **Sair do Noto**.

## 6. Como atualizar

O Noto avisa, em português, quando há uma versão nova. O aviso tem dois botões:

- **Atualizar agora:** o Noto baixa a versão nova, fecha com cuidado e abre já atualizado. Suas tarefas continuam todas lá.
- **Depois:** o aviso some por agora e volta mais tarde. Nada se perde.

O Noto **nunca baixa nem instala nada sem você pedir**.

Se você instalou o Noto antes, baixe esta versão uma vez; daqui em diante o Noto avisa quando houver versão nova.

Para atualizar à mão, basta baixar o instalador novo (item 1) e dar dois cliques nele. **Não precisa desinstalar o antigo.**

## 7. Qual é a versão e como desinstalar

**Para saber a versão:** abra o Noto, clique em **Ajustes** (a engrenagem, embaixo da barra do lado esquerdo) e escolha **Ajuda e atalhos**. Ali aparece **Versão** e um número.

**Para desinstalar:**

1. Abra o menu Iniciar e digite **Aplicativos instalados**. No Windows 10, o nome é **Aplicativos e recursos**.
2. Abra e procure **Noto** na lista.
3. Clique nos três pontinhos ao lado (no Windows 10, clique no Noto) e em **Desinstalar**.

Desinstalar remove o programa e os atalhos, mas **não apaga as suas tarefas**. Se instalar de novo, elas estarão lá.

## 8. Se algo der errado

Conte pelos Issues: <https://github.com/ajoseoliveira/noto/issues>. Diga:

- **qual é a versão** do Noto (veja o item 7), se ele chegou a abrir;
- **o que apareceu na tela**: um print ajuda. Se puder, conte também o que você tinha acabado de clicar.

Os Issues são públicos, então confira que o print não mostra nada pessoal antes de enviar.

Não precisa entender o problema. Só contar o que viu já ajuda muito.
