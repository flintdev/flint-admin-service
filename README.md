# flint-admin-service

#### endpoint

```text
admin-service:8080
```

#### Method

```text
POST
```

#### Payload Example
data can be any dictionary data which will be passed to authentication function.

```json
{
	"user": "gaoxin",
	"data": {
		"user": "gaoxin",
		"password": "123"
	}
}

```

#### Response Example

```json
{
    "message": "",
    "status": "success",
    "token": "Bearer eyJhbGciOiJSUzI1NiIsImtpZCI6InE2SG85V01Lc2JOa25pQ0tOWS1jNlViNWRMY0RSZTh1YWtGcFVxLXFHQ3MifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJnYWRhaSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJnYWRhaS10b2tlbi03cjR4aiIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50Lm5hbWUiOiJnYWRhaSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50LnVpZCI6ImJmNjk5OWIwLWFiMTUtNDNlYi1hNDIwLWRiOGNlODliN2ViNCIsInN1YiI6InN5c3RlbTpzZXJ2aWNlYWNjb3VudDpnYWRhaTpnYWRhaSJ9.e13dXzUsO_yX755gU3GVbRCACcFwGAjHd_DyFFyldWMTU9PKIM0aG43rL-hFYazFUAbVdw5PwIkmYixKcd9Hw3gYQZKyFCQmK4tBI8_7KK8RjZrB9qVwz9ht6sgyMJCrlBSW25YKifvUyTwJwZp6Gqa_G8BYvhqPG29bItlJwM2G6Iij9LGe-qbfFtsws_Eln81kio0KowaquZJwN9eEq6MwjcQJXg4Sm7E0GjIFR59BraFkb9isktZiH9qonWn9tAX4ssMAcg9qDJDEOMLjSAc_OGyPxECctrUp7rIQin4vRX_7kGu0tJn0EN2mppv9a3tKx_oYnxtOvO8MtWnBxA",
    "user": "gadai"
}

```
