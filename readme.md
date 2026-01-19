# **Overview**
A simple client-side web application for tracking income and expenses. Users can add transactions (positive for income, negative for expenses), view running totals, and delete entries. Data persists only for the current session (no storage backend).

The UI and structure is defined in 'index.html', 'style.css', with logic impllemented in 'script.js'.

#**Features**

*Add transactions with description and amount
*Income vs. expense categorization
*Running balance calculation
*Deletion of individual transactions
*Responsive and styled interface
*Animated list entries

#**How It Works**

*User enters a description and amount.
*Form submission triggers JavaScript to:
*Classify the transaction as income or expense
*Update the totals and balance
*Render a transaction item in the list
*Each transaction includes a delete control to remove it and calculate totals.

#**Tech Stack**

*HTML5
*CSS3 (Flexbox, Grid, animations)
*JavaScript (vanilla, no frameworks)

#**Usage**

Clone or download the repository and open index.html in any modern browser:
'''
$ open index.html
'''
No dependencies or build steps are required.

