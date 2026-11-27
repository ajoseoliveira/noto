[Versão em português](README.md)

# Noto

Noto is a smart task notebook for Windows. It brings tasks, reminders, goals, routines, your calendar and notes into one place, for people who want to organize their day and their thoughts without creating an account anywhere. Everything is saved on your own computer.

**The app's interface is in Brazilian Portuguese only.** This page describes it in English, and the screen names below appear as they do in the app.

## How to download

- **Download page:** <https://ajoseoliveira.github.io/noto/>
- **If the page does not open:** <https://github.com/ajoseoliveira/noto/releases/latest>

Noto is for 64-bit Windows. Download the installer and double-click it.

Windows may show a blue warning, **Windows protected your PC** (SmartScreen). It appears for programs that do not have a paid company signature yet, and Noto does not have one. To go on, click **More info** and then **Run anyway**. Step by step, with an explanation, in [INSTALL.md](INSTALL.md).

If you installed Noto before, download this version once; from now on Noto tells you when a new version is available.

## What Noto does

The names in quotes are the ones you will see on screen.

- **Tasks and views:** "Hoje" (today, with overdue tasks), "Entrada" (inbox: tasks with no project and no date), "Em breve" (upcoming, starting tomorrow), "Concluídas" (completed), projects, labels and search. Tasks have a description, date and time, repetition, priority, labels and subtasks.
- **Your plan for the day, inside "Hoje":** a "Comece por" card (start with) shows the next task, followed by "Atrasadas" (overdue), "Com hora" (timed, with a line marking "agora", now) and "Depois, nesta ordem" (then, in this order). "Reordenar" lets you move tasks up or down, and "Voltar à ordem sugerida" restores the suggested order. With an AI connected, "Ordenar com a IA" sets the order, explains each choice and can be undone with "Desfazer". Without AI, the plan still works.
- **Quick add** (key `Q`): type a task in natural language, in Portuguese, such as `Pagar conta amanhã às 10h p1 #Pessoal @casa`, and Noto reads the date, time, repetition, priority, project and label.
- **Reminders:** Windows notifications and an on-screen card with options to complete, open or snooze. Noto stays near the clock when you close the window, so it can remind you on time. To really quit, right-click its icon and choose **Sair do Noto**.
- **Focus mode** ("Modo Foco") and **Progress** ("Progresso"): a Pomodoro timer per task, and a screen with your streak of days, what you completed and the focus time of the week.
- **Goals** ("Metas"): quarter, month and week goals, linked to each other and to your tasks, with progress.
- **Routines** ("Rotinas"): lists of tasks you start in one click, such as a morning routine. Voice dictation uses the Windows voice typing (`Win+H`).
- **Calendar:** you can paste the secret iCal address of your Google Calendar to see your events next to your tasks. It is read-only: Noto never changes anything in Google.
- **Smart assistant (optional):** "Falar com o Noto" (key `K`) is a conversation where you ask Noto to create, move, complete or plan tasks and goals. It works with Claude, ChatGPT, Groq or Gemini. By default Noto proposes a plan and only applies it when you approve, with an Undo. Noto works fully without any AI.
- **Cérebro:** a notebook of notes stored as plain Markdown files, with live formatting, links between notes with `[[ ]]`, tags with `#tag`, and a map of the connections between your notes.
- **Backups:** every day, Noto keeps a copy of your data and lets you restore it in "Ajustes › Dados e cópias".

## Your data and privacy

- **There is no Noto account and no Noto server.** Your tasks, notes and settings are saved on your computer, in the Noto data folder, and uninstalling Noto does not delete them.
- **AI:** what you write leaves your computer only when you use the AI, and it goes to the provider you chose. API keys are encrypted with your Windows account.
- **Google Calendar:** read-only, through the secret address you pasted.
- **Updates:** Noto checks GitHub to find out whether there is a new version. Nothing you write is sent with that check.
- **Voice dictation:** uses the Microsoft speech services, through Windows.

## Updates

When there is a new version, Noto tells you, in Portuguese, with two buttons: **Atualizar agora** (update now) and **Depois** (later). **Depois** postpones the notice without losing anything, and it comes back later. Noto **never downloads or installs anything until you ask**. Without internet, it works as usual and shows no error.

## License

You may download and use Noto free of charge. You may not copy, modify, resell or redistribute the app or its code.

All rights reserved. The full text is in [LICENSE](LICENSE), and the notices for the libraries and the font Noto uses are in [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).

## Found a problem?

Tell us through the [Issues](https://github.com/ajoseoliveira/noto/issues), with the Noto version and what appeared on screen.
