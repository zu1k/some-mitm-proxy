# Some MITM Proxy

Get pre-compiled binary in the [Release](https://github.com/zu1k/some-mitm-proxy/releases) page.

Prepare accounts information: accounts.json

```json
[
    {
        "access_token": "account1 access token",
        "session_token": "account1 session token"
    },
    {
        "access_token": "account2 access token",
        "session_token": "account2 session token"
    }
]
```

Start the MITM proxy server:

```
# ./mitm-proxy
Running server on 0.0.0.0:34567
```
