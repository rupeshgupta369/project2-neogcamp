const chalk = require("chalk")
var readlineSync = require("readline-sync")
var score = 0;

console.log("=================================")
console.log(chalk.bold.white("          Dragonballz & Marvel Cinematic Universe"))
console.log("=================================")

var userName = readlineSync.question("Enter Your Name: ");
console.log("Welcome", userName.toUpperCase());
console.log("----------------------------"); 
console.log(chalk.bold.magenta("QUIZ Rules & Instructions:"));
console.log(chalk.bold.magenta("1) There will be Quiz on two topics i.e.\n 1] Dragonballz \n 2] MCU"));
console.log(chalk.bold.magenta("2) Each question will give you 1 point if you answer correctly and -1 for wrong answer."));
console.log(chalk.bold.magenta("3) First part is about Dragonballz and second part is about Marvel Cinematic Universe."));
console.log(chalk.bold.magenta("4) Both part will have 5 questions with 3 options."));

console.log("\n");




function quiz(question, answer){
  var userAnswer = readlineSync.question(question);
  if (userAnswer === answer){
console.log(chalk.bold.whiteBright("You are RIGHT!!!"))
score++;
    console.log(chalk.bold.whiteBright("Score is:", score))
  }else{
console.log(chalk.bold.whiteBright("You are WRONG!!!"))
score--;
    console.log(chalk.bold.whiteBright("Score is:", score))
  }
console.log("----------------------------"); 

}

console.log(chalk.bgBlue("Part 1"))

console.log(chalk.bold.redBright("              DragonBallz Quiz     "))


var dbz = [
  {Question:"1] During the Saiyan Saga, how does Goku reach King Kai's planet?\na) By making a wish with the Dragon Balls \nb) By teleporting there instantly \nc) By travelling along Snake Way \nd)Via High spedd vehicle\n",
  Answer:"c",},

  {Question:"2] What item is used to restore a wounded Z fighter to full health?\na) Z Sword \nb) Saiyan hair \nc) Capsule Corp medicine \nd)Senzu bean\n",
  Answer:"d",},

  {Question:"3] Who does Captain Ginyu serve?\na) Cell \nb) Freiza \nc) Lord Slug \nd)Turles\n",
  Answer:"b",},

  {Question:"4] What are the names of King Kai's little buddies?\na) Bubbles and Gregory \nb) Bobo and John \nc) Bernie and Jim \nd)Bonobo and Garrett\n,",
  Answer:"a",},

  {Question:"5] What planet does Vegeta come from??\na) Planet Z103 \nb) Planet Freiza \nc) Planet Vegeta \nd) Planet of the Kais\n",
  Answer:"c",},
 ]
 for (var i = 0; i < dbz.length; i++){
   var currentQuestion1 = dbz[i]
   quiz(currentQuestion1.Question, currentQuestion1.Answer)
 }

 /*************************************************/

/*Part 2 MCU */
console.log(chalk.bgBlue("Part 2"))
 console.log(chalk.bold.redBright("              Marvel Cinematic Universe     "));

 var mcu = [
   {Question:"1] What legislation required The Avengers to be governed by law?\na) Berlin Accords \nb) Dublin Accords \nc) Sokovia Accords \nd) Slovakia Accords",
  Answer:"c",},

  {Question:"2] What is the Iron-Man suit actually made up of??\na) Prometheum \nb) A Gold-Titanium alloy \nc) A Vibranium-Adamantium alloy \nd)Uru\n",
  Answer:"b",},

  {Question:"3] What is the name of unit Captain America fights in during World War II?\na) The Howling Commandos \nb) Brooklyn Marauders \nc) Harlem Hellfighters \nd)New York Rifles\n",
  Answer:"a",},

  {Question:"4] Who is Morgan Stark named after?\na) Tony Stark's Godfather \nb) Pepper Potts' Eccentric Uncle \nc) The Walking Dead character Tony Stark liked \nd)Morgan Freeman\n,",
  Answer:"b",},

  {Question:"5] What was the name of the Flerken that took Nick Fury's eye?\na) Goose \nb) Duck \nc) Maverick \nd) Alpha\n",
  Answer:"a",},
 ]
for (var i = 0; i < mcu.length; i++){
   var currentQuestion1 = mcu[i]
   quiz(currentQuestion1.Question, currentQuestion1.Answer)
 }
 
console.log(chalk.green.bold("           ***Game Over***"))

console.log(chalk.green.bold("           YOUR FINAL SCORE IS:", score))
console.log(chalk.bold.red("      THANK YOU FOR PLAYING THE QUIZ"))
