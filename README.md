**HTML**


Basic Structure

```
<!DOCTYPE html> // Defines the document as HTML5.
<html lang="en">
<head> 
    <title>My HTML Page</title>
</head>
<body>
    <h1>Welcome to HTML</h1>
    <p>This is a basic HTML page.</p>
</body>
</html>
```

**Common Tags**  
h1-h6, p, a, img, ul-li, ol, table, span  

**Form**  
```
<form>
  <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>
  <button type="submit">Submit</button>
</form>
```

**Images and Link**  
anchor tag  
```
<a href="https://www.tt.com" target="_blank">(For New browser tab) eg</a>
```

**Table Example**  
```
<table border="1">
    <tr> //New Row
        <th>Name</th> //Heading
        <th>Age</th>
    </tr>
    <tr>
        <td>John</td> //Data
        <td>25</td>
    </tr>
</table>
```
**CSS**

**Basic CSS Syntax**
```css
selector {
    property: value;
}
```

**Selectors**
```css
/* Select by element */
p {
    color: blue;
}

/* Select by class */
.my-class {
    font-size: 16px;
}

/* Select by ID */
#my-id {
    background-color: yellow;
}
```

**Box Model**
```css
div {
    width: 100px;
    height: 100px;
    padding: 10px;
    border: 5px solid black;
    margin: 20px;
}
```

**Flexbox**
```css
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}
```

**Grid Layout**
```css
.grid-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
}
```

**Positioning**
```css
.absolute-box {
    position: absolute;
    top: 50px;
    left: 50px;
}

.fixed-box {
    position: fixed;
    bottom: 0;
    right: 0;
}
```
**Transitions & Animations**
```css
div {
    transition: all 0.5s ease;
}

div:hover {
    transform: scale(1.1);
}
```

**Responsive Design**
```css
@media (max-width: 600px) {
    body {
        background-color: lightgray;
    }
}
```


