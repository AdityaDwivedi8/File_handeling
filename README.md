# Forms,Images and File Handeling
Node.js server application that allows users to upload images and videos to the server. It uses Express and the Express File Uploader middleware to handle file uploads. The uploaded files are then stored on Cloudinary, a cloud-based image and video management service. The application also sends an email to the user who uploaded the file, containing a link to the uploaded file.
# Contents:
The application should consists of four files:
1. index.js: This file sets up the Express app, connects to the database and Cloudinary, and defines the endpoints for file upload.

2./routes/FileUpload.js: This file defines the routes for file upload, which include image Upload, video upload, and image size reducer.

3./models/File.js: This file defines the schema for the uploaded files and defines a post-save hook that sends an email to the user who uploaded the file.

4./controllers/fileUpload.js: This file contains the logic for handling file uploads, including checking file types, uploading to Cloudinary, and saving the file to the database.
# Installation
npm i express 

npm i mongoose

npm i cloudinary

npm i express-fileupload

npm i nodemailer
