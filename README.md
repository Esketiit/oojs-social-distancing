# Alleviate Steven's Boredom During Social-Distancing

---

>Being trapped indoors has me wanting for some new TV series to watch. Let's build something using Object Oriented JavaScript to make a playlist of stuff I should binge while social distancing. 
>
>Also, I watch a lot of TV so you're going to have to get creative...
>
>*You can use the boilerplate files to test your code.*

---

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

9. What is a `prototype`? What purpose does it serve in JavaScript?

```

```

10. What will be the return of the following expression? Why? 

```javascript

let strangerThings = new tvSeries({
  title: "Stranger Things", 
  numberOfSeason: 3, 
  service: "Netflix", 
  genre: "Science Fiction", years: "2016-2019"
  })

strangerThings.__proto__ === tvSeries.prototype // what will the return of this expression be?
```

```

```

---

> I'm also getting into gaming during this period of isolation. Let's start building a role playing game for me to play while I'm bore.

---

11. Let's shift our domain to video games. Create a `Hero` class with a constructor that accepts `name`, `age`, and `damagePoints` properites. 

```javascript

```

12. Create a `Warrior` class that inherits from `Hero`. Its constructor should accept the same parameters as `Hero` in addition to `weaponType` (e.g., sword, battle axe, spear, club, etc.).

```javascript

```

13. Create a `Mage` class that inherits from `Hero`. Its constructor should accept the same parameters as `Hero` in addition to `talisman` (e.g., staff, wand, rabbit foot, I don't know...).

```jasvascript

```

14. Create a function that allows any given hero to attack an enemy. The function should return a string like this: `Conan the Barbian has attacked you with a needlessly large sword! You have receive 10 damage points!`. (Hint: Where will this method go? How will you make it work for any given subclass, including ones we might add in the future - e.g. dwarf, dark elf, baker, etc.)

```javascript

```