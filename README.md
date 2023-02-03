# sign-in-with-google

Use this boilerplate [index.html](src/index.html) and [package.json](package.json) to set up a client-side application that implements Sign In With Google, using the new Google Identity Services framework.

It has the following characteristics:
1. Contains separate logic for authentication (Sign in with Google button) and authorization (Google Drive)
2. Uses parcel to bundle the resulting application to be served on a static website
3. It simply displays the resulting ID token and Access token on the page. Modify this to suit your needs
4. `package.json` contains scripts for dev, build and deploy

IMPORTANT: Please remember to replace the values for client id in `src/index.html`, and your own S3 bucket in `package.json`

The resulting page can be viewed at [https://cloudmatica.s3.amazonaws.com/sign-in-with-google/index.html](https://cloudmatica.s3.amazonaws.com/sign-in-with-google/index.html)