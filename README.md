Example Code:

print "hello world!"

comment: #this is a comment

#variable assignments can be done on more than one variable at a time:

a, b = 2, 4

#lists are similar to arrays
mylist = []
mylist.append(1)
mylist.append(2)
mylist.append(3)
print(mylist[0]) # prints 1
print(mylist[1]) # prints 2
print(mylist[2]) # prints 3


#forms a string with a repeating sequence
lotsofhellos = "hello" * 10
#####################################-------------------------------------
#The "%" operator is used to format a set of variables enclosed in a "tuple" (a fixed size list), together with a format string, which contains normal text together with "argument specifiers", special symbols like "%s" and "%d"

# This prints out "Hello, John!"
name = "John"
print "Hello, %s!" % name

# This prints out "John is 23 years old."
name = "John"
age = 23
print "%s is %d years old." % (name, age)

%s - String (or any object with a string representation, like numbers)
%d - Integers
###############################----------------------------------------
astring = "Hello world!"

print len(astring) ## prints the length of astring

print astring.index("o") ###prints out 4, because the location of the first occurrence of the letter "o" is 4 characters away from the first character.

print astring.count("l") ##counts the number of "l" in the string
###################################--------------------------------------
