---
slug: yahoo-api-developer-network
date: 2005-10-18
 
title: Yahoo API Developer Network
published: true
---
I posted to the mailing list two issues over the weekend. <p />One about result number restriction:<br /><blockquote>Hi, <br />I was just reading the documentation which gives the following URL as an example:<br /><a href="http://api.search.yahoo.com/MyWebService/V1/relatedTags?appid=YahooDemo&amp;tag=yahoo&amp;results=2">http://api.search.yahoo.com/MyWebService/V1/relatedTags?appid=YahooDemo&amp;tag=yahoo&amp;results=2</a> It is supposed to return only two results yet all 48 are returned? Is this correct? I need to start using this API and I don't know if it will return the correct results. <br />Kind Regards, <br />Paul Kinlan</blockquote><br />And the other about Contextual term extraction not processing results after an HTML style tag. i.e anything that has a "&lt;" or "&gt;" in:<br /><blockquote>Hi, <br />I have been playing with the contextual term extraction API, and I have noticed (well at least I think I have) that if there is a HTML tag in the text for term extraction then the term extraction API doesn't examine data after the starting tag. <br />For instance if I had the following text: <br /><blockquote>I have been trying to play with <a href="http://help.blogger.com/default/bin/answer.py?answer=1235&amp;topic=39">Blogger BackLinks</a>, and I can say that I don't really like them. I don't really like them because people have to use them! I was expecting Blogger Backlinks to automatically link into the Google Blog search to find a list of all the blogs that link to my post. And then update my page from there. <br />I think what I will do is develop a version that does use them, it will fire a query off to Google and see what happens from there. I mean, after all Google Blog search allows you to do this, and export the results as RSS.</blockquote>
<br />The API only seems to analyse up to and including href="xyzabc"&gt;. Anything after this in not included in the results. <br />Has anyone else experienced this? <br />Kind Regards, <br />Paul Kinlan <br /><a href="http://www.kinlan.co.uk">www.kinlan.co.uk</a>
</blockquote><p />I got two replies on Monday (1 day after I posted the problem), one confirming that it is a bug that is being worked on and the other confirming that my problem has just been fixed.  Way to go Yahoo!  That is the way that I like to see services run.  Keep up the good work.<p /><table class="TechnoratiHead TagHeader">
<tr><td>Technorati Tags</td></tr>
<tr class="Technorati"><td>
<a href="http://www.technorati.com/tag/ahoo" class="Tag" rel="tag">ahoo</a> <a href="http://feeds.technorati.com/feed/posts/tag/Yahoo" class="Tag">[feed]</a>, <a href="http://www.technorati.com/tag/Api" class="Tag" rel="tag">Api</a> <a href="http://feeds.technorati.com/feed/posts/tag/Api" class="Tag">[feed]</a>, <a href="http://www.technorati.com/tag/Search" class="Tag" rel="tag">Search</a> <a href="http://feeds.technorati.com/feed/posts/tag/Search" class="Tag">[feed]</a>
</td></tr>
</table><br /><table class="TechnoratiHead TagHeader">
<tr><td>Wikipedia Documents</td></tr>
<tr class="Technorati"><td>
<a href="http://en.wikipedia.org/wiki/Search_algorithm">Search Algorithm</a> ,<a href="http://en.wikipedia.org/wiki/Search">Searching</a> ,<a href="http://en.wikipedia.org/wiki/API">Application Programming Interface</a> ,<a href="http://en.wikipedia.org/wiki/Yahoo!">Yahoo!</a> ,<a href="http://en.wikipedia.org/wiki/Yahoo">Yahoo</a> ,<a href="http://en.wikipedia.org/wiki/MSN_Search">Msn Search</a>
</td></tr>
</table><div class="blogger-post-footer"><img class="posterous_download_image" src="https://blogger.googleusercontent.com/tracker/8109338-112963218529941469?l=www.kinlan.co.uk%2Findex.html" height="1" alt="" width="1" /></div>

