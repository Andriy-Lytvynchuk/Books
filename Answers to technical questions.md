1.	How long did you spend on the coding assignment? 
    - 1 day
     
  a.	What would you add to your solution if you had more time?
      - functionality to sell books.
      
  b.	If you didn't spend much time on the coding test, then use this as an opportunity to explain what you would add.
      - shopping cart, chekout, payment gateway.
      
2.	What was the most useful feature that was added to the latest version of your chosen language? Please include a snippet of code that shows how you've used it.
    - Java Script Promises are useful, in particular when making API calls, like:
    function getData() {
    axios({
        method: 'get',
        url: 'https://official-joke-api.appspot.com/random_joke'
    })
    .then(res => console.log(res))
    .catch(err => console.error(err));
}
    
3.	How would you track down a performance issue in production? Have you ever had to do this?
    - Using React Testing Library. I read documentation about it and ran some examples.

4.	How would you improve the API that you just used?
   - not all the books have cover images, first thing I noticed.
    
5.	Please describe yourself using correctly formatted JSON.
    - {
        "species": "human",
        "isHappy": true,
        "fav_number": 5,
         "address": {
            "street": "1 Street",
            "city": "Los Angeles",
            "state": "CA",
            "postalCode": "12345"
            },
        "hobbies": ["digging the code", "writing Json"]
     }       
            

