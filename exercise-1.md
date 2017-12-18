### Resource:

For this exercise, you will be using the [GA SUPER-CRUD API](https://den-super-crud.herokuapp.com/), a publicly accessible web API.  To get started, check out [the documentation](https://github.com/den-materials/super-crud-api). Read it thoroughly, and please DO NOT reset the Seed Data (the very bottom option).

### Small exercise: 
Construct URL queries to answer the following questions:

- How many books are stored in the super-crud?
<!-- https://super-crud.herokuapp.com/books -->
- What's the enpoint (URL) of ONLY To Kill A Mocking Bird?
<!-- https://super-crud.herokuapp.com/books/594e48804cccd700112f1b10 -->
- What's Metapod's Pokedex number?
<!-- https://super-crud.herokuapp.com/pokemon/5964278e09c58b0011397f97 -->
- What does Vulpix evolve from?
<!-- https://super-crud.herokuapp.com/pokemon/5964278e09c58b0011397faf -->
- What is the plural form of 'Pokemon'?
<!-- It says in the documentation -->
- What properties are available for wines?
<!-- https://super-crud.herokuapp.com/wines -->
- How much does a bottle of Domaine du Bouscat cost?
<!-- https://super-crud.herokuapp.com/wines/594e48864cccd700112f1b14 -->

### Pair Activity:

Now turn to the person next to you.  Check your answers to the above exercises, and clear up any questions either of you have about these requests.

#### Post and Delete:

With the same partner, discuss how you would create a new object in Pokemons, Wines, or Books.

- `POST` this new object to the list, and verify it is there by getting the list again.
- `DELETE` your new object and verify it is gone.  **DO NOT DELETE OTHER PEOPLE'S OBJECTS**, that's just mean.

If you and your partner are not sure how to make the `POST` and `DELETE` requests, check [the documentation](https://github.com/SF-WDI-LABS/super-crud-api).
