<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sawasthaya - Your Health and Fitness Companion</title>
    <link rel="stylesheet" href="styles/style.css">
</head>
<body>
    <header>
        <h1>Sawasthaya</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Articles</a></li>
                <li><a href="#">Workouts</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Content goes here -->
    </main>

    <footer>
        <p>&copy; 2023 Sawasthaya - Your Health and Fitness Companion</p>
    </footer>

    <script src="scripts/main.js"></script>
</body>
</html>
<main>
    <section class="welcome-section">
        <h2>Welcome to Sawasthaya - Your Health and Fitness Companion</h2>
        <p>Empower yourself to live a healthy lifestyle. Discover articles, workouts, and expert advice tailored just for you.</p>
        <a href="#" class="cta-button">Get Started</a>
    </section>

    <!-- Additional sections or content can be added here -->
</main>
<main>
    <section class="welcome-section">
        <h2>Welcome to Sawasthaya - Your Health and Fitness Companion</h2>
        <p>Empower yourself to live a healthy lifestyle. Discover articles, workouts, and expert advice tailored just for you.</p>
        <a href="#" class="cta-button">Get Started</a>
    </section>

    <section class="articles-section">
        <h2>Latest Articles</h2>
        <article>
            <h3>10 Tips for a Healthy Lifestyle</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin tincidunt, velit vel tincidunt elementum.</p>
            <a href="#">Read more</a>
        </article>
        <article>
            <h3>The Importance of Regular Exercise</h3>
            <p>Nullam ac justo efficitur, tincidunt libero id, ultrices purus. Suspendisse vel feugiat nunc, vitae luctus orci.</p>
            <a href="#">Read more</a>
        </article>
        <!-- Add more articles as needed -->
    </section>

    <!-- Additional sections or content can be added here -->
</main>
<main>
    <section class="welcome-section">
        <h2>Welcome to Sawasthaya - Your Health and Fitness Companion</h2>
        <p>Empower yourself to live a healthy lifestyle. Discover articles, workouts, and expert advice tailored just for you.</p>
        <a href="#" class="cta-button">Get Started</a>
    </section>

    <section class="articles-section">
        <h2>Latest Articles</h2>
        <article>
            <h3>10 Tips for a Healthy Lifestyle</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin tincidunt, velit vel tincidunt elementum.</p>
            <a href="#">Read more</a>
        </article>
        <article>
            <h3>The Importance of Regular Exercise</h3>
            <p>Nullam ac justo efficitur, tincidunt libero id, ultrices purus. Suspendisse vel feugiat nunc, vitae luctus orci.</p>
            <a href="#">Read more</a>
        </article>
        <!-- Add more articles as needed -->
    </section>

    <section class="workouts-section">
        <h2>Featured Workouts</h2>
        <div class="workout">
            <h3>Full Body Workout</h3>
            <p>A high-intensity full-body workout to boost your metabolism and build strength.</p>
            <a href="#">View Details</a>
        </div>
        <div class="workout">
            <h3>Yoga for Beginners</h3>
            <p>Start your journey into yoga with this beginner-friendly routine for flexibility and relaxation.</p>
            <a href="#">View Details</a>
        </div>
        <!-- Add more workouts as needed -->
    </section>

    <!-- Additional sections or content can be added here -->
</main>
<section class="contact-section">
    <h2>Contact Us</h2>
    <p>Have questions or suggestions? Reach out to our team:</p>
    
    <div class="contact-person">
        <h3>Shrivats Kaushik</h3>
        <p>Phone: 9897923340</p>
        <!-- Add more details if needed -->
    </div>

    <div class="contact-person">
        <h3>Rohit Agrawal</h3>
        <!-- Add more details, e.g., email, additional phone numbers, etc. -->
    </div>

    <p>Alternatively, you can use the form below:</p>

    <form action="#" method="post" class="contact-form">
        <label for="name">Your Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Your Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Your Message:</label>
        <textarea id="message" name="message" rows="4" required></textarea>

        <button type="submit">Submit</button>
    </form>
</section>
<main>
    <!-- Previous sections... -->

    <section class="emergency-section">
        <h2>Emergency Assistance</h2>
        <p>If you require immediate medical attention, please contact the ambulance service:</p>
        
        <div class="emergency-contact">
            <img src="/Users/shrivatskaushik/Desktop/img" alt="Ambulance Image">
            <p>Ambulance Service: 7451999010</p>
        </div>
    </section>

    <!-- Additional sections or content can be added here -->
</main>


CSS code

body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #2c3e50;
    color: #ecf0f1;
    padding: 1rem;
    text-align: center;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

nav li {
    display: inline;
    margin-right: 20px;
}

nav a {
    text-decoration: none;
    color: #ecf0f1;
    font-weight: bold;
}

main {
    padding: 20px;
}

footer {
    background-color: #34495e;
    color: #ecf0f1;
    text-align: center;
    padding: 1rem;
    position: fixed;
    bottom: 0;
    width: 100%;
}
/* ... Previous CSS code ... */

main {
    padding: 20px;
}

.welcome-section {
    text-align: center;
    margin: 50px 0;
}

.welcome-section h2 {
    color: #3498db;
}

.welcome-section p {
    color: #555;
    margin-bottom: 20px;
}

.cta-button {
    display: inline-block;
    background-color: #e74c3c;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.cta-button:hover {
    background-color: #c0392b;
}

/* ... Remaining CSS code ... */
/* ... Previous CSS code ... */

.articles-section {
    margin: 50px 0;
}

.articles-section h2 {
    color: #3498db;
}

.articles-section article {
    margin-bottom: 20px;
}

.articles-section h3 {
    color: #333;
}

.articles-section p {
    color: #555;
}

.articles-section a {
    color: #e74c3c;
    text-decoration: none;
    transition: color 0.3s ease;
}

.articles-section a:hover {
    color: #c0392b;
}

/* ... Remaining CSS code ... */
/* ... Previous CSS code ... */

.workouts-section {
    margin: 50px 0;
}

.workouts-section h2 {
    color: #3498db;
}

.workout {
    border: 1px solid #ddd;
    padding: 20px;
    border-radius: 5px;
    margin-bottom: 20px;
}

.workout h3 {
    color: #333;
}

.workout p {
    color: #555;
}

.workout a {
    display: inline-block;
    background-color: #2ecc71;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.workout a:hover {
    background-color: #27ae60;
}

/* ... Remaining CSS code ... */
/* ... Previous CSS code ... */

.emergency-section {
    margin: 50px 0;
}

.emergency-section h2 {
    color: #e74c3c;
}

.emergency-section p {
    color: #555;
    margin-bottom: 20px;
}

.emergency-contact {
    text-align: center;
}

.emergency-contact img {
    max-width: 100%;
    height: auto;
    margin-bottom: 10px;
}

/* ... Remaining CSS code ... */

javascript
// Add JavaScript functionality here
document.addEventListener('DOMContentLoaded', function () {
    // Your JavaScript code goes here
});
