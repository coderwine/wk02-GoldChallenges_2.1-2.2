You will need to **FORK** this repository (repo) to your own account.  After you have forked it to your account, you will then need to **CLONE** that repo to your computer.  By doing this, you will be able to work through the challenges and push your code back to your own repo.  All instructions are within each file.  Below details the instructions for both challenges.

**2.1 Async&Await Challenge**

1. Write a fat arrow async function that does the following:
        - uses await to fetch data from this endpoint - 'https://swapi.dev/api/people/[input number here]'
        - uses await to jsonify the response received from the fetch
        - console.log's the results of the fetch before console.logging a message saying 'this should print last'

**2.2 Rick & Morty API Challenge**

API: 'https://rickandmortyapi.com/api/character'

- Use the provided HTML, CSS, and JS files to fetch images of two separate characters from the Rick and Morty API. You will not need to edit/change anything in the HTML file, everything you need is already there.

    - Your fetch call to the specified endpoint is already defined in the script.js file. Finish coding the necessary promise resolvers for your fetch to access character information from the API.

    - Once you are seeing character information in the console, define a function that will be used to display the data. Your jsonified data from the API will need to be passed to this function.

    Inside the display function you will need to:
    1. Declare two variables used to store the separate character image links from the API.
    2. Grab each image element from the index.html file, and set the src to be the image link you stored in a variable during step 1.

    After you are seeing images of two different characters, use the attached style.css file to style each image with the following properties:
    1. Each image must have a border-radius
    2. Each image must have a border
    3. Each image must be centered