# fullstack-developer

### Position Properties in CSS

1. static: Default one. does not have access to top, left, bottom, right properties. neither have access to z-index.
2. relative : Same as static. But lets you add top, right, bottom, left. Makes it move relative to it's normal position
3. absolute: Removes from the flow and positions absolute wrt to the parent. Parent has to be relative or absolute for top, right, bottom, left to work. Else it considers the main html element as the  parent .
4. fixed : Fixed to a place. Doesn't give two shits about the parent. Always considers html element as the parent. Stays there when scrolled.
5. sticky : Relative ( when normal) + fixed ( when scrolled). The values for top, right, bottom, left become active when scrolled


