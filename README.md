# Reverse the string
--------------------------------------------------------------------------
#Using Stringbuffer
--------------------
String given="Hello";

StringBuffer buffer=new StringBuffer();
buffer.append(given);
String reversed=buffer.reverse();
System.out.println("Reversed string is: " + reversed);

---------------------------------------------------------------------------
#using own logic
----------------
String given="Hello";
String reversed="";

Char[] Characters=given.toCharArray();
for(int start=given.length-1; start>=0;start--)
{
reversed=reversed+Characters[start];
}
System.out.println("The reversed string is: "+reversed);

------------------------------------------------------------------------------
#using collections
-------------------
String given="Hello";

Char[] Characters=given.toCharArray();
List<Character> array=new ArrayList<Character>();
for(Character Chars:array)
array.add(chars);
{
Collections.reverse(array);
ListIterator iterator=array.listiterator();
while(iterator.hasNext())
{
System.out.println("Reversed string is: "+iterator.next);
}
}

----------------------------------------------------------------------------------
