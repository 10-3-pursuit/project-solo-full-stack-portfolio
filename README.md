# Full-stack Portfolio Project

This project is designed to challenge all of the skills you've learned so far. By the end of this project, you should have a portfolio-ready project you can share on your resume as well as with potential employers.

### Completion

To complete this project, you will need to build a full-stack application that meets the following feature and technical requirements.

## Getting started

**Do Not** fork this repository.

Please choose one of two options:

1. If you would like to use login and logout authentication functionality, `fork` and `clone` the [jwt-auth-backend](https://github.com/10-3-pursuit/jwt-auth-backend) and [jwt-auth-frontend](https://github.com/10-3-pursuit/jwt-auth-frontend) into a parent folder. These will serve as your repos.

1. If you are not using authentication then `fork` and `clone` the [express-server-starter-db](https://github.com/10-3-pursuit/express-server-starter-db) and the [react-basic-starter](https://github.com/10-3-pursuit/react-basic-starter/tree/main).

1. Choose a differentiating idea for your application.

1. Create User Stories.

1. Create an ERD of your application.

After approval from your instructors, follow the specifications below to create your application.

#### Overall requirements

1. Both the frontend and backend applications should be successfully deployed to the web.
1. Your frontend repository should have a `readme.md` file with setup instructions for your application.
   - Your readme should also include links to your backend GitHub repository, both of your deployed URLs.
1. Your project should have a coherent theme and narrative.

#### Backend feature requirements

To complete the backend application, you will need to build a RESTful server that performs CRUD actions on a single resource.

1. Your server should incorporate at least one table that includes:
   - A primary key.
   - At least 7 total fields.
   - At least 4 different data types are used among those fields.
1. Your table should have at least two constraints, which can include `DEFAULT` values.
1. A route exists to:
   1. create new resources.
   1. read all resources.
   1. read a single resource.
   1. update a single resource.
   1. delete a single resource.
1. An appropriate "Not Found" response is given when a route is requested that does not match the created routes.

#### Frontend feature requirements

To complete the frontend application, you will need to build a React application that allows for CRUD operations to be performed on a single resource. You will also need to display the data thoughtfully and clearly.

1. All pages should include the same navigation bar, which includes the name of the application and a button to create a new resource.
1. You should have an Index page that presents all of the resources in your database table.
1. After clicking on a single resource, you should be brought to a Show page which includes more detailed information about the specific resource.
1. When the button in the navigation bar to create a new resource is clicked, you should be brought to a new page that includes a form to create a new resource.
1. Forms should be properly labeled and the type of inputs should be properly set. For example, an input that requires a number should have type number, not text.
1. When a new resource form is submitted, the resource should be created in the database and the user should be brought to that new resource's Show page.
1. On the resource's Show page, there should be a button to edit the current resource. When clicked, the user is brought to a form page with data already filled in that can be edited.
1. When an edited resource form is submitted, the resource should be edited in the database and the user should be brought to that existing resource's Show page.
1. On the resource's Show page, there should be a button to delete the current show page. When clicked, a message is displayed that asks the user if they are sure they want to delete the resource. If the user confirms, the resource is deleted and the user is brought to the Index page.
1. Using the resource's data, perform a calculation or create a useful feature (e.g., sort, filter, infinite-scroll) that can be performed on the frontend application and displayed to the user that has not been demonstrated in class.
   - For example, if your app has a list of products, load the first 10 and when the user scrolls to the bottom the next ten are loaded. Your sort or filter feature may take more than one argument and/or include being able to sort in ascending or descending order.

### Stretch goals

This section of the project measures your ability to go above and beyond in creating your project. To score points in this section, you should incorporate a feature, technology, or skill you have not tried before and that is not explicitly required by the project instructions.

When you submit your pull request, _make sure to include a description of any stretch goals you implemented._ You may choose from the list below or come up with features or tasks that are more relevant to your specific implementation of the project.

- Display errors to your user when they incorrectly fill out a form attempting to create or update a resource.
- Add a one-to-many table relationship to your database.
- Create middleware as part of your backend application that validates for particular values when a resource is being created or updated.
- Use query parameters to filter your resource by different fields or qualities.
- When viewing all resources, break up your resources visually onto multiple pages.
- Visually allow for interacting with a second resource from the frontend.
- Allow for a list of "favorite" resources that are stored locally through [localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage).
- Make your application responsive to different kinds of devices.

Points will be allocated in this section at the discretion of the instructor.

## Store App

If you are struggling to find an idea, you are welcome to create an [Online Store App](./README_STORE_APP.md).
