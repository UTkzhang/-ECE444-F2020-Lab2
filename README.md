# ECE444-F2020-Lab2
This repository is a clone of https://github.com/miguelgrinberg/flasky.

# activity 1
<img src="https://github.com/UTkzhang/ECE444-F2020-Lab2/blob/master/Snip20200921_22.png">

# activity 2
<img src="https://github.com/UTkzhang/ECE444-F2020-Lab2/blob/master/Snip20200921_24.png">

# activity 3
In flask, "context globals" are variables with global accessibility, and represents the context of a request to the server. Examples of context globals include request, session, current_app, and g. These variables are useful as it prevents view function (handler function) parameters from being clogged with information about the context which may or may not be used. It is interesting to note that in reality, contexts cannot be truly global, because servers are designed to handle multiple incoming requests at once (such as in multithreaded servers). This complication, however, is abstracted by flask, such that each thread only has access to the context it is handling, without interfering with other threads. 
