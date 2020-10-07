# React Props & State Workshop

1. create a `MenuList` component;
2. from `App.js`, pass the variable `foodItems` to `MenuList` component as *props*;
3. on `MenuList`, receive the *props* render a `MenuItem` component for each item in the array;
4. on `MenuItem`, create a state `isFavorite` that will have the initial value of the *prop* `isFavorite`;
5. on `MenuItem` access each property from *props* to show the food item name, image, description and price;
6. create a method `handleClickFavorite` that will switch the state `isFavorite` from true to false.
7. on the indicated area, conditionally render the `className` **"isFavorite"** or **"notFavorite"**, depending on the state `isFavorite`