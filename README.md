<h1 align="left">
  <span id="typewriter"></span>
</h1>

<script>
  var i = 0;
  var txt = "Hi there, I'm Rahaf Fayez";
  var speed = 100; // Speed of typing in milliseconds

  function typeWriter() {
    if (i < txt.length) {
      document.getElementById("typewriter").innerHTML += txt.charAt(i);
      i++;
      setTimeout(typeWriter, speed);
    }
  }

  window.onload = typeWriter;
</script>
