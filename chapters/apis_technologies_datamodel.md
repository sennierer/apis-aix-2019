+++?image=template/img/bg/blue.jpg&position=left&size=30% 100%
@title[Sidebar + Heading]

@snap[west text-white span-20]
@size[1em](Datamodel)
@snapend

@snap[east list-content-concise span-75 text-08]
@ol
- 5 core entities: Person, Place, Institution, Work, Event
- all entities can be interrelated
- fixed set of relation attributes (mini-event)
- unlimited full texts can be attached to entities
- annotations related to entities and relations
- annotations organized in projects
- entities organized in collections
@olend
<br><br>
@snapend

@snap[north-east template-note text-gray]
APIS technical aspects
@snapend

---?image=template/img/bg/blue.jpg&position=left&size=30% 100%
@title[Sidebar + Heading]

@snap[west text-white span-20]
@size[1em](Tool)
@snapend

@snap[east list-content-concise span-75 text-08]
@ul
- list views for entities and relations
- detail and create views fo entities
- autocompletes for entities:
	+ query internal and external resources in one autocomplete
	+ fetch metadata on save and create new objects
	+ GND, Geonames as examples
- annotation of full texts:
	+ offset annotations
	+ stored in projects
	+ >> multiple annotations possible
@ulend
<br><br>
@snapend

@snap[north-east template-note text-gray]
APIS technical aspects
@snapend
---

@uml[midpoint bg-white ](uml/datamodel_apis.puml)
