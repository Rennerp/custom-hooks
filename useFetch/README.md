# useFetch

Example
```
  const url = 'API-ENDPOINT';
  const { data: null, loading: true, error: null } =useFetch(url);
```

Receives an api-endpoint url and return an object with the following properties:

Data fetched from the API
```
data
```

A loading flag
```
loading
```

Returns the error if it happened
```
error
```
