# Redirects boilerplate
Static boilerplate for performing redirects on CloudCannon


[![Deploy to CloudCannon](https://buttons.cloudcannon.com/deploy.svg)](https://app.cloudcannon.com/register#sites/connect/github/CloudCannon/redirect-boilerplate)

On `.cloudcannon/routing.json`, change the URL on `to` for the desired redirect URL.

For more information, please check the [documentation here](https://cloudcannon.com/documentation/articles/configuring-custom-routing/).

```
# .cloudcannon/routing.json
{
  "routes": [
    {
      "from": "/(.*)",
      "status": 301,
      "to": "https://www.example.com/$1"
    }
  ]
}
```
