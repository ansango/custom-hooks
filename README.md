# custom-hooks

a custom hooks collection

## useCounter

```javascript
const { counter, increment, decrement, reset } = useCounter(10);
```

useCounter() // recibe un valor por defecto

## useForm

```javascript
const initialForm = {
  name: "",
  age: 0,
  email: "",
};

const [formValues, handleInputChange, reset] = useForm(initialForm);
```

## useFetch

```javascript
    const url = 'endpoint de una api';
    const { data: null, loading: true, error: null } = useFetch(url);

```
