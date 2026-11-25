---
icon:
  type: fluent-color:question-circle-20
  order: 3
---

# Python Fundamentals Quiz

```quiz
title: Variables, data types, output, arithmetic, calculations, comparisons, debugging
---
question: What is the value of `distance_km` after this code runs?<pre><code>   distance_km = 5.0<br>   distance_km = 8.5</code></pre>
---
options:
  - 5.0
  - 8.5
  - 13.5
  - None
correct: 1
---
question: Which variable name is the clearest choice for storing the number of laps completed by an athlete?
type: multiple-choice
options:
  - `x`
  - `number_of_laps`
  - `number`
  - `data`
correct: 1
---
question: What is the data type of `age`?  <pre><code>   age = 20</code></pre> 
type: multiple-choice
options:
  - `str`
  - `float`
  - `int`
  - `bool`
correct: 2
---
question: What is the data type of `distance`?  <pre><code>   distance = "12.5"</code></pre> 
type: multiple-choice
options:
  - `int`
  - `float`
  - `str`
  - `bool`
correct: 2
---
question: What is printed by this code?<pre><code>   laps = 6<br>   lap_distance_m = 400<br>   print(laps * lap_distance_m)</code></pre>
type: multiple-choice
options:
  - 240
  - 2400
  - 6
  - 4006
correct: 1
---
question: What is printed by this code? <pre><code>   athlete = "Alex"<br>   distance_km = 5.5<br>   print(f"{athlete} ran {distance_km} km")</code></pre>
type: multiple-choice
options:
  - `athlete ran distance_km km`
  - `Alex ran 5.5 km`
  - `Alex ran distance_km km`
  - Python produces an error
correct: 1
---
question: What is printed by this code?  <pre><code>   result = 2 + 3 * 4<br>   print(result)</code></pre>
type: multiple-choice
options:
  - 20
  - 14
  - 24
  - 9
correct: 1
---
question: What is printed by this code?  <pre><code>   distance_km = 24<br>   duration_minutes = 60<br>   speed = distance_km / duration_minutes<br>   print(speed)</code></pre>
type: multiple-choice
options:
  - 24.0
  - 0.4
  - 1.0
  - 1440
correct: 1
---
question: What is printed by this code?  <pre><code>   steps_recorded = 8650<br>   step_target = 8000<br>   print(steps_recorded >= step_target)</code></pre>
type: multiple-choice
options:
  - 8650
  - 8000
  - `True`
  - `False`
correct: 2
---
question: What is the difference between `=` and `==` in Python?
type: multiple-choice
options:
  - They both mean assignment
  - `=` assigns a value; `==` compares two values
  - `=` compares two values; `==` assigns a value
  - They both mean equality
correct: 1
---
 ```