# API Integration

## Problem

A page needs data from a remote service and must handle success and failure clearly.

## Approach

1. Identify the endpoint and expected response shape.
2. Request the data with `fetch`.
3. Check the response before parsing it.
4. Show loading, success, empty, and error states.
5. Keep secrets out of front-end code.

Read [MDN Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API) and [MDN CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS).

This is a later-course pattern. Do not add an API to a basic HTML/CSS assignment unless the assignment requires it.
