function convertTemperature() {
  const celsiusInput = document.getElementById("celsius");
  const fahrenheitInput = document.getElementById("fahrenheit");

  const celsiusValue = parseFloat(celsiusInput.value);
  const fahrenheitValue = (celsiusValue * 9/5) + 32;

  if (!isNaN(fahrenheitValue)) {
    fahrenheitInput.value = fahrenheitValue.toFixed(2);
  } else {
    fahrenheitInput.value = "";
  }
}

// Initial conversion on page load
convertTemperature();