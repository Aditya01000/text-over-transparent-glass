# How to use `linear-gradient's` CSS property to make transparent glass.
1. In `index.html` file I used **2** `div's`.
2. **First div** which is with class named as *parent* this is used to add background image for whole web page, I set width and height of 100% and added `background-size:cover;` and `background-repeat:no-repeat` so that background should be of whole width and should not be repeating. Moreover, In order to align all content in center in `parent div`I used display property to do so.
3. Moving on to `child div`, now real magic starts here! I first adjusted width and height in `%` of transparent glass. In order to make `top-left` and `bottom-right` border curved I used CSS property called `border-top-left(or right)-radius` and set value to `5%`. Again in order to align all content in center I used CSS property `display`. And set `font-weight` to bolder to make text redeable. 
4. In order to make **background transparent** we use `linear-gradient` CSS property with `rgba` colors, like in this case I used `rgba(255, 255, 255, 0.3) [white], rgba(0, 0, 0, 0.3)[black]` and if u look at it closely I used 0.3 as a rgba value to make background transparent and then I rotated it to 140° so that ratio should not be 50-50.... In addition, I used 50% so that there should be **clear line which gonna be seperating black color with white .
5. Last but not least, I used CSS property `box-shadow` to make transparent box more realistic and lifted up to make it beautiful.
Here's how my projext looks like - 
![img of results of text over transparent glass](C:\Users\Youknowme\Videos\text-over-transparent-glass\mountains.jpeg)

