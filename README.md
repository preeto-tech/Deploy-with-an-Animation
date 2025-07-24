# Deploy-with-an-Animation
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>BuildBand | Creative Landing</title>
  <style>
    /* Reset and base styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body, html {
      height: 100%;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    /* Animated background gradient */
    body {
      background: linear-gradient(-45deg, #6a11cb, #2575fc, #ff6f61, #42e695);
      background-size: 400% 400%;
      animation: gradientBG 15s ease infinite;
      color: white;
      overflow: hidden;
    }

    @keyframes gradientBG {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    /* Centered hero content */
    .hero {
      height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      animation: fadeInUp 2s ease-out;
    }

    h1 {
      font-size: 3.5rem;
      margin-bottom: 20px;
    }

    p {
      font-size: 1.3rem;
      max-width: 600px;
      margin-bottom: 30px;
      line-height: 1.5;
    }

    .btn {
      background-color: white;
      color: #2575fc;
      border: none;
      padding: 12px 30px;
      font-size: 1.1rem;
      font-weight: bold;
      border-radius: 30px;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    .btn:hover {
      background-color: #fff;
      color: #6a11cb;
      transform: scale(1.05);
      box-shadow: 0 10px 20px rgba(0,0,0,0.2);
    }

    @keyframes fadeInUp {
      0% {
        opacity: 0;
        transform: translateY(30px);
      }
      100% {
        opacity: 1;
        transform: translateY(0);
      }
    }

    /* Responsive text */
    @media (max-width: 768px) {
      h1 {
        font-size: 2.5rem;
      }
      p {
        font-size: 1rem;
      }
    }
  </style>
</head>
<body>
  <section class="hero">
    <h1>Welcome to BuildBand</h1>
    <p>We design experiences that move people. Let’s build something amazing together with creativity, code and passion.</p>
    <button class="btn">Get Started</button>
  </section>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>BuildBand | Creative Landing</title>
  <style>
    /* Reset and base styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body, html {
      height: 100%;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    /* Animated background gradient */
    body {
      background: linear-gradient(-45deg, #6a11cb, #2575fc, #ff6f61, #42e695);
      background-size: 400% 400%;
      animation: gradientBG 15s ease infinite;
      color: white;
      overflow: hidden;
    }

    @keyframes gradientBG {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    /* Centered hero content */
    .hero {
      height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      animation: fadeInUp 2s ease-out;
    }

    h1 {
      font-size: 3.5rem;
      margin-bottom: 20px;
    }

    p {
      font-size: 1.3rem;
      max-width: 600px;
      margin-bottom: 30px;
      line-height: 1.5;
    }

    .btn {
      background-color: white;
      color: #2575fc;
      border: none;
      padding: 12px 30px;
      font-size: 1.1rem;
      font-weight: bold;
      border-radius: 30px;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    .btn:hover {
      background-color: #fff;
      color: #6a11cb;
      transform: scale(1.05);
      box-shadow: 0 10px 20px rgba(0,0,0,0.2);
    }

    @keyframes fadeInUp {
      0% {
        opacity: 0;
        transform: translateY(30px);
      }
      100% {
        opacity: 1;
        transform: translateY(0);
      }
    }

    /* Responsive text */
    @media (max-width: 768px) {
      h1 {
        font-size: 2.5rem;
      }
      p {
        font-size: 1rem;
      }
    }
  </style>
</head>
<body>
  <section class="hero">
    <h1>Welcome to BuildBand</h1>
    <p>We design experiences that move people. Let’s build something amazing together with creativity, code and passion.</p>
    <button class="btn">Get Started</button>
  </section>
</body>
</html>
