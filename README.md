# SpendWise Dashboard

## About the Project

SpendWise is a responsive financial dashboard that helps users view and organize their spending information.

This project rebuilds the Budget Tracker layout using modern CSS Grid and Flexbox techniques.

## Dashboard Features

The dashboard contains:

* A sidebar navigation menu
* A dashboard header
* A total balance section
* Six financial category cards:

  * Food
  * Transport
  * Rent
  * Entertainment
  * Savings
  * Utilities

The financial information is static and is used to demonstrate the dashboard layout.

## CSS Grid

CSS Grid is used for:

* The overall dashboard layout
* The financial category card layout

The desktop layout uses a sidebar and main content area.

## Flexbox

Flexbox is used inside:

* The sidebar navigation
* The dashboard header
* The balance section
* Each financial card

No absolute positioning is used for the page layout.

## CSS Custom Properties

The project uses CSS variables inside `:root` for the theme.

The variables include:

* Brand color
* Accent color
* Surface color
* Background color
* Primary text color
* Secondary text color
* Border color

These variables keep the design consistent and make the theme easier to maintain.

## Responsive Design

The dashboard uses a media query at `max-width: 768px`.

On smaller screens:

* The sidebar and main content become a single-column layout.
* The navigation becomes flexible.
* The header stacks vertically.
* The financial cards display in one column.

The layout can be tested using the browser DevTools Device Toolbar.

## Card Micro-interactions

The dashboard cards include hover and keyboard focus effects.

The cards use:

* `transform`
* `box-shadow`

The transition takes 200ms, which is within the required 250ms limit.

## Dark Theme

A dark theme is included using:

`@media (prefers-color-scheme: dark)`

The dark theme changes the CSS custom properties while keeping the same dashboard structure.

## Files

* `index.html` — Contains the SpendWise dashboard structure and financial information.
* `style.css` — Contains the Grid, Flexbox, responsive design, theme variables, typography, and card interactions.
* `README.md` — Explains the dashboard and the CSS techniques used.
