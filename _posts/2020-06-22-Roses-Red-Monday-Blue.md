---
layout: post
title: "Roses Red, Monday Blue"
date: 2020-06-22
---

<h2>Description lists</h2>
<dl>
    <dt>We now format 9 the text</dt>
    <dd>Inside description list got description term and inside descrption term can have more than 1 description definition.</dd>
    <dd>This is 2nd description definition.</dd>
    <dt>Another description term</dt>
    <dd>Another description definition which has no definition at all.</dd>
</dl>

<h2>Quotations/References</h2>
<P><a href="https://en.wikipedia.org/wiki/Ip_Man"><cite>Ip Man</cite></a> once said:</p>
<blockquote cite="https://zhidao.baidu.com/question/1606385457153097947.html?qbl=relate_question_4">
<p><q>我要打十个. I want fight 10 people.</q></p>
</blockquote>
<p>and he did it, I did it too, not people, but aeroplane instead. jk.</P>

<h2>Abbrevations</h2>
<p>
<dl>
    <dt>Abbr</dt>
        <dd>Hover over to learn these words ;)</dd>
        <ul>
            <li><abbr title="Dual Dipped Lychee Yogurt">DDLY</abbr></li>
            <li><abbr title="Miniature Circuit Breaker">MCB</abbr></li>
            <li><abbr title="Thailand, China, Japan">TCJ</abbr></li>
        </ul>
</dl></p>

<h2>Address</h2>
<address>
  <p>
    Chris Mills<br>
    Manchester<br>
    The Grim North<br>
    UK
  </p>

  <ul>
    <li>Tel: 01234 567 890</li>
    <li>Email: me@grim-north.co.uk</li>
  </ul>
</address>

<h2>Superscript and subscript</h2>
<p>My birthday is on the 25<sup>th</sup> of May 2001.</p>
<p>Caffeine's chemical formula is C<sub>8</sub>H<sub>10</sub>N<sub>4</sub>O<sub>2</sub>.</p>
<p>If x<sup>2</sup> is 9, x must equal 3 or -3.</p>

<h2>Computer code</h2>
<pre><code>var para = document.querySelector('p');

para.onclick = function() {
  alert('Owww, stop poking me!');
}</code></pre>

<p>You shouldn't use presentational elements like <code>&lt;font&gt;</code> and <code>&lt;center&gt;</code>.</p>

<p>In the above JavaScript example, <var>para</var> represents a paragraph element.</p>


<p>Select all the text with <kbd>Ctrl</kbd>/<kbd>Cmd</kbd> + <kbd>A</kbd>.</p>

<pre>$ <kbd>ping mozilla.org</kbd>
<samp>PING mozilla.org (63.245.215.20): 56 data bytes
64 bytes from 63.245.215.20: icmp_seq=0 ttl=40 time=158.233 ms</samp></pre>

<h2>Times & dates</h2>
<ul>
<!-- Standard simple date -->
<li><time datetime="2016-01-20">20 January 2016</time></li>
<!-- Just year and month -->
<li><time datetime="2016-01">January 2016</time></li>
<!-- Just month and day -->
<li><time datetime="01-20">20 January</time></li>
<!-- Just time, hours and minutes -->
<li><time datetime="19:30">19:30</time></li>
<!-- You can do seconds and milliseconds too! -->
<li><time datetime="19:30:01.856">19:30:01.856</time></li>
<!-- Date and time -->
<li><time datetime="2016-01-20T19:30">7.30pm, 20 January 2016</time></li>
<!-- Date and time with timezone offset -->
<li><time datetime="2016-01-20T19:30+01:00">7.30pm, 20 January 2016 is 8.30pm in France</time></li>
<!-- Calling out a specific week number -->
<li><time datetime="2016-W04">The fourth week of 2016</time></li>
</ul>

