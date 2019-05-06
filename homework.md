1. Where do we directly access an element from the DOM in our React application?
	On index.js with ReactDOM.render()

2. From looking at the code, what do you think might be the difference between the components in the containers and components directories?

	The component in the containers directory has many components.
	The components in the components directory has no other components.

3. What is the responsibility of the ReleasesBox component
  It's the top of the hierarchy. This file contains the whole of the application.
	This creates the moves the data goes to the other components from here by props.

4. What is the responsibility of the MovieList component?
  Loops though the list of movies from MovieItem returns the list of the movies.

5. What is the responsibility of the MovieItem component?
  It gets props from MoviesList and create the list of movies with the url and name.
