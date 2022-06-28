# UseEffect Challenge



In this challenge we are going to be making a mini movie app. Here are the deliverables for this challenge:

1. Create a Movie Form. The movies should be stored in both the db.json via a post request and state.
2. MovieList should render movie cards based on the data of the db.json and any movies we may add via the form.
3. Have a counter in App.js that keeps track of how many movies we have. Initially set it to the length of the movies in the db.json. However, create a useEffect that anytime the movies state changes, that you add 1 to the to the counter (Don't use the movies length, try experimenting with the dependency array!)
4. Lastly Create another useEffect in the App.js that has no dependency and have it console.log('hi') so you can see what the result is. Run this, look in your console to see what it's doing, then comment it out!
5. :Bonus: Try implementing a feature that makes use of the cleanup function of useEffect! This feature will be entirely up to you!

**Note**: To run the db.json server, run `npm run server`, the json server will start at localhost:3001, while the react server will be localhost:3000.