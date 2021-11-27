# useForm Hook

Ejemplo:

```js
const initialForm = {
  name: "",
  email: "",
}

const [values, handleInputChange, reset] = useForm(initialForm)
```