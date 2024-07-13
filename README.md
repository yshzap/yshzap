### Hey there, YshZap here!

<div class="animated-text">
  <span>Hey there, YshZap here!</span>
</div>

<style>
  /* Importing a custom font from Google Fonts */
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

  /* Styling the animated text */
  .animated-text {
    font-family: 'Roboto', sans-serif; /* Applying the custom font */
    font-size: 24px;
    text-align: center;
    margin-top: 20px;
  }

  /* Keyframes for the color animation */
  @keyframes colorChange {
    0% { color: #FF5733; } /* Random color 1 */
    25% { color: #DAF7A6; } /* Random color 2 */
    50% { color: #C70039; } /* Random color 3 */
    75% { color: #00BFFF; } /* Random color 4 */
    100% { color: #900C3F; } /* Random color 5 */
  }

  /* Applying the animation to the span */
  .animated-text span {
    animation: colorChange 5s infinite; /* 5 seconds loop for animation */
  }
</style>
