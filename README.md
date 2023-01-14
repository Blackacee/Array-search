# Array-search

let people = [
 { name: "bob" },
 { name: "john" }
];
let bob = people.find(person => person.name === "bob");
// Or, more verbose
let bob = people.find(function(person) {
 return person.name === "bob";
});
In an
