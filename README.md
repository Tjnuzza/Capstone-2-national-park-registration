# Capstone 2: National Park Registration
Second capstone project for Tech Elevator coding bootcamp. This program allows the user to use a command line interface
to make reservations for a campsite at a park, using C# and SQL.

## Overview
This is our second project. I had a partner who shall for now remain nameless because I have not yet asked his permission.
It was the final project of our second module, which introduces database design and programming concepts using SSMS for the .Net track. We also learned how to access our database using C# tools to create a database access layer. We did not design this database, which has a rather simple structure regardless.

## How it works
There are a series of CLI menus within this program which allow the user to narrow down their choices. It starts with the user selecting which park they want to see, and then they can choose to see more information or make a reservation for camping at that park.

The user then selects the campground where they wish to stay. The program shows the information for the sites at this campground to allow the user to make further choices regarding their stay. When they enter their desired location and dates, they program shows a list of all campsites that the user may select for a stay. It then allows them to record their reservation and save it as a reservation in our database.

This final menu calls the database for a query to select all the sites at the chosen campground that are not reserved for the desired dates. If there are none available, the user must enter new information, because there cannot be overlapping reservations.

## Known issues and future plans
The CLI menus are stacked and nested in such a way that they were relatively difficult to keep straight.
We managed to make it work, but I feel there was a better way to do this.
If I ever have time, I may make a version of the project that has a simpler internal structure.
Additionally, I'm sure there are some glitches to iron out.

Additionally, we ran out of time to implement all of the challenge problems that were not necessary, because we both were unable to work over the weekend due to prior commitments. I may someday add these features, which include things like searching for campsites of a given size, sites that allow RVs, and an assortment of other things.
