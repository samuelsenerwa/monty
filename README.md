<h1>Monty Project(Group)</h1>
<p>Usage: <code>monty file</code><br>
<ul>
<li> Where <code>file</code> is the path to the file containing Monty byte code.<br>
If the user does not give any file or more than one argument to your program, print the error message<br>
<code>USAGE: monty file</code><br>
followed by a new line, and exit with the status <code>EXIT_FAILURE</code></p>
</li>
<li>
<p>If, for any reason, it's not possible to open the file, print the error message<br>
<code>Error: Can't open file &lt;file&gt;</code><br>
followed by a new line, and exit with the status <code>EXIT_FAILURE</code><br>
Where <code>&lt;file&gt;</code> is the name of the file.<br><li>
If the file contains an invalid instruction, print the error message<br>
<code>L&lt;line_number&gt;: unknown instruction &lt;opcode&gt;</code><br>
followed by a new line, and exit with the status <code>EXIT_FAILURE</code><br>
Where <code>&lt;line_number&gt;</code> is the line number where the instruction appears.<br>
Line numbers always start at 1.<br>
<li>
The monty program runs the bytecodes line by line and stops if either:<br>
- it executed properly every line of the file
- it finds an error in the file
- an error occurred.<br>
</li>
<li>
If you can't malloc anymore, print the error message<br>
<code>Error: malloc failed</code><br>
followed by a new line, and exit with status <code>EXIT_FAILURE</code>. <br>
You have to use malloc and free and are not allowed to use any other function from man malloc (realloc, calloc, …)</p>
</li>
</ul>

### Authors
- Samuel Senerwa
