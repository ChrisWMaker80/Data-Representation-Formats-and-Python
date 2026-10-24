# Data Representation Formats and Python
Data Representation Formats and Python Information



<h2>Python functions that operate on JSON data. </h2>
<table border="1">
  <tr>
    <th>Code or Function</th>
    <th>Explanation</th>
    <th>Example</th>
  </tr>
  <tr>
    <td>json.loads</td>
    <td>Reads JSON from a string and converts it into a Python object. <br>json.loads accepts any valid JSON, and the first character determines the Python type you get back. <br>(reads JSON from a string) </td>
    <td>Example: json.loads takes a JSON string like '{"x": 1}' and turns it into a Python dictionary.   </td>
  </tr>
  <tr>
    <td>json.dump </td>
    <td>Takes a Python object and writes it as JSON into a file. <br>(writes JSON to a file)</td>
    <td>json.dump takes a Python dictionary and saves it into a file as JSON text. ) </td>
  </tr>
   <tr>
    <td>Json.dumps</td>
    <td>Takes a Python object and converts it into a JSON-formatted string.  <br> (returns JSON as a string)</td>
    <td>json.dumps takes a Python dictionary and turns it into a JSON string you can print or send over a network. </td>
  </tr>
   <tr>
    <td>json.load</td>
    <td>Reads JSON from a file and converts it into a Python object. <br>  (reads JSON from a file) </td>
    <td>Json.load opens a JSON file on disk and turns its contents into a Python dictionary.</td>
  </tr>
</table>


<table>
<tr>
<td> json.dump </td>
<td>  writes JSON to a file → returns None</td> 
</tr>

<tr>
<td> json.dumps </td>
<td> returns JSON as a string → does not write to a file </td>
</tr>
  
</tr>



  
</table>


<h2>Python Statements (Control structures, behaviors, and flows) </h2>

<table>
<tr>
<td><I> With</I> Statement</td>
<td> With creates a context manager so the file closes when done.  <br> No need to use .close()  </td> 
</tr>

 
</table>

<h2> Selected Built-in Methods </h2>
<table>
<tr>
<td><I> .readlines()</I> </td>
<td> read a text file line‑by‑line <br> Can be used to configure network devices, line by line.  </td> 
</tr>




