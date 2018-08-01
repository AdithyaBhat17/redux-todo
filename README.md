## Redux-TODO Application
This is a TODO App built with redux without any GUI

## How to run ?

copy+paste the contents of `index.js` into your browser's console(make sure you're using a browser that supports ES6)

#### Add task

```
    store.dispatch({
        type:'ADD_TODO',
        todo:{
            id:0,
            name:'Learn Redux',
            complete:false
        }
    })
```

#### Remove task
```
    store.dispatch({
        type: 'REMOVE_TODO',
        id: 1
    })
```

#### Mark a task as COMPLETE
```
    store.dispatch({
        type: 'TOGGLE_TODO',
        id: 0
    })
```

#### Add a long-term GOAL
```
    store.dispatch({
        type: 'ADD_GOAL',
        goal: {
        id: 1,
        name: 'Lose 20 pounds'
        }
    })
```

#### Remove a long-term GOAL
```
    store.dispatch({
        type: 'REMOVE_GOAL',
        id: 0
    })
```
