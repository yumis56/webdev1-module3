# Using CSS Grid in the Skills Section

In our assignment, the CSS Grid plays a crucial role in organizing and presenting the 'Skills' section, which is meant to showcase the variety of skills in a structured and responsive manner.

## Required YouTube Videos
- [CSS Grid in 100 Seconds](https://www.youtube.com/watch?v=uuOXPWCh-6o)
- [Flexbox or grid - How to decide?](https://www.youtube.com/watch?v=3elGSZSWTbM)

- [Get started with grid WITHOUT being overwhelmed](https://www.youtube.com/watch?v=8QSqwbSztnA)

## Grid Container

Within our HTML, we would have a structure similar to this:

```html
<ul class="skill-list">
  <li>Skill 1</li>
  <li>Skill 2</li>
  <li>Skill 3</li>
  <!-- And so on... -->
</ul>
```

Here, `.skill-list` is the grid container. We establish this by declaring `display: grid;` in our CSS file. This immediately converts all direct children (`<li>` elements in this case) into grid items.

```css
.skill-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: calc(.5 * var(--base-spacing));
    margin-bottom: 1rem;
}
```

## Defining the Grid

The `grid-template-columns` property is used to define the grid's structure. In our assignment, we use the `repeat()` function, which allows us to repeat a particular pattern. The `auto-fit` keyword attempts to fit as many columns as it can, according to the minimum and maximum width defined by `minmax()`. This means our grid will have as many columns as can fit, with each column being at least `150px` wide, but also flexible enough to take up more space (indicated by `1fr`) if available.

## Grid Gap

The `gap` property determines the space between grid items. In our assignment, we calculate this gap using `calc(.5 * var(--base-spacing))`, which provides a responsive spacing based on the base spacing defined in our CSS variables.

## The Result

The result of using the CSS Grid in this manner is a dynamic and responsive 'Skills' section. It adapts to different viewport sizes by automatically adjusting the number of skill items per row based on the space available. This makes our 'Skills' section look well-organized and neat across different devices, which is a critical aspect of a responsive design.

By understanding these elements, you should now have a clear concept of how we have used CSS Grid in the 'Skills' section of our assignment.
