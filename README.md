# Project Overview

This project is a functional webpage for a **Food Ordering & Customer Management System** designed for Mr. Chuks' food business under **TrueMinds Innovations Ltd**

**The system visually represents a platform where customers can:**

* Register an account and sign in
* Browse available meals and
* View meal details

**Note:**
This website is strictly frontend only. No backend logic, APIs, authentication, or database integration were included as per project requirements.

## Tech Stack Used
**HTML5**
* Used for semantic structure and accessibility.

**CSS3**
* Used for styling and layout implementation.
* Flexbox – For arrange items horizontally/vertically within a container.
* CSS Grid – For meal card layout and responsive content grids
* Media Queries – For responsive design

**Google Fonts**
* Used to match the typography defined in the Figma design.

**Font awesome icons & Material symbols icons**
* Used to download icons on the webpage to match the icons defined in the figma design.

# Project Structure

```
Chuks Kitchen/
|
├── index.html
├── register.html
├── login.html
├── home.html
├── menu.html
├── menu-details.html
|
├── css/
     └── styles.css
|
├── images/
|
└── README.md
```

**Explanation of Key Files**

* index.html – Landing/Welcome page layout
* register.html – Customer registration form
* login.html - User signin form
* home.html - Homepage layout, it also displays featured food items in grid layout
* menu.html – Displays meal listing grid
* menu-details.html – Shows detailed meal information
* styles.css – Contains global styles, layout styles, and responsive rules
* images/ – Stores images and static resources

# Design Interpretation

The UI was implemented based on the provided Figma design.

**Key Translation Decisions**

* The card-based meal layout was implemented using CSS Grid for scalability.
* Navigation and header sections were built using Flexbox to maintain alignment.
* Consistent spacing was achieved using a spacing system (8px / 16px multiples).

**Assumptions Made**

* I implemeted hover effects on buttons and meal card.
*  Mobile breakpoint was assumed at 700px.

# Limitations & Improvements
 
* No backend logic
* No real authetication 
* I was able to create only six pages

## Improvements(If given more time)

I would:
* Connect to backend API for real-time data
* Add user authenticaion
* Create the **Add to Cart Page** and **Order Summary Page**
