<!DOCTYPE html>
<html>
<head>
  <title>Image Reflection</title>
  <style>
    .reflection {
      position: relative;
      width: 300px; /* Adjust width as needed /
      height: 200px; / Adjust height as needed /
    }
    .reflection img {
      width: 100%;
      height: 100%;
    }
    .reflection:after {
      content: '';
      position: absolute;
      top: 100%;
      left: 0;
      width: 100%;
      height: 100px; / Adjust reflection height as needed /
      background: linear-gradient(to bottom, rgba(255, 255, 255, 0.5), rgba(255, 255, 255, 0));
      transform: scaleY(-1);
      opacity: 0.5; / Adjust reflection opacity as needed */
    }
  </style>
</head>
<body>

<div class="reflection">
  <img src="image.jpg" alt="Image">
</div>

</body>
</html>
