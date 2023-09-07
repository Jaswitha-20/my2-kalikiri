# Jaswitha Kalikiri

I am currently pursuing my masters at Northwest Missouri State University. I am interested in playing sports like Badminton, Basket ball. Apart from this I really enjoy art and craft and sometimes drawing simple designs or mandala art. <br>

[A picture of me](https://github.com/Jaswitha-20/my2-kalikiri/blob/main/pic.jpg)

---
**Table for sports** <br>
This section gives the information about sports and it's advantages. This table shows each sport's advantage and how much minimum duration we have to play.
<br>
|Sport Name|Reason to recommend|Time to spend in a week|
|-----------------|-------------------|-------------|
|Basketball| It improves cardiovascular fitness and strengthens muscles| 8-10 hrs|
|Soccer|Fosters teamwork,communication and endurance| 7-9 hrs|
|Badminton| Improves muscle strength, weight management and flexibility| 8-10 hrs|
|Cycling|Great for cardiovascular health and leg muscle strength| 6-7 hrs|

---
#### Pithy Quotes
> " The whole Science is nothing more than a refinement of everyda.y thinking."
>
>\-*Albert Einstein*

<br>

> " Before anything else, preparation is the key to Scucess."
>
>\-*Alexander Graham Bell*

---
#### Code Fencing
Relevant question on StackOverflow 
>Randomize order of specific children elements<br>
<https://stackoverflow.com/questions/73249459/randomise-order-of-specific-children-elements-only?>
~~~ JQuery
$.fn.shuffleChildren = function() {
    $.each(this.get(), function(index, el) {
        var $el = $(el);
        var $find = $el.children();

        $find.sort(function() {
            return 0.5 - Math.random();
        });

        $el.empty();
        $find.appendTo($el);
    });
};
$("#some-element").on("postpaste", function() { 
    // do something
}).pasteEvents();
~~~
<https://css-tricks.com/snippets/jquery/shuffle-children/>