# Errors

The Backer API uses the following error codes:


Error Code | Meaning
---------- | -------
400 | Bad Request -- Your request is invalid.
401 | Unauthorized -- Your API token is wrong.
403 | Forbidden -- You are not allowed to access that data.
404 | Not Found -- The specified resource could not be found.
406 | Not Acceptable -- You requested a format that isn't json.
422 | Unprocessable Entity -- Your request is valid but the operation failed.
429 | Too Many Requests -- You are exceeding your request rate limit.
500 | Internal Server Error -- We had a problem with our server. Try again later.
503 | Service Unavailable -- We're temporarily offline for maintenance. Please try again later.
