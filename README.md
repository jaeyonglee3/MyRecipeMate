# MyRecipeMate

## Members
- Pratyush Dwivedi
- Jaeyong Lee
- David (Jia Jun) Wu
- Kevin Hu

## Problem Domain
- As university students, our busy lives often prevent us from spending too
much time cooking or trying new recipes
- Our application seeks to tackle this issue by providing a platform for users
to seek out new recipes, save their favourites, and add tags / categorise their
recipes

## Application Description

- Allows searching of recipes by various methods, including:
    - By name
    - By 5-digit ID
    - By cuisine
- Allows recipes to be "favourited"
- Allows recipes to be associated with a certain tag / tags
- Allows the user to save and load their information (e.g. favourited recipes,
tagged recipes and associated tags, etc) to / from a file

## API We Can Use

- For recipes, we make use of [TheMealDB API](https://themealdb.com/api.php)

![Sample usage of TheMealDB API](./docs/Sample_API_Usage.png)

## Example Output From Request To API

```
{
  "meals": [
    {
      "idMeal": "52770",
      "strMeal": "Spaghetti Bolognese",
      "strDrinkAlternate": null,
      "strCategory": "Beef",
      "strArea": "Italian",
      "strInstructions": "Put the onion and oil in a large pan and fry over a fairly high heat for 3-4 mins. Add the garlic and mince and fry until they both brown. Add the mushrooms and herbs, and cook for another couple of mins.\r\n\r\nStir in the tomatoes, beef stock, tomato ketchup or purée, Worcestershire sauce and seasoning. Bring to the boil, then reduce the heat, cover and simmer, stirring occasionally, for 30 mins.\r\n\r\nMeanwhile, cook the spaghetti in a large pan of boiling, salted water, according to packet instructions. Drain well, run hot water through it, put it back in the pan and add a dash of olive oil, if you like, then stir in the meat sauce. Serve in hot bowls and hand round Parmesan cheese, for sprinkling on top.",
      "strMealThumb": "https://www.themealdb.com/images/media/meals/sutysw1468247559.jpg",
      "strTags": "Pasta,Meat",
      "strYoutube": "https://www.youtube.com/watch?v=-gF8d-fitkU",
      "strIngredient1": "onions",
      "strIngredient2": "olive oil",
      "strIngredient3": "garlic",
      "strIngredient4": "lean minced beef",
      "strIngredient5": "mushrooms",
      "strIngredient6": "dried oregano",
      "strIngredient7": "tomatoes",
      "strIngredient8": "hot beef stock",
      "strIngredient9": "tomato puree",
      "strIngredient10": "worcestershire sauce",
      "strIngredient11": "spaghetti",
      "strIngredient12": "parmesan",
      "strIngredient13": null,
      "strIngredient14": null,
      "strIngredient15": null,
      "strIngredient16": null,
      "strIngredient17": null,
      "strIngredient18": null,
      "strIngredient19": null,
      "strIngredient20": null,
      "strMeasure1": "2",
      "strMeasure2": "1tbsp",
      "strMeasure3": "1 clove",
      "strMeasure4": "500g",
      "strMeasure5": "90g",
      "strMeasure6": "1tsp",
      "strMeasure7": "400g can",
      "strMeasure8": "300ml",
      "strMeasure9": "1tbsp",
      "strMeasure10": "1tbsp",
      "strMeasure11": "350g",
      "strMeasure12": "Topping",
      "strMeasure13": "",
      "strMeasure14": "",
      "strMeasure15": "",
      "strMeasure16": null,
      "strMeasure17": null,
      "strMeasure18": null,
      "strMeasure19": null,
      "strMeasure20": null,
      "strSource": null,
      "strImageSource": null,
      "strCreativeCommonsConfirmed": null,
      "dateModified": null
    },
    {
      "idMeal": "52982",
      "strMeal": "Spaghetti alla Carbonara",
      "strDrinkAlternate": null,
      "strCategory": "Pasta",
      "strArea": "Italian",
      "strInstructions": "STEP 1\r\nPut a large saucepan of water on to boil.\r\n\r\nSTEP 2\r\nFinely chop the 100g pancetta, having first removed any rind. Finely grate 50g pecorino cheese and 50g parmesan and mix them together.\r\n\r\nSTEP 3\r\nBeat the 3 large eggs in a medium bowl and season with a little freshly grated black pepper. Set everything aside.\r\n\r\nSTEP 4\r\nAdd 1 tsp salt to the boiling water, add 350g spaghetti and when the water comes back to the boil, cook at a constant simmer, covered, for 10 minutes or until al dente (just cooked).\r\n\r\nSTEP 5\r\nSquash 2 peeled plump garlic cloves with the blade of a knife, just to bruise it.\r\n\r\nSTEP 6\r\nWhile the spaghetti is cooking, fry the pancetta with the garlic. Drop 50g unsalted butter into a large frying pan or wok and, as soon as the butter has melted, tip in the pancetta and garlic.\r\n\r\nSTEP 7\r\nLeave to cook on a medium heat for about 5 minutes, stirring often, until the pancetta is golden and crisp. The garlic has now imparted its flavour, so take it out with a slotted spoon and discard.\r\n\r\nSTEP 8\r\nKeep the heat under the pancetta on low. When the pasta is ready, lift it from the water with a pasta fork or tongs and put it in the frying pan with the pancetta. Don’t worry if a little water drops in the pan as well (you want this to happen) and don’t throw the pasta water away yet.\r\n\r\nSTEP 9\r\nMix most of the cheese in with the eggs, keeping a small handful back for sprinkling over later.\r\n\r\nSTEP 10\r\nTake the pan of spaghetti and pancetta off the heat. Now quickly pour in the eggs and cheese. Using the tongs or a long fork, lift up the spaghetti so it mixes easily with the egg mixture, which thickens but doesn’t scramble, and everything is coated.\r\n\r\nSTEP 11\r\nAdd extra pasta cooking water to keep it saucy (several tablespoons should do it). You don’t want it wet, just moist. Season with a little salt, if needed.\r\n\r\nSTEP 12\r\nUse a long-pronged fork to twist the pasta on to the serving plate or bowl. Serve immediately with a little sprinkling of the remaining cheese and a grating of black pepper. If the dish does get a little dry before serving, splash in some more hot pasta water and the glossy sauciness will be revived.",
      "strMealThumb": "https://www.themealdb.com/images/media/meals/llcbn01574260722.jpg",
      "strTags": "Pasta,BBQ,Breakfast",
      "strYoutube": "https://www.youtube.com/watch?v=_T6jkRvhlkk",
      "strIngredient1": "Spaghetti",
      "strIngredient2": "Egg Yolks",
      "strIngredient3": "Salt",
      "strIngredient4": "Bacon",
      "strIngredient5": "Pecorino",
      "strIngredient6": "Black Pepper",
      "strIngredient7": "",
      "strIngredient8": "",
      "strIngredient9": "",
      "strIngredient10": "",
      "strIngredient11": "",
      "strIngredient12": "",
      "strIngredient13": "",
      "strIngredient14": "",
      "strIngredient15": "",
      "strIngredient16": "",
      "strIngredient17": "",
      "strIngredient18": "",
      "strIngredient19": "",
      "strIngredient20": "",
      "strMeasure1": "320g",
      "strMeasure2": "6",
      "strMeasure3": "As required",
      "strMeasure4": "150g",
      "strMeasure5": "50g",
      "strMeasure6": "As required",
      "strMeasure7": " ",
      "strMeasure8": " ",
      "strMeasure9": " ",
      "strMeasure10": " ",
      "strMeasure11": " ",
      "strMeasure12": " ",
      "strMeasure13": " ",
      "strMeasure14": " ",
      "strMeasure15": " ",
      "strMeasure16": " ",
      "strMeasure17": " ",
      "strMeasure18": " ",
      "strMeasure19": " ",
      "strMeasure20": " ",
      "strSource": "https://www.bbcgoodfood.com/recipes/ultimate-spaghetti-carbonara-recipe",
      "strImageSource": null,
      "strCreativeCommonsConfirmed": null,
      "dateModified": null
    }
  ]
}
```
