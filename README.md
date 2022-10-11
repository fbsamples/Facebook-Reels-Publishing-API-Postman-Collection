# Facebook Reels Publishing API - Postman Collection

A Postman collection is a set of saved HTTP requests used to learn how to use a specific API. It encloses all the possible calls to an API that can be done, as well as the parameters or headers needed to successfully use it. They encapsulate those resources in a tidy way to save, reuse and share with others. Using them allows developers to quickly onboard and understand the way an API works by generating documented requests with examples. To use the Facebook Reels Publishing API Postman Collection, all that is needed is Postman on web or app and the JSON file containing the requests. This collection allows developers to upload and publish a Reel into a Facebook page from a local file or CDN.

## Requirements

* Postman Web/Postman Application
* Facebook Reels Publishing API Postman Collection JSON file
* Knowledge in HTTP Requests
* A video (hosted or local) with a 9:16 aspect ratio and maximum 60s long
* A Page Access Token

## Installation and usage

1. Open Postman on web or desktop
2. Click on Environments
3. Create a new environment or edit an existing one
4. Add a Variable named access_token
5. Paste your Page Access Token into the initial value cell
6. Click on Save
7. Select your environment under the drop-down list in the top right corner
8. Click on Import on the My Workspace header on the left side
9. Upload the JSON Collection file
10. Click on the orange import button
11. Click on Collections on the left sidebar and expand the Facebook Reels Publishing API section
12. Send request #1, Create Reel.
13. Upload your Reel either locally or hosted
    * Local Upload: Open request #2.A.
        1. Switch to the Headers tab of the request.
        2. Enter the file size in bytes of your video on the value field of the file_size header.
        3. Switch to the Body tab of the request.
        4. Select binary and select your file.
        5. Send the request
    * Host Upload: Open request #2.B
        1. Switch to the Headers tab of the request.
        2. Enter the hosted file URL on the file_url header value field.
        3. Send the request
14. (Optional) Track the status of your upload, request and processing using the request #3 only by clicking send.
15. Publish the reel with request #4. You may edit the description, title and video_state parameters to your needs.
16. Done! You now have a published Reel into your page.


## License

Please refer to the LICENSE file.
