**Test**: Updating the user's email address<br>
**Method**: PUT<br>
**Endpoint**: https://jsonplaceholder.typicode.com/users/3<br>
Body:<br>
{<br>
    "id": 3,<br>
    "name": "Clementine Bauch",<br>
    "username": "Samantha",<br>
    "email": "test@test.net",<br>
    "address": {<br>
        "street": "Douglas Extension",<br>
        "suite": "Suite 847",<br>
        "city": "McKenziehaven",<br>
        "zipcode": "59590-4157",<br>
        "geo": {<br>
            "lat": "-68.6102",<br>
            "lng": "-47.0653"<br>
        }<br>
    }<br>
}<br>

**Expected result**<br>
The API returns a user object updated with data from the request.<br>
**Response status**: 200 OK<br>
**Response body**:<br>
{<br>
    "id": 3,<br>
    "name": "Clementine Bauch",<br>
    "username": "Samantha",<br>
    "email": "test@test.net",<br>
    "address": {<br>
        "street": "Douglas Extension",<br>
        "suite": "Suite 847",<br>
        "city": "McKenziehaven",<br>
        "zipcode": "59590-4157",<br>
        "geo": {<br>
            "lat": "-68.6102",<br>
            "lng": "-47.0653"<br>
        }<br>
    }<br>
}<br>

**Additional verifications**:<br>
The response email has a new value (test@test.net).<br>
The remaining data (id, name, username, address) remains unchanged.<br>
The response format is JSON.<br>
The response time is < 500 ms.<br>

The test was performed on the public JSONPlaceholder API. The endpoint returned a correct 200 OK response, but the data is not actually updated because the API is running in mock mode.
