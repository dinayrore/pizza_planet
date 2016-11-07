### Pizza Planet

TODO:
- [ ] Set up basic modeling for Pizza Planet
  - [ ] Customer: name, email, address
  - [ ] Pizza: name, description
  - [ ] Order: customer, pizza, fulfilled boolean
  - [ ] Anything else? What limitations have we put in place for ourselves with this modeling?
- [ ] Set up relationship between models
  - [ ] Order <--> Customer
  - [ ] Customer <--> Pizza
  - [ ] Pizza <--> Order
- [ ] What should people be able to do in our app?
  - [ ] What should a customer be able to do?
  - [ ] What should a Pizza Planet employee be able to do?
- [ ] Add controller actions, routes and views

Assignment:
- [ ] Pizza Planet wants to expand their menu to include appetizers, salads and desserts. Refactor the existing app to make `menu items` instead of just `pizza`. Make sure to update the pizza menu view!
- [ ] Pizza Planet customers are having a hard time reading the menu, since it's all on one page. Help Pizza Planet reduce the clutter! Some ideas you could implement:
  * Sorting by column
  * Display items in groups
  * Add a [simple search](https://github.com/Casecommons/pg_search) to the menu
- [ ] Pizza Planet is having a hard time keeping track of all the orders coming in. Help them reduce the number of items in their order view! Some ideas you could implement:
  * Automatically archive orders that have been fulfilled that are older than a day using ActiveJob.
  * [Paginate](https://github.com/amatsuda/kaminari) orders
- [ ] Pizza Planet is an very poorly designed app right now. Make it look good!
- [ ] Pizza Planet managers are upset since customers and admins have no distinction in their app, and it's creating chaos. Add authentication and authorization.
- [ ] Pizza Planet customers want to be able to save their favorite orders to reorder in the future. Plan and implement a "favorites" model with views and controllers if necessary.
