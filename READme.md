# Welcome to: Áccent
A web application, inspired by pinterest, designed to give users the ability browse through the categories of fashion, food and interior decor. Users will be able to add their own pins and favorite the pins they like. 

- Users will be able to post pins by choosing a category and providing:
  - A link to an image
  - A short description of the item(s)
  - A link to the webpage where the item(s) can be found

## Installation

  - Navigate to https://github.com/ken025/Accent-Frontend.git
  - Provided there, are the folders to the Frontend and Backend which are also linked below 
  - Click the green **Code** button and copy the link by clicking on the **clipboard**
  - Once the repository is cloned: 
    - cd into the backend and run `bundle install` to load the gems and dependencies
    - When loaded, run `rake db:create` to create the database
    - Once that is done, run `rake db:migrate` to have access to the database
    - To have access to user and/or default posts, run `rake db:seed`
    - To access the web application run `rails s` 
  - Once that is done successfully:
    - cd into the backend and enter `open index.html`
  
  - User login info:
    - email: "test@test.com" & password: "test" 
      - (to change this information, alter the seed file located in the db folder)

## Repos

  [Backend](https://github.com/ken025/Accent-Backend.git)

  [Frontend](https://github.com/ken025/Accent-Frontend.git)

## Contributing

Bug reports and pull requests are welcomed.

## License
This code is free to use under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Future Plans for this Project
- Implement incrementing like feature
- Make sign up avaliable with JWT 

