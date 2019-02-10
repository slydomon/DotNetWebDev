# HTML

## Tag
```
1.Tag define the structure of the content of HTML
2.Tag is contained within "<>" and followed by 0 to many attribute: <a(tag) href(attribute)= "http..."
3.non void Tag has opening and closing tags(<a>...</a>) while void Tag has only one opening+closing tag(<img src=.../>)
4.content is things that between opening and closing tag: <a> content </a>
```

## HTML Doc Structure
```
<!DOCTYPE html>
<html>
<head>
  <title>Page title</title> //contain info for brower and search engine such as meta-data.
</head>

<body>
  (<p>content...</p>) //contain contain shown to custom.
</body>

<html>
```

## Document Object Model(DOM)
```
Def: DOM is a tree that represent the structure of a HTML document.
Ex:
accouding to the document structure above, the DOM looks likes this:

  html
  /  \
head body
      |
      p
```

