# ASCII ART WEB

#### a project by eternal17 & tb38r
---
</br>

### <ins>Table of Contents</ins>

1.    Description
2.    Authors
3.    Usage: how to run
4.    Implementation details: algorithm
</br>
</br>



### <ins>Description</ins>

Ascii art web uses Golang's HTML/Templates & net/HTTP packages to create an API that creates a static server & listens and responds to . An accompanying HTML file illustrates the client and provides the required inputs.
</br>
The primary aim is take a string from the user and return it to the client in Ascii form.
</br>
</br>
### <ins>Authors</ins>
tb38r: https://git.learn.01founders.co/tb38r
</br>
eternal17: https://git.learn.01founders.co/eternal17
</br>
</br>
### <ins>Implementation Details: Algorithm</ins>
</br>

First, a brief summary of the *imports used within this project. 
</br>
*Bufio implements a buffered I/O which allows for a range of manipultions. In this instance, we've used it to scan the text within a given file and returned the output as a slice of string.
</br>
*Fmt implements formatted I/O.
</br>
*Html/template implements data-driven templates for generating HTML output safe against code injection.
</br>
*Net/http provides HTTP client and server implementations
</br>
*Os import here is used to open  files as well as some minor error handling
</br>
Lastly, *Strings implements simple functions to manipulate UTF-8 encoded strings. We use its contains function to search for specific parameters of the user input.
</br>
__________________

</br>

The ListenandServe function on line 154 starts an HTTP server, listens on port 8080 incoming requests, and serves on '/ ' . (see Usage above)
</br>
</br>
The http.HandleFunc(handlers) functions in Lines 152 & 153 respond to the HTTP request and register the corresponding functions with the HTTP server.
(Handler functions are a convenient way of creating handlers which allow us to build web applications that are more modular.)
</br>
</br>
We initialised tp1 with the Must helper for effeciency & brevity.
</br>
</br>
Also of note, is a function Newline, called in from a previous project. Newline() takes in a slice of string(s) and returns it illustrated in ascii form. It's limited to the 128 characters of the ascii table.
</br>
</br>
______
Part 1 of the usage guidelines occurs on line 154. 













