# README notes

```
npx create-react-app react-redux
```

```
cd react-redux
npm i redux --save-dev
mkdir -p src/js/store
npm i react-redux --save-dev
```

##Redux principles
2 - the only way to change the state is by sending a signal to the store (an action) - ie dispatching an action = sending a signal to the store
3 - the state is immutable and cannot change in place.

best practices:
- wrap every action within a function and takes name of action creator
- use concat, slice, spread operator for arrays
- use Object.assign or object spread of objects

key methods in Redux:
- getState - reading the current state of the application
- dispatch - for dispatching an action
- subscribe - for listening to state changes