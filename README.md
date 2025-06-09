# Backstage class diagram representation
> make backstage knowledge (red hat developer hub) easier

![backstage-uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/jovemfelix/backstage-catalog-model/master/docs/uml-en_US.iuml)


# Core Entities
We model software in the Backstage catalogue using these three core entities (further explained below):

* Components are individual pieces of software
* APIs are the boundaries between different components
* Resources are physical or virtual infrastructure needed to operate a component

![Core-Entities](https://backstage.io/assets/images/software-model-core-entities.drawio-51a40db7ca2e0d0026d99f519657677f.svg)

# Ecosystem Modeling
A large catalogue of components, APIs and resources can be highly granular and hard to understand as a whole. It might thus be convenient to further categorize these entities using the following (optional) concepts:

* Systems are a collection of entities that cooperate to perform some function
* Domains relate entities and systems to part of the business


# Reference
* https://backstage.io/docs/features/software-catalog/descriptor-format/#kind-template
* https://backstage.io/docs/features/software-catalog/system-model