# [Help Queue](https://github.com/jiwon-seattle/Help-queue-React.git)

#### React Fundamentals exercise at [Epicodus](https://www.epicodus.com/), 04.20.2020

#### By **Jiwon Han**

## Description

**Using the Sieve of Eratosthenes and recursion, given a number, write a method that returns all of the prime numbers less than that number.**

As our diagram demonstrates, our application will start with the following functional components:

Header: Our header will remain the same regardless of whether the user is looking at all tickets, a specific ticket, or the form for creating a new ticket.
This will be a very small component, which is exactly what we want. Remember, our goal is to compose our application of many smaller components as opposed to fewer larger and cumbersome components.

Ticket List: This component will loop through all of our individual tickets, displaying them on the page. We will cover looping in JSX soon.

Ticket: We will also have a component for an individual ticket. Each ticket will have different properties passed into it (such as name, issue and station). As shown in the diagram above, the Ticket component will be nested inside TicketList, which means it will be the TicketList component's child.

Add Ticket: This will have a button for adding a ticket.

## Fundamentals

1. Building a Static Site
App.js is the parent component for all other components in our application. For that reason, as we add each component to our application, we will also need to add it either to App.js or to its parent component.

2. Props

Passed props down to a child component using JSX tags and updated the TicketList.js component so it can pass props to its child Ticket.js component

Props are read-only which means their values are not changeable.

Declared import PropTypes from "prop-types" and each component's proptypes.

Looped a Ticket component using map() function in TicketList.js.
## Screenshots

<image src="src/react.jpg" width="750px" />

## Setup/Installation Requirements

- Clone this [repository](https://github.com/jiwon-seattle/Help-queue-React.git) 
- run $npm install and #npm start

## Known Bugs

No known bugs at this time.

## Support and contact details

Email jiwon1.han@gmail.com with any questions, feedbacks, or concerns.

## Technologies Used

- Webpack
- Node.js

### License

This console application is licensed under the MIT license.

Copyright (c) 2020 **Jiwon Han**
