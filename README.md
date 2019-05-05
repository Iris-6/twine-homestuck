# twine-homestuck
CSS and HTML to recreate the look and feel of Homestuck using Twine (Harlowe)
## How to (Method A)
Import twine-homestuck-example.html into Twine, modify the example as you please.
## How to (Method B)
1. Paste the contents of css.css into "Edit Story Stylesheet".
1. Paste the contents of log_passage.html into a new Twine passage.
## Including a Pesterlog/Dialoglog
1. Set the $log variable (using `(set: $log to {text})` for example)
1. Include the passage you've pasted log_passage.html into by using `(display:{passage name})`
1. By default, the button will just display 'Show log' rather than 'Show Dialoglog'. To change this, replace 'log' by 'Dialoglog' or 'Pesterlog' on your passage. You will need to use $Dialoglog or $Pesterlog as the variable afterwards though!
## Including Images?
Just use `<img src={url} class="center">`. 
