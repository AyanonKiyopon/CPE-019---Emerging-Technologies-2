# CPE-019-Emerging-Technologies-2
## INTRODUCTION:
Good day! I am **Christian Jay Cuevas**, an undergraduate student currently pursuing BS in Computer Engineering in Technological Institute of the Philippines - Quezon City. This repository is used for the hands-on activities in our course which is the Emerging Technologies 2. The activities here will be mainly python based and will be focused in machine learning. 

![image](https://github.com/AyanonKiyopon/CPE-019---Emerging-Technologies-2/assets/143265700/6fb89f23-ef40-40cd-a377-3614308f244a)


## TABLE OF CONTENTS:
1. **Hands-On 1.1** - Python Challenge (Not Recorded and No Folder)
2. **Hands-On 2.1** - Working-with-Python-and-SQLite 
3. **Hands-On 3** ...

## DESCRIPTION OF EACH HANDS-ON:
1. An assessment of our python capabilities which will be used as a basis for the pacing of our course.
2. An activity which introduces us to SQLite functions and how to integrate it to python language.


## HOW EVERY HANDS-ON WORKS AND SUMMARY OF LEARNINGS:
1. Basic programming with python which can be executed in the Google Colab. Includes basic manipulation of lists, dictionaries, basic built-in functions, creation of functions, and creation of classes.
   * To split strings, use .split() which creates a list of the separated strings. The default separator is whitespace but the parameters of .split() allows you to specify the separator and maxsplit.
     > (string.split(separator, maxsplit))
   * You can use .format() to automatically change the values of the curly brackets {} in a string based on the specified variable inside the curly brackets or the sequence of the values.
     > (string.format(value1, value2...))
   * You can get a specific value or access a nested list by using multiple indices.
     > (lst = ['a','b',[4,10,11],['c',[1,66,['this']],2,111],'e',7]
     > 
     > print(lst[3][1][2][0]))
   * You can get a specific value or access a nested dictionary by using multiple indices.
     >d = {'k1':['val1','val2','val3',{'we':['need','to','go',{'deeper':[1,2,3,'that']}]}]}
     >
     >print(d['k1'][3]['we'][3]['deeper'][3])
   * Manipulating strings and getting a specific value inside it can be accomplished by using slicing notation. Slicing notation works by getting a specific element in a string, list or array.
     > _Slicing Notation_
     > 
     > string[start:stop:step]
     > 
     > _Sample Algorithm_
     > 
     > for i in range(len(x)):
     > 
     >    if(find == x[i]):
     > 
     > return x[i+1:]

2. The usage of SQLite adds an additional capability to the tradational python programming. It allows us to manipulate databases without the need for a separated software like MySQL. 

## FUTURE APPLICATIONS OF EACH HANDS-ON:
1. It can be used for a refresher when programming with python.
