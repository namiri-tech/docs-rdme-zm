---
title: Errors
excerpt: >-
  Error handling: troubleshooting declines, invalid data, network problems, and
  more.
deprecated: false
hidden: false
metadata:
  robots: index
---
## HTTP response codes

Conventional HTTP response codes are used to indicate the success or failure of an API request.

Responses are grouped in five classes:

* Informational responses (100 – 199)
* Successful responses (200 – 299)
* Redirection messages (300 – 399)
* Client error responses (400 – 499)
* Server error responses (500 – 599)

For our interactive API, these are the main HTTP response status codes:

* 200 OK

* 201 Created

* 400 Bad Request

* 401 Unauthorized

* 500 Internal Server Error

* 501 Not Implemented

* 503 Service Unavailable

> 📘 503 is unlikely for DigiTax
>
> We pride ourselves to provide 99.99% uptime!

Head over to [MDN HTTP Status codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status) for details on the entire list of HTTP response status codes.

## Errors and examples

### Access error

If you enter an invalid X-API-Key in the header, then the response would be a **403 Forbidden** error with a response body like this.

```Text JSON
{
  "message": "Unauthorized"
}
```

### Data errors

#### Value validation

Data value validation is done for path parameters and body parameters.

If the ID, for example, passed as a path parameter for [Get a specific item](ref:get_items-item-id), then the response would be a **404 Not Found** error with a response body like this.

```Text JSON
{
  "message": "Item not found"
}
```

#### Schema validation

Data schema validation is done for body parameters

If the item\_class\_code, for example, was not passed as a body parameter for [Add business item](ref:post_items), then the response would be a **404 Not Found** error with a response body like this.

```Text JSON
[
  {
    "type": "Body",
    "errors": {
      "issues": [
        {
          "code": "invalid_type",
          "expected": "string",
          "received": "undefined",
          "path": [
            "item_class_code"
          ],
          "message": "Required"
        },
        ...
      ],
      "name": "ZodError"
    }
  }
]
```

You can get the list of issues (`errors.issues`) and highlight that in your system when integrating to inform your users.