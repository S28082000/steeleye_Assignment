Q1: Explain what the simple List component does.

We know that it is used for displaying "items" which passed as props into List component in an ordered format and it's functional component returns other component 
In this way we create a list of elements, A character key needed to include and determine the element in the list had modified or not.

Q2: What problems / warnings are there with code?

Problem 1: misssing of dependency 'setSelectedIndex' in react hook

Problem 2: setSelectedIndex in useEffect() hook accepts two arguments in it.

Problem 3: There is a wrong fuctionname in useeffect hook we need to change it as well.



Q3: Please fix, optimize, and/or modify the component as much as you think is necessary.
removing dependecy "items" from useEffect hook.

I need to fix useState hook setting the function i.e. setSelectedIndex correctly.

I need to add items "item1", "item2" into the list component.

I need to put a  "onClickHandler" function inside arrow function.

Also, i add a unique key prop to singleListItem component.
