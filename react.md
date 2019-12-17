# ASSESSMENT 4: REACT ASSESSMENT
## Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own, there is always something more to learn.  

1. Correctable True/False: Mark the following TRUE or FALSE. If FALSE, correct the statement to be TRUE.

- React is a modern, efficient answer to complex UI applications (true)
- React will only render on the server using Node.js (false. Yarn is used.)
- React is a full stack framework for modern web applications (false. React doesn't work in the backend.)
- React is a flexible library that plays the role of V in an MVC framework (true)
- You should always update a component's state directly using this.state (false. Use setState instead.)
- React is made up of encapsulated components that manage their own state (true)
- React components render HTML (false. It renders with JSX.)


2. What are "smart" and "dumb" components? Explain the difference and also add why we bother to make the distinction between them.

  Your answer: Dumb components are only used once while smart components make the app work and manage the state.

  Researched answer:
.Dumb components are also called ‘presentational’ components because their only responsibility is to present something to the DOM. Once that is done, the component is done with it.
.Smart components (or container components) on the other hand have a different responsibility. Because they have the burden of being smart, they are the ones that keep track of state and care about how the app works.



3. When we use "yarn add ..." in the terminal - what is yarn doing? And what file will always be automatically updated after we add a package with yarn?

  Your answer  Yarn add installs dependencies. The package.js file is automatically updated

  Researched answer:n general, a package is simply a folder with code and a package.json file that describes the contents. When you want to use another package, you first need to add it to your dependencies. This means running yarn add [package-name] to install it into your project.This will also update your package.json and your yarn.lock so that other developers working on the project will get the same dependencies as you when they run yarn or yarn install.



4. What is the difference between component state and props? Your answer should include a short explanation of both.

  Your answer: props is only passed to a component while state is managed within the component.

  Researched answer:
  props (short for properties) are a Component's configuration, its options if you may. They are received from above and immutable as far as the Component receiving them is concerned. A Component cannot change its props, but it is responsible for putting together the props of its child Components.

  The state starts with a default value when a Component mounts and then suffers from mutations in time (mostly generated from user events). It's a serializable* representation of one point in time—a snapshot. A Component manages its own state internally, but—besides setting an initial state—has no business fiddling with the state of its children. You could say the state is private



5. How would you explain state to a friend who doesn't know code?

  Your answer: state determines how a components renders or behaves.
