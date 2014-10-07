= rand_svg_generator

This Project will be in OOP and TDD Python

== Structure

The module should be structured in the following classes
``Pattern``
	All Patterns should inherit from this class
``Group``
	All Groups should inherit from this class
``Model``
``View``
``Controller``

=== Patterns

``pattern``'s define how many groups will be placed where on in the view box.
``random`` for example would put a random number of groups in random location

=== Groups

Groups can be any svg group containing how ever many elements.
``stickfigure`` for example maybe a ``group``
All groups have the method ``generate`` which has to accept two integer arguments: ``complexity`` and ``size``.

=== Model

> That's where all the action happens

=== View

The view should be what would be called by a user.
All interaction with the view should be very generic.
It may have the following methods:
``add``
``render``
``clear``

=== Controller

The controller passes the parameters to the Model

== Testing

Think I might use this for Testing
https://docs.python.org/3.3/library/unittest.html

For testing for vaild XML output this might help:
https://docs.python.org/2/howto/regex.html
