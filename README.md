


# Kata--Test Driven Development

Simple, easy kata to learn and practice Test Driven Development ( C#)

## :alien: Kata

You are given strings of different lengths. if the number of vowels are more than 30% of the string length then insert 'mummy' for each continous set of vowels.

## :gem: Compiling from source

Clone this repository to your machine, compile and test it:

```sh
git clone https://github.com/adarshkavallore/Katas--TDD-.git
cd tdd-demo-mummifier
dotnet test
```

## :construction_worker: Use cases

This project was designed do cover the following use cases and requirements:


1.""  -> ""                           //empty string

2."str" ->"str"                       //no vowels

3."a"->"mummy"                        //single vowel

4."blah"->"blah"                      //<30% length

5."bla"-> "blmummy"                   //>30% length

6."blaa"->"blmummy"                   //continous vowels

7."blaaha"->"blmummyhmummy"           //multi sets of vowels

8."blA"->"blmummy"                    //capital letters

9.Null-> raise exception              //null checks


## :computer: Tech stuff

* .NET Core 2.0
* nUnit


### :alien: Create a Test Class for the Mummifier use case.
### :alien: Then begin with the Mummifier implementation.
### :alien: Refactor the code.
### :alien: Add more tests and continue with the implementation.
### :alien: Refactor and Repeat.