---
title: "Container file formats"
teaching: 0    # teaching time in minutes
exercises: 0    # exercise time in minutes
---

:::::::::::::::::::::::::::::::::::::: questions

* TODO

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

* TODO

::::::::::::::::::::::::::::::::::::::::::::::::

# Container-based Formats {#container-based-formats}

Consists of multiple items/subfiles, contained within a single containing file structure.

| *What containers are (DROID @ present)* | *What Containers are not* |
| :---- | :---- |
| ZIP & OLE-based contained formats  Examples include Microsoft Word 97-2003 .doc (OLE-based), Microsoft Word 2007 onwards .docx (Zip-based), ePub (Zip-based).  | Not *currently* supported by DROID include Info-Tech Storage Format (ITSF), installer files (e.g. .msi), GZIP (often used to compress otherwise inefficient formats, such as the XML-based Gnumeric file format) |

*\> Within A/V, formats such as MP4 and MXF are also referred to as container formats, and they may contain distinct audio and video streams, subtitles and more. DROID **does not** deal with these at a container level, just binary identification (**MediaInfo is your best friend\!**)*

—-

# Container-based Formats {#container-based-formats-1}

Consists of multiple items/subfiles, contained within a single containing file structure.

Examples on the just solve it wiki:

OLE2:

* [http://fileformats.archiveteam.org/wiki/Category:Microsoft\_Compound\_File](http://fileformats.archiveteam.org/wiki/Category:Microsoft_Compound_File)


ZIP:

* [http://fileformats.archiveteam.org/wiki/Category:ZIP\_based\_file\_formats](http://fileformats.archiveteam.org/wiki/Category:ZIP_based_file_formats)

—-

![A screenshot from a wiki of a list of files that use ZIP - 112 pages are listed][image13]![A screenshot from a wiki of a list of files that use OLE2 - 91 pages are listed][image14]**OLE2**: 91 Pages
**ZIP**: 112 Pages
—-

Like Matryoshka Dolls, but the Dolls are directory paths, filenames and file formats…
![Matryoshka dolls displayed with the purpose of illustrating how container signatures can be seen as files within files within files.][image15]![][image16]**zip**
**![][image16]![][image17]xml**
**ole2**
**![][image18]jpg**
**![][image19]   \***
**![][image17]![][image20]  \***
**json**

—-




::::::::::::::::::::::::::::::::::::: keypoints

* TODO...

::::::::::::::::::::::::::::::::::::::::::::::::
