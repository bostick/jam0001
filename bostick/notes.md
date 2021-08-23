# Notes for LangJam2021 "first-class comments"


I could not come up with a good idea for the LangJam, but I did take some notes.


## ideas

what could first-class mean?

assignable

storable

the comment content must be valid code



maybe use unicode in a wacky way:

unicode symbols to use:

proofreading symbols




from the discord:

introspectable?

concept of "this" location in source file





what restrictions on comments give more structure?

must be valid code syntax


maybe has a "precedence" ?

juxtaposition of comments is like implicit times







## “Whitespace ≤ Comments ＜＜ Code”

CppCon 2017: Walter E. Brown “Whitespace ≤ Comments ＜＜ Code”
https://www.youtube.com/watch?v=NLebZ3XT92E


punch card story


```
debug = true // eslaf = gubed
```

Really good talk!


simulate flipping a punch card on the vertical axis?


RTL language comments?



## Comments in other languages

### Clojure

Rich comment blocks in Clojure:
https://betweentwoparens.com/blog/rich-comment-blocks/

Discard the next form:
https://clojure.org/guides/weird_characters#_discard



### C / C++ comments

history of C / C++ comments:
https://en.wikibooks.org/wiki/C%2B%2B_Programming/Code/Style_Conventions/Comments

Multi-line comments (informally, C style), start with ``/*`` and end with ``*/``

Single-line comments (informally, C++ style), start with ``//``

Note: Since the 1999 revision, C also allows C++ style comments

Single-line comments (informally, C++ style), start with ``//`` and continue until the end of the line. If the last character in a comment line is a ``\`` the comment will continue in the next line.



### OCaml

OCaml uses ``(**)`` and has no syntax for single-line comment syntax
https://ocaml.org/learn/tutorials/basics.html


### Maude

Maude uses ``***``
https://en.m.wikipedia.org/wiki/Maude_system


### Rust

Rust uses ``///`` and ``//!`` for doc comments
https://doc.rust-lang.org/1.26.2/book/first-edition/comments.html


### Scheme

``#;`` "datum comments" in scheme:
http://www.r6rs.org/final/html/r6rs-rationale/r6rs-rationale-Z-H-6.html



### Sublime test syntax

```
  foo::bar = "message"
(*   ^^ keyword.operator.MessageName *)
(*     ^^^ string.unquoted *)
(*             ^ string.quoted *)
```





