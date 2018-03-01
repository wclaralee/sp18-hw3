## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?
	it just means that the course placeholder will have nothing in it, so if you put something in it, the answer wills tart off with a value in it already. 

2. Go to `localhost:3000/teachers` in your browser; why does this not work?

	this is because we dont have a teachers instance yet, and we need to call 'new' to create a teacher. 
3. What type of request did your browser just perform?
	Get

4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
	localhost:3000/teachers

5. Why does `localhost:3000/teachers` work now?
	because we created a new instance of teachers, and saved it to teachers, so now something exists in it. 