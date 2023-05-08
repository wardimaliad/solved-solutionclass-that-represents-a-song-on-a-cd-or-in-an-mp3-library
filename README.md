Download Link: https://assignmentchef.com/product/solved-solutionclass-that-represents-a-song-on-a-cd-or-in-an-mp3-library
<br>
Programming Problem:Design, implement, and test a class that represents a song on a CD or in an MP3 library. If you did Programming Warm-Up Exercises 4 through 6, you already have a good start. It should have members for title, album, artist, playing time in minutes and seconds, and music category. The music category is represented by an enumeration type calledCategory; make up an enumeration of your favorite categories. The class should have a constructor that allows all of the data members to be set, and a default constructor that sets all of the data members to appropriate empty values. It should have an observer operation for each data member, and an observer that returns all of the data for the song as a string. An observer that compares two songs for equality should be developed as well.Programming Warm-Up Exercises4. Write the specification for a Song ADT (Abstract Data Type) that represents a song entry in an MP3 library. It should have fields for title, album, artist, playing time in minutes and seconds, and music category. The music category is represented by an enumeration type called Category. (See Attachment A for clarification of two questions below.)a. What operations should Song ADT have?

b. What observers should Song ADT have?

5. Write the specification file for class Song that implements the Song ADT from Exercise 4.

6. Write the implementation file for the class Song from Exercise 5.

Attachment A

To aid in understanding the two questions put in Item #4 above, there is a context that must be considered. This text is from Dale and Weems book Programming and Problem Solving with C++: Comprehensive, Sixth Edition in Chapter 12 – Classes and Abstractions: 12.1 Abstract Data Types at bottom after Theoretical Foundations – Categories of Abstract Data Type Operations.In general, the basic operations associated with an abstract data type fall into one of three categories: constructors, tran sformers, and observers.

Constructor An operation that initializes a new instance (variable) of an ADT.

Transformer An operation that changes the value of the ADT; also known as a mutator.

Observer An operation that allows us to observe the state of an instance of an ADT without changing it; also known as an accessor.

An operation that initializes a new instance of an ADT (such as a list) is a constructor. Operations that change the value of an ADT, such as inserting an item into a list, are transformers (in the programming languages research community, they are also called mutators because they yield a mutation of the ADT’s value). An operation that takes one list and appends it to the end of a second list is also a transformer.

A Boolean function that returns true if a list is empty and false if it contains any components is an example of an observer (also known as an accessor). A Boolean function that tests whether a certain value is in the list is another kind of observer.

Some operations are combinations of observers and constructors. An operation that takes two lists and merges them into a (new) third list is both an observer (of the two existing lists) and a constructor (of the third list).

In addition to the three basic categories of ADT operations, two other categories are sometimes defined: destructors and itera tors. A destructor is the opposite of a constructor; it cleans up an instance of an ADT just before its storage is released for reuse. An example of an iterator is an operation that returns the first item in a list when it is called initially and returns the next item with each successive call.

Destructor An operation that cleans up the state of an ADT instance just prior to releasing its storage for reuse.

Iterator An operation that allows us to process—one at a time—all the components in an instance of an ADT.


