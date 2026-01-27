---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "GPA Calculator"
date: 2024-04-28
published: true
labels:
  - Python
  - Project
summary: "For my AP Computer Science Principles create performance task, I coded a 4.0 GPA scale calculator."
---

<div class="text-center p-4">
  <img width="800px" src="../gpa-calc-img.png" class="img-thumbnail" >
</div>

The GPA Calculator is a python program that aims to help high school students easily calculate their GPA. At my high school, there was no such thing as a "B-" or an "A+", so it only takes the base letter grade. However, if the class is an AP class, the calculator will take the grade as a 5.0 grade scale. First, the program asks the user to input the number of grades they have, and then ask for their grade in each class, with a + at the end of a Letter indicating it is an AP class. After, the user's GPA is calculated and printed.

While this project is very basic, it was my first use of coding to solve a real world problem. I had lots of setbacks, as I had never worked with this scale project before. Eventually, I taught myself the necessary skills to successfully complete this program, learning a lot on the way. The most this program taught me was how to look at a problem that needs to be solved. While it is helpful to know how to code, it doesn't help if a programmer doesn't know how to apply those skills in a real life environment.

Here is some code that displays how I accepted inputs from the user

```cpp
{
    while True:
        grade = input ('What is your letter grade? (Add a "+" at the end of the letter if the class is an AP): ')
        if grade in possible_grade:
            letter_grade = False
        if letter_grade == True:
            print('Please use the letters "A", "B", "C", "D", "F"')
        if grade.islower():
            print("Use capital letters")
        if not letter_grade and not upper:
            grade_list.append(grade)
            break
    print(grade_list)
}
