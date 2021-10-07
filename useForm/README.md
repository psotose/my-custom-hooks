# useForm

Example:
```
  const initialForm = {
    name: 'Alguien',
    age: 15,
    email: 'alguien@gmail.com'
  }

  const [ formValues, handleInputChange, reset ] = useForm( initialForm );
```