---
title: "Creating a Container Signature"
teaching: 0    # teaching time in minutes
exercises: 0    # exercise time in minutes
---

:::::::::::::::::::::::::::::::::::::: questions

* How do we apply the knowledge we have gleamed so far?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

* Create your first container signature file
* Load your signature file in DROID or Siegfried
* Identify questions that you may have of the process

::::::::::::::::::::::::::::::::::::::::::::::::

:::: challenge

## Task: Creating and Testing Container Signatures

_20 mins.._

*  Manually create your signatures using the template.

TODO: add the XML template to the resources section of the workshop

FFDev.info [https://ffdev.info/](https://ffdev.info/) provides a form for ease of creation of standard and container signature files.

* To use new signatures they will need to be added to the right folders in the droid config:

```bash
$ROOT/$USERHOME/.droid6/…
```

Binary and Container signatures are contained in separate folder within the
.droid6 folder. This folder is likely hidden at the root of your user folder.
Signatures must have a unique signature version number at the beginning of the
XML so as not to conflict with other signature files. These can be manually
moved into these folders or regular signature loaded within DROID.

If you are using Siegfried, you can use the Roy tool to build a new signature
using your new signatures.

:::::: hint

Check out the "try-it" section of ffdev.info to try this signature file in
the browser with your test files.

::::::

::::

![Screenshot of the signature development utility.](./fig/ffdev-info-1.png){alt="TODO"}

![Screenshot of the droid6 folder showing locations for the container signatures and regular signature files.](./fig/droid6-folder-1.png){alt="TODO"}

<!-- NB. Keypoints should appear at the end of the markdown file. Aesthetically
     it looks like it's better with an additional newline so adding that
     here and using this comment as a separator to make it easy to read
     content.
-->

<br>

::::::::::::::::::::::::::::::::::::: keypoints

* You can use an XML template or ffdev.info to create a signature file
* Signature files exist in specific locations on your hard disk
* ffdev.info allows you to test your files in the web-browser

::::::::::::::::::::::::::::::::::::::::::::::::
