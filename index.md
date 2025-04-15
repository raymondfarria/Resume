<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Centered PDF</title>
    <style type="text/css">
        @import url(https://themes.googleusercontent.com/fonts/css?kit=fpjTOVmNbO4Lz34iLyptLUXza5VhXqVC6o75Eld_V98);
        body {
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f7f7f7; /* Optional background color */
        }
        .pdf-container {
            display: flex;
            justify-content: center;
            align-items: center;
            width: 100%;
            height: 100%;
        }
        .pdf-container embed {
            width: 80%; /* Adjust width as needed */
            height: 90%; /* Adjust height as needed */
            border: 1px solid #ccc; /* Optional border */
        }
    </style>
</head>
<body>
    <div class="pdf-container">
        <embed src="your-pdf-file.pdf" type="application/pdf">
    </div>
</body>
</html>
