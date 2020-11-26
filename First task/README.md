# Part one

### Project scope

Our project will be focused on working with XML markup language. Why we have to use so outdated format? 

Answer is simple - printing industry is working with the standard which is called Job Definition Format (JDF). This format is based on XML and it is storing all the information about job ticket, message description and message intercharge (and it's also widely used in Prinect system.) If you are interested in this topic, you can find more information about it at the following address: 
[JDF in a nutshell - presentation](https://docs.google.com/presentation/d/1wcOl7Hj0GaYH8QJPGoi7DVP0l-hAVGzs8tRDcf0wmU8/edit?usp=sharing)
[CIP4 JDF standard homepage](https://confluence.cip4.org/display/PUB/JDF)

We will focuse on creating Python objects and relations between them which can be later translated into XML. In order to not to obscure the view of the Python concepts themselves, some simplifications will be applied. During our work we will create a book project which will contains not only content of the book, but also the printing process reduced to essentials.

## Task

Inside of the pages.py file create function, which as an input will take number of words and count how many pages will be filled with them. Let's assume that standard page has 300 words. 

**Input**: integer, between 15000 to 300000 - this will be the number of words
**Return**: integer, number of pages which is needed to contain all of the words

Important! Prepare input validation inside function body.

## Helpful links

[Functions](https://www.learnpython.org/en/Functions)
[Loops](https://www.learnpython.org/en/Loops)
[Conditional statements](https://realpython.com/python-conditional-statements/)
