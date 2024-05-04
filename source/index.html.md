---
title: API Docs

language_tabs: # must be one of https://github.com/rouge-ruby/rouge/wiki/List-of-supported-languages-and-lexers
  - json
  
includes:
  - codes
  - user
  - statuspages

search: true

code_clipboard: false

meta:
  - name: description
    content: Documentation for the Aura API.
---

# Introduction

Welcome to the Aura API Docs! You can use our API to access Aura API endpoints, which can get information on game servers we monitor, status pages and team + user information.

The Aura API can be accessed at `https://app.auramon.xyz/api/`.

# Authentication

Aura uses API keys to allow access to the API. You can create a new API key in your account settings. 

Aura requires the API key to be included in the header of all API requests to the server in the following format:

`Authorization: Bearer YOUR_API_KEY`

<aside class="notice">
You must be on a trial or have a subscription to use the API.
</aside>

# Headers

Please ensure you have the following headers set to use the API.

```
Accept: application/json
Content-Type: application/json
```
