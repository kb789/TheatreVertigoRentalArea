# TheatreVertigoRentalArea

As a Software Developer Intern at Prosper I.T. Consulting, I had the opportunity to work on a portion of a website for a theatre, Theatre Vertigo. This site is an ASP.NET MVC 5 application that uses Entity Framework 6 for data access, and Bootstrap for styling. I worked on the Rental Histories arrea of the website. Utilizing Code-Based Migrations, I created a model for the Rental Histories and then scaffolded a controller with views to enable basic CRUD functionality.

I customized the listing of rentals so that rentals that were damaged would display with a red X, and rentals that weren't damaged would display with a green check mark.

![Rental Histories](https://github.com/kb789/TheatreVertigoRentalArea/blob/master/images/Screenshot%202023-10-11%20215516.png)

I implemented sorting functionality, so that the list can be sorted by damaged or undamaged rentals, or A-Z or Z-A. I utilized a partial view and jquery to ensure that the entire page woul not reload when the sort button is clicked.

![Sort1](https://github.com/kb789/TheatreVertigoRentalArea/blob/master/images/Screenshot%202023-10-11%20220342.png)
![Sort1](https://github.com/kb789/TheatreVertigoRentalArea/blob/master/images/Screenshot%202023-10-11%20220421.png)

I also added accordion functionality. If the description of the damage is long, it is shortened by default; if you click on it, you will see the full listing.

![Accordion](https://github.com/kb789/TheatreVertigoRentalArea/blob/master/images/Screenshot%202023-10-11%20215552.png)

I created a hover menu that links to Edit, Details, and Delete options for the rental listings. 

![Hover](https://github.com/kb789/TheatreVertigoRentalArea/blob/master/images/Screenshot%202023-10-11%20220455.png)

On the Add and Edit Rental Forms, I implemented a "damaged" checkbox that toggles the label of the textbox to either "Damages incurred" or "Notes"

![DamageToggle1](https://github.com/kb789/TheatreVertigoRentalArea/blob/master/images/Screenshot%202023-10-11%20215644.png)
![DamageToggle2](https://github.com/kb789/TheatreVertigoRentalArea/blob/master/images/Screenshot%202023-10-11%20215718.png)

I created a History Manager role, and restricted the creating, editing, and deleting of rentals to users with this role.


I seeded the database with a test user that has the history manager role, and then created a History Manager button for development purposes that, when clicked, would automatically log the person in as this user.




 
