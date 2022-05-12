# IndexOperaters_py
"""
index operater [] = gives to access to a sequence's element (str,list,tuples)

"""

name = "bro code"

if(name[0].islower()):
    name =name.capitalize()
# print(name)


fist_name = name[0:3].upper()
last_name = name[4:].lower()

last_char = name[-1]# -ve indexing
print(last_name)
