# SC2006-ThisIsNotFair-Docs

Documentations for SC2006 ThisIsNotFair codebase

This Repo contains the Documentations.

Please click on `global.html` to open the docs on your browser.

### JSDocs - React Cavaet

Note that we coded this in React. So it's functional based instead of class based methodology. To circumvent this we broke down every "class"-method into its own function.

For example

```
class MainClass(SuperClass){
    define constructor(props){
        ...
    }
    define methodA(props){
        ...
    }
}
```

has been broken down into

```

function MainClass(props){...}
function constructor(props){...}
function methodA(props){...}
```

or else JSDocs would not be able to interpret the codebase to create the relevant documentations.
