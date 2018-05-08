# Hello and welcome to year one IBCS!

Here is your user documentation for the first lesson. This guide will take you through the steps of setting up a developers environment. Make sure your are familiar with the following terms:

- [what is user documentation](http://www.teach-ict.com/as_a2_ict_new/ocr/A2_G063/331_systems_cycle/slc_stages/miniweb/pg20.htm)
- [what is a developers environment](https://en.wikipedia.org/wiki/Deployment_environment)
- [IDE](https://computersciencewiki.org/index.php/IDE)
- [package manager](https://en.wikipedia.org/wiki/Package_manager)
- [version control](https://whatis.techtarget.com/definition/version-control)
- [object-oriented programming](https://computersciencewiki.org/index.php/Object-Oriented_Programming)
- [terminal](https://www.quora.com/In-coding-terms-what-is-a-terminal-and-what-is-it-used-for)
- slack
- gitlab


## Slack: Sign up for and download slack.
![slack}(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQOKscP8y4mmanOVVWYYSmVULFZ26DQ671QCgi44ug-oWGpjqXo6A)

This is how you will get class notes and todos. Slack is basically taking all the good parts of email and leaving the bad parts behind

- [slack](https://slack.com/signin)

our team name is ibcs2018


### If you have questions:

In slack, there is a channel called q&a. You can post and answer questions here. I will also check this channel everyday, giving help as needed.

After you download Atom, you can share your code with me much like a google document.

## Download Atom:

This will be your IDE for the course. The terminal is where you will run your code.

- [atom](https://atom.io/)
- enable teletype
- file-icons
- tokamak-terminal
- and your own theme

![atom ided](http://i.imgur.com/qYa5q9S.png)




## Download homebrew:
This is your package manager. Basically, it is an easy way to download software, stay updated, and manage dependencies.
- [brew](https://brew.sh/)
![brew](https://s3.amazonaws.com/stackabuse/media/homebrew-website.jpg)

## Install Oh-my-zsh:
- [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
- check out a few plugins you want to use
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

## Create a GitHub account
![git](https://assets-cdn.github.com/images/modules/open_graph/github-octocat.png)
Make sure you keep it professional. This is how the whole programming world will know you
- [github](https://github.com/)



# Project Initium
What is IBCS? Well, it is meant to teach you about hardware, software, networks, programming, the design cycle, version control, etc. There is a ton of material. So, being organized is key.


The first goal of this lesson is to ensure organization. The second goal is to acquaint you with a project-based class. The final goal is to introduce you to managing ambiguity, meaning, often times you will feel lost, confused, and overwhelmed. This is completely normal when learning a new subject. All you need to do is accept that this is normal and try your best!

Please email me with any questions or if you get stuck! I will be around campus until August.
![dog](http://i0.kym-cdn.com/photos/images/original/000/234/765/b7e.jpg)

## Course Norms:
Every time you write a program, the following will be expected:

- All programs must have comments explaining what your code is doing
- After each program, I will ask you to explain your work in a short paragraph (3-5 sentences)

## Grading
The breakdown is simple:

- projects
- midterm
- final
- ted talk

You will only have two tests this year. A midterm and a final. The exams carry a large weight of your grade and will be built up to in the course. All exams are culminating and will be completed in blue books (aka paper).

The rest of your grade will be determined by projects completed in class- which is a huge bulk of the grade. Projects will consist of commented code and user documentation.

The last major component is giving a ted talk on a culminating project.



## Part One: Terminal Commands

 Learn the terminal! You will complete this project using the terminal. If you don't know what a terminal is our any terminal commands, no worries. That is the goal of this project! The first link goes deep into what/how. The second link will get you to where you need to be. It's the tl;dr version.

- [full story](https://www.learnenough.com/command-line-tutorial)
- [tl;dr](http://www.cs.virginia.edu/diochnos/tips/terminal/basics.html)

In order to create part one, you'll need to know how to:

- navigate in the terminal  		(cd)
- create folders					(mkdir)
- create files 						(touch)
- remove folders/files      		(rm)
- run a ruby and python program
- what a file path is
- root level

These are the basic building blocks of the course.

## Warning: With great power comes great responsibility
- Deleting files/folders in the terminal is a bad idea.
- Dont do anything in the terminal you are unsure about!!!
- Never copy and paste in the terminal!


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


## Part Two: User Documentation

Learn to use [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) and create a bio in unit_0/readme.md. You can fill with any information you like. Just make sure to include:

- what you want out of the class
- experience level
- some sort of picture
- a snippet of code that stands out to you (not too long!)

## Part Three: Hello World
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

## Policies

- Life happens, if you are going to turn work in late I need an email 48 hours before the work is due asking for an extension.

- Office hours are a real thing! Many students will need to take advantage of this during the year

- If you need a letter of reference, allow at least seven days for completion
