console.log("Js Loaded!");

let element = document.querySelector("#numberInput");

element.addEventListener("input",function(){
    if(element.value<=-10 || element.value>=10)
    {
        alert("The number should be between -10 and 10");
    }
});

const fruit = {
    Name: "Apple",
    Color: "Red",
    Taste: "Sweet"
};

let element1 = document.querySelector("#fruitName");
element1.innerHTML = `Name: ${fruit.Name}`;
console.log(element1.innerHTML);

let element2 = document.querySelector("#fruitColor");
element2.innerHTML = `Color: ${fruit.Color}`;
console.log(element2.innerHTML);

let element3 = document.querySelector("#fruitTaste");
element3.innerHTML = `Taste: ${fruit.Taste}`;
console.log(element3.innerHTML);
