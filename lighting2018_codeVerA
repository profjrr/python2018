
# -*- coding: utf-8 -*-
"""
Created on Mon Jul 23 13:57:38 2018

@author: jrree
"""

## Starting out right with Assertions in Python
##asserts 2018 verC
##
##
### Python asserts presented by Professor Reed
### last updated (27-JUL-2018)
### for Python 3.4+
###Lighting Talks -- PyOhio 2018 -- ProfJRR
##
##
### NOW WITH ASSERTS!!! ###
import pytest

#float(i = 1)
#print("int(123) is:", int(123))

def mainasertions(x):
# x=1
# x=-1
# print("int(123) is:", int(123))
assert(x>=0),("### x is not greater than or equal to zero")
print("asserting x is greater than or equal to zero")
print("x is: ",x)
print()

## determines x is greater than a negative value")
#
##
### --- Professor Reed's test driver area --- ###
##
def testMyassertions(x):
### Part II ###
## int(x)
print()
print("=== Testing My Assertions ===")
print()
x=1
print("with a value of 1 for test #1")
mainasertions(x)
x=0
print("with a value of 0 for test #2")
mainasertions(x)
x=-1
print("xxx should never execute or occur xxx")
print("with a value of -1 for test #3")
mainasertions(x)
# final test or otherwise ###
print()

### Testing values and area follow: ##
##
#print("[negative value test1:]")
#x = -1
##x = 0
##x = 999
##x = 1011
testMyassertions(x)
##
##
### note: the test driver area above is a replacement for main()
##
### Professor Reed uses test cases instead of main()!
##if __name__ == '__main__':
## main()

