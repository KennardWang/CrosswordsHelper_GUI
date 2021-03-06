# Crossword-Helper
### An interesting story

> ![puzzle](https://kennardwang.github.io/ImageSource/Project/CrosswordsPuzzle.png)

> Kennard is playful boy who is very interested in crosswords. ( a kind of puzzle )  
> Kennard is not an expert in English, so that sometimes he has no idea about the words of the puzzle.  
> Now, can you try to write a useful software to help him finish the crosswords ?
------
### Demo

![demo](https://kennardwang.github.io/ImageSource/Project/CrosswordsDemo.png)

+ We all know about dictionary, we can easily find a word if we know the exact character position
+ For example, we define `pattern` as a term consists of character and number

  + `u,3` denotes that the character `u` is on `third` index of the word  
  + Kennard can use foregoing pattern groups `u,3 a,4` if he wants to search a word whose `third` index is `u`, `fourth` index is `a`  
  + He can also select `Top-N` rank words ( ***highest appearance rate*** ) to display, here `N=15`
------
### Development Environment
+ System : **Windows 10 64bits**
+ Language : **C++**
+ IDE : **Qt Creator 4.8.0 (Enterprise)**
------
### File Explanation
+ `Experiment Report` : Study about time complexity of software
+ `QtSrc` : Source code, please open with Qt Creator ( choose to open .pro file )
+ `TestData` : Used to generate a dictionary
+ `Design Report` : Detailed report
------
### Download
+ [Release](https://github.com/KennardWang/CrosswordsHelper_GUI/releases)
------
### Tutorial
+ [Design Report](https://github.com/KennardWang/CrosswordsHelper_GUI/blob/master/Design%20Report.pdf)
------
### License  
+ [MIT License](https://github.com/KennardWang/CrosswordsHelper_GUI/blob/master/LICENSE)
------
### Author
+ Kennard Wang ( 2020.6.1 )
------
