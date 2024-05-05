# User

## Me

> API Response:

```json
  {
    "id": 1,
    "full_name": "K Janeway",
    "avatar_url": "https://www.gravatar.com/avatar/4564674656874",
    "email_address": "k@janeway.com",
    "joined_at": "2023-11-15 00:37",
    "has_subscription": true
  }
```

This endpoint provides information about the authenticated user.

### HTTP Request

`GET /api/user`

## My Teams

> API Response:

```json
[
  {
    "id": 1,
    "name": "Janeway's Team",
    "is_personal_team": true,
    "created_at": "2023-11-15 00:37:36"
  },
  {
    "id": 2,
    "name": "Sisko's Team",
    "is_personal_team": false,
    "created_at": "2024-03-27 11:41:01"
  }
]
```

This endpoint retrieves the teams user is either a member of or owns.

### HTTP Request

`GET /api/user/teams`
