# Welcome to: Áccent
A web application, inspired by pinterest, designed to give users the ability browse through the categories of fashion, food and interior decor. Users will be able to add their own pins and favorite the pins they like. 

[See the layout!](http://accent.surge.sh/)
![](https://scontent.ftpa1-2.fna.fbcdn.net/v/t1.0-9/152384700_1802005103302772_7230147619599388606_o.jpg?_nc_cat=111&ccb=3&_nc_sid=730e14&_nc_ohc=tGqG_sLx51oAX-i95o9&_nc_ht=scontent.ftpa1-2.fna&oh=1722f3c381b968a35013ffb293d012fb&oe=6056BC05)
![](https://scontent.ftpa1-1.fna.fbcdn.net/v/t1.0-9/151206218_1802005026636113_3315755095960402365_o.jpg?_nc_cat=108&ccb=3&_nc_sid=730e14&_nc_ohc=PLLApczl5XEAX9IwUz4&_nc_ht=scontent.ftpa1-1.fna&oh=c0d057b9dfc5bc31f49ff49b839b4e7f&oe=60544B89)

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

