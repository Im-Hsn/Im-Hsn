# GitHub Profile

<!-- Container for the typing effect -->
<div style="position: relative; width: 100%; height: 300px; overflow: hidden;">
  <!-- SVG 1: Shows the first and second phrases -->
  <img id="typing-svg-1" src="https://readme-typing-svg.herokuapp.com?font=Inconsolata&color=008cff&size=50&center=true&vCenter=true&width=1600&height=300&lines=Hello+there,+I'm+Hassan;and+I'm+studying+Computer+%26+Communications+Engineering" width="100%" />
  
  <!-- SVG 2: Shows the first and third phrases -->
  <img id="typing-svg-2" src="https://readme-typing-svg.herokuapp.com?font=Inconsolata&color=008cff&size=50&center=true&vCenter=true&width=1600&height=300&lines=Hello+there,+I'm+Hassan;Specialized+in+Software+Engineering" width="100%" style="display: none;" />
</div>

<!-- JavaScript for transitioning between SVGs -->
<script>
  let svg1 = document.getElementById('typing-svg-1');
  let svg2 = document.getElementById('typing-svg-2');

  function switchSVG() {
    svg1.style.display = svg1.style.display === 'none' ? 'block' : 'none';
    svg2.style.display = svg2.style.display === 'none' ? 'block' : 'none';
  }

  setInterval(switchSVG, 10000); // Switch every 10 seconds
</script>


![GitHub Grid Snake SVG](assets/snake.svg)


<img src="assets/footer.svg" width="100%">
