<!-- {% raw %} -->
<img src="https://images.unsplash.com/photo-1600981806713-d141a32a4f7b" width="900">

# Finch Collector Lab

## Intro

We have chosen to collect Finches in this example!


## Exercises

Following the steps we took in the **Django URLs, Views, and Templates lesson**, complete the following exercises:

1. Create a Finch model with at least 3 attributes - Name, Scientific Name, Colors - Plus any that you'd like
2.  Simulate finch data using a list of finch dictionaries in **views.py**.1. 
3. Implement the following User Stories:
	- AAU, I want to be able to navigate to separate pages for `About` and `All Finches` using a navbar for my Index and Show route
	
	- AAU, when I visit the `About` page, I want to view some details about the finchcollector application.

	- AAU, when I visit the `All Finches` page, I want to view a list of all finches (index view) that displays each of the attributes of a finch.


4. Using the Python Interactive Shell (`python3 manage.py shell`), create some finches in your database to be rendered on the page.

    > Don't forget to import your Finch model

5. Register the Finch model with the admin portal in `admin.py`.

6. Implement the following User Stories:
	- AAU, when I visit the `All Finches` page, I want to view a list of all finches **from the database** (index view) that displays each of the attributes of a finch.

	- AAU, when I click on a finch card on the index page, I want to be taken to a details page where I can see all attributes of the finch.

	- AAU, I want to be able to add a Finch to my list of Finches

	- AAU, I want to be able to add edit the attributes of a Finch

	- AAU, I want to be able to remove a Finch from my list of Finches

7. Create another model "Feeding" that will have a One:Many relationship with your main data entity.
   Implement similar functionality to the Feeding model in catcollector, including the following User Stories:

  - AAU, when I visit the detail page for a finch, I want to see a list of feedings for that finch.

  - AAU, when I visit the detail page for a finch, I want to be able to add a feeding for a finch.


8.  Create another model "Habitat" that will have a Many:Many relationship with your main data entity.

    - Don't forget to add a ManyToManyField on one of the Models.
      
    - Attach Many of your Finches to Many of your Habitats
  
    - Create Views with Create, Update, and Delete functionality for each of your habitats with Finches related


## Bonus

1. Customize your application using CSS, or even a third party CSS library! Here are a few links to some great ones below:
	- [Materialize CSS](https://materializecss.com/getting-started.html)
	- [Bootstrap](https://getbootstrap.com/docs/5.1/getting-started/introduction/)
	- [Foundation](https://get.foundation/sites/docs/installation.html)
	- [Bulma](https://bulma.io/documentation/overview/start/)


<!-- {% endraw %} -->
