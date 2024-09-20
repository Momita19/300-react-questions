# 300-react-questions
I will explore 300 react questions, to revise basic to advance react.

## Day 1
1. What is virtual dom?
      - virtual dom is like a blueprint tree for react, it is update the change on virtual dom and compare with real dom and update only the exact change on the real dom instead changing in the whole real dom.
2. what is diffing and reconciliation algorithm?
      - The difference between the virtual dom tree and real dom tree, is driffing algorithm and this process called reconciliation.
3. What is react fibre?
4. what is synthetic system in react?
5. what is the events and what are the different events in react?
      Events are the actions that occurs in the web browser.
      Different types of events with example:
      1. click : onClick
      2. keyboard : onKeyDown, onKeyPress, onKeyUp
      3. mouse : onMouseEnter, onMouseLeave, onMouseMove
      4. submit : onSubmit
      5. change : onChange
         - click event
           
        ```function ClickButton(){
            function handleClick(){
           alert("you clicked me")
           }
           return(
           <button onClick={handleClick}>
            Click me
           </button>
           )
           }```
         - 
         

6. Refs in react?
      1. Refs are used to directly access or manipulate the dom events,
      2. we should not use refs
         
7. functional vs class components
8. server side and client side rendering
9. node?
      - it is runtime environment, we can use javascript out of the compiler.      
10. 


