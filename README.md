### Comments

### fib.py

* "./fib.py approx n" works great, good job
* "./fib.py converge filename" doesn't work because you can't specify another argument. Try adding the commented out code I put in fib.py in the part of the code that handles the arguments entered by the client's call (how do you now have to change the parameter(s) that phi_converge() accepts? should the new parameter(s) be optional?). This will allow the user to specify an output file to write the output to if they want.
* The output.txt file doesn't get written over as a new file each time, the new call to phi_converge() simply adds to the file, writing the new output below. How would you change your code so that it rewrites the entire file instead of just adding to it?

* Overall good job! - Joey