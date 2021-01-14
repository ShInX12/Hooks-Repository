# useForm
Hook para manejar el estado de un formulario

### Ejemplo de uso:

```
 const initialForm = {
     name: '',
     age: 0,
     email: ''
 };
 
 const [ formValues, handleInputChange, reset ] = useForm( initialForm );
 
 const { age } = formValues;
```

### En el template:
```
<input
    name='age'
    value={ age }
    onChange={ handleInputChange }
    type="text"/>
    
...
    
<button onClick={ reset }> Reset </button>
```
