# PhotoCloud - A File Upload / Image Hosting Project

This project allows users to upload files via a web interface, which are then stored in MongoDB and uploaded to Cloudinary.

## Prerequisites

- Node.js
- npm
- MongoDB Atlas account
- Cloudinary account (free tier works)

## Setup Instructions

### 1. Clone the Repository

```sh
git clone git@github.com:JeetChauhan17/PhotoCloud.git
cd PhotoCloud
```

### 2. Install dependencies

```sh
npm install
```

### 3. Configure Environment Variables
Make a .env file to store your credentials. Use this a template:

```sh
CLOUDINARY_CLOUD_NAME=your-cloudinary-cloud-name
CLOUDINARY_API_KEY=your-cloudinary-api-key
CLOUDINARY_API_SECRET=your-cloudinary-api-secret
MONGODB_URL=your-mongourl/DBNAME
```
*NOTE: Dont put quotes in the values.*

### 4. Start the Server 🚀:
```sh
node server.js
```
### 5. Open index.html in Browser:

### Usage
1. Open the index.html file in a web browser.
2. Select a file using the file input.
3. Click the "Upload" button to upload the file.
4. The response will display the URL of the uploaded file if successful.

### Troubleshooting
- Ensure MongoDB and Cloudinary credentials are correctly set up.
- Check for any errors in the console and the server logs.

### License
This project is licensed under the MIT License.
