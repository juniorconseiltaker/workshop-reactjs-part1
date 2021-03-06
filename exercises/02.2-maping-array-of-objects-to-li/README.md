# `02.2` Mapping function

When you are mapping an array of data to convert it into an array of HTML you have to specify a **"mapping function"** that will receive each item from the original array, transform it and insert it into the new array. E.g.:

```js

const originalData = [];

const mappingFunction = (item, index) => {
  // return something in JSX.
};

const htmlList = originalData.map(mappingFunction);
// the htmlList variable now contains a new array.
```

# 📝 Instructions:

1. Use the [list-group bootstrap](https://getbootstrap.com/docs/4.1/components/list-group/#basic-example) component to render a list of planets from a given array:

```js
const planets = [ 'Mars', 'Venus', 'Jupiter', 'Earth', 'Saturn', 'Neptune' ];
```

2. Use the [.map function](https://medium.com/poka-techblog/simplify-your-javascript-use-map-reduce-and-filter-bd02c593cc2d) and make your algorithm output the following HTML:

```jsx
<ul class="list-group m-5">
  <li class="list-group-item">Mars</li>
  <li class="list-group-item">Venus</li>
  <li class="list-group-item">Jupiter</li>
  <li class="list-group-item">Earth</li>
  <li class="list-group-item">Saturn</li>
  <li class="list-group-item">Neptune</li>
</ul>
```

3. Include them all together inside the website.

## Expected result:

![list-group](../../.learn/assets/02.2-1.png?raw=true)

---

<div align="center">

<a href="https://github.com/juniorconseiltaker" target="_blank"><img src="../../.assets/taker-icon.png" width="50"></a>

</div>