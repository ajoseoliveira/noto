[Versão em português](INSTALAR.md)

# How to install Noto

This guide is for anyone who has never installed a program. Read it in order. It takes about five minutes.

Noto is a task notebook. It lives on your 64-bit Windows computer, and your tasks are saved only there. **The app's interface is in Brazilian Portuguese only**, so the names of buttons and menus below are quoted as they appear on screen.

## 1. Download the installer

Open the download page, <https://ajoseoliveira.github.io/noto/>, and click the download button. If the page does not open, the same file is at <https://github.com/ajoseoliveira/noto/releases/latest>, in the list of files of the newest version.

The file is called **Noto-Instalador** and ends in `.exe`. Your browser saves it in the **Downloads** folder.

While downloading, Chrome or Edge may show a warning that the file is not commonly downloaded. That is normal for a new program. Click the three dots next to the warning and then **Keep**. If another question appears, click **Keep anyway**.

**Want to check that it is the right file?** The page shows the checksum (SHA-256) of the installer, next to the button. In PowerShell, in the Downloads folder, the command below shows the checksum of the file you downloaded. If it matches the one on the page, the file is complete and is the same one that was published.

```text
Get-FileHash .\Noto-Instalador-*.exe -Algorithm SHA256
```

## 2. Install with two clicks

1. **Double-click** the **Noto-Instalador** file.
2. Windows will show a blue warning: **Windows protected your PC**. This is expected.
3. Click **More info**.
4. Click **Run anyway**.

That is all. There are no more questions: no folder, license or "next" screens. The installation takes a few seconds.

**Why does the warning appear?** Windows shows this warning for every program that does not have a paid company signature. Noto does not have one. The warning does not mean the file is dangerous: it only says that Windows does not know the program yet. To be sure the file is the one that was published, use the checksum from step 1.

If your antivirus blocks the file, or it disappears from the Downloads folder, **do not try again on your own**. Tell us what happened through the Issues (see step 8).

## 3. What happens next

Noto opens by itself. The first time, it shows a **short tutorial**. Read it at your own pace. You can use **Próximo** (next) and **Voltar** (back), or **Pular** (skip) to see it later.

To see the tutorial again, click **Ajustes**, the button with the gear icon at the bottom of the left sidebar. Choose **Ajuda e atalhos** and, there, **Ver o tutorial de novo** (the whole path is **Ajustes › Ajuda e atalhos › Ver o tutorial de novo**).

The AI is optional: Noto works fully without it. If you want to talk to Noto one day, the tutorial shows how to connect.

## 4. Where to find Noto afterwards

Noto creates two shortcuts named **Noto**:

- on the **Desktop** (the home screen of the computer);
- in the **Start menu** (the Windows button at the bottom). Type "Noto" to find it faster.

## 5. Closing the window does not close Noto

When you close the Noto window, it **keeps running near the clock**. This is on purpose: it lets Noto remind you at the right time.

The Noto icon sits in the taskbar, near the clock. Sometimes it hides behind the little arrow **^**. Click the arrow to see it.

To **really quit**, right-click the Noto icon and choose **Sair do Noto**.

## 6. How to update

Noto tells you, in Portuguese, when there is a new version. The notice has two buttons:

- **Atualizar agora** (update now): Noto downloads the new version, closes carefully and opens already updated. All your tasks are still there.
- **Depois** (later): the notice goes away for now and comes back later. Nothing is lost.

Noto **never downloads or installs anything until you ask**.

If you installed Noto before, download this version once; from now on Noto tells you when a new version is available.

To update by hand, download the new installer (step 1) and double-click it. **You do not need to uninstall the old one.**

## 7. Which version you have and how to uninstall

**To see the version:** open Noto, click **Ajustes** (the gear, at the bottom of the left sidebar) and choose **Ajuda e atalhos**. There you will see **Versão** and a number.

**To uninstall:**

1. Open the Start menu and type **Installed apps**. On Windows 10, the name is **Apps & features**. On a Windows set to Portuguese they are called **Aplicativos instalados** and **Aplicativos e recursos**.
2. Open it and look for **Noto** in the list.
3. Click the three dots next to it (on Windows 10, click Noto) and then **Uninstall**.

Uninstalling removes the program and the shortcuts, but it **does not delete your tasks**. If you install again, they will be there.

## 8. If something goes wrong

Tell us through the Issues: <https://github.com/ajoseoliveira/noto/issues>. Say:

- **which version** of Noto you have (see step 7), if it managed to open;
- **what appeared on screen**: a screenshot helps. If you can, also tell us what you had just clicked.

Issues are public, so check that your screenshot shows nothing personal before sending it.

You do not need to understand the problem. Just telling us what you saw already helps a lot.
