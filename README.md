<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Speedy Rides - Driver Dashboard</title>
    <link rel="stylesheet" href="driver.css">
</head>
<body>

    <!-- Navigation Bar -->
    <nav class="navbar">
        
        <ul class="nav-items">
            <li><a href="dashboard.html">Dashboard</a></li>
            <li><a href="earnings.html">Earnings</a></li>
            <li><a href="ride-history.html">Ride History</a></li>
            <li><a href="safety.html">Safety Tips</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>

    <!-- Driver Introduction Section -->
    <section class="intro">
        <h1>Welcome, Future Speedy Driver!</h1>
        <p>Join the fastest-growing ride service platform and earn on your terms. Work at your own schedule and be your own boss!</p>
        <button onclick="window.location.href='driver-signup.html'">Sign Up to Drive</button>
    </section>

    <!-- Driver Dashboard Section -->
    <section class="dashboard">
        <h2>Your Dashboard</h2>
        <div class="stats">
            <div class="stat-item">
                <h3>Total Rides</h3>
                <p>15</p>
            </div>
            <div class="stat-item">
                <h3>Total Earnings</h3>
                <p>₹15,000</p>
            </div>
            <div class="stat-item">
                <h3>Driver Rating</h3>
                <p>4.8/5</p>
            </div>
        </div>
        
        <h3>Upcoming Rides</h3>
        <ul class="upcoming-rides">
            <li>
                <span>Pickup: 10:30 AM - Location A</span>
                <button class="accept-btn">Accept</button>
                <button class="decline-btn">Decline</button>
            </li>
            <li>
                <span>Pickup: 11:00 AM - Location B</span>
                <button class="accept-btn">Accept</button>
                <button class="decline-btn">Decline</button>
            </li>
        </ul>
    </section>

    <!-- Driver Incentives Section -->
    <section class="incentives">
        <h2>Driver Incentives</h2>
        <p>Earn up to ₹5,000 extra every month with our incentives program. Complete 50 rides and get ₹1,000 bonus!</p>
        <div class="incentive-card">
            <h3>50 Rides Completed Bonus</h3>
            <p>Earn ₹1,000 after completing 50 rides this month!</p>
            <button class="btn-incentive">Check Eligibility</button>
        </div>
        <div class="incentive-card">
            <h3>Fuel Reimbursement</h3>
            <p>Get fuel reimbursements on long-distance rides.</p>
            <button class="btn-incentive">Apply Now</button>
        </div>
    </section>

    <!-- Get Verified by Face Recognition Section -->
    <section class="verification">
        <h2>Get Verified by Face Recognition</h2>
        <p>Ensure the safety and security of our platform by completing face recognition verification. This ensures your identity and gives you access to exclusive benefits.</p>
        <button class="verify-btn">Verify Now</button>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Speedy Rides. All rights reserved.</p>
        <a href="terms.html">Terms & Conditions</a> | <a href="privacy.html">Privacy Policy</a>
    </footer>

</body>
</html>
