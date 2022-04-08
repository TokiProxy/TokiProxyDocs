# Socks5 Proxies
`https://tokiproxy.co.uk/api/proxies/socks5`

Using our Socks5 proxies endpoint you can get working Socks5 proxies

Example usage:
```js
const axios = require('axios');
const token = "API Key Here"

const config = {
    headers: { Authorization: `Bearer ${token}` }
}

axios.get('https://tokiproxy.co.uk/api/proxies/socks5', config).then(response => {
    const proxies = response.data;
    console.log(proxies)
}
```