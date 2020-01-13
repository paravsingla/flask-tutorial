---
title: Installation
permalink: /book/installation
key: book-installation
---
Flask is called a "microframework", since the core flask framework is really small and bulk of the work is done by extensions - which means a great amount of flexibility.

## Python

You can download and install Python from the official website. Be sure to download 64-bit installer if your system is 64-bit. I'm going to use Windows 10, since that's what I assume the majority of people reading this will be using. I'll highlight the differences, if any, if you are using other OSes.

We want to add Python to the PATH. For windows, the installer provides you with an option for this. If you forgot it, just open the environment variables and add the location of your python installer.

To make sure you have it added to the path, open a command prompt and type Python.

## Virtual Environment

We are going to work in a virtual environment for the duration of the book. This is good practice regardless.
I'm going to use the package virtualenv. You can use whatever you like.

pip install virtualenv

Now, I'm creating a new folder on my desktop called 'Workspace'. This is where we will work. First, we need to open a command prompt in this folder. To do this, you can either cd into the directory or you can click on the address bar of the file explorer and type cmd and press enter. (See the gif below)

To create a new virtual environment, we run the following command:

python -m virtualenv venv

Here, venv is the name of my virtual environment.

To activate this virtual environment, use:

venv\Scripts\activate

if you're not on windows you can use

source activate


## Talk about pip and explain what creating a virtual environment does.


## Development Environment

Our development environment consists of a text editor, a file explorer and a terminal. While we can use simple text editors like Notepad or gedit or even vim, I would recommend you install something more substantial. I would recommend Atom and Sublime Text, both of which are free to use. For large projects though, I have had a good experience using IntelliJ Idea. I'll be using Atom for the course of this book. But everything I'll show you can be accomplished by any of the popular text editors.
