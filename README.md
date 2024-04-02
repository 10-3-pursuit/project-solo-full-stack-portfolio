# Full-stack Portfolio Project

<img src="./assets/idea.png" width="400" height="400">

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

#### Additional Requirements

1. Both the frontend and backend should be successfully deployed to the web.
1. Your frontend repository should have a `readme.md` file with setup instructions for your application. Your readme should also include links to your backend GitHub repository, both of your deployed URLs.
1. Your project should have a coherent theme and narrative.

#### Backend feature requirements

To complete the backend application, you will need to build a RESTful server that performs CRUD actions on a single resource.

1. Your server should incorporate at least one table that includes:
   - A primary key.
   - At least 7 total fields.
   - At least 4 different data types are used among those fields.
1. Your table should have at least two constraints, which can include (e.g.):
   - `DEFAULT`
   - `NOT NULL`
   - `CHECK`
1. A route exists to:
   1. create a new resource
   1. read all resources
   1. read a single resource
   1. update a single resource
   1. delete a single resource
1. An appropriate "Not Found" response is given when a route is requested that does not match the created routes.

#### Frontend feature requirements

To complete the frontend, you will need to build a React application that allows for CRUD operations to be performed on a single resource. You will also need to display the data _thoughtfully_ and _clearly_.

1. Use of React Router 6.2.1 is required
1. All views should include the same navigation bar, which displays the name of the application and a button to create a new resource.
1. You should have an Index view that presents all of the resources in your database table.
1. After clicking on a single resource, the app should navigate to a Show view which includes more detailed information about the specific resource.
1. When the new resource button in the navigation bar is clicked, the app should navigate to a view that includes a form.
1. Inputs should include labels with coinciding values for `htmlFor` and `id` and the type attribute should represent the data type of the input. e.g. number
1. When a new resource form is submitted, the resource should be created in the database and the user should be brought to the Show view for that resource.
1. On the resource's Show view, there should be a button to edit the current resource. When clicked, the user is brought to a form view that includes the current data to be edited.
1. When an edited resource form is submitted, the resource should be updated in the database and the app should navigate to the resource's Show view.
1. On the resource's Show view, there should be a button to delete the current resource. When clicked, a message is displayed that asks the user if they are sure they want to delete the resource. If the user confirms, the resource is deleted and the user is brought to the Index view.

#### Differentiation goals

This portion of the project measures your ability to go above and beyond and differentiate yourself from other programmers. To score points, you should incorporate two features, technologies, or skills not explicitly required by these instructions. It is suggested you try a different goal than one you have already incorporated in previous applications.

_Make sure to include a description of any differentiating features you implemented inside your readme.md._ You may choose from the list below or come up with features or tasks that are more relevant to your specific implementation of the project.

**Ideas:**

- CSS Framework such as Bootstrap or Tailwind
- Favorites Feature
- Filtering and showing results by subject e.g. genres, tags, favorites, items in cart
- Comments on a resource that persist in the JSON server
- Sorting some data
- Searching for data
- Light Mode/Dark Mode
- Error Components
- Designed CSS 404 Page
- Programmatically upload and store images on Cloudinary and in your JSON as a string.
- Integrate an external React package such as [React DnD](https://react-dnd.github.io/react-dnd/about) or [Styled Components](https://styled-components.com/) or some other package. (research carefully)
- Use CSS Animations for your landing page and/or other views.
- Use Chart.js or another package that will enhance the application.
- Optionally, fetch and incorporate third party api data.

## Store App

If you are struggling to find an idea, you are welcome to create an [Online Store App](./README_STORE_APP.md).
