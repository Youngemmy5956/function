# function


This is a data dat i use to set function for each of a user despite being together in one form of data....
  this function dat i created helps u to easily call a task without involving the other users in the data...
  
       function called printEmails which console.log's every email for the users.
printEmails(); 
// larry@foo.com 
// jane@test.com 
// sam@test.com 
// anne@test.com 
// david@test.com

        function called printHobbies which console.log's each hobby for each user.
printHobbies(); 
// "Fishing"
// "Sailing"
// "Hiking"
// "Swimming"
// "Biking"
// "Hiking"
// "Golf"
// "Cooking"
// "Archery"
// "Tennis"
// "Biking"
// "Archery"
// "Volunteering"
// "Biking"
// "Coding"

    function called findHometownByState which returns the first user which has a hometown of the state that is passed in
For Example:
findHometownByState('CA'); 
/*/ 
{ 
     username: "larry", 
     email: "larry@foo.com",
     years_experience: 22.1, 
     favorite_languages: ["Perl", "Scala", "C++"], 
     favorite_editor: "Vim",  
     hobbies: ["Fishing", "Sailing", "Hiking"],
     hometown: {
city: "San Francisco",
state: "CA"
} 
} 
/*/

    function called allLanguages which returns an array of all of the unique values
For Example:
allLanguages();
// ["Perl", "Scala", "C++","Haskell", "PHP","JavaScript","Ruby", "Python", "Go","C#", "F#", "Swift"]

      function called hasFavoriteEditor which returns a boolean if any of the users have the editor passed in
For Example:
hasFavoriteEditor('VS Code'); // true 
hasFavoriteEditor('Eclipse'); // false

     function called findByUsername which takes in a string and returns an object in the users array that has that username
For Example:
findByUsername('david'); 
/*/ 
{ 
     username: "david", 
     email: "david@test.com", 
     years_experience: 12.5, 
     favorite_languages: ["JavaScript", "C#", "Swift"], 
     favorite_editor: "VS Code", 
     hobbies: ["Volunteering", "Biking", "Coding"], 
     hometown: { 
          city: "Los Angeles", 
          state: "CA" 
     } 
} 
/*/
