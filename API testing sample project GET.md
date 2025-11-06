**Test**: Retrieve comments for post with ID = 2<br>
**Method**: GET<br>
**Endpoint**: https://jsonplaceholder.typicode.com/comments?postId=2<br>
**Params**: postID = 2<br>

**Expected result**<br>
The API should return an array of JSON objects with comments associated with the post with postId: 2.<br>
**Response status**: 200 OK<br>
**Response body**:<br>

![2025-11-06 21 19 26](https://github.com/user-attachments/assets/297a96a9-8589-454c-aeb7-9f920c74d504)

**Additional verifications**:<br>
Each comment contains the following fields: postId, id, name, email, body.<br>




