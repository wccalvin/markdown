# Markdown Basics

## Headlines, Paragraphs and Basic formatting

### Headlines

#### Heading level 4
##### Heading level 5
###### Heading level 6

### Paragraphs and Line Breaks

We create paragraphs by typing the way we would in any program. Just hit return twice to start another paragraph.

Line breaks can be done by providing two spaces and a return. Follow along the below stanza as an example.

Oh God, forgive us - by for king and country  
With a white flag sailing in the night  
eyes pointed to the sky  
hands up and open wide, open wide  
Oh God, forgive us.

### Emphasis and Bolding

#### Italics

This *works* and this _works_ too.

#### Bolding

This **works** and this __works__ too.

#### Italics and Bolding together

This ***works*** and this ___works___ too.

### Blockquotes
>I believe in Christianity as I believe that the sun has risen: not only because I see it, but because by it I see everything else. - [C.S. Lewis](http://www.cslewis.com/us/ "Official Site of C.S. Lewis")
>
>You are never too old to set another goal or to dream a new dream. - [C.S. Lewis](http://www.cslewis.com/us/ "Official Site of C.S. Lewis")

### Horizontal Rule

___

---

***

### Lists

#### Numbered Lists

1. Item 1
2. Item 2


1. Item 1
  1. Item 1
  2. Item 2

#### Bulleted Lists

* Item 1
* Item 2


* Item 1
  * Item 1
  * Item 2

* Item 2
  * Item 1
  * Item 2

---

### Code

To list all the files in a directory, you can type `ls -la` from your terminal.

```Perl
#!/usr/bin/env perl

use strict;
use Data::Dumper;

my $foo = 'bar';
my $bar = 'foo';

print Dumper $foo . ' ' . $bar;
```

---

### Links

[@wccalvin](https://twitter.com/wccalvin)

[@wccalvin](https://twitter.com/wccalvin "My twitter profile")

[@wccalvin][1]

[1]: https://twitter.com/wccalvin "Reference link to my twitter profile"

---
