# Images and Media
In this exercised we implemented media objects and images.  Note that with Bootstrap 5, media objects were removed, and therefore I had to use some alternative methods of implementing the classes to mimic the behavior.

Originally:
```html
<div class="media">
    <img class="d-flex mr-3 img-thumbnail align-self-center" src="img/uthappizza.png" alt="uthappizza">
    <div class="media-body">
        <h2 class="mt-0">Uthappizza</h2>
        <p class="d-none d-sm-block">A unique combination of Indian Uthappam (pancake) and Italian pizza, topped with Cerignola olives, ripe vine cherry tomatoes, Vidalia onion, Guntur chillies and Buffalo Paneer.</p>
    </div>
</div>
```
Modified:
```html
<div class="d-flex">
    <div class="flex-shrink-0 mr-3 img-thumbnail align-self-center">
        <img src="img/uthappizza.png" alt="uthappizza">
    </div>
    <div class="flex-grow-1 ms-3">
        <h2 class="mt-0">Uthappizza</h2>
        <p class="d-none d-sm-block">A unique combination of Indian Uthappam (pancake) and Italian pizza, topped with Cerignola olives, ripe vine cherry tomatoes, Vidalia onion, Guntur chillies and Buffalo Paneer.</p>
    </div>
</div>
``` 

[Return to Main](https://github.com/mizakiharuno/Portfolio)
