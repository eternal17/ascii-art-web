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

The ListenandServe function on line 154 starts an HTTP server, listens on port 8080 incoming requests, and serves on '/ ' . (see Usage above)
</br>
</br>
The http.HandleFunc(handlers) functions in Lines 152 & 153 respond to the HTTP request and register the corresponding functions with the HTTP server.
(Handler functions are a convenient way of creating handlers which allow us to build web applications that are more modular.)


</br>











