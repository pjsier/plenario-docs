#Response Format

All JSON API responses return their data in the `objects` block. Additional information is returned in the `meta` block:

| Parameter   | Description                                                       |
|-------------|-------------------------------------------------------------------|
| **status**  | **ok** if the query is successful, **error** if not.                  |
| **query**   | Original query parameters passed in.                              |
| **message** | If `status` is **error**, a detailed message as to what went wrong. |
