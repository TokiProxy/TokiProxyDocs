# HTTP Proxies
`https://tokiproxy.co.uk/api/proxies/http`

Using our HTTP proxies endpoint you can get working http and working https proxies

Example usage:
```js
const axios = require('axios');
const token = "API Key Here"

const config = {
    headers: { Authorization: `Bearer ${token}` }
}

axios.get('https://tokiproxy.co.uk/api/proxies/http', config).then(response => {
    const proxies = response.data;
    console.log(proxies)
}
```
