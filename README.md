# ES6

## const and let

      let age = 21           // ***can be reassigned*** 
      const name = 'John'    //cannot be reassigned
      
      
## arrow functions

      const array = [1,2,3]

      array.map(num => console.log(num) );
       
## template string

      const greeting = ( name ) => {

         const string = ` Hello, ${name}! .`

         console.log(string)

         }

      greeting('Rihaan')
      
## default parameter
        
        const value = ( a = 2 , b = 3 ) => console.log(a + b) 
        
        value();       // 5 
        value(5,5)     // 10
        
## array destructing

        const array = [ 1 , 2 , 3 ]
        
        const [ first , , third ] = array
        
        console.log(first, third);
        
## object destructing

       const object = { 
                         channelName : " code2night " ,
                         views : 23223 ,
       }
       
       const { channelName , views } = object ;
       
       console.log( channelName , views );
       
## rest operator

     const add = ( ...number) => console.log( number.reduce((a,b) => a+b , 0 ));
     
     add(1,2,3,4,5);
     
## spread operator

     const array = [ 1 , 2 , 3 ]
     
     console.log( ...array)


