GUIDED QUESTIONS:
- It went 20px away from the top and 20px away from the left of its original postion.
- It stays in a permanent position on the viewport. Even if you scroll up and down it will always be on the viewport and never change its position.
- It changed its postion to be besides sidebar which is the nearest non-static element
- The notice appears on top of the content because it has a higher index than the content. If you switch their z-index values the main content will cover the notice
    - CHALLENGES:
       - 
       -
       - It causes to cover an element or be covered by it depending on the index value.

3. 
  a) Static causes an element to stay in its exact position and is the default positon for html elements. Relative moves an element a specfic number of px or units away from its original position. Absolute positions elements  automatically to the nearest non-static element. Fixed removes an element from the document flow meaning even if you scroll up and down it will always stay in the same poistion on the viewport.
  <br>
  b) When there's a non-statitc element, it will position itself next to the narest non-static element and how far away it is from the element depends on what the user inputted for position such as top, botton, left, and etc.
  <br>
  c) Fixed always stays on the viewport, while sticky initiallya cts like relative until a certain condition about its position is fulfilled then starts acting like fixed.
  <br>
  d) 
