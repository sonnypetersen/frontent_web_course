# frontent_web_course
notes regarding JS

For Of Loof
Spread operartor, loop i et array
destructuring objects / arrays

arrow function
special case with only 1 input parameter
const dinnerMenu = food => `I will eat ${food}`
const dinnerMenu = (food,drink) => `I will eat ${food} and drink ${drink}`
example of default parameter
const dinnerMenu = (food = 'Burger') => `I will eat ${food}`

Arrays
search function 
const arr = [10, 20, 30]
if (arr.includes[10]) will return true


// Promises

const buyFlightTicket = () => {
    return new Promise( (resolve, reject) => {
        setTimeout( () => {
            const error = true;
            
            if( error ) {
                reject("Sorry your payment was not successful")
            } else {
                resolve("Thank you, your payment was successful");
            }
        }, 3000)
    })
}

buyFlightTicket()
.then( (success) => console.log(success))
.catch( (error) => console.log(error) );

Fetch
 * RESTFul API - https://jsonplaceholder.typicode.com/
 * Docs - https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch
