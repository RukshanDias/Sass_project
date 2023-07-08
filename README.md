# Sass crash course
 - Syntactically Awsome StyleSheet
 - CSS preprocessor
 - sass files will be compiled to css

## Sass vs Scss
 - Sass use indentation, Scss use curly brackets.
 - But both will be compiled into same css.


### Variables
- use '$' initialize var. ($color: #333)
- reusable.

### Nesting
- Reduce code repeating.
- <img src="readMe_imgs/nesting_code.png" alt="Nesting" width="600px">

### Models or Partials
- these are Sass or Scss files that have an underscore in the front of the filename.
- underscore will make this file compile only when the file is imported.
- <img src="readMe_imgs/modules_code.png" alt="Modules" width="600px">

### Mixins & Functions
- Mixins will provide setof css rules, which are reuseable.
    - use '@mixin' to create.
    - use '@include' to call.
- Function will performe calculations, that will return something.
- <img src="readMe_imgs/mixins_code.png" alt="Mixin" width="600px">

### Inheritance (Extende)
- copy the same style & apply to an element.
- write '@extend' and name of the styling.
- <img src="readMe_imgs/extend_code.png" alt="Extend" width="600px">

### Conditionals
- use '@if', '@else if', 'else'.
- <img src="readMe_imgs/conditionals_code.png" alt="Condition" width="600px">
