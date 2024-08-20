## Use Case Example

```html
<script src="https://cdn.jsdelivr.net/gh/DeshiJS/DeshiRouter@main/1.0v.js" defer></script>
`  <nav>
    <a href="/" onclick="route(event)">Home</a>
    <a href="/about" onclick="route(event)">About</a>
    <a href="/contact" onclick="route(event)">Contact</a>
  </nav>
  
  <div id="root"></div>
`
```

## JavaScript

```javascript
const routes = {
  '/': 'home.html',
  '/about': 'about.html',
  '/contact': 'contact.html',
  404: '404.html'
};
```

# Example HTML Files

### home.html
```html
<h1>Welcome to the Home Page</h1>
<p>This is the home page content.</p>
```
### about.html

```html
<h1>About Us</h1>
<p>Information about us.</p>

```
