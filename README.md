function generateNumber() {
  // Generate a random number between 10 and 99
  const randomNum = Math.floor(Math.random() * 90) + 10;
  // Display the number
  document.getElementById('randomNumber').textContent = randomNum;
}

// Generate a number when the page loads
window.onload = generateNumber;
