# Markdown Links

This is a library to check if your link is working properly through a Markdown file
## summary 
[Markdown](https://pt.wikipedia.org/wiki/Markdown) is a lightweight markup language
that you can use to add formatting elements to plaintext text documents. It's used on 
many platforms that handle text (GitHUb, forums, blogs, etc) and it's very common 
find files with this format in any repository (starting with the traditional 'README.md').

'Markdown' files usually contain_links_ which may be broken or that are no longer 
valid, decreasing the value of the information conntained.

is possible with this library :
- Analyze witch .md extension;
- Check if there is any links in the MarkDown file, otherwise report an error message warning
that there are no links in the file .
- when Finding the links there's  an option to list or check them
using the 'validar' function, which returns a set with the links and ther http status.

## Install
In the terminal, run the command:
'npm i scan-links'
Use this way command to run in terminal:
'node <name of  file .js> <path of file .md> validar'
*** The file path can be relative to the directory you are running the library or absolute.



