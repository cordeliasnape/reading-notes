### Why would a developer use local storage for a web application?

A developer might use local storage to store user-inputted data between pages of a document. It can be displayed later if saved onto the local storage.

### What information should not be stored in local storage?

Sensitive information such as passwords and personal information can be accessed by attacks if stored in local storage. Local storage should only contain themes, languages and preferences.

### Local storage can store what type of data? How would you convert it to that type before storing?

Local data stores data in the form of strings. Data can be set and then converted back to its intended data type by ‘parse’ing it.

> `const user = { name: “Cordelia, age: 25 };` > `localStorage.setItem("user", JSON.stringify(user));`
>
> `const storedUser = JSON.parse(localStorage.getItem("user”));`
