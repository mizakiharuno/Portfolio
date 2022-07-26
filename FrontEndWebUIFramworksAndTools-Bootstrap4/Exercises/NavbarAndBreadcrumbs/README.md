# Navbar and Breadcrumbs
In this exercise we worked with implementing a navbar and breadcrumbs into our previous website. Note that there were some changes I had to make due to using a newer version of Bootstrap (5.2.0-beta1).  
I had to add remove active from the list tag and move it into the anchor tag:
```html
<li class="nav-item active">
```
To
```html
<a class="nav-link active">
```
I also had to switch up the attribute structure within the navbar-toggler button.
```html
<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#Navbar">
```
Became
```html
<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#Navbar">
```
With inclusion of the bs after data.

[Return to Main](https://github.com/mizakiharuno/Portfolio)
