Download Link: https://assignmentchef.com/product/solved-ece39595-homework-10
<br>
You should create a templated class TwoTuple that holds two values, i1 and i2. i1, i2 and TwoTuple should all have operators ==, &lt; and &gt; defined on them.  TwoTuple should also define operator&lt;&lt;, which is given to you. Note that its definition is inlined into the .h part of the template definition – this is the preferred way to do this. Given TwoTuple objects o1 and o2,

o1 &lt; o2 if o1.i1 &lt; o2.i1 or o1.i1 == o2.i1 and o1.i2 &lt; o2.i2.

and

o1 == o2 if o1.i1 == o2.i1 and o1.i2 == o2.i2 otherwise o1 &gt; o2.

Your Node should be able to hold TwoTuple objects, and form a tree of TwoTuple objects.

I would strongly suggest that when doing your homework, you comment out the lines in HW12.cpp that use TwoTuple, get the program working with the Node template, and then implement the TwoTuple template.

You are also provided Int.h Int.cpp and main.cpp.  You should need to change these files except to comment out things in main.cpp, as suggested in the last paragraph.

<em>Remember to always define the .h and .cpp parts of a templated class C in the file C.h</em>.