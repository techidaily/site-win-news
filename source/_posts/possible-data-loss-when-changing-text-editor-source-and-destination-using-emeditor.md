---
title: Possible Data Loss When Changing Text Editor Source & Destination - Using EmEditor
date: 2024-10-05T16:39:04.615Z
updated: 2024-10-10T18:21:33.816Z
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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-in-depth-app-investigation-via-az-screen-recorder/"><u>[New] 2024 Approved In-Depth App Investigation via AZ Screen Recorder</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-a-decade-in-review-top-8-free-online-srt-translators/"><u>[Updated] A Decade in Review Top 8 Free Online SRT Translators</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-live-action-top-9-gaming-portals/"><u>[Updated] In 2024, Live Action Top 9 Gaming Portals</u></a></li>
<li><a href="https://some-approaches.techidaily.com/convertir-mp4-sin-costo-a-mjpeg-usando-la-herramienta-en-linea-de-movavi/"><u>Convertir MP4 Sin Costo a MJPEG Usando La Herramienta en Línea De Movavi</u></a></li>
<li><a href="https://win-news.techidaily.com/exploring-the-versatility-of-flipped-images-how-many-orientation-options-on-flipbuildercom/"><u>Exploring the Versatility of Flipped Images: How Many Orientation Options on FlipBuilder.com?</u></a></li>
<li><a href="https://win-news.techidaily.com/how-to-change-your-preferred-language-on-flipbuilder-understanding-the-menu-bar-settings/"><u>How to Change Your Preferred Language on FlipBuilder: Understanding the Menu Bar Settings</u></a></li>
<li><a href="https://win-news.techidaily.com/how-to-convert-rtf-documents-to-pdf-on-flipbuildercom-a-simple-guide/"><u>How to Convert RTF Documents to PDF on FlipBuilder.com: A Simple Guide</u></a></li>
<li><a href="https://win-news.techidaily.com/how-to-convert-word-files-into-engaging-digital-magazines-using-flipbook-creator-online/"><u>How to Convert Word Files Into Engaging Digital Magazines Using FlipBook Creator Online</u></a></li>
<li><a href="https://win-news.techidaily.com/how-to-embed-a-minute-logo-in-your-browsers-status-bar-with-flipbuilder/"><u>How to Embed a Minute Logo in Your Browser's Status Bar with FlipBuilder</u></a></li>
<li><a href="https://win-news.techidaily.com/how-to-self-design-your-own-book-theme-using-flipbuilders-tools/"><u>How to Self-Design Your Own Book Theme Using FlipBuilder's Tools</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-a-straightforward-path-to-turn-off-igtv/"><u>In 2024, A Straightforward Path to Turn Off IGTV</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-expert-tips-for-precise-control-with-xbox-zoom/"><u>In 2024, Expert Tips for Precise Control with Xbox Zoom</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-art-of-virtual-environments-in-cinema/"><u>In 2024, The Art of Virtual Environments in Cinema</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-unlock-your-marketing-potential-with-our-50plus-free-youtube-banners/"><u>In 2024, Unlock Your Marketing Potential with Our 50+ Free YouTube Banners</u></a></li>
<li><a href="https://win-news.techidaily.com/mastering-dynamic-presentations-create-interactive-powerpoints-with-flippower-your-guide-to-animated-content-and-ebook-style-pages/"><u>Mastering Dynamic Presentations: Create Interactive PowerPoints with FlipPower - Your Guide to Animated Content and Ebook-Style Pages</u></a></li>
<li><a href="https://win-news.techidaily.com/mastering-multi-page-spreads-tips-for-scaling-up-your-pdf-presentations-on-two-pages-with-flipbuilder/"><u>Mastering Multi-Page Spreads: Tips for Scaling Up Your PDF Presentations on Two Pages with FlipBuilder</u></a></li>
<li><a href="https://win-news.techidaily.com/mastering-page-zoom-tips-for-enlarging-text-in-pdfs-from-word-conversions-with-flipbuilder/"><u>Mastering Page Zoom: Tips for Enlarging Text in PDFs From Word Conversions with FlipBuilder</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/stepwise-czech-study-top-efficient-online-tutorials/"><u>Stepwise Czech Study: Top Efficient Online Tutorials</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/ultimate-iphone-data-retrieval-tool-shop-today/"><u>Ultimate iPhone Data Retrieval Tool – Shop Today!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557743/17382" target="_top" id="1557743">
  <img src="//a.impactradius-go.com/display-ad/17382-1557743" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557743/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

