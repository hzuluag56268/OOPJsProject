This is a link to the GitHub repository:

https://github.com/hzuluag56268/OOPJsProject.git


Object oriented programming is a style in coding in which code is written by creating objects that have properties and methods. I would use it to make my code more efficient since I can tap into the functionality of inheritance.  So to speak, it lets me create general objects and then create more specific objects with added properties and methods.  

This OOP pattern would be a better choice when the same objects are used often in the project since it lets you re-use the code. It would also work when  different objects have  properties and methods in common because you can simply inherit, modify and use those that are relevant to the object in question. 

A project that would benefit from an oop structure would be one that had objects which relate to one another with various similarities.  In this case, the application  is sort of an University database. The purpose of it is to store and display relevant information of both teachers and students. Students have a subcategory for scholarship holders.  On home page the user can create a teacher, student or a student with scholarship with its pertinent information. This required information is the following:  

The teacher object has properties  such as experience in years and faculty, whereas a student has year, which is the scholar year the student is currently studying, and two boolean values representing if the student is international and is working. Teacher and student both inherit from the University member object which has the properties: id, name, age, sex, and a boolean value that represents whether the member has children.  Finally, the scholarship Holder inherits from the student object and has own properties: scholarship percentage and English level denoted by the  TOEFL exam.  

On home page the user will also find three buttons, one for teacher, student and scholarship placeholder. On the teacher page, the user can enter an ID and display its information including the one inherited from the University member object. In addition, that information can also be modified there.  This functionality is quite similar to the student and scholarship placeholder page, where the information is displayed with the ID number.   