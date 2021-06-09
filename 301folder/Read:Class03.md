## React Docs - lists and keys

*  ### What does .map() return?
###### results of calling a provided function on every element in the calling array

*  ### If I want to loop through an array and display each value in JSX, how do I do that in React?

* ###### ou can put any valid JavaScript expression inside the curly braces in JSX. For example, 2 + 2, user.firstName, or formatName(user) are all valid JavaScript expressions.


*  ### Each list item needs a unique __key__.
*  ### What is the purpose of a key?
* ###### Keys used within arrays should be unique among their siblings

________________


## The Spread Operator

* ### What is the spread operator?
 ###### Spread operator to the rescue! It looks similar to rest parameters, also using ..., but does quite the opposite
*  ### List 4 things that the spread operator can do.
###### 
*  ### Give an example of using the spread operator to combine two arrays.
1. Copying an array
2. Concatenating or combining arrays
3. Using Math functions
4. Using an array as arguments
5. Adding an item to a list

*  ### Give an example of using the spread operator to add a new item to an array.
`
[...["😋😛😜🤪😝"]] // Array [ "😋😛😜🤪😝" ]
[..."🙂🙃😉😊😇🥰😍🤩!"] // Array(9) [ "🙂", "🙃", "😉", "😊", "😇", "🥰", "😍", "🤩", "!" ]

const hello = {hello: "😋😛😜🤪😝"}
const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}

const helloWorld = {...hello,...world}
console.log(helloWorld) // Object { hello: "😋😛😜🤪😝", world: "🙂🙃😉😊😇🥰😍🤩!" }`

*  ### Give an example of using the spread operator to combine two objects into one.
_______________________
*  ### In the video, what is the first step that the developer does to pass functions between components?
*  ### In your own words, what does the increment function do?
*  ### How can you pass a method from a parent component into a child component?
 *  ### How does the child component invoke a method that was passed to it from a parent component?