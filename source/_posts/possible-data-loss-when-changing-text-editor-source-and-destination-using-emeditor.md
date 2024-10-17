---
title: Possible Data Loss When Changing Text Editor Source & Destination - Using EmEditor
date: 2024-10-13T01:48:52.613Z
updated: 2024-10-16T20:37:25.020Z
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
<li><a href="https://extra-guidance.techidaily.com/new-securing-smooth-iphone-video-playback-top-three-strategies/"><u>[New] Securing Smooth iPhone Video Playback Top Three Strategies</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-versatile-biz-decks-free-template-and-resource-options/"><u>[New] Versatile Biz Decks FREE Template and Resource Options</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-android-freedom-the-most-popular-top-10-fb-video-extraction-tools/"><u>[Updated] In 2024, Android Freedom The Most Popular Top 10 FB Video Extraction Tools</u></a></li>
<li><a href="https://technical-tips.techidaily.com/a-step-by-step-journey-through-the-how-to-train-your-dragon-films/"><u>A Step-by-Step Journey Through the How to Train Your Dragon Films</u></a></li>
<li><a href="https://hardware-help.techidaily.com/dont-waste-money-on-high-end-models-choose-a-top-rated-affordable-android-smartphone/"><u>Don't Waste Money on High-End Models – Choose a Top-Rated Affordable Android Smartphone</u></a></li>
<li><a href="https://win-news.techidaily.com/error-code-0x80070003-in-windows-10-troubleshooting-guide-discover-five-effective-solutions/"><u>Error Code 0X80070003 in Windows 10 Troubleshooting Guide - Discover Five Effective Solutions</u></a></li>
<li><a href="https://win-news.techidaily.com/fixing-the-issue-discover-how-to-resolve-ssd-detection-problems-in-your-systems-bios/"><u>Fixing the Issue: Discover How to Resolve SSD Detection Problems in Your System's BIOS</u></a></li>
<li><a href="https://win-news.techidaily.com/renaming-and-saving-your-file-a-step-by-step-guide-using-emeditors-features/"><u>Renaming & Saving Your File: A Step-by-Step Guide Using EmEditor's Features</u></a></li>
<li><a href="https://win-news.techidaily.com/snelheid-van-de-herstelproces-van-een-verloren-partitiedata-op-externe-harde-schijven-seo-optimiseerd/"><u>Snelheid Van De Herstelproces Van Een Verloren Partitiedata Op Externe Harde Schijven - SEO-Optimiseerd</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-perfect-pathway-insta-to-tiktok-junction-for-2024/"><u>The Perfect Pathway Insta to TikTok Junction for 2024</u></a></li>
<li><a href="https://win-news.techidaily.com/transfert-zero-defaillance-des-donnees-clonage-dun-ssd-nvme-a-laide-de-clonezilla/"><u>Transfert Zéro Défaillance Des Données: Clonage D'un SSD NVMe À L'aide De Clonezilla</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlock-your-motorola-moto-g13s-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>Unlock Your Motorola Moto G13s Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-text-to-audio-conversion-from-words-to-mp3-across-all-devices/"><u>Updated 2024 Approved Text-to-Audio Conversion From Words to MP3 Across All Devices</u></a></li>
<li><a href="https://win-news.techidaily.com/windows-1011-recovery-drive/"><u>Windows 10/11 における Recovery Drive の作り方</u></a></li>
<li><a href="https://win-news.techidaily.com/icloud2/"><u>いとも簡単!iCloudメールをバックアップする軽やかな2方法</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052060/7443" target="_top" id="2052060">
  <img src="//a.impactradius-go.com/display-ad/7443-2052060" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052060/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

