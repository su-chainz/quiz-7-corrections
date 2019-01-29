# quiz-7-corrections

QUESTION 1
I need to populate an ArrayList of Integers that will represent each of the perfect squares between 1 and 10. Which of the following code segments below accomplishes that task? Select all that apply.

Answers:
B. ArrayList<Integer> perfectSquares = new ArrayList<Integer>();

for (int i = 1; i <= 10; i++) {
    perfectSquares.set(i, (i * i));
}

C. ArrayList<Integer> perfectSquares = new ArrayList<Integer>();

for (int i = 1; i <= 10; i++) {
    perfectSquares.add(i * i);
}

D. ArrayList<Integer> perfectSquares = new ArrayList<Integer>();

int i = 1;
while (i <= 10) {
    perfectSquares.add(i, i * i);
    i++;
}

Explination: I originally had put just C as the answer because I was confused about the syntax for the add method. I thought that the value had to be in the argument before the method, thus I did not select it. 

QUESTION 9
Which method(s) of the ArrayList class is being called in the code segment below?

ArrayList<String> names = new ArrayList<String>();

names.add("Paul");
names.remove(0);

System.out.println("There are " + names.size() + " elements in the ArrayList.");
Select all that apply.

Answers: 
The remove method.
The add method.
The size method.

Explination: I got this one wrong because I thought the ArrayList constructor was a method. However, it is a constructor which is different.


QUESTION 12
Consider the following code segment.

ArrayList<String> names = new ArrayList<String>();
names.add("Alex");
names.add("Brittany");
names.add("David");
names.add("Ethan");
names.add("Francesca");
names.add(2, "Carson");

System.out.println(names):
What is printed to the console as the result of executing this code?

Answer:
Nothing, because this code will not compile.

Explination: I got this question wrong because I did not see the way they tried to print the array, System.out.println, which does not work for arraylists. Thus, I selected an option that actually displayed names. 

QUESTION 13
I need to keep a list of students who have registered to take AP Computer Science A next year. All I need to store are the students' names. To do this, I've decided to use an array. The maximum enrollment for the course is 50 students.

Which of the following represents a correct declaration and initialization of my ArrayList?

Answers:
B. ArrayList<String> registeredStudents = new ArrayList<String>();
D. ArrayList<String> registeredStudents = new ArrayList<String>(50);

Explination: I got the first answer wrong because I didn't realize they did the same thing practically. Because neither of the choices actually limit the size, it would be both of the options.
