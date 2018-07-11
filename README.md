# uidev_test
Assignment to assess UI developer skills
# Envoy FED Candidate Demo

This is a demo project to gauge a candidate's HTML, CSS and JS knowledge.

It uses Node and npm modules to setup local server.

## Fork the repository

This repository is read only so to push your changes you'll need to fork it.

* In Bitbucket click the `+` button on the left hand navigation
* In the _GET TO WORK_ section, choose _Fork this repository_
* In your forked repo click the _Settings_ cog in the left hand navigation and choose _General_ / _User and group access_
  Give read access to `lukaszpietraszek` and `timhillman`

## Getting Started

The project is a Node project.

Please make sure that you have it installed it on your local machine.

To install all necessary npm modules run:
`npm install`

Start up the server by running
`npm start`

Now the local server should have started.
Now you should have access to local server at: `http://localhost:8080/`
Navigate your browser to: `http://localhost:8080/app` to preview your project.

It will watch for all the changes in `src/less` directory - however it won't auto-reload your browser.


## Tips

* Try to have a least one commit per task so that we can see the work progress
* Use descriptive commit comments
* It's up to you whether you want to push regularly or once you are finished with all of your commits
* Use Less preprocessor to style it. `main.less` - file is already included in `src/less/` directory
* When working with Less please demonstrate you understand how to use it the most modular and effective way
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
Once you've completed the above, please email `stephanie.wilson@envoydigital.com` so that we know your work is ready to be reviewed.
