<img src="https://i.imgur.com/u8uvaan.jpg">

# React Appointment Tracker Lab

## Intro

You will need to create a new React CodeSandbox project named `react-appointments`.

For this lab, you will be creating an appointment management system that will persist your data using localStorage!

### Local Storage

See [localStorage docs](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage) for more info.

You are only able to store strings in localStorage, but through the power of JSON.stringify() & JSON.parse() we are able to effectivetly store array or objects in localStorage as well.

Example:

```js
const people = [{name: "Chris"}, {name: "Jesse"}, {name: "Stephen"}, {name: "Drew"}]

// Adding to localStorage
localStorage.setItem('people', JSON.stringify(people));

// Getting from localStorage
const peopleFromStorage = JSON.parse(localStorage.getItem('people'));
```

## Requirements

  - AAU, when the page first loads, I want to see my list of appointments, or a message saying "You have no appointments yet"
  - AAU, I want to be able to add an appointment to my list
    - Each appointment should have at least three properties - `title`, `date`, and `duration`
  - AAU, I want to be able to refresh the page and still see my list of appointments
    - This is where localStorage comes in handy!
    - You will need to update your array of appointments in localStorage each time a new appointment is added
  - AAU, I want to be able to delete an appointment from my list


## Deliverable

#### This lab is not a deliverable.
