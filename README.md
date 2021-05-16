# Overview
experiment interaction with our playground!
Here you can make calls with diffrent methods and retrieve data as json

![Screenshot_2021-05-15_15-47-01](https://user-images.githubusercontent.com/51862788/118399934-74a03b00-b657-11eb-92fe-e2e5d1c1aa7b.png)

# How to use

  ## GET request
   - Select `GET` to make a GET request.
   - In the input field, past your token.
   - Select an endpoint `pages` for example.
   - Hit Send. you should see a response back with the data.
   
   ### GET with params
   - you can specify a parameters to get a custom data from the `endpoint` (optional).
   - you can enter more that a paramter by clicking `+` button (optional).
   - example:
     - Select `query parameters` option.
     - Enter a `key`/`value` pair. for example (`q`/`faq`).
     - Hit send. you should see a response with data that contines the world `faq`.  
  
  ## POST request
   - Select `POST` option to make a POST request
   - In the input field, past your token.
   - Select an endpoint `pages` for example.
   - Select `Form data` option.
   - Enter a `key`/`value` pair. for example (`name`/`awesomeName`; `slug`/ `awesomeSlug`)
   - Hit send. you should see a response with your posted data.

  ## DELETE request
   - Select `DELETE` option to make a DELETE request
   - In the input field, past your token.
   - Select an endpoint `pages` for example.
   - Select `Form data` option.
   - Now `key`/`value` pair should be something like `id`/`534jk5j35lkj3;5;l3k5;l3kl;5k345jkht809`
   - Hit send. you should see a success response.

    
