# Object-Enhancement

ES2015- Same Keys and Values

function createInstructor(firstName, lastName){
  return {
    firstName,
    lastName
  }
}


ES2015- Computed Property Names

let favoriteNumber = 42;

const instructor = {
  firstName: "Colt",
  [favoriteNumber]: "That is my favorite!"
}


ES2015- Object Methods

const instructor = {
  firstName: "Colt",
  sayHi(){
    return "Hi!";
  },
  sayBye(){
    return this.firstName + " says bye!";
  }
}


ES2015- Create Animal Function

function createAnimal(species, verb, noise){
  return {
    species,
    [verb](){
      return noise;
    }
  }
}





