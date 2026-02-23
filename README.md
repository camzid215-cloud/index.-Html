<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Zam's Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: lightblue;
            margin: 0;
            padding: 20px;
        }
        
        .contact-box {
            max-width: 500px;
            margin: 0 auto;
            background: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        h2 {           
            color: #333;
            margin-bottom: 25px;
        }
        
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 8px 0 15px;
            border: 1px solid #ddd;
            border-radius: 4px;
            box-sizing: border-box;
        }
        
        button {
            background: #007bff;
            color: white;
            padding: 12px 25px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
            font-size: 16px;
        }
        
        button:hover {
            background: #0056b3;
        }
        
        label {
            font-weight: bold;
            color: #555;
        }
        
        .intro {
            color: yellow;
            font-size: 20px;
            text-align: center;
            margin: 20px 0;
        }
        
        .blue-text {
            color: blue;
            text-align: center;
        }
        
        .link-section {
            text-align: center;
            margin: 20px 0;
        }
        
        .video-section {
            text-align: center;
            margin: 20px 0;
        }
        
        video {
            max-width: 100%;
            height: auto;
        }
        
        /* Simple unordered list style */
        .my-list {
            background: white;
            padding: 20px 30px;
            border-radius: 8px;
            max-width: 500px;
            margin: 20px auto;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        .my-list h3 {
            color: #333;
            margin-bottom: 15px;
            text-align: center;
        }
        
        .my-list ul {
            padding-left: 30px;
        }
        
        .my-list li {
            color: #555;
            margin: 10px 0;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <div class="contact-box">
        <h2>Contact Us</h2>
        
        <form>
            <label for="name">Name</label>
            <input type="text" id="name" placeholder="Your name">
            
            <label for="email">Email</label>
            <input type="email" id="email" placeholder="Your email">
            
            <label for="message">Message</label>
            <textarea id="message" rows="4" placeholder="Your message"></textarea>
            
            <button type="submit">Send Message</button>
        </form>
    </div>

    <!-- Simple Unordered List (required) -->
    <div class="my-list">
        <h3>my favorite things I do hehe</h3>
        <ul>
            <b><li>sleep</li></b>
            <b><li>doomscorlling</li></b>
            <b><li>chat with myfriends</b></li>
            <b><li>chess</li></b>
        </ul>
    </div>

    <div>
        <p class="intro">Hi I'm Zam Nico this is my first Webpage</p>
        
        <center>
            <!-- Note: Image source needs to be fixed - using placeholder comment -->
            <!-- Image: src="content://com.android.externalstorage.documents/tree/primary%3ADownload%2FPHOTO%20VIDEO%20HTML/document/primary%3ADownload%2FPHOTO%20VIDEO%20HTML%2Fdownload%20(1).jpeg" width"30" height"30" -->
            <img src="content://com.android.externalstorage.documents/tree/primary%3ADownload%2FPHOTO%20VIDEO%20HTML/document/primary%3ADownload%2FPHOTO%20VIDEO%20HTML%2Fdownload%20(1).jpeg" width"30" height"30""
        </center>
        
        <div>
            <p class="blue-text">this is my first picture I put :></p>
            
            <center>
                <h3 style="color:blue;">LINK</h3>
            </center>
            
            <div class="link-section">
                <a href="https://m.youtube.com/">this is my first link</a>
            </div>
        </div>
        
        <div class="video-section">
            <!-- Note: Video source needs to be fixed - using placeholder -->
            <!-- Video: content://com.android.externalstorage.documents/tree/primary%3ADownload%2FPHOTO%20VIDEO%20HTML/document/primary%3ADownload%2FPHOTO%20VIDEO%20HTML%2F%23follow%20%23lonewolf%F0%9F%90%BA%20%23milion%C3%A1ria.mp4 -->
            <video controls>
                <source src="content://com.android.externalstorage.documents/tree/primary%3ADownload%2FPHOTO%20VIDEO%20HTML/document/primary%3ADownload%2FPHOTO%20VIDEO%20HTML%2F%23follow%20%23lonewolf%F0%9F%90%BA%20%23milion%C3%A1ria.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
            <br>
            <p style="font-family:courier;">my first video</p>
        </div>
    </div>
</body>
</html>
