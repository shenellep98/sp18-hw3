## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?
The second argument 'nil' means the value will be empty for the course name placeholder. If we replace nil with a string, the textbox will start with a value in it already.

2. Go to `localhost:3000/teachers` in your browser; why does this not work?
There is no instance of a teacher yet. New must be called to first create a teacher. 

3. What type of request did your browser just perform?
Get request.


4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
localhost:3000/teachers


5. Why does `localhost:3000/teachers` work now?
A new teacher instance has been created and is saved to /teachers. 
