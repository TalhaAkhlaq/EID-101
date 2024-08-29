# Potential Solutions

## Potential Solution 1: Spring system

<div style="display: flex; justify-content: center; align-items: center;">
  <button onclick="prevImage()" style="border: none; background: transparent; cursor: pointer; font-size: 24px;">&#10094;</button>
  <div id="image-container" style="position: relative; width: 80%; max-width: 600px; height: auto;">
    <img id="image1" src="https://github.com/TalhaAkhlaq/EID-101-Robotics-Crash-Course/blob/main/Final%20Project/Releasing%20Mechanism/Potential%20Solution%201.png" style="width: 100%; height: auto; display: block;">
    <img id="image2" src="https://github.com/TalhaAkhlaq/EID-101-Robotics-Crash-Course/blob/main/Final%20Project/Releasing%20Mechanism/Potential%20Solution%201%20(2)%20.png" style="width: 100%; height: auto; display: none;">
  </div>
  <button onclick="nextImage()" style="border: none; background: transparent; cursor: pointer; font-size: 24px;">&#10095;</button>
</div>

<script>
  let currentImage = 1;

  function showImage(index) {
    document.getElementById('image1').style.display = index === 1 ? 'block' : 'none';
    document.getElementById('image2').style.display = index === 2 ? 'block' : 'none';
    currentImage = index;
  }

  function prevImage() {
    showImage(currentImage === 1 ? 2 : 1);
  }

  function nextImage() {
    showImage(currentImage === 1 ? 2 : 1);
  }
</script>

## Potential Solution 2: Gravitational slide 

## Potential Solution 3: Pneumatic Thruster (Compressed Air)

