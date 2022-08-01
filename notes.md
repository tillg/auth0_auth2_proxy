## 2022-07-13

Config snippet 
```config
	  cookie-expire: 24h0m0s
      cookie-refresh: 0h60m0s
      provider: oidc
      # Use Auth0 as identity provider
      oidc-issuer-url: https://giantswarm.eu.auth0.com/
      login-url: https://giantswarm.eu.auth0.com/authorize
      redeem-url: https://giantswarm.eu.auth0.com/oauth/token
      validate-url: https://giantswarm.eu.auth0.com/userinfo
```