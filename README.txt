Because this program was written with Python, the invocations MUST be prepended
with the "python" command, and the source name must have ".py" appended. 
Everything else works exactly as it would had the program been written in C or 
C++.

Also, Python files do not require MAKEFILEs, so it would be pointless to make
and/or require one.

The possible invocations are as follows:
  1. "python P1.py"
      -if you want to write your file in the console

  2. "python P1.py < file.cs4280"
      -if you want to redirect a file through stdin
      -"file" can be any name

  3. "python P1.py file"
      -if you want to pass the file name as an argument
      -"file" can be any name