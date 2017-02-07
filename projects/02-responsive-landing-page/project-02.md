# Project 02 - Responsive Landing Page

This project consists of designing and implementing a responsive landing page. You will sketch 


## Topics covered

* RWD (Responsive Web Design)
* Wireframing
* Intro to CSS Media Queries







## Resources

[Printable Wireframing Grids](http://sneakpeekit.com/)



- - -



The project consists on analyzing and deconstructing an abstract painting or illustration and recreating it with code. We will dissect a painting and select a few key elements. Then we will draw these shapes and recreate them with code.

> Analyze, Sketch, Code







## Project: Drawing art with CSS

1. Find an abstract artist/painting
2. Crop it into a square
3. Trace it with [geometric primitives](https://en.wikipedia.org/wiki/Geometric_primitive) using vector drawing software (Sketch, Illustrator)
4. Name and group each shape logically
5. Use the color picker to match each shape's color
6. Recreate each shape in CSS (size, color, border)
7. Arrange the shapes into position using CSS




- - -


### 1. Find an abstract artist/painting

![Kandinsky](img/01-art.jpg "Circles in a Circle")

_[Kandinsky - Circles in a Circle](http://www.philamuseum.org/collections/permanent/51019.html)_


### 2. Crop it into a square

![Kandinsky Crop](img/02-crop.png "Circles in a Circle cropped")


### 3. Trace it with using vector drawing software (Sketch, Illustrator)

![Kandinsky Trace](img/03-trace.png "Circles in a Circle traced")

![Kandinsky Vector](img/03b-vector.png "Circles in a Circle vector")


### 4. Name and group each shape logically

![Vector Groups](img/04-groups.png "Circles in a Circle vector")


### 5. Use the color picker to match each shape's color

![Color](img/05-color.png "Circles in a Circle vector")


### 6. Recreate each shape in CSS (size, color, border)

```
<style>

  .container {
    width: 600px;
    height: 600px;
    background-color: #E3D1C3;

  }

  .oval-01 {
    width: 556px;
    height: 556px;
    border: 29px solid #171719;
    box-sizing: border-box;
    border-radius: 100%;
    position: absolute;
    top: 20px;
    left: 25px;
  }

  .oval-02 {
    width: 178px;
    height: 178px;
    border: 2px solid #3B371E;
    background-color: #31331F;
    box-sizing: border-box;
    border-radius: 100%;
    position: absolute;
    top: 198px;
    left: 236px;
    opacity: 0.56;
  }

  .oval-03 {
    width: 68px;
    height: 68px;
    border: 3px solid #381B15;
    background-color: #C72B22;
    box-sizing: border-box;
    border-radius: 100%;
    position: absolute;
    top: 247px;
    left: 243px;
  }

  .oval-04 {
    width: 15px;
    height: 15px;
    background-color: #20131D;
    box-sizing: border-box;
    border-radius: 100%;
    position: absolute;
    top: 273px;
    left: 270px;
  }

</style>
```

### 7. Arrange the shapes into position using CSS

![CSS Position](img/06-position.png "Circles in a Circle vector")




