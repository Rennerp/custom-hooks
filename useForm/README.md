# useForm

Example:
```
const initialForm = {
  name: '',
  age: 0,
  email: ''
}

const [values, handleInputChange, reset] = useForm( initialForm )
```

Receives and initial state
```
const initialForm = {
  name: '',
  age: 0,
  email: ''
}
```

Returns the value if it changed
```
  values
```

Returns a function for handling input field changes

```
handleInputChange

<input onChange = { handleInputChange }>
```

Returns a function to reset the input field to its initial state

```
reset
```