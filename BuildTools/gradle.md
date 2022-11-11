# Gradle Cheat Sheet

- declarative vs imperative
- conventions vs adaptability 
- elaboration of groovy lang, DSL Extension of Groovy
  - can add imperative Groovy code in build

#### Resources
- [ A Gentle Introduction to Gradle ](https://www.youtube.com/watch?v=OFUEb7pLLXw)
- [Introduction to Groovy and Gradle](https://www.youtube.com/watch?v=fHhf1xG0pIA)
- https://gradle.org/
- [gradle dsl](https://docs.gradle.org/current/dsl/index.html)

## Tasks
- task is an object
- task has API
- dependency and order
- look up gradle DSL
- task form a directed acyclic graph

### Configurations
- how are these distinguished from tasks
- observed that configurations run first

## Plugins
- show all tasks imported from plugin
  - gradle tasks --all

### Types
- tasks can inherit from types


## Too Cool Shortcuts
- -q for quiet
- camel case shortcut, e.g. gradle helloWorld => gradle hW
- 