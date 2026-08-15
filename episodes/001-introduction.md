---
title: "Introduction"
teaching: 10    # teaching time in minutes
exercises: 0    # exercise time in minutes
---

:::::::::::::::::::::::::::::::::::::: questions

* What is PRONOM?
* What are file format signatures?
* Why do we need container signatures?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

* Gain an overview of PRONOM and its benefits
* Understand what container signatures are
* Begin to understand the differences between standard signatures and
container signatures.

::::::::::::::::::::::::::::::::::::::::::::::::

:::: instructor

Some things to take care of if you are doing this in a live setting.

* Welcome, housekeeping.
* Introduction to the presenters.
* Icebreaker if this hasn't already been done.
* Participant engagement, e.g.
  * show of hands about experience with signature development.
  * show of hands about experience with container signatures.
  * ask pparticipants about their motivations,

> everyone will be interested in FFID to some extent.

::::


## Why are we interested in identifying file formats?

* Knowing what you’ve got is a basic first step for managing digital
information - whether that’s records management, managing digital
continuity or digital preservation.
* To keep digital information usable, we need to understand its technical
characteristics.
* This is detailed work. The precise format (e.g. what version of Word or PDF
do we have?) can be important.
* Your institution or organization might work with verfy different digital
records to anyone else, you might also have more resources than smaller
institutions working with similar records.
* Any skills you can to contribute to the community record of PRONOM benefits
us all.

## How can we identify file formats?

* There’s not one single method.

### What tool was used?

* You may simply know what tools or software were used to create your
digital records.
* We don;t usually know this with confidence after their creation and
transfer to an archive or other repository.

### File extensions

* File extensions can be very helpful. But they can be changed and they
don’t usually tell us about specific versions.

### Looking inside the files

* We can look inside the digital files at the precise sequence of
codes in the file.
* Sometimes the file format is plainly stated inside the file.
More often we will be looking for characteristic patterns that point
us towards an identification.
* These patterns are known as file format
signatures. The starts and ends of files are good places to look for
these patterns.
* We have looked at file format signatures in a previous workshop. These
are sometimes part of a file format specification, or become de-facto
identifiers that can be modelled in PRONOM.
* Container signatures build on existing file format signature work.
* Because of how file formats are built using "containers" we can often
access more precise information about the files inside the container and
byte sequences inside those files.
* Container signatures, can therefore, often provide greater accuracy
than your standard file format signatures.
* That being said, because some file formats are containers and some are
not, both methods remain completely complementary.

:::: callout

## An art and a science

File format research is both an art and a science. Looking for patterns
in files is a structured activity. Making a judgment about how strict to
be or when to be flexible is more of an art.

If we make the signature too strict, we’ll fail to identify real world
examples that do not strictly adhere to a specification, e.g. through
errors or misunderstanding of the spect. If we make it too flexible, we
risk false positives.

::::

## PRONOM

* File format signatures are useful to all of us. PRONOM provides
 a central registry of signatures.
* PRONOM is hosted and managed by The UK National Archives and it is
free to use.
* PRONOM is used across the community and by multiple tools to help us
identify our digital recorrds.
* PRONOM is not comprehensive, far from it.
* When you discover something not identified by PRONOM's tooling, you will
want to embark on researching and creating a new signature, **_which is what
we’re going to look at in the following sections_**.

> Once you’ve created a new file format signature, please contribute it to
> PRONOM!

<!-- NB. Keypoints should appear at the end of the markdown file. Aesthetically
     it looks like it's better with an additional newline so adding that
     here and using this comment as a separator to make it easy to read
     content.
-->

<br>

::::::::::::::::::::::::::::::::::::: keypoints

By the end of this workshop, you should be able to:

* Look into container files
* Investigate their contents
* Identify consistent patterns in file names and byte sequences
* Express patterns in PRONOM syntax
* Create a contaiiner signature file
* Use your signature file locally
* Contribute signatures to PRONOM
<br>
If it's the beginning of your PRONOM journey, thank you for joining in! If
you are supercharging your PRONOM knowledge, then we hope you enjoy the
information we can impact.
<br>
Enjoy!

::::::::::::::::::::::::::::::::::::::::::::::::
