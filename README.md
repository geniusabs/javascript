# javascript code

function test(name){
  let somename = "welcome to my site " + name
  return test;
}

console.log("Oscar");

 function countVowels(word) {
   // Define a string of vowels
   let vowels = "aeiouAEIOU";
   let count = 0;
 
   // Loop through each character in the word
   for (let i of word) {
       // If the character is in the vowels string, increment the count
       if (vowels.includes(i)) {
           count++;
       }
   } 
   return count;
}

