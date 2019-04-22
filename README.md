# JavaScript-Race-Day

```markdown

let raceNumber = Math.floor(Math.random() * 1000);
let registeredEarly = true;
let runnerAge = 19;
if (registeredEarly === true) {
  raceNumber += 1000;
}
if (runnerAge >= 18 && registeredEarly === true){
  console.log(`${raceNumber + 1000} will start at 9:30 AM.`);
} else if (runnerAge == 18) {
  console.log (`${raceNumber + 1000} please see registration desk.`);
} else if (runnerAge >= 18 && registeredEarly === false) {
  console.log(`${raceNumber + 1000} will start at 11:00 AM.`);
} else if (runnerAge <= 18) {
  console.log(`${raceNumber + 1000} will start at 12:30 PM.`);
} 

```
