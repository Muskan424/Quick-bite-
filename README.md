# Quick-bite-
A fast and reliable Food Delivery service ! Bringing food at your doorstep!
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Best Online Food Delivery Service in India | MyOnlineMeal.com</title>
    <link rel="stylesheet" href="index.css">
    <link rel="stylesheet" media="screen and (max-width: 1170px)" href="phone.css">
    <link href="https://fonts.googleapis.com/css?family=Baloo+Bhai|Bree+Serif&display=swap" rel="stylesheet">
</head>

<body>`````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````
    <nav id="navbar">
        <div id="logo">
            <img src="logo.png" alt="MyOnlineMeal Logo">
        </div>
        <ul>
            <li class="item"><a href="#home">Home</a></li>
            <li class="item"><a href="#services-container">Services</a></li>
            <li class="item"><a href="#client-section">Our Clients</a></li>
            <li class="item"><a href="#contact">Contact Us</a></li>
        </ul>
    </nav>

    <section id="home">
        <h1 class="h-primary">Welcome to MyOnlineMeal</h1>
        <p>Craving something tasty? Order now and enjoy restaurant-quality food at home!</p>
        <input type="text" id="searchBox" placeholder="Search for food...">
        <button class="btn" id="orderNowBtn">Order Now</button>
    </section>

    <section id="services-container">
        <h1 class="h-primary center">Our Services</h1>
        <div id="services">
            <div class="box" data-name="Food Catering">
                <img src="food-catering.jpg" alt="Food Catering Service">
                <h2 class="h-secondary center">Food Catering</h2>
                <p class="center">We provide high-quality food catering services for events, ensuring delicious meals and excellent service.</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
            <div class="box" data-name="Food Ordering">
                <img src="bicycle-7900268_1280.jpg" alt="Food Ordering Service">
                <h2 class="h-secondary center">Food Ordering</h2>
                <p class="center">Order your favorite meals online with quick delivery and a wide range of cuisines available.</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
            <div class="box" data-name="Bulk Ordering">
                <img src="bulk-ordering2.png" alt="Bulk Ordering Service">
                <h2 class="h-secondary center">Bulk Ordering</h2>
                <p class="center">We offer bulk ordering services for corporate and group events at competitive prices.</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
        </div>
    </section>

    <section id="cart-section">
        <h1 class="h-primary center">Your Cart</h1>
        <ul id="cart"></ul>
        <p>Total Price: <span id="totalPrice">$0</span></p>
    </section>

    <section id="client-section">
        <h1 class="h-primary center">Our Clients</h1>
        <div id="clients">
            <div class="client-item">
                <img src="google.png" alt="Google Logo">
            </div>
            <div class="client-item">
                <img src="microsoft.png" alt="Microsoft Logo">
            </div>
            <div class="client-item">
                <img src="skype.png" alt="Skype Logo">
            </div>
            <div class="client-item">
                <img src="apple.jpg" alt="Apple Logo">
            </div>
        </div>
    </section>

    <section id="contact">
        <h1 class="h-primary center">Contact Us</h1>
        <div id="contact-box">
            <form id="contactForm">
                <div class="form-group">
                    <label for="name">Name: </label>
                    <input type="text" name="name" id="name" placeholder="Enter your name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email: </label>
                    <input type="email" name="email" id="email" placeholder="Enter your email" required>
                </div>
                <div class="form-group">
                    <label for="message">Message: </label>
                    <textarea name="message" id="message" cols="30" rows="5" placeholder="Enter your message" required></textarea>
                </div>
                <div class="form-group">
                    <label for="phone">Phone Number: </label>
                    <input type="tel" name="phone" id="phone" placeholder="Enter your phone number" required>
                </div>
                <button type="submit" class="btn">Submit</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="center">
            Copyright &copy; 2025 www.MyOnlineMeal.com. All rights reserved!
        </div>
    </footer>

    <script>
        document.getElementById("contactForm").addEventListener("submit", function (e) {
            e.preventDefault();
            let name = document.getElementById("name").value.trim();
            let email = document.getElementById("email").value.trim();
            let message = document.getElementById("message").value.trim();

            if (name === "" || email === "" || message === "") {
                alert("All fields are required!");
                return;
            }

            if (!email.includes("@") || !email.includes(".")) {
                alert("Please enter a valid email address!");
                return;
            }

            alert("Thank you for contacting us! We will get back to you soon.");
            this.reset();
        });
    </script>
</body>

</html>

