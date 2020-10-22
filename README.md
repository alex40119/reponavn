# reponavn
Hello from me
does this work?

class Person {
  constructor(inName, inAge, inHeight) {
    this.name = inName;
    this.age = inAge;
    this.height = inHeight;
    Person.people.push(this);
  }

static list() {
  for (let i= 0; i < Person.people.length; i++)
   Person.people[i].print();
}

print ()
console.log("Name: " + this.name + "Age: " + this.age + "Height: " + this.height);

let somePerson = new Person ("Alex","17", "175");
console.log(somePerson.name, somePerson);

  new Person  ("Alex", 17, 175);
  new Person  ("Karen", 69, 169);
]
console.log(people[0]);
