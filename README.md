
# _Product_Review_

#### _Project for Week 11 at the coding school, Epicodus, written on August 9, 2019._

#### By _**Tae Lee**_

## Description

_You've in the running for a freelance development job as the developer for Mario's Speciality Food Products (or another fictional company of your choosing). First, Mario wants to make sure you're the right person for the job. He's asked you for an MVP and wants it by 5:00 tonight. The stakes are higher than usual, since Mario's old site had thousands of unique visitors each day. If you can get the job, this is a great way to increase your profile as a developer. In particular, Mario is concerned about the information in his database being correct; your goal for today is to have the most comprehensive validations and callbacks to ensure information is properly saved and formatted in the database.

Database
The site should have functionality to review products so your database should include a one-to-many relationship between Products and Reviews. All products must have a name, cost and country_of_origin. All reviews should have an author, content_body and rating. (A rating can be a number between 1 and 5.) You can include other fields of your choosing as well._

## Setup/Installation Requirements

* _Clone this repository_
* _Open terminal and type 'git clone [git link]'_
* _Navigate to project directory using cd in terminal_
* _Open project in text editor (atom .)_
* _Type 'bundle install' in terminal to load Gems (if you have capybara version incompatible issue with current version of ruby, try "/Users/[User Name]/.rubies/ruby-2.6.3/bin/bundle install" instead of "bundle install"_
* _To run tests, type 'rspec' in terminal_
* _postgres DB installation with sql script in project (if your Postgres DB is not starting at login, please execute "pg_ctl -D /usr/local/var/postgres -l /usr/local/var/postgres/server.log start" on terminal._

## Specs
| Behavior                                       | Input                                 | Output                 |
| ---------------------------------------------- |:-------------------------------------:| ----------------------:|
| DB schema design for one-to-many relationship  | create products table                 |                        |
| make CURD logic for application                | create model for product              |                        |
| DB schema design for one-to-many relationship  | create reviews table                  |                        |
| DB schema design for one-to-many relationship  | set up foreign_key with dependent     |                        |
| Testing with Rspec and Shoulda Matchers        | rspec                                 | 2 examples, 0 failures |
| Routing with Rails (Nested Routing with Rails) |                                       |                        |
| creating Rails Controllers                     |                                       |                        |
| creating Views with link_to method             |                                       |                        |
## Known Bugs

_No known bugs_

## Support and contact details

_Please contact us if you have any issues at: taebumlee@gmail.com_

## Technologies Used

* Ruby 2.6.3
* RubyGems
* Atom
* GitHub
* Postgres DB 11.4

### License
_This software is licensed under MIT license._

Copyright (c) 2019 **_Tae Lee**
