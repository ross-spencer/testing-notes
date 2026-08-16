---
title: "Testing File Format Signatures"
teaching: 0    # teaching time in minutes
exercises: 0    # exercise time in minutes
---

:::::::::::::::::::::::::::::::::::::: questions

* What other methods do we have to test file format signatures?
* What are skeleton files?
* Where do we get them from?
* What testing properties do they have?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

* Understand what false-positives are
* Learn the pupose of skeleton files
* Learn where to access them and how to use them

::::::::::::::::::::::::::::::::::::::::::::::::

<!-- TODO: Advanced topic we might not practically cover but you need to
know about -->

## Testing signatures

We want to identify **false-positives** and **collisions**.

* False-positives are files that are identifying incorrectly using the
signature.
* False-positives are resolved through careful testing of signatures against
existing patterns using tools like the skeleton suite (below).
*  Collisions are a subset because they might occur because they are a subset
of a file format, e.g. SVG might collide with XML
* Collisions are resolved through a directive in PRONOM to give piriority of one
format over the other. The ideal - one format identificaiton per file, i.e.
no multiple identification.

## Skeleton suite

The skeleton suite can help us to do this.

The skeleton suite is ...

> info box:

Builder: Current Skeletons, Maintained by Richard Lehane

* Updated when a new PRONOM is released
* Contains standard and container skeleton samples.

> https://github.com/richardlehane/builder


![Social media preview of Richard Lehane's GitHub repository github.com/richardlehane/builder](./fig/builder-1.png){alt="TODO"}

> info box:

[https://github.com/exponential-decay/skeleton-test-suite-generator](https://github.com/exponential-decay/skeleton-test-suite-generator)

![Screenshot showing many different file icons against a dark background. The Skeleton Suite provides the opportunity to make this screenshot as it represents all the files in the PRONOM corpus.](./fig/skeleton-1.png){alt="TODO"}


<!-- NB. Keypoints should appear at the end of the markdown file. Aesthetically
     it looks like it's better with an additional newline so adding that
     here and using this comment as a separator to make it easy to read
     content.
-->

<br>

::::::::::::::::::::::::::::::::::::: keypoints

* False positives happen when a signature matches other records in PRONOM
* Sometimes a signature needs to be improved or a priority set for it
* Skeleton files were developed by Ross Spencer
* Richard Lehane builds these files each new PRONOM release and makes them
available via Builder
* They are used in Siegfried and PRONOM workflows to identify DROID regressions
and newly introduced multiple identifications or false positives

::::::::::::::::::::::::::::::::::::::::::::::::
