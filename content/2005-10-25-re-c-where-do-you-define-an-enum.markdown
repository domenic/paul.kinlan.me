---
slug: re-c-where-do-you-define-an-enum
date: 2005-10-25
 
title: "RE: C# : Where do you define an enum"
published: true
---
I have replied again on <a href="http://blogs.msdn.com/abhinaba/archive/2005/10/24/484120.aspx">Abhinaba's blog</a>. <p />You said "I have time again seen that people point to intellisense and other editor features to justify or nullify arguments. But a editor feature can never justify design decisions. Not everyone uses VS editor. Moreover a lot of people have build systems that _do not_ use solutions and rely on make files (nmake) or "sources" "dirs" files (NTBuild). Since there is no sln/proj files for the VS editor to use, intellisense do not work and users open CS files individually to edit. This is not a corner case situation and some teams even in MS uses this approach.". <p />You're right, intellisense can't justify having lengthened/shortend etc Naming conventions, but neither can its use or lack of be used to justify the reverse [I think that makes sense]. I understand that you want to be as verbose as you can in as smaller an area, but I still think verbosity wins the day. <p />Again for your second class, you shouldn't really be ripping the enums out and using them elsewhere [this could cause unintended consequences, at least having to change the class declaration makes it explicit that you know are changing all the enum refeneces], they should be referenced in the context that they are to be used in, and thus I belive having them in the class where it is initially related is the better choice. <p />Obviously [and I might condraticy myself now] if you have many classes from the start that use them I agree with your point. But, if you have a file filter [specific to files] and a directory filter [specific to directories] I would keep them at class level named as filter and not at the namespace level named as FileFilter, DirectoryFilter.<p /><table class="TechnoratiHead TagHeader">
<tr><td>Technorati Tags</td></tr>
<tr class="Technorati"><td>
<a href="http://www.technorati.com/tag/Intellisense" class="Tag" rel="tag">Intellisense</a> <a href="http://feeds.technorati.com/feed/posts/tag/Intellisense" class="Tag">[feed]</a>, <a href="http://www.technorati.com/tag/Filter" class="Tag" rel="tag">Filter</a> <a href="http://feeds.technorati.com/feed/posts/tag/Filter" class="Tag">[feed]</a>, <a href="http://www.technorati.com/tag/Verbose" class="Tag" rel="tag">Verbose</a> <a href="http://feeds.technorati.com/feed/posts/tag/Verbose" class="Tag">[feed]</a>, <a href="http://www.technorati.com/tag/Editor%20Feature" class="Tag" rel="tag">Editor Feature</a> <a href="http://feeds.technorati.com/feed/posts/tag/Editor%20Feature" class="Tag">[feed]</a>, <a href="http://www.technorati.com/tag/Enum" class="Tag" rel="tag">Enum</a> <a href="http://feeds.technorati.com/feed/posts/tag/Enum" class="Tag">[feed]</a>, <a href="http://www.technorati.com/tag/Namespace" class="Tag" rel="tag">Namespace</a> <a href="http://feeds.technorati.com/feed/posts/tag/Namespace" class="Tag">[feed]</a>
</td></tr>
</table><br /><table class="TechnoratiHead TagHeader">
<tr><td>Wikipedia Documents</td></tr>
<tr class="Technorati"><td>
<a href="http://en.wikipedia.org/wiki/Namespace">Namespace</a> ,<a href="http://en.wikipedia.org/wiki/Enum">Enum</a> ,<a href="http://en.wikipedia.org/wiki/Enumeration">Enumeration</a> ,<a href="http://en.wikipedia.org/wiki/Visual_C_Plus_Plus">Visual C Plus Plus</a>
</td></tr>
</table><div class="blogger-post-footer"><img class="posterous_download_image" src="https://blogger.googleusercontent.com/tracker/8109338-113027370400153153?l=www.kinlan.co.uk%2Findex.html" height="1" alt="" width="1" /></div>

