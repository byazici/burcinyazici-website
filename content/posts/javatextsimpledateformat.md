+++
title = "java.text.SimpleDateFormat"
date = "2007-06-26T12:17:20+03:00"
slug = "javatextsimpledateformat"
categories = ["Yazılım"]
tags = ["tarih"]
+++
Java'da tarih formatlamak her zaman sorun olmuştur. Elinizde  java.util.Date var ve bunu herhangi bir formata çevrip String olarak almak istiyorsanız ilgili kodşöyle:

<code>import java.text.SimpleDateFormat;
import java.util.Date;
...
SimpleDateFormat sdf = new SimpleDateFormat("yyyyMMdd");
String formattedDate = sdf.format(new Date());
system.out.println(</code><code>formattedDate</code><code>);</code>

burada <code>formattedDate değeri "</code>20070626" şeklinde olacaktır.

Buradan bizde

<code>SimpleDateFormat'ın "pattern" parametresiyle ilgili referans tablosu da şöyle:</code>
<table border="0" width="100%">
<tbody>
<tr>
<td><strong>Sembol</strong></td>
<td><strong>Anlamı</strong></td>
<td><strong>Tipi</strong></td>
<td><strong>Örnek</strong></td>
</tr>
<tr>
<td>y</td>
<td>Year</td>
<td>Number</td>
<td>“yy” -&gt; “03″
“yyyy” -&gt; “2003″</td>
</tr>
<tr>
<td>d</td>
<td>Day in month</td>
<td>Number</td>
<td>“d” -&gt; “3″
“dd” -&gt; “03″</td>
</tr>
<tr>
<td>H</td>
<td>Hour (0-23)</td>
<td>Number</td>
<td>“H” -&gt; “15″
“HH” -&gt; “15″</td>
</tr>
<tr>
<td>K</td>
<td>Hour (0-11 AM/PM)</td>
<td>Number</td>
<td>“K” -&gt; “15″
“KK” -&gt; “15″</td>
</tr>
<tr>
<td>s</td>
<td>Second</td>
<td>Number</td>
<td>“s” -&gt; “15″
“ss” -&gt; “15″</td>
</tr>
<tr>
<td>E</td>
<td>Day in week</td>
<td>Text</td>
<td>“EEE” -&gt; “Tue”
“EEEE” -&gt; “Tuesday”</td>
</tr>
<tr>
<td>F</td>
<td>Day of week in month (1-5)</td>
<td>Number</td>
<td>“F” -&gt; “1″</td>
</tr>
<tr>
<td>W</td>
<td>Week in month (1-5)</td>
<td>Number</td>
<td>“W” -&gt; “3″</td>
</tr>
<tr>
<td>z</td>
<td>Time zone</td>
<td>Text</td>
<td>“z” -&gt; “EST”
“zzz” -&gt; “EST”
“zzzz” -&gt; “Eastern Standard Time”</td>
</tr>
<tr>
<td>”</td>
<td>Single quote</td>
<td>Literal</td>
<td>“ss”SSS” -&gt; “45′876″</td>
</tr>
</tbody></table>