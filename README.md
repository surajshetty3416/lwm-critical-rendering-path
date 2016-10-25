### Critical Rendering path
> Reference [Free Course By Udacity](https://classroom.udacity.com/courses/ud884/)

It may be defined as a sequence of steps that the browser take to convert HTMl, CSS and JavaScript files to convert into actual breathing websites

Here we will try to optimize the critical rendering path so as to Improve our website performance and for better UX.

### Generic CRP can be given as
~~~~
          ([DOM](building_dom/building_dom.md))
            |   } (JavaScript)
         (CSSOM)
            |
      (Render Tree)
            |
        (Layout)
            |
         (Paint)

~~~~