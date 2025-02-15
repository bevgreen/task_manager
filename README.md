1. Define CRUD.
- Create, Read, Update, and Delete tasks
2. Define MVC.
- Model, View, Controller. A model is the internal representation of info, a view is the interface that presents info to the user, the controller is the software that links the model and the view. 
3. What two files would you need to create/modify for a Rails application to respond to a GET request to /api/v1/tasks, assuming you have a Task model.
- The config/routes.rb needs to be updated first to handle the GET request. Then the controller needs to be added or updated to perform the controller action.
4. What are params? Where do they come from?
- Params are an object that holds dynamic values that are taken from the URL. The route is set up to expect a parameter called :id. This allows us to manipulate and access specific pieces of data in the controller. 
5. What is the purpose of a serializer?
- A serializer reformats tasks in the JSON response. With a serializer, devs can chooose which fields are sent to the front end and how they are formatted. # task_manager
