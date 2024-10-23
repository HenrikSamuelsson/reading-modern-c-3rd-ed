# Takeaways

The book includes special one-liner paragraphs marked up with the tag *Takeaway*. These takeaways summarizes concepts introduced in the book that are deemed important.

The takeaways are listed below along with my personal interpretation of each takeaway.

## Preface

### Takeaway #1

> C and C++ are different: don't mix them, and don't mix them up.

C and C++ do have many similarities that can cause the languages to be treated as one entity. If cutting out a code snippet from a source file and presenting it isolation it might not even be possible to tell if it is from a C or C++ project.

Even if C and C++ being similar we should remember that the two are different languages. They are defined by different ISO committees. Not all C code will compile with a C++ compiler, and in some cases the code will compile but actually give different results when being executed.

It is fully possible to have a mixed project that is a based source files with both C and other in C++ code. But if mixing C and C++ in a project it should be based of a compelling reason, such as having legacy modules that are beneficial to reuse. Otherwise it is simpler to stick to using only either C or C++ in a given project.

## Chapter 1

### Takeaway 1 #2

> Don't panic.

This takeaway is a reference to the *The Hitchhiker's Guide to the Galaxy*, a fictional guide book with the words don't panic printed on its cover. This guide book is an element in the multimedia series with the same name by Douglas Adams. It is here described as "the standard repository for all knowledge and wisdom".

In the context of programming in general, and in particular when working with the book Modern C, it is important not to panic. The book is challenging and will require an effort from the reader. Instead of panicking the reader need to work methodically taking advantage of all the material in the book including the exercises and challenges. This will take time so lets put away our smart phones and get working.
