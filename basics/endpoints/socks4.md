# Socks4 Proxies
`https://tokiproxy.co.uk/api/proxies/socks4`

Using our Socks4 proxies endpoint you can get working Socks4 proxies

Example usage:
```js
const axios = require('axios');
const token = "API Key Here"

const config = {
    headers: { Authorization: `Bearer ${token}` }
}

axios.get('https://tokiproxy.co.uk/api/proxies/socks4', config).then(response => {
    const proxies = response.data;
    console.log(proxies)
}
```