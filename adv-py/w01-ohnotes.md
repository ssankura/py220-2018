Open House 1: Advanced Python Programming
=========================================

Class groundrules and principles
--------------------------------
1. What does success on this class look like?
* Participation
* Getting everything right?
2. What do I need to do?
* Try things out
* Ask
* Tell us what you need
* Tell us what can be made better
* As soon as possible!
* You don't have to master everything to pass.
* But you will fail if you don't try.
3. WE ARE HERE TO HELP!
* Use us / contact us
4. Questions?


Object Orientation
==================

How do I get started?
---------------------

1. Recap
* Benefits of OO?
* Any disadvantages?
2. Python syntax for OO is straightforward.
  *. Someone describe...
  .. _a Quick guide to Python OO: https://python.swaroopch.com/oop.html
3. But how do I know which classes I need?
The answer to that is less straightforward. It can be difficult. We'll try to make it as simple as possible.
First, some terminology:
    * Problem domain = the subject area for which we are developing a solution. Could be human resources, sales, accounting,...
    * Model - a simplification of reality. Always wrong, hopefully useful.
    * Diagram - part of a model.
4. Discovering classes (the most simple way possible).
* Think about your problem domain. Find some related documentation (ideally from the person who is requesting the development). Failing that, talk to the person who made the request. Note down what they are asking you.

* When you have the notes and/or documentation, use a highlighter so mark all of the nouns. So, in a human resources example, you might highlight employee, job, department, and company. Think of some others...

* Get a large piece of paper and small yellow stickies. Alternatively, use a modeling tool. For example:

* Modeling tool: https://www.genmymodel.com/
* Now, either write each noun on a separate sticky, or start to build a model. We'll show the modeling tool. It will quickly become be obvious how to do this with stickies.

*So now, watch this demo...

*I'll embed the diagram here when the session finishes. I'll check the code in here too.

5. Some comments:

    5.1 Keep problem domain code separate from technical code. Why?

    5.2 Don't spend too long modeling. Start coding and demoing as soon as you can. Why?

    5.3 Focus on what your classes do, not what they need to know. Why?

    5.4 Define all classes in docstrings. Why?

    5.5 Decomposition and business boundaries. Why?

    5.6 State transitions.

    5.7 GenMyModel is not free; use draw.io (but you lose code generation).

6. Resources:
GenMyModel: https://www.genmymodel.com
DDD book: https://www.infoq.com/minibooks/domain-driven-design-quickly
OO in Python: https://realpython.com/python3-object-oriented-programming/
More Python OO: https://jeffknupp.com/blog/2014/06/18/improve-your-python-python-classes-and-object-oriented-programming/
OO thought process: https://www.amazon.com/Object-Oriented-Thought-Process-Developers-Library/dp/0321861272
Conway's law: https://en.wikipedia.org/wiki/Conway%27s_law
Class models: http://www.agilemodeling.com/artifacts/classDiagram.htm


7. Like this? Want to make it better?
* Clone and branch / amend / push and send a PR.
* File an issue