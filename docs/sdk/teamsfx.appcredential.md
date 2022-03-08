<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/teamsfx](./teamsfx.md) &gt; [AppCredential](./teamsfx.appcredential.md)

## AppCredential class

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.
> 

Represent Microsoft 365 tenant identity, and it is usually used when user is not involved like time-triggered automation job.

<b>Signature:</b>

```typescript
export declare class AppCredential implements TokenCredential 
```
<b>Implements:</b> TokenCredential

## Remarks

Only works in in server side.

## Example


```typescript
loadConfiguration(); // load configuration from environment variables
const credential = new AppCredential();
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(authConfig)](./teamsfx.appcredential._constructor_.md) |  | <b><i>(BETA)</i></b> Constructor of AppCredential. |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [getToken(scopes, options)](./teamsfx.appcredential.gettoken.md) |  | <b><i>(BETA)</i></b> Get access token for credential. |
