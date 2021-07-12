This repository contains generated golang code for:
* Event Family: https://desp.kroger.com/event-family/81dec467-059d-32d3-ba4f-80310eca86e7
* Version: v1.0.1

To use this in your go client, add the following requirements to your go.mod file.

```
module github.com/krogertechnology/my-go-client-application

go 1.13

require (
	github.com/actgardner/gogen-avro/v9 v9.0.0 // indirect
	github.com/rhammonds1-kr/desp-catalog-go-api-program-apip-metric-events v1.0.1
	...
```