# swe-sr-1-3

## Setup

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/how-tos/working-with-assignments#how-to-work-on-assignments).

Here are some useful commands to remember.

```sh
npm i                   # install dependencies
git checkout -b draft   # switch to the draft branch before starting

git add -A              # add a changed file to the staging area
git commit -m 'message' # create a commit with the changes
git push                # push the new commit to the remote repo
```
## Question 1

Read the documentation for `findIndex` and `indexOf` on MDN:
- [findIndex](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/findIndex)
- [indexOf](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/indexOf). 

Explain the difference between the methods and explain when you would choose one over the other. Provide examples to enhance your response.

### Response

`findIndex` is a callback method that allows you to do something similar to the `indexOf` method but with a twist, you can use logic. `indexOf` gets the first of an element that looks like what you give it but findIndex lets you find an element using that method or even a test via logic.

I would use  `indexOf` if the array uses basic datatypes is flat, and **I Know** what im looking for. Whereas findIndex is more suitable when i dont know what im looking for but i know where to look or what to check for.
