A web page that renders its own source code:

    <!DOCTYPE html><head><title>_</title></head>
    <body>
    <script>d=document;d.body.innerHTML="<xmp>"+new XMLSerializer().serializeToString(d.doctype)+d.children[0].innerHTML</script></body>
