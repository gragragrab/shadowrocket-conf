# Shadowrocket Config

## What is this?

This is a git-based config file for shadowsocks ios client.

The main objective is to centralize config management among multiple devices.

## How to use

Open your Shadowrocket client and add configuration:

- **From URL:** `https://raw.githubusercontent.com/gragragrab/shadowrocket-conf/main/shadowrocket.conf`
- **Or scan the QR code below:**

![QR code](https://raw.githubusercontent.com/gragragrab/shadowrocket-conf/main/images/config-qr.png)

### Then configure:

- **Data** → Proxy Enable Logging → Turn Off
- **Settings** → Proxy → Compatibility Mode → Turn On
- **Settings** → Proxy → Proxy Share → Enable Share → Turn On
- **Settings** → Diagnostics → Enable Logging → Turn Off
- **Settings** → Config → Auto Background Update → Turn On

## Reference

- [Configuration file format](https://manual.nssurge.com)
- [misha-tgshv repository](https://github.com/misha-tgshv/shadowrocket-configuration-file)

## Streisand app routes

### Bypass ru domains:

<details>
  <summary>Bypass ru domains</summary>
 
```
streisand://aW1wb3J0L3JvdXRlOi8vWW5Cc2FYTjBNRERWQVFJREJBVUdEaGdaR2xWeWRXeGxjMTFrYjIxaGFXNU5ZWFJqYUdWeVZHNWhiV1ZlWkc5dFlXbHVVM1J5WVhSbFozbFVkWFZwWktJSEU5VUlDUW9MREEwT0R4QVNXMjkxZEdKdmRXNWtWR0ZuWFdSdmJXRnBiazFoZEdOb1pYSldaRzl0WVdsdVVtbHdWMjVsZEhkdmNtdFdaR2x5WldOMFZtaDVZbkpwWktDaEVWaG5aVzlwY0RweWRWZDBZM0FzZFdSdzFCUVZDZ3dORGhZU1cyOTFkR0p2ZFc1a1ZHRm5YV1J2YldGcGJrMWhkR05vWlhLaEYxbGtiMjFoYVc0NmNuVlpVbFV0WkdseVpXTjBYRWxRU1daT2IyNU5ZWFJqYUY4UUpFUkROVGxETXpsRExVUXdSRVl0TkRsR015MDVRVEl3TFVFMlJUVkVSakkwUkRaRE9RQUlBQk1BR1FBbkFDd0FPd0JBQUVNQVRnQmFBR2dBYndCeUFIb0FnUUNJQUlrQWl3Q1VBSndBcFFDeEFMOEF3UURMQU5VQTRnQUFBQUFBQUFJQkFBQUFBQUFBQUJzQUFBQUFBQUFBQUFBQUFBQUFBQUVK
```
</details>


<details>
  <summary>Bypass ru domains + geoip + whatsapp, telegram, google are not routed</summary>

```
streisand://aW1wb3J0L3JvdXRlOi8vWW5Cc2FYTjBNRERWQVFJREJBVUdEQjhnSVZWeWRXeGxjMTFrYjIxaGFXNU5ZWFJqYUdWeVZHNWhiV1ZlWkc5dFlXbHVVM1J5WVhSbFozbFVkWFZwWktNSEVSWFVDQWtLQ3d3TkRoQmRaRzl0WVdsdVRXRjBZMmhsY2xaa2IyMWhhVzVTYVhCYmIzVjBZbTkxYm1SVVlXZFdiR2x1WldGeW9LRVBXR2RsYjJsd09uSjFWbVJwY21WamROSVNDUkFUVzI5MWRHSnZkVzVrVkdGbm9SUmVjbVZuWlhod09pNHFYQzV5ZFNUVEZoY0pFQmdaVzI5MWRHSnZkVzVrVkdGblhXUnZiV0ZwYmsxaGRHTm9aWEpXYUhsaWNtbGtwUm9iSEIwZVh4QVFaMlZ2YzJsMFpUcDBaV3hsWjNKaGJWOFFFR2RsYjNOcGRHVTZkMmhoZEhOaGNIQmRaMlZ2YzJsMFpUcGhjSEJzWlY1blpXOXphWFJsT21kdmIyZHNaVjVuWlc5emFYUmxPbWwwZFc1bGMyMEFVZ0JWQUMwQVJBQnBBSElBWlFCakFIVFlQTjMzMkR6ZCtscEpVRTl1UkdWdFlXNWtYeEFrUXpRelFrVTVSRGt0T0RGQk15MDBRamhGTFRrM1JrTXRPRFE0TlVFNFJqZENRelkyQUFnQUV3QVpBQ2NBTEFBN0FFQUFSQUJOQUZzQVlnQmxBSEVBZUFCNUFIc0FoQUNMQUpBQW5BQ2VBSzBBdEFEQUFNNEExUURiQU80QkFRRVBBUjRCTFFGSUFWTUFBQUFBQUFBQ0FRQUFBQUFBQUFBaUFBQUFBQUFBQUFBQUFBQUFBQUFCZWc9PQ==
```
</details>

