# Status Pages

## List Status Pages

> API Response:

```json
[
  {
    "id": 1,
    "name": "excelsior",
    "public_url": "https://class.app.auramon.xyz",
    "public_favicon_url": "https://app.auramon.xyz/images/default-favicon.png",
    "public_logo_url": "https://app.auramon.xyz/storage/status-pages/1/logo.png",
    "created_at": "2024-01-17 08:47:15",
    "updated_at": "2024-01-17 08:47:15"
  },
  {
    "id": 2,
    "name": "yorktown",
    "public_url": "https://probe.app.auramon.xyz",
    "public_favicon_url": "https://app.auramon.xyz/images/default-favicon.png",
    "public_logo_url": "https://app.auramon.xyz/storage/status-pages/2/logo.png",
    "created_at": "2024-01-17 09:12:07",
    "updated_at": "2024-01-17 09:12:07"
  }
]
```

This endpoint retrieves a list of status pages the user has created.

### HTTP Request

`GET /api/status-pages`

## Get Status Page

> API Response:

```json
  {
    "id": 3,
    "name": "crossfield",
    "public_url": "https://class.app.auramon.xyz",
    "public_favicon_url": "https://app.auramon.xyz/images/default-favicon.png",
    "public_logo_url": "https://app.auramon.xyz/storage/status-pages/3/logo.png",
    "created_at": "2024-01-17 04:12:45",
    "updated_at": "2024-01-17 04:12:45"
  }
```

This endpoint retrieves a specific status page derived from the id.

### HTTP Request

`GET /api/status-pages/{id}`
