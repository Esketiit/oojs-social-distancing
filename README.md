# Build Steven a Binge-Watching List in OOJS

Being trapped indoors has me wanting for some new TV series to watch. Let's build something using Object Oriented JavaScript to make a playlist of stuff I should binge while social distancing. 

Also, I watch a lot of TV so you're going to have to get creative...

*You can use the boilerplate code to test your 

1. Create a TV Series class in JavaScript. It should initialize with the following properties: title, number of seasons, streaming service, genre, years.

```javascript

```

2. How is `this` being used above? What object does it reference?

```

```

3. Create an instance method in the class called `prettyPrint` that returns a string formatted like this: `Stranger Things, Science Fiction, 3 seasons, available on Netflix, 2016-2019`

```javascript

```

4. Create an instance method that returns the following HTML. Give it an appropriate name.

```html
<div>
  <h1>Stranger Things</h1>
  <h3>Science Fiction</h3>
  <p>3 Seasons</p>
  <p>2016-2019</p>
  <p>Netflix</p>
</div>
```

```javascript

```

5. Create an instance method called `render` that accepts a DOM node as an argument and appends the div from above onto it.

```javascript

```

6. Create a class method called `all` that returns all the TV Series that have been created. (Hint: how will you have to modify the constructor?)

```javascript

```

7. Write a function separate from the class that, when given an array of object literals representing TV Series, returns an array of pretty printed strings.

```javascript

```

8. Write a function separate from the class that will render all the TV series that have been created onto a page with the following HTML.

```html
<div id="container"></div>
```