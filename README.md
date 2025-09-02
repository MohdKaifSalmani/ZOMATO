**📖 Documentation for Zomato Restaurant Listing Project**

**1. HTML (Structure of the Webpage)**

(a) **Header Section**
Contains the Zomato logo.
**Has buttons:** Filters, Offers, Rating 4.5+, Serves Alcohol, Open Now.

(b) **Filter Popup**
Hidden by default.
Opens when you click Filters button.
Options available:
Sort by Rating
Cost: High to Low
Cost: Low to High
Distance

(c) **Main Content Area (#root)**
This is where restaurant cards are displayed.
Cards are created dynamically using JavaScript.

(d) **Footer**
Shows copyright.


**2. CSS (Styling of the Webpage)**

**Bod**y → Dark background for contrast.
**Header** → Black background, Zomato in red, buttons in green (turn black on hover).
**Restaurant Cards**
~ White box with shadow and rounded corners.
~Hover effect → card slightly moves up.
~Each card shows: image, offer label, name, rating, food type, price, location, and distance.
**Filter Popup** → A centered box with radio buttons and "Apply" & "Close".
**Footer** → Dark background with white text.

**3. JavaScript (Functionality of the Webpage)**

(a) **Restaurant Data**
~ Stored as objects (name, rating, food type, cost, location, distance, offers, alcohol, opening/closing times).

(b) **Creating Cards (getrestaurant)**
~ Uses restaurant data to create and display restaurant cards inside #root.

(c) **Filter & Sorting Functions**
**Offers** → Shows restaurants with discounts.
**Alcohol** → Shows restaurants serving alcohol.
**Rating 4.5+** → Shows only restaurants with high ratings.
**Open Now** → Compares restaurant timings with current time.
**Filters Popup** → Sorts restaurants by rating, cost, or distance.

**4. How It Works (Step by Step)**

When page loads → all restaurants are shown in card format.
User clicks a filter button → list updates instantly.
User opens Filters popup → selects sorting (rating, cost, distance).
Restaurants rearrange accordingly.
Footer stays fixed at bottom.
