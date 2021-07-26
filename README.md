# Lodgify - Frontend Technical Test

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## The Task 

List the houses of customers using a grid of cards.

The data was an array of object, like below:

```json
[
	{
		"id": "6489887061",
		"name": "Roxbury",
		"image": "https://picsum.photos/1614/807",
		"bookable": true,
		"booked":7
	}
]
```

The conditions were following:

- **id :** the id of the house
- **name :** the name of the house
- **image** : the image of the house
- **bookable** : if it's - **available** or **unavailable**
- **booked** : 0 means that can be **booked (button)** or shows how many days is booked

![Alt text](https://github.com/aditidw/lodgify-react-app/blob/develop/public/Figma_image.png?raw=true "Figma Image")

## First time setup

The first step to running lodgify-app locally by downloading the code by cloning the repository:

git clone git@github.com:aditidw/lodgify-react-app.git

If you get Permission denied error using ssh refer here or use https link as a fallback.

git clone https://github.com/aditidw/lodgify-react-app.git


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.
