**Test**: Adding a new post<br>
**Method**: POST<br>
**Endpoint**: https://jsonplaceholder.typicode.com/posts<br>
**Body**:<br>
  {<br>
    "userId": 11,<br>
    "id": 101,<br>
    "title": "Post testowy",<br>
    "body": "Testowy post"<br>
  }

**Expected result**<br>
The API should return an object containing the data sent in the request.<br>
**Response status**: 201 Created<br>
**Response body**:<br>
{<br>
    "userId": 11,<br>
    "id": 101,<br>
    "title": "Post testowy",<br>
    "body": "Testowy post"<br>
}

**Additional verifications**:<br>
The correct id (numeric type) was returned in the response.<br>
The values of the userId, title, and body fields match the sent request.<br>
The response format is valid JSON.<br>
Response time < 1 s.<br>
No server errors (4xx, 5xx).<br>

The test was performed on the public JSONPlaceholder API. The endpoint returned a correct 201 Created response, but the data is not actually updated because the API is running in mock mode.
