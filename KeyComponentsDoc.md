# Key Components Doc for <Project>
#### *Author: John Reiley*
#### *Date: 5/17/19*

# Preliminary Design

## Magic Box Chart

![alt text](magicBoxChart.jpg)

<!-- Think through the process as much as makes sense, and then create a magic box chart with the whiteboard and place it here. -->

## Explanation of Design
<!-- Add explanation of the Magic Boxes image above. Answers to the prompts below may also be appropriate to include here. -->
1. Read in the CSV file and convert to string
2. Parse the string into an array of city objects using d3-dsv.  Each object will have 4 keys: "Country Name," "State Name," "Name," and "Population"
3. Convert the array of city objects into an array of country objects using, array.reduce()
4. Sort by country, state, and population
5. Convert country object array into json using JSON.stringify()
6. Save the JSON data into a json type file of the same name of the CSV file

### Used Libraries
- d3-dsv (https://www.npmjs.com/package/d3-dsv)

## Things to Consider Before Getting Project Approved
- Are there any approved libraries that I can use? [Link to Approved Library List]
- Are there design patterns that will help?  [Link to Design Patterns]
- Can I design it so that it is a general tool instead of a specific solution?
- How can it be easily expanded?
- What does the minimum viable product look like?

## Prep for Learning Phase
- What do I need to learn
- How will I learn it
- What will I do to learn it (prototypes/tutorials/research time limit?)
- What is the definition of done for my learning process
- How do I measure the progress of learning
- Is there a deliverable that can be created during the learning process?
-----
- Read d3-dsv documentation
- Learn how to save a file to the same directory as the processed file
-----

#### *Preliminary Design Approved By:* 
#### *Preliminary Design Approval Date:*

# Full Design  

## Component Diagrams
<!-- Diagrams and companion explanations for all Key Components.
These would include information about inputs, outputs, and what a function does for every major function. -->

<!-- For each component, the following template will be followed: (In other words, the template below will repeat for each component)-->

### *Insert Component name here*

Diagram:

*Insert Diagram Here*

Explanation:

*Insert Explanation here*

<!-- For a future release:
## Test Plans
For each major function the test plan template will be as follows (in other words the template below will repeat for each test) 
### *Insert name of component here (e.g. convertIdToCourseObject function)*
#### Test 1: *Insert Test name here*
Summary: 
 *Insert Test Summary Here*
 Type: *Insert Type here (Unit Test, Manual Test, Selenium/Puppeteer test (Overkill?))* 
Procedure:
1. *Insert Steps here*
1. *and here*
1. *and here*
Expected Outcome:
*Insert Expected Outcome here*
-->

## Test Plans

### *Insert Module Name Here*
#### How to Test:





-----

#### *Full Design Approved By:* 
#### *Full Design Approval Date:*


<!-- Diagram Types:
 - Data Flow (I think this will be the most popular)
 - Structure Charts (This is really good for showing input and output of every function)
 - UML Class Diagram (a must for object oriented projects) -->


