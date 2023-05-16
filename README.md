# PostmanTesting
URL : https://simple-books-api.glitch.me

API Documentation: https://github.com/vdespa/introduction-to-postman-course/blob/main/simple-books-api.md
![image](https://github.com/huysam11/PostmanTesting/assets/99052999/df3e27ae-1e29-4487-9d99-cf346a772833)

These tests ensure that user can perform these actions without error

Using postman.setNextRequest('null') for Delete request to ignore APi client request since it will create new user every refreshed. Which caused the test to fail every run. 
