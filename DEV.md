

## 生成 html 的方法

在命令行下运行

    java -classpath lib/saxonb9-1-0-8j/saxon9.jar net.sf.saxon.Transform -s:draft-ietf-httpbis-http2-zh.xml -xsl:lib/rfc2629.xslt -o:draft-ietf-httpbis-http2-zh.html