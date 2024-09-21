# css-interview-questions

### Table of Contents 

| No | Questions |
|-| ----------------------- |
1 | [Draw two divs, one inside the other and center the inner one?](https://github.com/erblackcode/interview-questions?tab=readme-ov-file#Draw-two-divs-one-inside-the-other-and-center-the-inner-one) |
2 | [What is box sizing in css?](https://github.com/erblackcode/interview-questions?tab=readme-ov-file#What-is-box-sizing-in-css) |
3 | [What are the various positions in css Explain all?](https://github.com/erblackcode/interview-questions?tab=readme-ov-file#What-are-the-various-positions-in-css-Explain-all) |
4 | [If there are multiple styles (css) for the same node, which takes precedence (concept of css specificity)?](https://github.com/erblackcode/interview-questions?tab=readme-ov-file#If-there-are-multiple-styles-css-for-the-same-node-which-takes-precedence-concept-of-css-specificity) |

## Questions

### Draw two divs, one inside the other and center the inner one?

```html
<div class='parent'>
<div class='child'>
I am centered!
</div>
</div>

// CSS
.parent {
  border: 1px solid black;
  display: flex;
  justify-content: center;
}
.child {
  border: 1px solid red;
}
```
**OUTPUT-** ![App Screenshot](https://images.app.goo.gl/QPvtVX3YrZT8StvY8)
