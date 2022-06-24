# 🍲 Vegon 🍛
![Logo](https://github.com/VegoGreen/vegon-foodish/blob/main/public/logo.ico "Samosa")

A Node.js/Express.js REST API to GET a random picture of food dishes.

![](https://img.shields.io/badge/contributions-welcome-34cdfa)

## Demo
Visit https://api.vegon.cloud/

## API Documentation
Base URL for all endpoints https://api.vegon.cloud/

_The response time will likely be a few seconds long on the first request, because this app is running on a free Heroku dyno. Subsequent requests will behave as normal._

### Endpoints
Routes | Description
------------ | -------------
`GET /api/` | Random food dish from random category.

Example Request-

`GET /api/`

Example Response-
```
{"image":"https://api.vegon.cloud/images/burger/burger101.jpg"}
```
----------------------------
Routes | Description
------------ | -------------
`GET /api/images/:food` | Random picture from `food` category.

Please visit the [demo](https://github.com/surhud004/Foodish#demo) website to view the list of available `food` categories.

Example Request-

`GET /api/images/biryani`

Example Response-
```
{"image":"https://api.vegon.cloud/images/biryani/biryani32.jpg"}
```
----------------------------
## Usage
* You are designing a restaurant website and you want to add random food pictures as placeholders.
* You are creating a guess the food dish game.
* You are ordering a pizza but you just want a random choice, visit https://foodish-api.herokuapp.com/images/pizza/ because that's fun! Didn't like the pizza? Just hit refresh!
* You just like to see food pictures (visual hunger) because _you eat with your eyes first._

## Authors
* [Surhud Bhagali](https://github.com/surhud004)
* * [revego](https://github.com/revego)
* Special thanks to [Rajaraman Ekambaram](https://github.com/Rtech2014) for providing the initial Foodish image database via [Kaggle](https://www.kaggle.com/datasets).
* Special thanks to [RitaE](https://pixabay.com/users/ritae-19628/) for providing some additional Foodish images via [Pixabay](https://pixabay.com/).
###### Please note that I do not own any of the Foodish dataset images. All Foodish images and their ownership belong to their original creators.

## Support
Please [create a new issue](https://github.com/revego/vegon-foodish/issues/new) for support and issues.

## Contributing
Please read the [CONTRIBUTING](https://github.com/revego/vegon-oodish/blob/main/CONTRIBUTING.md) for details on adding images to the Foodish Database.

## Contributors
* [angelina-tsuboi](https://github.com/angelina-tsuboi)
* [ElijahRus250](https://github.com/ElijahRus250)

## License
This project is licensed under [MIT](https://opensource.org/licenses/MIT). Please read the [LICENSE](https://github.com/surhud004/Foodish/blob/main/LICENSE) for details.

----------------------------
###### [Foodish API](https://github.com/surhud004/Foodish) is maintained by [surhud004](https://github.com/surhud004).
