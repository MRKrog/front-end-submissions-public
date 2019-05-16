# Palette Picker Submission Form

[Project Spec](http://frontend.turing.io/projects/palette-picker.html)

# Basics

#### Link to the GitHub Repository for the BE
[palette-picker BE](https://github.com/MRKrog/palette-api)

#### Link to the Deployed BE
[heroku BE](https://palette-api.herokuapp.com/)

#### Link to the GitHub Repository for the FE
[palette-picker FE](https://github.com/MRKrog/palette-ui)

#### Link to the Deployed FE
[heroku FE](https://paletteui.herokuapp.com/)

## Completion

#### Were you able to complete the base functionality?

We were able to complete all of the functionality for both the front and backend expectations.

#### Link to an image of your wireframe(s)
[Main Page](https://raw.githubusercontent.com/MRKrog/palette-ui/master/src/images/palette-picker-wireframe.png)
[Modal and Pop ups](https://raw.githubusercontent.com/MRKrog/palette-ui/master/src/images/palette-pick-wireframe.png)

#### Which extensions, if any, did you complete?

- We did not complete any extensions

# Code Quality

#### Link to a specific block of your code on GitHub (from either repository) that you are proud of
[happy code](https://github.com/MRKrog/palette-api/blob/master/app.js)

* Why were you proud of this piece of code?
- Lines 128-143: Delete Project Endpoint. For this endpoint we utilized async await on the backend which provides more readable code with fewer lines. It gave us the ability to easily delete all palettes associated in a project and then the project itself. When we first tried with .then() it was getting really confusing to first check if project has palettes and then delete the palettes followed by the project. We decided to go a different route that was not introduced in class, to challenge ourselves, as well ending up making the rest of the backend endpoints easy to create.

#### Link to a specific block of your code on GitHub that you feel not great about
[sad code](https://github.com/MRKrog/palette-ui/blob/master/src/containers/Modal/Modal.js)

* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
- Lines 32-49: for the handleSendPalette instance method we created for the modal, I wish I could of refactored this more/simpler. I could not figure out a way to send the correct object without recreating it before posted it to the backend. The variable sendPalette is a bit bulky, but was necessary because I could not figure out a way to supply the fetch call a premade variable. As well from lines 54 - 92 I feel like this is a big chunk of jsx that could of been broken down into smaller components. For what we had to do, and was required for saving a palette it took a lot of code to make happen that I would want to have be simpler and broken down for better developer empathy. Overall this component was my biggest challenge and in the future I would go want to create more components and break it down into smaller pieces of jsx.

#### Link to Design Inspiration

[design inspiration](https://coolors.co/app)
- I took the design of having the colors display 100% width/height of the app, from coolors.co. I thought it looked clean and simple as well as the best user experience because when picking color combinations you would want to see them together and how they mesh.
- For the modal, project window and buttons, we came up with the design ourselves. Using Material UI for the functionality of the project window, we wanted to have this app be a complete single page application. We wanted simplicity with minimal focus on anything other than the color combinations.

#### Reflection on New Concepts

* Describe your thoughts on server-side testing
- Easier than frontend testing, which made learning in testing the server side simpler to grasp. I really enjoyed how straight forward it is to test routes and their happy sad paths.
* Describe your thoughts on TravisCI
- When using TravisCI at first I thought it was a bit complicated and over engineered. After finally getting it implemented it all makes a lot more sense. It is super powerful to have a seamless transition when pushing code to Github. It is extremely user friendly to be able to push code to Github which will then go through all your tests, and then push the code live to Heroku.
* Describe your thoughts in creating a single project whose codebase was distributed across multiple repositories
- Working together as team it was extremely useful to have two separate repositories. One of could be working the backend, while the other would be working on the frontend. This allowed for efficient utilization time programming and not worrying about conflicting code. Also when we wanted to switch roles, it was easy to do, when you are working solo in the codebase. Also helps with separation of concerns in regards to developer empathy.

#### Please feel free to ask any other questions or make any other statements below!

Anything else you wanna say!

-----


# Instructor Feedback (Instructor Name)

## Specification Adherence

**x score**:

## User Interface

**x score**:

## Testing

**x score**:

## Workflow

**x score**:

# Outcome: pass/fail
