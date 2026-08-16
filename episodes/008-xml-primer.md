---
title: "A Brief XML Primer"
teaching: 0    # teaching time in minutes
exercises: 0    # exercise time in minutes
---

:::::::::::::::::::::::::::::::::::::: questions

* What is Extensible Markup Language (XML)?
* How is XML used by PRONOM?
* How do container signatures utilize XML?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

* Gain a basic understanding of XML
* Understand the structural components of XML
* Recognize that container sygnatures are structured using XML

::::::::::::::::::::::::::::::::::::::::::::::::

# A (very brief) XML primer {#a-(very-brief)-xml-primer}

* XML = e**X**tensible **M**arkup **L**anguage
* Consists of **Elements**, **Attributes**, and **Data**
* Usually starts with a **Prolog**:

```xml
 <?xml version="1.0" encoding="UTF-8"?>
```

* Indentation helps with readability, but is not mandatory and whitespace
(tabs, carriage returns, spaces) are ignored by the XML parser
* Elements *must* have a closing tag
* Elements are hierarchical - they can have child elements
* Attribute values *must* be quoted (single/double)

```xml
<ContainerSignatureMapping schemaVersion="1.0" signatureVersion="38">

  <ExampleElement>Example data</ExampleElement>

</ContainerSignatureMapping>
```

<!-- NB. Keypoints should appear at the end of the markdown file. Aesthetically
     it looks like it's better with an additional newline so adding that
     here and using this comment as a separator to make it easy to read
     content.
-->

<br>

::::::::::::::::::::::::::::::::::::: keypoints

* XML has a basic structure that is required to be well-formed
* XML begins with an XML declaration
* XML elements bookend other information recorded in the format
* Container signatures are structured using XML's hierarchical structure

::::::::::::::::::::::::::::::::::::::::::::::::
