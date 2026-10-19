# Part 1: How to Enable Developer Mode (Debug Mode) in Odoo

Developer Mode unlocks technical configuration menus, advanced database fields, XML view editing, and server parameters.

## Method 1 Via Odoo Settings (Standard Way)

1. Log in to your Odoo instance as an Administrator. 
2. Navigate to Settings from the main app dashboard.  
3. Scroll down to the bottom to the Developer Tools section.
4. Click Activate the developer mode (or "Activate the developer mode (with assets)" for debugging raw JS/CSS files). 

Visual Check: A bug icon ($\text{🪲}$) will appear in the top right menu bar next to your profile photo, confirming Developer Mode is active.

---

## Method 2: Via URL Parameter (Fast Method)

1. Open any page in your Odoo database. 
2. In your browser's web address bar, insert ?**debug=1** into the URL directly after /web. 
-  Example: [https://your-company.odoo.com/web?debug=1#action=123](https://your-company.odoo.com/web?debug=1#action=123)...
 3. Press Enter to reload the page with Developer Mode enabled. 
 