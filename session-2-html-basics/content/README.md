# HTML 2


## Lists

An unordered list starts with the `<ul>` tag. Each list item starts with the `<li>`tag.

```
<ul>
  <li>Red</li>
  <li>Green</li>
  <li>Blue</li>
</ul>

```

An ordererd list starts with the `<ol>` tag. Each list item starts with the `<li>`tag.

```
<ol>
  <li>Yellow</li>
  <li>Orange</li>
  <li>Purple</li>
</ol>

```

## Tables

**tables are very useful when it comes to navigation bars**

Use `<table> </table>` tags to define a table, and 

Each table cell is defined by a `<td> </td>` tag (table data tags).

You can also use `<tr> </tr>` tag to further define your rows (table row tags).

```
<table>
  <tr>
    <td>A</td>
    <td>B</td>
    <td>C</td>
  </tr>
</table>
```

## Forms

![Meme](https://img-9gag-fun.9cache.com/photo/aV3wWMd_460s.jpg)

The HTML `<form>` element is used to create an HTML form for user input, a container for different elements like text fields, checkboxes, radio buttons, submit buttons, etc.

The HTML `<input>` (single) element is the most used form element.

```
<input type="text">
<input type="radio">
<input type="checkbox">
<input type="button">
<input type="submit">
```

For each input tag, you can link each tag with a `<label>` tag, and the `for` attribute of the label must match the `id` attribute of the `<input>` element.

```
  <label for="name">First name:</label><br>
 <input type="text" id="name" >

```

The `<input type="submit">` defines a button for submitting the form data to a form-handler.

The form-handler is typically a file on the server with a script for processing input data.

The form-handler is specified in the form's `action` attribute

Notice that each input field must have a `name` attribute to be submitted.

If the name attribute is omitted, the value of the input field will not be sent at all.


```
<form action="/some-random-server.php">
  <label for="name">First name:</label><br>
  <input type="text" id="name" value="John"><br><br>
  <input type="submit" value="Submit">
</form>

```
