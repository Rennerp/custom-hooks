# useFetch

Example
```
  const url = 'API-ENDPOINT';
  const { data: null, loading: true, error: null } =useFetch(url);
```

Receives an api-endpoint url and return an objecto with the following properties

```
data
```
Data fetched from the API

```
loading
```
A loading flag

```
error
```
Returns the error if it happened