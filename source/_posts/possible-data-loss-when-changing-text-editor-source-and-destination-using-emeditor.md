---
title: Possible Data Loss When Changing Text Editor Source & Destination - Using EmEditor
date: 2024-11-26T19:55:48.991Z
updated: 2024-11-30T19:34:31.319Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/d02f0d2061399f021d19d9bbfd673d9a86e50237396b8522657b45e5482dbe37.jpg
---

## Possible Data Loss When Changing Text Editor Source & Destination - Using EmEditor

Viewing 4 posts - 1 through 4 (of 4 total)

* Author  
Posts
* July 24, 2017 at 5:53 pm [#22100](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/50ed232c5aeade0aa4b1e48c684cf791?s=80&d=identicon&r=g)sky](https://www.emeditor.com/forums/users/s-k-y/ "View sky's profile")  
Participant  
Fresh EmEditor 17.0.0 portable, and also launch Chrome browser  
 1\. Type 12345679  
 2\. Press Ctrl + A (Select 12345679)  
 3\. Press and hold Left-Shift  
 4\. Press Left -> F8 -> Right -> F8 -> Left -> F8 -> Right -> F8 -> Left -> F8 -> Right -> F8  
 (Now, release Left-Shift, and it will select 456 only)  
 5\. Click menu Help – Keyboard map – Keyboard properties – Press New Shortcut Key text box  
 6\. Press Shift + F8  
 7\. Switch to Chrome browser, and back to EmEditor  
 8\. Repeat step.7 few times, it may cash.  
 Not always, but I can reproduce this crash many times.  
 \======================error log as below==============  
 \*\*\* Unhandled Exception!  
 ExpCode: 0x00000000C0000005  
 ExpFlags: 0  
 Version: 17.0.0 (64-bit)  
 Notes: Main ExceptionFilter  
SymInit: Symbol-SearchPath: ‘.’, symOptions: 530, UserName: ‘xxx’  
 OS-Version: 6.1.7601 (Service Pack 1) 0x100-0x1  
 xxx\\EmEditor.exe:EmEditor.exe (0000000140000000), size: 1847296 (result: 0), SymType: ‘-nosymbols-‘, PDB: ‘xxx\\EmEditor.exe’  
 C:\\Windows\\SYSTEM32\\ntdll.dll:ntdll.dll (0000000077150000), size: 1744896 (result: 0), SymType: ‘-exported-‘, PDB: ‘C:\\Windows\\SYSTEM32\\ntdll.dll’  
 C:\\Windows\\system32\\kernel32.dll:kernel32.dll (0000000077030000), size: 1175552 (result: 0), SymType: ‘-exported-‘, PDB: ‘C:\\Windows\\system32\\kernel32.dll’  
 C:\\Windows\\system32\\KERNELBASE.dll:KERNELBASE.dll (000007FEFD010000), size: 434176 (result: 0), SymType: ‘-exported-‘, PDB: ‘C:\\Windows\\system32\\KERNELBASE.dll’  
 C:\\Windows\\system32\\GDI32.dll:GDI32.dll (000007FEFD310000), size: 421888 (result: 0), SymType: ‘-exported-‘, PDB: ‘C:\\Windows\\system32\\GDI32.dll’ ……………  
July 25, 2017 at 3:57 am [#22101](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/50ed232c5aeade0aa4b1e48c684cf791?s=80&d=identicon&r=g)sky](https://www.emeditor.com/forums/users/s-k-y/ "View sky's profile")  
Participant  
After test several times again, step 1\~4 can be skipped.  
 Just need step 5\~8 to reproduce this crash.  
 Tested on Win 7 64 bit and Win 10 64 bit.  
July 25, 2017 at 5:44 pm [#22107](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/50ed232c5aeade0aa4b1e48c684cf791?s=80&d=identicon&r=g)sky](https://www.emeditor.com/forums/users/s-k-y/ "View sky's profile")  
Participant  
Finally, I found the simple duplicate method, please ignore above steps.  
1\. Launch EmEditor  
 2\. Click menu Help – Keyboard map – Keyboard properties  
 3\. Click on the any EmEditor edit area (outside of dialog box)  
 4\. Crash (100%)  
July 25, 2017 at 7:47 pm [#22108](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
I got it. This will be fixed on the next version.  
 Thanks!
* Author  
Posts

Viewing 4 posts - 1 through 4 (of 4 total)

* You must be logged in to reply to this topic.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-timed-success-organizing-video-conferences-via-slackplusfilmora/"><u>[New] 2024 Approved Timed Success Organizing Video Conferences via Slack+Filmora</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-2024-approved-unlocking-value-for-vendors-and-viewers-through-youtuber-sponsorship/"><u>[New] 2024 Approved Unlocking Value for Vendors and Viewers Through YouTuber Sponsorship</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-essential-tips-for-engaging-with-youtube-comments/"><u>[Updated] 2024 Approved Essential Tips for Engaging with YouTube Comments</u></a></li>
<li><a href="https://win-news.techidaily.com/erfolgreiche-tipps-zur-effizienten-synchronisation-ihrer-dateien-verwenden-sie-ein-synology-nas-auf-dem-windows-system/"><u>Erfolgreiche Tipps Zur Effizienten Synchronisation Ihrer Dateien: Verwenden Sie Ein Synology NAS Auf Dem Windows System</u></a></li>
<li><a href="https://win-news.techidaily.com/how-to-seamlessly-reinstate-your-files-using-cloud-storage-backups-a-compreh/"><u>How to Seamlessly Reinstate Your Files Using Cloud Storage Backups – A Compreh</u></a></li>
<li><a href="https://win-news.techidaily.com/il-top-choice-per-il-backup-locale-di-windows-11-sostituisci-dell-datasafe/"><u>Il Top Choice Per Il Backup Locale Di Windows 11: Sostituisci Dell DataSafe</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-navigating-average-incomes-in-the-podcasting-industry/"><u>In 2024, Navigating Average Incomes in the Podcasting Industry</u></a></li>
<li><a href="https://driver-install.techidaily.com/install-latest-gpu-drivers-for-pcs/"><u>Install Latest GPU Drivers for PCs</u></a></li>
<li><a href="https://win-news.techidaily.com/les-meilleurs-outils-pour-fabriquer-une-cle-usb-de-demarrage-avec-windows-11/"><u>Les Meilleurs Outils Pour Fabriquer Une Clé USB De Démarrage Avec Windows 11</u></a></li>
<li><a href="https://win-able.techidaily.com/masterclass-resolving-compatibility-issues-and-crashes-in-football-manager-2021-for-pc-users/"><u>Masterclass: Resolving Compatibility Issues and Crashes in Football Manager 2021 for PC Users</u></a></li>
<li><a href="https://win-news.techidaily.com/mastering-bi-directional-file-synchronization-on-windows-tips-and-techniques-from-vista-to-11/"><u>Mastering Bi-Directional File Synchronization on Windows: Tips and Techniques From Vista to 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/obs-versus-screensnapper/"><u>OBS Versus ScreenSnapper</u></a></li>
<li><a href="https://win-news.techidaily.com/recover-vanished-files-and-ink-incident/"><u>Recover, Vanished Files, and Ink Incident.</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repaired-inkjet-non-operational/"><u>Repaired Inkjet Non-Operational</u></a></li>
<li><a href="https://driver-download.techidaily.com/streamline-your-touch-experience-simple-guide-to-revamping-synaptics-ps2-drivers/"><u>Streamline Your Touch Experience: Simple Guide to Revamping Synaptics PS/2 Drivers</u></a></li>
<li><a href="https://win-news.techidaily.com/transferts-completes-de-fichiers-avec-xcopy-sur-systemes-windows-7-a-11-methode-resolue/"><u>Transferts Complètes De Fichiers Avec XCopy Sur Systèmes Windows 7 À 11 - Méthode Résolue</u></a></li>
<li><a href="https://win-news.techidaily.com/unlock-superior-computer-efficiency-comprehensive-step-by-step-tutorial-for-rebooting-your-asus-bios/"><u>Unlock Superior Computer Efficiency: Comprehensive Step-by-Step Tutorial for Rebooting Your ASUS BIOS</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

