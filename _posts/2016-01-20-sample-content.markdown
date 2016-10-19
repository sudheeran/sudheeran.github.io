---
layout: default
title:  "Google Page Rank Algorithm!"
date:   2016-01-20 16:50:00
categories: main
---

<h2><span>Google Page Rank Algorithm!</span></h2>

PageRank is a way of measuring the importance of website pages.

PageRank is a link analysis algorithm used by Google to help determine the relative importance of a website. Every website is given a Google PageRank score between 0 and 10 on an exponential scale.

<h3><span>According to Google:</span></h3>

PageRank works by counting the number and quality of links to a page to determine a rough estimate of how important the website is. The underlying assumption is that more important websites are likely to receive more links from other websites.

It is not the only algorithm used by Google to order search engine results, but it is the first algorithm that was used by the company, and it is the best-known.



Mathematical PageRanks for a simple network, expressed as percentages.

<figure><img src="/images/PageRanks.png" title="PageRanks Algorithm"></figure>



The original PageRank algorithm was described by Lawrence Page and Sergey Brin in several publications. It is given by :

<pre><code>PR(A) = (1-d) + d (PR(T1)/C(T1) + ... + PR(Tn)/C(Tn))</code>

where :

	PR(A) is the PageRank of page A,
	PR(Ti) is the PageRank of pages Ti which link to page A,
	C(Ti) is the number of outbound links on page Ti and
	d is a damping factor which can be set between 0 and 1.

</pre>

So, first of all, we see that PageRank does not rank web sites as a whole, but is determined for each page individually. Further, the PageRank of page A is recursively defined by the PageRanks of those pages which link to page A.

<hr>
How Many Backlinks I need to get PR1?

No one can say HOW many links you will need to get to a PR 1. What it really depends on is how GOOD are the links in which are pointing back to your website.

<hr>

In today’s world, <code>QUALITY is more important than quantity</code>. Google penalties have caused many website owners to not only stop link building, but start link pruning instead. Poor quality links (i.e., links from spammy or off-topic sites) are like poison and can kill your search engine rankings. Only links from quality sites, and pages that are relevant to your website, will appear natural and not be subject to penalty. So never try to buy or solicit links — earn them naturally or not at all.