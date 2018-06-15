# SyntaxHighlighter

- Add following code above </head> tag in HTML of Blogger Theme:
    <link href='http://rawgit.com/hcuongvn/SyntaxHighlighter/master/styles/shCore.css' rel='stylesheet' type='text/css'/>
    <link href='http://rawgit.com/hcuongvn/SyntaxHighlighter/master/styles/shThemeDefault.css' rel='stylesheet' type='text/css'/>
    <script src='http://rawgit.com/hcuongvn/SyntaxHighlighter/master/scripts/shCore.js' type='text/javascript'/>
    <script src='http://rawgit.com/hcuongvn/SyntaxHighlighter/master/scripts/shBrushCpp.js' type='text/javascript'/>
    <script src='http://rawgit.com/hcuongvn/SyntaxHighlighter/master/scripts/shBrushJScript.js' type='text/javascript'/>
    <script src='http://rawgit.com/hcuongvn/SyntaxHighlighter/master/scripts/shBrushPerl.js' type='text/javascript'/>
    <script src='http://rawgit.com/hcuongvn/SyntaxHighlighter/master/scripts/shBrushSystemVerilog.js' type='text/javascript'/>
    <script language='javascript'>
      SyntaxHighlighter.config.bloggerMode = true;
      SyntaxHighlighter.all();
    </script>

- For Dynamic Views theme, add following script at the end of your post to highlight code:
<script type="text/javascript">
 SyntaxHighlighter.highlight();
</script>
