This is the json database required by the HappyGrocery project. The actual implementation was made possible by typicode json-server (https://github.com/typicode/json-server).

While a full REST interface could be used HappyGrocery will resort to the single query:

"https://my-json-server.typicode.com/AlessandroCaste/HappyGroceryShopsDB/stores?=<storeId>"

in order to retrieve the necessary info for a single store.