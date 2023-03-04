
# Mykhailo Artemenko

<img src="./photo.jpg" width="200" alt="My photo">

## Trainee Front-end engineer

### Contact information:
*  **Phone:** +38 (099) 195-81-31;
*  **E-mail:** artemenko.mik@gmail.com;
*  **Telegram:** [@domino_sl](https://t.me/domino_sl);
*  **LinkedIn:** [Mykhailo Artemenko](www.linkedin.com/in/mykhailo-artemenko);

### About:
  I am your typical guy who wants to enter the world of informational technologies, having almost nothing in common with it. I won't say that I have made a wrong turn with my current profession, it's just that I find myself lacking problem-solving delight.
git push origin
### Education:
  * National Aviation University;
    * Maintenance and repair of aircraft and aircraft engines;
  * SoftServe:
    * HTML/ CSS/ Javascript basics;
  * Mate academy:
    * Front-end engineer bootcamp;

### Skills:
* a little bit of html;
* a pinch of css;
* and a fraction of javascript;

### Code examples:
#### [Directions Reduction task from codewars](https://www.codewars.com/kata/596f610441372ee0de00006e)
````
function dirReduc(arr){
  const directions = {
    "NORTH": "SOUTH",
    "SOUTH": "NORTH", 
    "EAST": "WEST",
    "WEST": "EAST",
  }
  const result = [];

  for (const dir of arr) {
    if (result[result.length - 1] === directions[dir]) {
      result.pop(); 
    } else {
      result.push(dir);
    }
  }

  return result
}
````