# Takeaways

The book includes special one-liner paragraphs marked up with the tag *Takeaway*. These takeaways summarizes concepts introduced in the book that are deemed important.

The takeaways are listed below along with my personal interpretation of each takeaway.

## Takeaway 1

> C and C++ are different: don't mix them, and don't mix them up.

C and C++ do have many similarities that can cause the languages to be treated as one entity. If cutting out a code snippet from a source file and presenting it isolation it might not even be possible to tell if it is from a C or C++ project.

Even if C and C++ being similar we should remember that the two are different languages. They are defined by different ISO committees. Not all C code will compile with a C++ compiler, and in some cases the code will compile but actually give different results when being executed.

It is fully possible to have a mixed project that is a based source files with both C and other in C++ code. But if mixing C and C++ in a project it should be based of a compelling reason, such as having legacy modules that are beneficial to reuse. Otherwise it is simpler to stick to using only either C or C++ in a given project.
