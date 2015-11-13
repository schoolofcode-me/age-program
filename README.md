# Age Program

This program is part of [http://schoolofcode.me/courses/complete-python-web-course-learn-by-building-8-apps](*The Complete Python Web Developer Course: Learn by Building 8 Apps*). This is the first program in the course, intended to introduce students to Python.

## Structure

The program uses one method which asks the user for their age by using the `input` method:

	user_age = input("Enter your age: ")

Then, we convert the age `string` to an `int` and multiply it by `365*24*60*60` to get the number of seconds per year:

	age_seconds = int(user_age) * 365 * 24 * 60 * 60

Finally, we print out the age to the console for the user to see:

	print("Your age in seconds is {}".format(age_seconds))

## Method

All of the code above goes in one method, so that we can simply call that method to execute the program. The method looks like this:

	def age_program():
	    user_age = input("Enter your age: ")
	    age_seconds = int(user_age) * 365 * 24 * 60 * 60
	    print("Your age in seconds is {}".format(age_seconds))

That way, to run the program we only have to execute the `age_program()` method.