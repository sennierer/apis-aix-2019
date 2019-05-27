+++
@snap[midpoint text-black span-100]
<h2>On top of base serialization, renderers to various formats/ontologies</h2>
@snapend

---
@snap[span-100 text-08]
@code[xml](data/tei_serialization.xml)
@[19-27](Metadata)
@[32-36](Relations to other entities)
@[51](LOD links)
@snapend

---
@snap[midpoint span-100]
<h3>More to come:</h3>
@ul
- Links to vocabularie entries
- Annotation of texts
- ...
@ulend
@snapend

---
@snap[midpoint span-100]
<h3>Basic CIDOC CRM serialization:</h3>
@ul
- Name
- LOD Links
- Place of Birth
- Date of Birth
- >> more planned
- >> ACDHs omnipod
@ulend
@snapend

---
@snap[span-100 text-08]
@code[XML](data/cidoc_serialization_v2.xml)
@[28-33](Basic metadata)
@[51-57](Death event)
@[13-20](related place)
@[8-12](time span)
@snapend

---
@snap[midpoint span-100]
<h3>ProsopogrAPhI serialization:</h3>
@ul
- [ProsopogrAPhi](https://github.com/GVogeler/prosopogrAPhI) 
- Created by Georg Vogeler & colleagues
- Based on the idea of factoids
- easy to implement while allowing for some matching
- Definition in swagger
- contributions & ideas welcome on GitHub
@ulend
@snapend

---
@snap[span-100 text-08]
@code[json](data/prosop_serialization.json)
@[4-16](Metadata on person and source)
@[17,22-30](list of statenments about person, e.g. birth)
@[54-77](several statmentContents in one statement)
@[106-119](new factoid for staments created by user, including revisions)
@[134-153](statement including annotations of biographical text)
@snapend
