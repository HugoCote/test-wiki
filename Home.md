> Nous croyons à la supériorité de la civilisation occidentale.
> 
>  Jean-Marie Le Pen,

# Table des matières

[[_TOC_]]

# Inclusion de page

[[include:/programmation/installation]]

[[include:_Header]]

[[include:_Header.ext]]

[[include:/programmation/_Header.ext]]

# Comment faire des hyperliens :
- Syntaxe markdown [gollum](https://github.com/gollum/gollum/wiki)
- Syntaxe markdown [gitlab](https://docs.gitlab.com/ee/user/markdown.html)
- [[exmple|http://example.com/pdfs/gollum.pdf]]
- [Installations méthode 1](programmation/installation.md), mauvais
- [Installations méthode 2](programmation/installation), bon
- [[Installations méthode 3|programmation/installation]], bon
- [[Installations méthode 4|/programmation/installation]], bon

# Schema 

```mermaid
graph TD;
  A-->B;
  A-->C;
  B-->D;
  C-->D;
```
# Diff
Inline
- {+ additions +}
- {- deletion -}

Code block

```diff
+ additions +
- deletion -
```
# Math

Inline : $`a^2+b^2= \sum_{i=0}^n c_i^2`$

Centered :

```math
a^2+b^2= \sum_{i=0}^n c_i^2
```

# Code snippets
```python
def function():
    #indenting works just fine in the fenced code block
    s = "Python code"
    print s
```

# Requirement

## Require rubygems 
require 'rubygems'

## Require the Gollum library
require 'gollum'
```

