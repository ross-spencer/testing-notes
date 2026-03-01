---
title: "A Brief XML Primer"
teaching: 0    # teaching time in minutes
exercises: 0    # exercise time in minutes
---

:::::::::::::::::::::::::::::::::::::: questions

* TODO

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

* TODO

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

::::::::::::::::::::::::::::::::::::: keypoints

* TODO...

::::::::::::::::::::::::::::::::::::::::::::::::
