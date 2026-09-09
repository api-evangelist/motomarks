# Motomarks API v1

Base URL: `https://motomarks.io`

Authentication uses a secret key in the `Authorization` header:

```
Authorization: Bearer sk_...
```

Endpoints:

- `GET /api/v1/brands?q=&limit=`: search published brands.
- `GET /api/v1/brands/{slug}`: get a published brand by slug.
- `GET /api/v1/brands/{slug}/assets?type=&format=&aspect=`: list brand assets.

Secret keys must not be exposed in client-side code, README examples, screenshots, or agent outputs.
