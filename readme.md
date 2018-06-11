# Welcome to year one IBCS!
![welcome](http://i0.kym-cdn.com/photos/images/facebook/000/217/040/48ACD.png)

This guide will take you through the basics of getting your computer ready for the course. The advanced options are there in case you want to go above and beyond. Everyone will be at a different level coming into the course. It is alright to know nothing and it is alright to know a lot. I have designed the start of the year to even the playing field so to speak. So, be happy where you are, and know you will learn!


## Download Atom:

This will be your IDE for the course. An IDE stands for integrated development environment. Atom is where you will write and run your code. Where you write your code we will call a text editor, and where you run your code we will call the terminal.

- [atom](https://atom.io/)


![atom ided](http://i.imgur.com/qYa5q9S.png)



## Create a GitHub account
This is where you will store your code and share/build with other. You just need to create an account for now.


![git](https://assets-cdn.github.com/images/modules/open_graph/github-octocat.png)
Make sure you keep it professional. This is how the whole programming world will know you
- [github](https://github.com/)


# Choose Your Own Adventure 
- If you have never used the terminal, you should work via [code academy](https://www.codecademy.com/learn/learn-the-command-line). Just do the nav lesson and know the following and you are all set!

- navigate in the terminal  		(cd)
- create folders					(mkdir)
- create files 						(touch)
- remove folders/files      		(rm)
- run a ruby and python program
- what a file path is
- root level

These are the basic building blocks of the course.


- Else, you have programming experience and have used the terminal for more than 3 months, read the rest of this document.

# Advanced Options 

For Atom:

- enable teletype
- file-icons
- tokamak-terminal
- and your own theme


### Directories at the root level:
Create the following file structure in a dir on your desktop called year_one_ibcs. Make the following file structure at your year_one_ibcs root level:

- unit_0
- unit_1
- unit_2
- unit_3
- unit_4
- oop
- adt
- api
- networks
- control
- extras

These are all the topics covered in year one.

### Directories within each folder

All directories need the following two folders and one file inside of them
- programming
- projects
- readme.md

we can tell readme.md is a file simply by noting the extension at the end. .md tells us that this is a markdown file. Similarly a .rb means ruby, and .py means python.


# Even More Advanced Options 

## Download homebrew:
- [brew](https://brew.sh/)
This is your package manager. Basically, it is an easy way to download software, stay updated, and manage dependencies.

![brew](https://derrekyoung.files.wordpress.com/2016/08/homebrew-mac-osx-logo.png?w=640)

## Install Oh-my-zsh:
- [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
- Optional: check out a few plugins you want to use
![zsh](https://mobomo.s3.amazonaws.com/uploads/external/zsh_prompt_annotated_small.png)

## Install python3 with brew
``` bash
brew install python
```

## Make sure ruby is up to date
```bash
brew install ruby
```
## Install Node
```bash
brew install node
```

## User Documentation

Learn to use [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) and create a bio in unit_0/readme.md. You can fill with any information you like. Just make sure to include:

- what you want out of the class
- experience level
- some sort of picture
- Write the most complex program you can in under 10 lines of code. This might just be a print statement. This is so I may gather the range of experience in the class. Remember, you don't need any experience to take this course!

Example 1

```python3
def kebabize(s):
    new = list(s)
    new_list = []
    for i in new:
        if i.isupper():
            i = "-"+i.lower()
        new_list.append(i)
    done = ''.join(i for i in new_list if not i.isdigit())
    return done.strip('- ')
 ```
 
 Example 2
 ```ruby
 puts " oh boy, this is all I know"
 puts " and that is 100% fine!"
 ```

## Hello World:
![hello world](https://i.ytimg.com/vi/zecueq-mo4M/maxresdefault.jpg)
On the first day of class, you will be asked to run your hello_world program as your introduction to the class and then push your year_one_ibcs folder to github. Hello world is a programming tradition when learning a new language. For your hello world, you will print out a few strings from your bio.

A string is a form of datatype in programming, which is composed of a sequence of characters. Think ""

#### How-to
In year_one_ibcs/unit_0/programming (that's your file path) create a file called hello_world. If you want to use ruby add .rb to the end of the file, and if you want to use python use .py at the end of the file. The extension lets the computer know what language to expect.

Example:

ruby: file path => year_one_ibcs/unit_0/programming/hello_world.rb
```ruby
puts "Hello, I'm Mr. James and I'm from Chicago and loves dogs"
puts "Machine learning is my hobby, and I one day want to live on Mars"
```

python: file path => year_one_ibcs/unit_0/programming/hello_world.py
```python3
print("Hello, I'm Mr. James and I'm from Chicago and loves dogs")
print("Machine learning is my hobby, and I one day want to live on Mars")
```

To run the program, navigate your terminal to the same dir level (or run using your file path). Type ls in the terminal. You should see your program.

```bash
ls
hello_world.py hello_world.rb
```

If using ruby

```ruby
ruby hello_world.rb
```

If using python

```python3
python3 hello_world.py
```

Your terminal should now show the strings you have programmed. Congrats!!!

#### Debug

The terminal will give you clues as to why your program isn't working. For this program, if you are having trouble, check to make sure

- you saved the program
- you have the right file path when running the program

If you can't see your file

```bash
[Errno 2] No such file or directory
```

you aren't in the right location. Use your terminal commands to navigate. Here is your file path: year_one_ibcs/unit_0/programming/hello_world

