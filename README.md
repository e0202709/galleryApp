# GalleryApp

GalleryApp is a simple react app that is built to allow users to search for images online.

It was cloned from https://github.com/renatognunes/react-gallery-app, and improvements have been made to the app, such as:

- Added sorting function that allows users to sort based on ascending, descending or default.
- Rewrote components from class to functional
- Made improvements on the code
- Added unit tests using react testing library

Please view the app from here: [App][app].

[app]: https://e0202709.github.io/galleryApp/

**CI/CD pipeline is built with using github actions and hosted via github pages** 


# Landing Page
![Landing Page](/public/galleryApp.png?raw=true "Landing Page")


# Ascending Sort

![Ascending Sort Page](/public/ascendingSort.png?raw=true "Ascending Sort Page")


# Descending Sort

![Descending Sort Page](/public/descendingSort.png?raw=true "Descending Sort Page")


# Example of Search

![Search Page](/public/search.png?raw=true "Search Page")



# Set up

run locally in your machine by entering these commands 
``` 
npm install
npm run dev
```

to check for linting issues, run this command 
``` 
npm run lint
```

to automatically format code using prettier, run this command
``` 
npm run format
```

to run all unit tests
``` 
npm run test
```

to run all unit tests with coverage
``` 
npm run test:coverage
```


# Unit tests 
1. Initial page renders correctly with no sorting
2. Without searching, click on 'descending' button
3. Click on 'ascending' sort, and search for a new query, it should display results with no sorting
4. Test on page not found
5. Sorting works as expected


# Improvements to react code/good coding practices
1. UseRef instead of useState in the form, doesn’t cause the component to re-render when updated
2. UseMemo to memoise functions
3. Used functional component instead of class component
4. Added prettier formating and eslint
5. Added unit tests
