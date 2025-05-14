// Change text dynamically
document.getElementById("changeTextBtn").addEventListener("click", function() {
    document.getElementById("textDisplay").textContent = "You changed the text!";
});

// Change background color
document.getElementById("changeColorBtn").addEventListener("click", function() {
    document.body.style.backgroundColor = "#ffcc00";
});

// Secret action on double-click
document.getElementById("secretActionBtn").addEventListener("dblclick", function() {
    alert("Secret action triggered! 🤫");
});

// Keypress detection
document.getElementById("keypressBox").addEventListener("keyup", function(event) {
    document.getElementById("textDisplay").textContent = `You typed: ${event.key}`;
});

// Form validation
document.getElementById("signupForm").addEventListener("submit", function(event) {
    event.preventDefault();
    let email = document.getElementById("email").value;
    let password = document.getElementById("password").value;
    let errorMessage = document.getElementById("errorMessage");

    if (!email.includes("@")) {
        errorMessage.textContent = "Invalid email!";
    } else if (password.length < 8) {
        errorMessage.textContent = "Password must be at least 8 characters!";
    } else {
        errorMessage.textContent = "Success!";
    }
});
