# App OVERVIEW

This app contains two part authentication and product part.Each part are described as follows:

## AUTHENTICATION

1. Signin using `https://dummyjson.com/docs/auth`
2. Store `Token` into our local storage.
3. Login state:

   - Logged in: Token is stored in local storage and not expired ie; https://dummyjson.com/auth/me this Api should return 400 with our token provided in bearer

   - Logged out: Token absense / expired then cart detail should not available

4. While in logged out state addToCart should redirect to login page

## BEERS

1. Default homepage should show list of beers

   - List all beer cards in grid
   - Each card should have cartAction and viewDetail buttons
   - We should be able to get beers/ search beers from its name
   - Sorting/filter of beers should be availbale through available

     - beer_name
     - abv_lt
     - abv_gt

     Note: max abv and min abv should be displayed from existing abv values in beers array

## Cart

1. Each added beers should be available here
2. Beers can be removed from cart as well
