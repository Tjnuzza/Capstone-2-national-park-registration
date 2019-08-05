# Capstone-2-national-park-registration
Second capstone project for Tech Elevator coding bootcamp. This program allows the user to use a command line interface
to make reservations for a campsite at a park, using C# and SQL.

## Overview
This is our second project. I had a partner who shall for now remain nameless because I have not yet asked his permission.
It was the final project of our second module, which focused on databases and SQL.
We also used C# to access the database.

## How it works
The Program uses command lines to ask the user which park, campground, and site they wish to camp at.
When they make a reservation, the database checks to see if there are any campsites at the chosen campground
that will be available for the dates that the user selected.
If they can, the user then selects a site where they will stay, and the database records the reservation.

## Known issues and future plans
The CLI menus are stacked and nested in such a way that they were relatively difficult to keep straight.
We managed to make it work, but I feel there was a better way to do this.
If I ever have time, I may make a version of the project that has a simpler internal structure.
