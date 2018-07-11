# Nunc UI Developer Candidate Demo
This is a demo project to gauge a candidate's HTML, CSS and JS knowledge.

## Fork the repository
This repository is read only so to push your changes you'll need to fork it. After completeing all the tasks push code to your own repo and let us know.

## Tips

* Try to have a least one commit per task so that we can see the work progress
* Use descriptive commit comments
* It's up to you whether you want to push regularly or once you are finished with all of your commits
* You are free to add whatever frameworks or libraries you like, but be prepared to justify your use of them.
* Things to consider: performance, efficient use of space, usability, cross-browser, responsiveness.

## Tasks
### 1. Create product listing page
* Use `app/index.html` file
* Create a full width page with a header, a footer and a main section in index.html.
* Main section should be populated with products using AJAX - data set `src/data/products.json`
* Each product should include image thumbnail, product name, product price (current, was and discount price), size and be linked to `url` key
* Add Favourite icon to each product
* Desktop design for products layout is provided in `app/plp-design.png` 
* It should be fully responsive
* Add toggle option between list and grid view
* Add comments on what other improvements would you add to this page
* **Optional task:** The data set is reasonably large so we need to be able to: **filter the data by:** category, price, size and **sort the data by:** price (ascending), price (descending) and name (ascending)

### 2. Form Validation
* Use `app/form.html` file
* Add a form with following fields:
  - name: text only, no case sensitive
  - surname: text only, no case sensitive
  - email: alphanumeric, no case sensitive must contain `@` symbol and domain name
  - phone: can contain `+` (only in front of the number) and `space` characters and numbers only
  - password: must be at least 8 long and contain at least 1 special character
* Display error messages for each invalid field
* All fileds are required and needs to be valid before form can be submitted
* Use only vanilla JS for this tasks (do not use plugins or HTML5 API)
* **Optional task:** add unit tests

## Finished
Once you've completed the above, please email so that we know your work is ready to be reviewed. Push your code to your repo.
