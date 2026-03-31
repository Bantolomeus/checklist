# Introduction 
This is a checklist to hopefully not forget anything during the review process. 
Regardless of who is doing it. 



# The CHECKLIST
- [ ] verify the text color is the same as in Figma. For all available colors.
  - [ ] light mode
  - [ ] dark mode
  - [ ] high emphasis
  - [ ] lower emphasis
- [ ] verify the background color is the same as in Figma. For all available colors.
  - [ ] light mode
  - [ ] dark mode
  - [ ] high emphasis
  - [ ] lower emphasis
- [ ] verify the border color is the same as in Figma.
    - [ ] light mode
    - [ ] dark mode
    - [ ] high emphasis
    - [ ] lower emphasis
- [ ] verify that all states are implemented as stated in Figma
    - [ ] every state behaves like described in Figma
    - [ ] universal rules for states apply, ask designer if you do not know them
    - [ ] text and background color for every state match with Figma
- [ ] verify that every border is in place
- [ ] verify that the scroll bar is looking good
- [ ] verify that we have no hooks in underlines
- [ ] verify that the font size is in rem 
- [ ] verify that the font size matches with Figma
- [ ] verify that the component size matches with Figma
- [ ] verify that the border thickness matches with Figma
- [ ] verify that the font has the same thickness as in Figma
- [ ] verify that the padding matches with Figma
- [ ] verify that the margin matches with Figma
- [ ] verify that empty spaces have the correct width, as stated in Figma
- [ ] verify that all optional elements are shown in at least one variation in storybook (not necessarily all in one)
- [ ] verify that all configurations are shown in at least one variation in storybook
  - [ ] verify that all configurations are working 
  - [ ] verify that all combinations of configurations that are valid work together  
- [ ] verify that keyboard navigation is working
  - [ ] pressing the tab key will move you into the first interactive element
  - [ ] pressing tab multiple times will move you through interactive elements 
  - [ ] after pressing tab enough times, you will start at the same element again where you started off
  - [ ] there is no variation in the order of the interactive elements that you reach via pressing the tab key
  - [ ] everything that works for the tab key also works for tab + shift just backwards 
- [ ] If a component has more keyboard strokes for interactions, then they also need to work
  - [ ] look up your component(s) [here](https://www.w3.org/WAI/ARIA/apg/patterns/) and implement the accessibility accordingly
- [ ] verify that every acceptance criteria is fulfilled
- [ ] verify that everything from in scope is implemented and works 
- [ ] verify that the component behaves as the intended behavior  
- [ ] verify that fork bombs do not work
- [ ] verify that a large number of characters (20 mio) do not break components  
- [ ] verify that responsive behavior works as intended ([one source for it](https://www.figma.com/design/qRiJQ2gKcuAkBKiRZkagVe/Playground--GrAS-Nova-Library-Setup?node-id=33-27569&p=f&m=dev))
- [ ] use everything that the component has to offer
- [ ] read everything that stands in Figma regarding your component and compare it with your implementation that everything matches 
- [ ] stretch and slim down the component to see the responsive behavior
- [ ] If something feels strange, ask a designer and/or dev and/or po.
- [ ] hover over icons
  - [ ] if the mouse pointer indicates a clickable icon something should happen on click
- [ ] check for breaking changes
  - [ ] was an attribute/input/configuration made mandatory that was not before? 
  - [ ] was an attribute/input/configuration removed?
  - [ ] was the naming of an attribute/input/configuration changed?
  - [ ] was a data type changed? Like changing boolean into enum.
  - [ ] was an option of a selectable attribute/input/configuration removed?
  - [ ] was the export changed in any way?
  - [ ] was the visibility level of an attribute/input/configuration changed?
  - [ ] have there been changes to the public API changed?
