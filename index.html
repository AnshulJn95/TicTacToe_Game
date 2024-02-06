let userScore = 0;
let compScore = 0;

const choices = document.querySelectorAll(".choice");
const msg = document.querySelector("#msg");
const userScorePara = document.querySelector("#user-score");
const compScorePara = document.querySelector("#comp-score");

const genCompChoice = ()=>{
    const options = ["rock","paper","scissors"]
    //rock , paper ,scissors
    const randIdx = Math.floor(Math.random()*3)  // range 0-2 
    return options[randIdx]
};

const drawGame = () =>{
    console.log("game as draw.")
    msg.innerText ="It was a Draw . Play again";
    msg.style.backgroundColor = "blue";
};

const showWinner = (userWin,choiceId,compChoice) =>{
    if(userWin){
        userScore++;
        userScorePara.innerText = userScore;
        console.log("you win");
        msg.innerText = `You win! Your ${choiceId} beats ${compChoice}`;
        msg.style.backgroundColor = "green";
    }else{
        compScore++;
        compScorePara.innerText = compScore;
        console.log("you lose");
        msg.innerText = `You lose! ${compChoice} beats your ${choiceId}`;
        msg.style.backgroundColor = "red";
    }
}
const playgame = (choiceId)=>{
    console.log("user choice = ",choiceId);
    //Generate Computer Choice
    const compChoice = genCompChoice();
    console.log("comp choice ",compChoice);

    if(choiceId=== compChoice){
        // Draw
        drawGame();
         }
         else{
            let userWin = true;
            if(choiceId==="rock"){
            // scissors, paper
            userWin=compChoice==="paper"? false :true;          
          }
          else if(choiceId==="paper"){
            // rock ,scissors
            userWin = compChoice==="scissors"?false:true;
          }
          else if(choiceId="scissors"){
          // rock,paper
          userWin = compChoice==="rock"?false :true;
        }
   showWinner(userWin, choiceId,compChoice) ;
         }

};
 

choices.forEach((choice)=>{
    choice.addEventListener("click",()=>{
    const choiceId = choice.getAttribute("id");
     // console.log("choice was clicked",choiceId)   
     playgame(choiceId);
    });
});  
