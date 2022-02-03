# Holberton SmileSchool Javascript

## Description

Implement 3 web pages with Bootstrap and javascript (jQuery)

<p align="center"><img src="https://github.com/felipesv/holberton-smiling-school/blob/master/mockup.jpg" alt="mockup"></a></p>

---

### [Reuse and polish your Bootstrap integration](./0-homepage.html)

* Copy files from [0x0B. Implement a design with bootstrap](https://github.com/felipesv/holberton-smiling-school)
  * homepage.html -> 0-homepage.html
  * pricing.html -> 0-pricing.html
  * courses.html -> 0-courses.html
  * styles.css and any files/folders needed (images, fonts…)
* **Interactions note:**
  * Web pages must switch to the tablet version when the screen width is 768px
  * Web pages must switch to the mobile version when the screen width is 576px
  * button hover/active: opacity: 0.9

### [Homepage - quotes](./1-homepage.html)

* Replace static quotes by dynamic loading

**Example of my loader:**

~~~html
<div class="loader"></div>
~~~

~~~css
.loader {
    border: 10px solid #f3f3f3;
    border-top: 10px solid #C271FF;
    border-radius: 50%;
    width: 80px;
    height: 80px;
    animation: spin 2s linear infinite;
    margin: auto;
}

@keyframes spin {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
}
~~~

**Final result:**
![final_result](./assets/1-task.gif)

### [Homepage - popular tutorials](./2-homepage.html)

* Replace static video cards by dynamic loading
  * URL: `https://smileschool-api.hbtn.info/popular-tutorials`
  * No static video cards should be present in the section
  * During the Ajax request, a loader should be present
  * Carousel should work by sliding card by card (like GIF below) - this kind of carousel is not unique, make it generic to reuse it easily!
  * Don’t forget the responsive part!

**Final result:**
![final_result_2](./assets/2-task.gif)

### [Homepage - latest videos](./homepage.html)

* Replace static video card by dynamic loading

**Final result:**
![final_result_3](./assets/3-task.gif)

### [Pricing - quotes](./pricing.html)

* Replace static quotes by dynamic loading:

### [Courses](./courses.html)

* Replace static video card by dynamic loading:
  * URL: `https://smileschool-api.hbtn.info/courses`
  * No static video cards should be present in the section
  * During the Ajax request, a loader should be present

![result](./assets/5-task.gif)

### [JSON to XML](./xml-scripts.js)

* Convert all your JSON Ajax call to another API… a XML API!
