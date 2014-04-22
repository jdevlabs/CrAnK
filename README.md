# CrAnK

A Cryptanalaysis toolkit.

## Introduction

For starters, we will aim at creating a clone of [this CrAnK](http://crank.sourceforge.net/about.html). It is written in C and relies on GTK+ (Glade) but was last updated in 2001 (I was 8 then.)

We will have a lot of features to copy first and then we can extend them in every possible direction.

**Interface:**

We'll begin with a basic interface with just two text boxes, one where ciphered text will be entered and the other where decrypted text will be generated.

A status bar will be used to display progress of the decryption process.

As we gain knowledge of Qt, we could add a Tabbed interface so a user can work on multiple documents at the same time.

**Ciphers**

Ceaser will be our first target, once we get past that, we'll have to figure out algorithms for fully or semi automatic cracking of other ciphers as well.

Monoalphabetic Substitution ones will be the easiest probably as they just require some funky frequency analysis of the text.

We can embed other tools (like xortool) to break other ciphers (like xor).

## Tech Used

* Python 3.3 (and not 2.7)
* PyQt 5.2
