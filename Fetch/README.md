# useFetch
Hook para realizar una peticion get usando fetch

### Ejemplo de uso:
```
const { loading, data } = useFetch(url);

const { value1, value2 } = !!data && data[0];
```

### En el template:
```
{ loading ?
     (
         <p>Loading...</p>
     ) : (
         <p>{ value1 }</p>
         <p>{ value2 }</p>
     )
 }
```
