# React + Vite
75 days hard placement challange day 04
     **********Most imp topic coverd today********
     01==Custom Hook
When we want to share logic between two JavaScript functions, we extract it to a third function. Both components and Hooks are functions, so this works for them too!
A custom Hook is a JavaScript function whose name starts with ”use” and that may call other Hooks.

     02====useId===

     ===>useId is a React Hook for generating unique IDs that can be passed to accessibility attributes.

      ====>it does not take any parameters.
for ex==>
     const id = useId()

  Usage >>useId()

01>>>Generating unique IDs for accessibility attributes
02>>>Generating IDs for several related elements
03>>>Specifying a shared prefix for all generated IDs
04>>>Using the same ID prefix on the client and the server


useId is a Hook, so you can only call it at the top level of your component or your own Hooks. You can’t call it inside loops or conditions. If you need that, extract a new component and move the state into it.

