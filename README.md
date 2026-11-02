<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# AI-Powered Smart Fridge

Final project for the Building AI course

## Summary

This project is an AI-based system designed to track food items inside a refrigerator to reduce food waste. An internal camera captures images of the ingredients, automatically updates an expiration list, and alerts the user before food spoils. 

## Background

This idea solves several widespread issues:
* Every year, tons of food are wasted globally simply because people forget about items until they expire.
* Families often buy duplicate items at the grocery store because they cannot remember what is already inside their fridge.
* My personal motivation is to save household budgets and support sustainability by reducing kitchen waste.

## How is it used?

The solution operates automatically every time the refrigerator door closes. 
* Internal cameras take images of the shelves, and the Computer Vision model updates the food inventory app.
* Users can check their fridge content remotely while shopping.
* When an item is 2 days away from expiring, the app suggests creative recipes to use it up.
* Target users include busy professionals, students, and families looking to optimize their food management.

## Data sources and AI methods
The project relies on the following data resources and technology:
* **Data Sources:** Open-source food image datasets (such as ImageNet or specialized grocery datasets) to train the model.
* **AI Methods:** Computer Vision and Convolutional Neural Networks (CNN) for precise image recognition and object classification.

## Challenges

There are several constraints to consider:
* Physical limitations: Items hidden behind other products might be missed by the camera.
* Variety: Recognizing thousands of different brands and changing packaging shapes with 100% accuracy requires massive training data.
* Ethics: Personal consumption habits and data privacy must be strictly protected and secured.

## What next?

In the future, this project can scale up:
* It can integrate with broader Smart Home ecosystems to automatically order missing ingredients from online grocery stores.
* To achieve this, I would need assistance from mobile app developers and specialists in Big Data infrastructure.

## Acknowledgments

* Inspired by the educational framework of the "Building AI" course.
* Created by Reaktor Innovations and the University of Helsinki.
