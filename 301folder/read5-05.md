# How would you break a mock into a component heirarchy?
To do this, I would search through the data file that is returned by the API, and then compare it to sections of the mock to identify like-areas for component creation.
# What is the single responsibility principle and how does it apply to components?
This means that a component should "only do one thing". This gives React its definition as an atomic or modular component based UI library.
# What does it mean to build a ‘static’ version of your application?
This means to create the mock version, without implementing any of the functionality that is brought in from external data.
# Once you have a static application, what do you need to add?
Functions / classes to actually use the data brought in from the API or external data.
# What are the three questions you can ask to determine if something is state?
Quoted directly from website:
Is it passed in from a parent via props? If so, it probably isn’t state.
Does it remain unchanged over time? If so, it probably isn’t state.
# Can you compute it based on any other state or props in your component? 
If so, it isn’t state.
# How can you identify where state needs to live?
State needs to live within the component that the specific data is getting used or modified.
The whole article on this is review from Read-01 and Read-02 notes.

## Questions:

More of a comment, but I need as much practice as I can get. I thought I grasped a topic on day 2 in React then when something else was introduced, the ideas got jumbled up in my brain and I got confused again. On day 4, with different explanations given things are starting to fit together again, but I just need to practice implementing props, state, passing data between elements, and using functions / classes to pass data as well.