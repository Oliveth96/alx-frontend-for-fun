<h1>Markdown to HTML</h1>
<br>


**DESCRIPTION**
<p>Markdown is awesome! All your README.md are made in Markdown, but do you know how GitHub are rendering them?</p>

<p>It’s time to code a Markdown to HTML!</p>

<br>

**REQUIREMENTS**

<ul>
<li>All your files will be interpreted/compiled on Ubuntu 18.04 LTS using python3 (version 3.7 or higher)</li>
<li>The first line of all your files should be exactly #!/usr/bin/python3</li>
<li>A README.md file, at the root of the folder of the project, is mandatory</li>
<li>Your code should use the PEP 8 style (version 1.7.*)</li>
<li>All your files must be executable</li>
<li>All your modules should be documented:  python3 -c 'print(__import__("my_module").__doc__)'</li>
<li>Your code should not be executed when imported (by using if __name__ == "__main__":)</li>
</ul>

<br>
<br>



<h4> TASKS</h4>

| S/N | DESCRIPTION | FILE |
|---- | ----------- | ---- |
|0.  Start a script |<p>Write a script markdown2html.py that takes an argument 2 strings: <li>First argument is the name of the Markdown file</li><li>Second argument is the output file name</li></p><p>Requirements:<li>If the number of arguments is less than 2: print in STDERR Usage: ./markdown2html.py README.md README.html and exit 1</li><li>If the Markdown file doesn’t exist: print in STDER Missing <filename> and exit 1</li><li>Otherwise, print nothing and exit 0</li></p>|[markdown2html.py](https://github.com/Oliveth96/alx-frontend-for-fun/markdown2html.py)|


<br>
<h2>Author</h2>

[Ndubuka Oliveth](https://github.com/Oliveth96)