---
title: How to Respond to Weird Patterns with EmEditor - Expert Tips for Text Editing
date: 2024-11-09T19:16:08.828Z
updated: 2024-11-12T19:37:09.412Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/a49c2f71f9d056e749c5a574cc37d025a924e06d161f32912baf28d3cb32fbc8.jpg
---

## How to Respond to Weird Patterns with EmEditor - Expert Tips for Text Editing

November 30, 2007 at 8:30 pm [#5077](https://tools.techidaily.com/emeditor/products/) 

[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")

Keymaster

> jugaor wrote:  
> Hi, thank you very much for your response.
> 
> 1\. In Spanish, the ‘special’ letters are ÁÉÍÓÚÜ, áéíóúü, Ñ, ñ. I presume that these Unicode chars cover them :)
> 
> 2\. The spaces are needed, since they’re two whole words:  
> “esta” = “this” / “estas” = “these”, both feminine.  
> “es” = “is” (singular, verb to be)  
> “son” = “are” (plural, verb to be)  
> The strange thing is that EmEditor rightly works with the same subexpression after, not before (i.e. “(¡|¿)esta(s?)(?! es| son)” is correct).
> 
> I have been trying to use EmEditor to automatically correct words with bad orthography in subtitles files (Spanish). I wrote some complex VBEE scripts for that, and I found these issues above.
> 
> Thanks for your attention,  
> jugaor
> 
> PS: please, write me when the new beta is ready :)

 (?=pattern) (positive lookahead search) and (?!pattern) (negative lookahead search) look ahead from the position where search begins.

 For example, expression “(?=x)x” always matches, and expression “(?!x)x” never matches.

 So it doesn’t make sense to place (?=pattern) or (?!pattern) at the beginning of a search term.

 I will release beta 41 today or tomorrow.

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
<li><a href="https://fox-http.techidaily.com/new-enhance-photoshop-snaps-with-shake-effects-for-2024/"><u>[New] Enhance Photoshop Snaps with Shake Effects for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-ultra-hd-gaming-top-graphics-card-choices/"><u>[Updated] Ultra HD Gaming Top Graphics Card Choices</u></a></li>
<li><a href="https://win-news.techidaily.com/1728506453315-usb/"><u>失去USB文件？用我们的方法轻松找回你的数据！</u></a></li>
<li><a href="https://extra-resources.techidaily.com/crafting-content-that-wins-on-ig-unboxing-edition/"><u>Crafting Content That Wins on IG Unboxing Edition</u></a></li>
<li><a href="https://win-news.techidaily.com/effective-techniques-for-formatting-windows-10-drives/"><u>Effective Techniques for Formatting Windows 10 Drives</u></a></li>
<li><a href="https://win-news.techidaily.com/essential-techniques-for-securely-preserving-windows-11-files-on-an-external-hard-drive/"><u>Essential Techniques for Securely Preserving Windows 11 Files on an External Hard Drive</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-keep-your-files-intact-weekly-windows-backups/"><u>How to Keep Your Files Intact: Weekly Windows Backups</u></a></li>
<li><a href="https://some-techniques.techidaily.com/ideal-photo-and-video-shows-on-latest-iphone-models-xr-ios12-for-2024/"><u>Ideal Photo & Video Shows on Latest iPhone Models (XR-iOS12) for 2024</u></a></li>
<li><a href="https://win-news.techidaily.com/seamlessly-downsize-your-storage-transforming-a-large-hdd-into-an-ssd-using-macrium-reflect/"><u>Seamlessly Downsize Your Storage: Transforming a Large HDD Into an SSD Using Macrium Reflect</u></a></li>
<li><a href="https://fox-tls.techidaily.com/troubleshooting-tips-resolving-icloud-message-synchronization-problems-across-ios-and-macos-devices/"><u>Troubleshooting Tips: Resolving iCloud Message Synchronization Problems Across iOS and macOS Devices</u></a></li>
<li><a href="https://win-news.techidaily.com/tutoriel-facile-recouvrer-votre-partie-manquante-sur-xbox/"><u>Tutoriel Facile : Recouvrer Votre Partie Manquante Sur Xbox</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082520/7443" target="_top" id="2082520">
  <img src="//a.impactradius-go.com/display-ad/7443-2082520" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082520/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

