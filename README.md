<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amima Travels_Umrah Travel Booking</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            line-height: 1.6;
        }
        header {
            background: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            margin: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 16px;
        }
        .hero {
            background-image: url('kaaba-5488001_1280.png');
            background-size: cover;
            background-position: center;
            height: 1200px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            font-size: 3em;
        }
        .hero h1 {
            font-size: 2.5em;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
        }
        .form-group input, .form-group select {
            width: 100%;
            padding: 8px;
            box-sizing: border-box;
        }
        button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            font-size: 16px;
        }
        .packages {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
        }
        .package {
            flex: 1;
            margin: 0 10px;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 8px;
            text-align: center;
        }
        .testimonials {
            background: #f1f1f1;
            padding: 20px;
            margin: 20px 0;
        }
        .testimonial {
            margin-bottom: 15px;
        }
        footer {
            background: #4CAF50;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Amima Travels</h1>
	<h2>Umrah Travel Booking</h2>
        <nav>
            <a href="#home">Home</a>
            <a href="#packages">Packages</a>
            <a href="file:///C:/inetpub/wwwroot/AMIMA%20TRAVELS/umrahbooking.html">Booking</a>
            <a href="#testimonials">Testimonials</a>
            <a href="file:///C:/inetpub/wwwroot/AMIMA%20TRAVELS/contact.html">Contact</a>
	    <a href="https://wa.me/917384366415">WhatsApp</a>
        </nav>
    </header>

    <div class="hero" id="home">
        <h1>Experience the Journey of a Lifetime</h1>
        <p>Book your Umrah package with us and make your spiritual journey seamless.</p>
    </div>

    <div class="container">
        <section id="booking">
            <h2>Book Your Umrah Package</h2>
            <form action="/submit-booking" method="post">
                <div class="form-group">
                    <label for="name">Full Name:</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email Address:</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="phone">Phone Number:</label>
                    <input type="tel" id="phone" name="phone" required>
                </div>
                <div class="form-group">
                    <label for="package">Select Package:</label>
                    <select id="package" name="package" required>
                        <option value="basic">Basic Package</option>
                        <option value="standard">Standard Package</option>
                        <option value="luxury">Luxury Package</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="dates">Preferred Dates:</label>
                    <input type="date" id="dates" name="dates" required>
                </div>
                <button type="submit">Book Now</button>
            </form>
        </section>

        <section id="packages">
            <h2>Our Packages</h2>
            <div class="packages">
                <div class="package">
                    <h3>Basic Package</h3>
                    <p>Affordable and essential services to complete your Umrah journey.</p>
                </div>
                <div class="package">
                    <h3>Standard Package</h3>
                    <p>Comfortable accommodations and additional services for a better experience.</p>
                </div>
                <div class="package">
                    <h3>Luxury Package</h3>
                    <p>Top-notch facilities and exclusive services for a premium Umrah experience.</p>
                </div>
            </div>
        </section>

        <section id="testimonials" class="testimonials">
            <h2>What Our Clients Say</h2>
            <div class="testimonial">
                <p>"An unforgettable experience! The service was exceptional and the journey was smooth."</p>
                <p>- Ahmed A.</p>
            </div>
            <div class="testimonial">
                <p>"Highly recommended for anyone looking to perform Umrah with comfort and ease."</p>
                <p>- Fatima B.</p>
            </div>
        </section>
    </div>

    <footer id="contact">
        <p>&copy; 2024 Umrah Travel Booking. All rights reserved.</p>
        <p>Contact us at: <a href="mailto:info@umrahbooking.com">info@umrahbooking.com</a></p>
    </footer>
</body>
</html>
