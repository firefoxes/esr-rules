

# Rule of Modularity

Developers should build a program out of simple parts connected by well defined interfaces, so problems are local, and parts of the program can be replaced in future versions to support new features.

This rule aims to save time on debugging complex code that is complex, long, and unreadable.

---

# Rule of Simplicity

Developers should design for simplicity by looking for ways to break up program systems into small, straightforward cooperating pieces.

This rule aims to discourage developers’ affection for writing “intricate and beautiful complexities” that are in reality bug prone programs.

---

Focusing on one thing:

* UUID
* URI

Ruby Example: `STDOUT.write` is simpler than `puts` which is simpler than `p`

Complex (many things):

* ActiveRecord (OMG)
* jQuery
* Ruby/Node/Java
* Browser
