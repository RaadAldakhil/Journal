# C++ Coding Reference
References and guide on C++

## Language Specifics With C++
Let's face it: C++ is not an easy language to learn. Mastering the basics of C++ means you've developed some strong skills.

First, learn the basics of object-oriented programming; also know data structures and algorithms inside and out. For example, know how to build a linked list, even though you'll probably use one that's part of an existing library.
Mastered those? Here are some more items:
* Learn what stack variables are and how objects can be allocated on the heap; take this to the next level and understand that when you call **new**, you will typically store a pointer to the object in a variable; the object lives in the heap and the variable lives on the stack. Learn if and when these variables go out of scope. Why is this important? If you return the address of a local variable, you're going to (a) create bugs and (b) anger other programmers.
* Learn how references truly work, and how they're different from pointers. Understand how variables are passed in functions, and about passing an entire structure versus passing a pointer to a structure into a function.
* Learn how arrays get allocated with new and delete, and how to create an array that you can safely return from a function.

Got a handle on all of the above? You're doing well. Here are a few new things to learn:
* Virtual methods
* Virtual destructors
* Operator overloading
* How templates work (functions, classes. and instantiation)
* Correct syntax
* The standard library, as well as Boost (practice them both)

Spend time with professional code such as some of the bigger open source C++ projects on GitHub. This will allow you to "learn from the masters," so to speak.
Here's some insight into how many senior developers view entry-level developers: Most aren't patient with them. They expect the entry-level developers to be so good at coding that they'll move up to senior level quickly. Senior level developers do not want to hand-hold entry-level developers.
In other words, if you start a C++ job and ask a senior developer what a reference is, the senior-level developer is going to get angry. It's not that they're angry people in general; it's just that they have a job to do... and that job isn't to teach programming. While they don't expect entry-level developers to make architectural decisions, they do expect them to be strong, competent coders; they're also impressed when entry-level developers quickly learn what they need to know and barrel forward on their own.

## Things you should know
* Everything from C
* Function overloading
* Operator overloading
* Member functions, constructors, and destructors
* Access specification
* Inheritance and virtual functions
* Exceptions
* Namespaces, name lookup and ADL
* Templates
* References, rvalue references, and move semantics
* RAII and smart pointers
* Lambdas
* Constexpr

## Book Roadmap 1
* Teach Yourself C++ in 24H (Do ASAP in short time)
* A Tour of C++
* Structure & Interpretation of Computer Programs(Read alongside A Tour of C++)
* C++ Primer(Only do exercises, starts at CH.1)
* Programming: Principle & Practices using C++(Tail Stroustrup by 3 Chapters)
* Introduction to Algorithms(Take all your time here, reference back to 'Programming: Principle & Practices using C++' if necessary)

## Book Roadmap 2
* C++ Primer / The C++ Programming Language
* Exceptional C++ / Effective C++ / The C++ Standard Library
* More Exceptional C++ / More Effective C++ / C++ Concurrency in Action / Effective STL
* Exceptional C++ Style / Effective Modern C++ / The Boost C++ Libraries
* C++ Coding Standards / Optimized C++
* Inside The C++ Object Model / C++ Templates / Elements of Programming
* Imperfect C++ / Modern C++ Design / From Mathematics to Generic Programming

## Book Roadmap 3
* Introductory, no previous programming experience:- C++ Primer / Programming: Principles and Practices Using C++
* Introductory, with previous programming experience:- A Tour of C++ / Accelerated C++
* Best practices:- Effective C++ / Effective Modern C++ / Effective STL
* Intermediate:- More Effective C++ / Exceptional C++ / More Exceptional C++ / Exceptional C++ Style / Exceptional C++ Style / C++ Coding Standards / C++ Templates: The Complete Guide
* Advanced:- Modern C++ Design / C++ Template Metaprogramming / C++ Concurrency In Action / Advanced C++ Metaprogramming
* Reference Style - All Levels:- The C++ Programming Language / C++ Standard Library Tutorial and Reference / The C++ IO Streams and Locales
* C++11/14/17/… References:- The C++ Core Guidelines / The C++ Super-FAQ / cppreference.com
* Classics / Older:- The Design and Evolution of C++ / Ruminations on C++ / Large Scale C++ Software Design / Inside the C++ Object Model / The Annotated C++ Reference Manual / Thinking in C++ / Scientific and Engineering C++: An Introduction to Advanced Techniques and Examples

# C++ Notes
Notes from various C++ tutorial and programming references and books.
