<h1>Chai And Python</h1>
<h2>My Python Notes (Ref: Chai and Python Playlist by Hitesh Choudhary)</h2>
<h2>
  <a href="https://www.youtube.com/playlist?list=PLu71SKxNbfoBsMugTFALhdLlZ5VOqCg2s">https://www.youtube.com/playlist?list=PLu71SKxNbfoBsMugTFALhdLlZ5VOqCg2s</a>
</h2>

<h3> 1. How to install Python</h3>
<p>
  1.1. Visit www.python.org.<br>
  1.2. Go to download and download the latest package. The latest version is version 3.<br>
  1.3. Once you install it, go to the command prompt and check the version Type the command "python --version".<br>
</p>

<h3> 2. Writing our first program</h3>
<p>
  2.1. Create a folder on your local PC. <br>
  2.2. Open that folder in VS code. Create a file with a .py extension in it. <br>
  2.3. Write the following code:<br>
  >> print("chai aur python")<br>
  2.4. To run this file, open the terminal in VS code, go to the location where the python file is placed, and write command: "python filename.py"
</p>

<h3> 3. Importing one file into another</h3>
<p>
  3.1. Create one file named hello_chai.py. Define a function in it.<br>

  ````PYTHON
def chai(n):
    print(n)
````
  3.2. Create another file chai.py and import this function. <br>
  ````PYTHON
import hello_chai
hello_chai.chai(6)
````



</p>
