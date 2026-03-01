---
title: "Binary Signatures Recap"
teaching: 0    # teaching time in minutes
exercises: 0    # exercise time in minutes
---

:::::::::::::::::::::::::::::::::::::: questions

* TODO

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

* TODO

::::::::::::::::::::::::::::::::::::::::::::::::

# Binary Signature File Format Identification Recap

* Deals with **internal bytecode** - the ones and zeros that make up a
digital file
* Identification based on **pattern matching of hexadecimal values**
* Ideally based on elements clearly defined by the format creator -
‘**magic number**’ sequences
* However, such sequences may not be specified so other elements may need
to be used
* **File format specifications** *really* help. May not be readily available
* Sequences may need to be inferred based on observation, ideally from a
representative and diverse set of known-good file instances
* Main tool used by a file format researcher is a **Hex Editor**
* Based on your pre-workshop feedback, we will look to deliver a workshop on
this topic in the near future\!

## Identification based on specification example:

| TZX Header - information recreated from original source: https://web.archive.org/web/20191028200053/https://worldofspectrum.org/TZXformat.html |  |  |  |
| :---: | :---: | :---: | :---: |
| **length: 10 bytes** |  |  |  |
| **Offset** | **Value** | **Type** | **Description** |
| 0x00 | "ZXTape\!" | ASCII\[7\] | TZX signature |
| 0x07 | 0x1A | BYTE | End of text file marker |
| 0x08 | 1 | BYTE | TZX major revision number |
| 0x09 | 20 | BYTE | TZX minor revision number |

Signature: **5A5854617065211A01**

![A screenshot of the file 'Dynamite Dan 2.tzx' as viewed in a Hex
Editor. The image highlights the first 10 bytes of the file, which
correspond with the data described by the specification in the table
also seen on this slide.](../images/zx-tape-1.png)

## The text file and other formats

* Some files are completely unpredictable and have no official structure.
* For example a .txt file consists of whatever you choose to type in ASCII.
* Other examples of this may include some coding languages or files made up of strings of data.

![Screenshot of a text file that says "A lovely
file format"](../images/text-file-1.png)

![Screenshot the same text file in a hex editor showing its
hexadecimal encoding. The bytes are:
"41 20 6C 6F 76 64 6C 79 20 66 69 6C 65 20 66 6F 72 6D 61 74"](../images/text-file-2.png)

## Task: Hex Editors

Look at the internal bytecode of any file. Do you notice any consistencies in the file? Any patterns in the head, body, and tail?

Use hex editor you have installed, or one online one, such as:

[https://hexed.it/](https://hexed.it/)

***\> Always be wary of uploading sensitive files or data to random web pages\!***

[www.menti.com](http://www.menti.com) 5136 8099

::::::::::::::::::::::::::::::::::::: keypoints

By the end of this workshop, you should be able to:

* TODO...

::::::::::::::::::::::::::::::::::::::::::::::::
