# Fetch-iOS-Exercise

SwiftUI iOS app that allows users to browse recipes using the following API:
https://themealdb.com/api.php

There are 2 endpoints that the app will utilize:

* https://themealdb.com/api/json/v1/1/filter.php?c=Dessert for fetching the list of meals in the Dessert category.
* https://themealdb.com/api/json/v1/1/lookup.php?i=MEAL ID for fetching the meal details by its ID.

When the user selects a meal, it will be taken to a detail view that includes:

* Meal name
* Instructions
* Ingredients/measurements
