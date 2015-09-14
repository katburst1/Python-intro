<h1>Python</h1>


![python-comic](https://imgs.xkcd.com/comics/python.png "XKCD")
----------------------------------------
<h2>Python Background</h2>
<li>Multi-paradigm programming language- supports OOP and Structured Programming</li>
<li>Small core language, large standard library</li>
<li>Can be easily embedded in existing applications</li>
<li>Code emphasizes readability</li> 
<li>Has a weird cult following</li>

----------------------------------------
<h2>Example Code</h2>
<pre><code>
print "hello world!"
</code></pre>
<pre><code>
comment: #this is a comment
</code></pre>
variable assignments can be done on more than one variable at a time:
<pre><code>
a, b = 2, 4
</code></pre>
lists are similar to arrays
<pre><code>
mylist = []
mylist.append(1)
mylist.append(2)
mylist.append(3)
print(mylist[0]) # prints 1
print(mylist[1]) # prints 2
print(mylist[2]) # prints 3
</code></pre>
forms a string with a repeating sequence
<pre><code>
lotsofhellos = "hello" * 10
</code></pre>

-------------------------------------
The "%" operator is used to format a set of variables enclosed in a "tuple" (a fixed size list), together with a format string, which contains normal text together with "argument specifiers", special symbols like "%s" and "%d"

This prints out "Hello, John!"
<pre><code>
name = "John"
print "Hello, %s!" % name
</code></pre>
This prints out "John is 23 years old."
<pre><code>
name = "John"
age = 23
print "%s is %d years old." % (name, age)

%s - String (or any object with a string representation, like numbers)
%d - Integers
</code></pre>

----------------------------------------
<pre><code>
astring = "Hello world!"
</code></pre>
<pre><code>print len(astring)</code></pre> prints the length of astring
<pre><code>print astring.index("o")</code></pre> prints out 4, because the location of the first occurrence of the letter "o" is 4 characters away from the first character.
<pre><code>print astring.count("l")</code></pre> counts the number of "l" in the string
-----------------------------------------------
<pre><code>
	Instance variables are for data unique to each instance and class variables are for attributes and methods shared by all instances of the class:
</code></pre>
<pre><code>
	class Dog:

    kind = 'canine'         # class variable shared by all instances

    def __init__(self, name):
        self.name = name    # instance variable unique to each instance

>>> d = Dog('Fido')
>>> e = Dog('Buddy')
>>> d.kind                  # shared by all dogs
'canine'
>>> e.kind                  # shared by all dogs
'canine'
>>> d.name                  # unique to d
'Fido'
>>> e.name                  # unique to e
'Buddy'
</pre></code>
--------------------------------------
<h2>Python Frameworks</h2>
[DJANGO](https://www.djangoproject.com/start/)
[FLASK](http://flask.pocoo.org/)
[PYRAMID](http://www.pylonsproject.org/)

----------------------------------------
<h2>Further Resources</h2>
[Beginner's Guide](https://wiki.python.org/moin/BeginnersGuide/Programmers)
[Learn Python the Hard Way](http://learnpythonthehardway.org/book/)
	
	


