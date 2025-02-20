# ASP.net-api-tut
Following the tutorial from microsoft
https://learn.microsoft.com/en-us/training/modules/build-web-api-aspnet-core/8-exercise-implement-crud

# What I learned
### Controller Class:
This is where the API endpoints are handled. They inherit from the ControllerBase class and you use Attriubtes to define certain behaviors for the API. For instance using [Route("[controller]")] pattern replaces [controller] with the class name (minus "Controller"). If the class name is PizzaController then the endpint would be /pizza. Each method that handles the endpoints uses an attribute like [HttpPost] to describe which method it handles. These methods use the servies to sperate the controllers from the buiness logic.

### Service Class:
This where the data is passed to when the controllers receive the data. Here the business logic happens to make it easier for testing and resuability.

### Models:
These are the templates/structures of the data that is being used. In this example the model is called pizza and all the properties are defined to store information about a pizza.

# What I am still confused about
### IEnumerable, IActionResult, Aactionresult:
All three of these were used when creating the return type for the function in the controllers to handle one the API endpoint methods. I have looked up when they mean and I know IEnumerble is for a list but I am unsure why each one was used in their specific instances.

# How I am feeeling?
At first it was overwhelming but I looked into everthing that I did not understand. I am unsure of the some the vocabulary that I used above, but I think I got my points across. I am excited to learn more so I can have a better understanding and the ability to create a more complex API without a tutorial. I have made a CRUD API in Node.js and Go before so I was familiar to how everything is supposed to work, which definitly help my confidence.

