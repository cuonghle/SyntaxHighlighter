# SyntaxHighlighter

1. First, take backup of your blogger template
2. After that open your blogger template (In Edit HTML mode) & copy the all css given in this link before </b:skin> tag
3. Paste the followig code before </head> tag

<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shCore.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushCpp.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushCSharp.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushCss.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushDelphi.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushJava.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushJScript.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushPhp.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushPython.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushRuby.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushSql.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushVb.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushXml.js' type='text/javascript'></script>
4. Paste the following code before </body> tag.

<script language='javascript'>
dp.SyntaxHighlighter.BloggerMode();
dp.SyntaxHighlighter.HighlightAll('code');
</script>
5. Save Blogger Template.
6. Now syntax highlighting is ready to use you can use it with <pre></pre> tag.

<pre name="code">
...Your html-escaped code goes here...
</pre>

<pre name="code" class="php">
    echo "I like PHP";
</pre>
