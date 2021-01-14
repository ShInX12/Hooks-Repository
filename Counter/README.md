# useCounter
Hook para tener un contador en nuestra app

### Ejemplo de uso:
```
const { counter, increment, decrement, reset } = useCounter(initialValue);
```

### En el template:
```
<h1>{ counter }</h1>

<button onClick={ increment }> - 1 </button>
<button onClick={ reset }> Reset </button>
<button onClick={ decrement }> + 1 </button>
```
