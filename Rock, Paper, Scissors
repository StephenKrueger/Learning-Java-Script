//Random Computer Choice
function GetChoice(choices) { 
  var randomIndex = Math.floor(Math.random() * choices.length);
  return choices[randomIndex];
}
// Arayy of choices
const choices = ["rock","paper","scissors"];
var computerchoice= GetChoice(choices);
//Socres
let playerscore = 0;
  let computerscore = 0;
  //Computerchoice
  let computerslection = computerchoice;


function playround (playerslection,computerslection) {
  // win condtions

  console.log("You Chose ",playerslection);
  console.log("The Computer Chose ",computerslection);
  

if (playerslection === "rock" && computerslection === "scissors") {console.log("You Win"); playerscore+=1 }
else if (playerslection ==="paper" && computerslection ==="scissors") {console.log("You Lose"); }
else if (playerslection ==="scissors" && computerslection ==="scissors") {console.log("Its A Tie");}

else if (playerslection ==="scissors" && computerslection ==="paper") {console.log("You Win");playerscore+=1}
else if (playerslection ==="rock" && computerslection ==="paper") {console.log("You Lose"); computerscore+=1}
else if (playerslection ==="paper" && computerslection ==="paper") {console.log("Its A Tie");}

else if (playerslection ==="paper" && computerslection ==="rock") {console.log("You Win");playerscore+=1}
else if (playerslection ==="scissors" && computerslection ==="rock") {console.log("you Lose");computerscore+=1}
else if (playerslection ==="rock" && computerslection ==="rock") {console.log("Its A Tie");}
else {console.log("Invaild Choice");}

}


function PlayGame() {
  //gameloop
  for (let round = 0; round < 5; round++) {
    let playerslection = prompt("Rock, Paper, or Scissors? (Type 'quit' to end)").toLowerCase();
      if (playerslection === "quit") {
          console.log("Thanks for playing");
          return;
      } else {
        const computerslection=GetChoice(choices);
          playround(playerslection, computerslection);

      }
  }
  console.log("Your score is ", playerscore);
  console.log("The computer's score is ", computerscore);
  if (playerscore>computerscore){console.log("You Win");}
  else if (playerscore==computerscore) {console.log("Its a tie");}
  else if(computerscore>playerscore) {console.log("You Lose");}
  
  

}
PlayGame();
