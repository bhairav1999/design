Good morning, sir. First of all, thank you for giving me this opportunity to introduce myself. My name is Bhairavnath Karande,
 and I am from Pune.
  I have completed my graduation in Electronics and Telecommunication Engineering from Pune University. 
  I have 3 years of experience as a Frontend Developer and am currently working at Crescendo Worldwide as a React.js Developer.

I have hands-on experience with HTML, CSS, Bootstrap, JavaScript, React.js, and Redux. 
Regarding my projects, I have worked on many projects using React.js,
 and I am currently working World Beyond Metaverse project. 
 In this project, I have implemented functional components and hooks for state management, 
 used React Router for seamless navigation between pages, 
 and integrated user authentication for secure access. 
 Additionally, I have efficiently managed state and utilized APIs to dynamically fetch and display data, 
 enhancing the user experience.
 I enjoy front-end development and always work to improve my skills.
  I believe my experience and dedication would be valuable to your team.
   Thank you.

Scope: var is function-scoped, while let and const are block-scoped.
Hoisting: All three are hoisted, but let and const are not initialized 
Reassignment: var and let can be reassigned. const cannot be reassigned 
Redeclaration: var allows redeclaration within the same scope, whereas let and const do not allows redeclaration.

find second largest number

const secondLargest = (arr) => {
    if (arr.length < 2) {
        throw new Error("Array must contain at least two elements");
    }

    let largest = arr[0];
    let secondLargest = -Infinity;

    for (let i = 1; i < arr.length; i++) {
        if (arr[i] > largest) {
            secondLargest = largest;
            largest = arr[i];
        } else if (arr[i] > secondLargest && arr[i] !== largest) {
            secondLargest = arr[i];
        }
    }
    return secondLargest;
}
console.log(secondLargest([1, 5, 8, 9, 2, 6])); // Output: 8

