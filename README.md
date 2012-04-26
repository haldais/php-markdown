Attributes support
======

##Paragraphs

id & class support

    {.id}
    This is a normal paragraph.  
    This is a preformatted  
    code block.

    {.class}
    This is a normal paragraph.  
    This is a preformatted  
    code block.

##Headers

class support

    #Header 1 {#heading1} {.foo bar}
    
    ##Header 2 {#heading2} {.foo bar}
    
    ##Header 2 {.foo bar}

##Links

class support

    An [example](http://url.com/ "Title" {.foo})

##Images

class support

    ![alt text](/path/img.jpg "Title" {.bar})