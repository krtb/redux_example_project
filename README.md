# AN EXPLANATION OF REDUX

## What Redux Does
> 1. Provides `connect` function, that generates `container components`
> 2. Allows for a `provider component` that exposes a `context` for the child component to access the `redux store`

### Using only two mapping functions
1. `mapStateToProps`
2. `mapDispatchToProps`

### What is a `connect function`?
> * is a `Higher Order Function`
> * returns a `Higher Order Component`
> * when the `Higher Order Component` is returned, it returns a `Container Component`