# class 2 uy-27


# Essential tag in html

* [id, class]
* a [href, target, title]
* form [action, method] {get, post}
* label[for]{<input_id>}
* input [type, required, name, value, placeholder] {text, email, password, submit, checkbox, radio}
* select [name]
* option [value]
* textarea [name]
* img [src, alt, title]

# id and class Attribute

All html tag has `id` and `class` attribute. `id` use for uniquely select a html element in entire document. So there will be only one id in entire document. Id can be select by `#` sign. Class can be used for selecting group of element. In css class is select by `.` sign

## a

~~~html
in `href` attribute you will give your desired path
<!-- absolute path with http/https -->
<a href="https://google.com" target="_blank" title="google link">visit google</a>
<!-- relative path -->
<a href="about.html">visit google</a>
<!-- id -->
<a href="#home">Home section</a>
~~~

## form 

~~~html
<form action="somepage.php" method="get"></form>
~~~

## label  and input

~~~html
<label for="name">Name</label>
<input type="text" name="name" value="some value" placeholder="Enter your name" required>
~~~

## select and option 
Select create a droption selection 

~~~html
<select name="city" id="city">
  <option value="1">Dhaka</option>
  <option value="1">Dhaka</option>
  <option value="1">Dhaka</option>
</select>
~~~

##  textarea 

~~~html
<textarea name="contet" ></textarea>
~~~


## img 

~~~html
<img src="google.png" alt="some alternative text about google">
~~~






