<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title>فيديو بتول</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      background-color: #f0f0f0;
    }

    .video-container {
      width: 100%;
      max-width: 900px; /* أقصى عرض */
      position: relative;
      padding-bottom: 56.25%; /* نسبة 16:9 */
      height: 0;
      margin-bottom: 20px;
    }

    .video-container iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      border: none;
    }

    a.download-btn {
      display: inline-block;
      padding: 12px 20px;
      background-color: #ff4081;
      color: white;
      text-decoration: none;
      border-radius: 6px;
      font-size: 16px;
      transition: background 0.3s;
    }

    a.download-btn:hover {
      background-color: #e91e63;
    }

    @media (max-width: 600px) {
      a.download-btn {
        font-size: 14px;
        padding: 10px 16px;
      }
    }
  </style>
</head>
<body>
  <div class="video-container">
    <iframe src="https://drive.google.com/file/d/1x52z-jcbo9PslEUthoM2n3Jhd7FrhNVj/preview" allow="autoplay"></iframe>
  </div>

  <a class="download-btn" href="https://drive.google.com/uc?export=download&id=1x52z-jcbo9PslEUthoM2n3Jhd7FrhNVj" download>
    ⬇ تحميل الفيديو
  </a>
</body>
</html>
