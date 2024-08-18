<h1 text="center"> scss mixin </h1>
<p>To Use ash_sass_mixins</p>

```sh
npm i ash_sass_mixins
```

To Import Flex Mixins Styles For Example;
```scss
@use '../node_modules/ash_sass_mixins/src/flex' as *;
```

<p>You Have Sass And Grid Controlling Mixins Classes</p>
<p>Can You Save A Lot Of Lines</p>
<p>Reset Page Spaces</p>

## Responsive Utilities

### 1. Responsive Padding

```scss
// SCSS
@include responsive-padding(10px, 20px, 30px, 40px, 50px);
```

### 2. Responsive margin
```scss
@include responsive-margin(5px, 10px, 15px, 20px, 25px);
```

### 3. Responsive Flex Direction
```scss
@include responsive-flex-direction(row, column, row-reverse, column-reverse, row);
```

### 3. Responsive Flex Container
```scss
@include responsive-flex-container(row, center, center, 10px, column, space-between, center, 20px);
```



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

This project was created by Ashraf Mohaemd. For any inquiries, please contact the author at [ashraf-1.vercel.app](https://ashraf-1.vercel.app/).

## Repository

The source code for this project can be found at [GitHub Repository](https://github.com/ashrafmo-1/sassMixins).

## Copyright

© 2024 Ashraf Mohaemd. All rights reserved.