# Frontend Take-Home Challenge Instructions

## Overview

As a member of the Valstro UI Engineering team, you'll be building a multi-window & multi-process frontend application, which regularly interacts with event-driven APIs.

The purpose of this assessment is to show that you can build an extremely simple reactive application that shares its state across mutliple windows through an event-based architecture using the [Broadcast Channel API](https://developer.mozilla.org/en-US/docs/Web/API/Broadcast_Channel_API) & the [localStorage API](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage).

## Setup

- Clone the repo & cd into it.
- Run `yarn install`
- Followed by `yarn dev` to start the development server

## The Challenege

Build a simple message board in `ReactJS` & `TypeScript`, which allows you to post text-based messages to a list, with the capability to delete individual messages.

## Requirements & rules

- The list must persist when the page is refreshed using [localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)
- The list must update in real-time across multiple windows/tabs using [BroadcastChannel](https://developer.mozilla.org/en-US/docs/Web/API/Broadcast_Channel_API)
- Do not install new NPM packages, you can only work with what's in `package.json` 

## Bonus Points
- Use a reducer ([useReducer](https://reactjs.org/docs/hooks-reference.html#usereducer)) & the [flux pattern](https://www.newline.co/fullstack-react/p/intro-to-flux-and-redux/)
- Use [typesafe](https://github.com/piotrwitek/typesafe-actions) & [flux standard actions](https://github.com/redux-utilities/flux-standard-action)
- Use [react's native hooks](https://reactjs.org/docs/hooks-reference.html) & your own custom hooks
- Implement simple & clean styles using CSS best practices

## Expert Mode
- Highlight in the list which messages are from the sender, and which are from a receiver
- Think about a11y, dark mode & responsive-design
- Use RxJS in some relevant way

## Time

The project should take no longer than 2-4 hours to complete. If you've not had experience with some of the technologies above and you'd like to spend more time, take as long as you need.

## Example

**There's no requirement to copy the example's design/ui. Feel free to use your own flare.**

**YouTube Video**: https://www.youtube.com/watch?v=dcfxyFoRMlU

![Screenshot](https://github.com/valstro/frontend-challenge-solution/blob/main/screenshot.PNG?raw=true)