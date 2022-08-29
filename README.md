# MyReads Project

This is Randa ahmed's  myreads project this app can me used to search for bokks and select the one you want to read than you can filter the if it's read or currently reading or want to read 

The project hiraricay is:
App.js contains all he api calls and setting the main states for other components.
I devided the project to 4 other component:
1. the book it self  and it's drope down list in book.js
2. the main page the shelfs in it in mainList.js
3. the searchPage containg the search bar and hheandling the user query, in SearchPage.js
4. Each shelf of books in shelfOfBook.js

Method:
- [`getAll`](#getall)
- [`update`](#update)
- [`search`](#search)


The backend API uses a fixed set of cached search results and is limited to a particular set of search terms, which can be found in [SEARCH_TERMS.md](SEARCH_TERMS.md). That list of terms are the _only_ terms that will work with the backend, so don't be surprised if your searches for Basket Weaving or Bubble Wrap don't come back with any results.



Resources:
https://www.freecodecamp.org/news/how-to-use-props-in-react/
https://www.freecodecamp.org/news/javascript-map-reduce-and-filter-explained-with-examples/
https://reactjs.org/docs/hooks-effect.html
https://www.freecodecamp.org/news/build-a-search-filter-using-react-and-react-hooks/
https://javascript.plainenglish.io/how-to-implement-a-search-bar-in-react-js-8cf8f5513b8e