# python_study_note

python important learning points

1. class: use when need attribute+method, center of OOP
    - encapsulatiopn: data/attribute + method
    - inheritance, cleaner, lesser repeat code
    - polymorphism: diffeernt class, but if have same method name, can polymorphism call
    - abstract: create a template ( use abc.ABC & abc.abstarctmethod) with essentiate method defined ( with pass only)

2. python is compiled to byttecode, and run by python-virtual-machine (PVM, interpreter), while c++ is compiled to machine code, run by CPU

3. mutable datatype can be changed after create, list/dict/set
    - immutable can only be reassigned, memory address changed

4. argument pass by object-reference
    - muttable data: passed by reference, i.e., can be updated by function
    - immutable data: passed by value
        - for function to call var in outer fucntion (nested function): use nonlocal
        - for fucntion to call var in outside(non-fucntion): use global

5. list comprehension:
    -[a for a in range(10)]
    -[a if a==b else aa for a in range(10)]

6. lambda:
    - y=lambda x:x*k #k can be vairable form global, x is the argument
    - y=lambda a,b=0:a*b #can set default value
    - y=lambda a,b=None: a*(b if b is not None else 0) # use if else
