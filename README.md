<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MaxPoly - Your 5TB 3D Library Universe</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        .hero-bg {
            background: linear-gradient(to bottom, #1e3a8a, #3b82f6), url('https://via.placeholder.com/1920x1080?text=3D+Model+Preview');
            background-size: cover;
            background-position: center;
        }
        .fade-in {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.6s ease-out, transform 0.6s ease-out;
        }
        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }
        .countdown {
            font-size: 1.5rem;
            color: #ef4444;
            margin-top: 10px;
        }
    </style>
</head>
<body class="font-sans text-gray-800 bg-gray-100">
    <!-- Hero Section (Updated to highlight 30-day plan) -->
    <section class="hero-bg text-white py-20">
        <div class="container mx-auto px-4 text-center">
            <div class="flex justify-center items-center mb-6 fade-in">
                <img src="https://via.placeholder.com/48/1e3a8a/ffffff?text=MP" alt="MaxPoly Logo" class="w-12 h-12 mr-2">
                <h1 class="text-4xl font-bold">MAXPOLY</h1>
            </div>
            <h2 class="text-5xl md:text-6xl font-bold mb-4 fade-in">30-Day Access</h2>
            <p class="text-lg md:text-xl max-w-2xl mx-auto mb-6 fade-in">Access a 5TB+ Google Drive Library with Over 100,000 3D Models—Updated Regularly</p>
            <p class="text-3xl md:text-4xl font-bold mb-8 fade-in">$100 for 30 Days</p>
            <div class="flex justify-center gap-4 fade-in">
                <a href="https://www.paypal.com/ncp/payment/VG8HPDSTVY2NC" class="bg-blue-600 text-white px-6 py-3 rounded-lg hover:bg-blue-700 transition">Get 30-Day Access</a>
                <a href="#pricing" class="bg-transparent border border-white text-white px-6 py-3 rounded-lg hover:bg-white hover:text-gray-800 transition">See Lifetime Plan</a>
            </div>
            <p class="countdown fade-in" id="countdown">Special Offer Ends in: 3 days, 12:00:00</p>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12 fade-in">Why Choose MaxPoly?</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="text-center fade-in">
                    <svg class="w-12 h-12 mx-auto mb-4 text-blue-600" fill="currentColor" viewBox="0 0 20 20"><path d="M10 2a8 8 0 100 16 8 8 0 000-16zm0 14a6 6 0 110-12 6 6 0 010 12zm0-10a2 2 0 100 4 2 2 0 000-4z"/></svg>
                    <h3 class="text-xl font-semibold mb-2">Massive 3D Library</h3>
                    <p>Over 100,000 architecture models in a 5TB+ Google Drive folder.</p>
                </div>
                <div class="text-center fade-in">
                    <svg class="w-12 h-12 mx-auto mb-4 text-blue-600" fill="currentColor" viewBox="0 0 20 20"><path d="M10 2a8 8 0 100 16 8 8 0 000-16zm0 14a6 6 0 110-12 6 6 0 010 12zm0-10a2 2 0 100 4 2 2 0 000-4z"/></svg>
                    <h3 class="text-xl font-semibold mb-2">Constant Updates</h3>
                    <p>Regular additions and refinements by our expert team.</p>
                </div>
                <div class="text-center fade-in">
                    <svg class="w-12 h-12 mx-auto mb-4 text-blue-600" fill="currentColor" viewBox="0 0 20 20"><path d="M10 2a8 8 0 100 16 8 8 0 000-16zm0 14a6 6 0 110-12 6 6 0 010 12zm0-10a2 2 0 100 4 2 2 0 000-4z"/></svg>
                    <h3 class="text-xl font-semibold mb-2">Easy Navigation</h3>
                    <p>Meticulously categorized for quick access to the perfect model.</p>
                </div>
                <div class="text-center fade-in">
                    <svg class="w-12 h-12 mx-auto mb-4 text-blue-600" fill="currentColor" viewBox="0 0 20 20"><path d="M10 2a8 8 0 100 16 8 8 0 000-16zm0 14a6 6 0 110-12 6 6 0 010 12zm0-10a2 2 0 100 4 2 2 0 000-4z"/></svg>
                    <h3 class="text-xl font-semibold mb-2">Unbeatable Value</h3>
                    <p>$100 for 30 days for thousands of models—far less than competitors.</p>
                </div>
            </div>
            <div class="text-center mt-8 fade-in">
                <p class="text-gray-600">Trusted by <strong>5,000+ designers</strong> worldwide!</p>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="py-16 bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12 fade-in">What Our Users Say</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="text-center p-6 bg-white rounded-lg shadow fade-in">
                    <p class="mb-4">"MaxPoly has transformed my workflow with its vast library!"</p>
                    <p class="font-semibold">- John D., Architect</p>
                </div>
                <div class="text-center p-6 bg-white rounded-lg shadow fade-in">
                    <p class="mb-4">"The categorization makes finding models a breeze!"</p>
                    <p class="font-semibold">- Sarah K., 3D Designer</p>
                </div>
                <div class="text-center p-6 bg-white rounded-lg shadow fade-in">
                    <p class="mb-4">"Best $500 investment for my projects!"</p>
                    <p class="font-semibold">- Alex M., Freelancer</p>
                </div>
            </div>
        </div>
    </section>

    <!-- How It Works Section -->
    <section id="how-it-works" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12 fade-in">How It Works</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="text-center fade-in">
                    <div class="text-4xl font-bold text-blue-600 mb-4">1</div>
                    <h3 class="text-xl font-semibold mb-2">Subscribe</h3>
                    <p>Choose your plan and provide your Gmail address at checkout via PayPal.</p>
                </div>
                <div class="text-center fade-in">
                    <div class="text-4xl font-bold text-blue-600 mb-4">2</div>
                    <h3 class="text-xl font-semibold mb-2">Access</h3>
                    <p>Receive shared access to our 5TB+ Google Drive library instantly.</p>
                </div>
                <div class="text-center fade-in">
                    <div class="text-4xl font-bold text-blue-600 mb-4">3</div>
                    <h3 class="text-xl font-semibold mb-2">Manage</h3>
                    <p>Use the free Connecter app to organize your resources on any device.</p>
                </div>
            </div>
            <p class="text-center mt-8 text-gray-600 fade-in">Cancel anytime—access is revoked until you renew, no hassle.</p>
            <div class="text-center mt-8 fade-in">
                <a href="https://www.paypal.com/ncp/payment/VG8HPDSTVY2NC" class="bg-blue-600 text-white px-6 py-3 rounded-lg hover:bg-blue-700 transition">Get Started</a>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing" class="py-16 bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12 fade-in">Choose Your Plan</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-4xl mx-auto">
                <div class="border rounded-lg p-6 text-center shadow-lg bg-blue-50 fade-in">
                    <h3 class="text-2xl font-semibold mb-4">30-Day Access</h3>
                    <p class="text-4xl font-bold mb-4">$100<span class="text-lg">/30 days</span></p>
                    <p class="mb-6">Access a 5TB+ library with 100,000+ models, updated regularly. Revoked if canceled.</p>
                    <a href="https://www.paypal.com/ncp/payment/VG8HPDSTVY2NC" class="bg-blue-600 text-white px-6 py-3 rounded-lg hover:bg-blue-700 transition">Subscribe for 30 Days</a>
                </div>
                <div class="border rounded-lg p-6 text-center shadow-lg fade-in">
                    <h3 class="text-2xl font-semibold mb-4">Lifetime Access</h3>
                    <p class="text-4xl font-bold mb-4">$500<span class="text-lg">/one-time</span></p>
                    <p class="mb-6">Permanent access to the 5TB+ library with all updates included.</p>
                    <a href="https://www.paypal.com/ncp/payment/VG8HPDSTVY2NC" class="bg-blue-600 text-white px-6 py-3 rounded-lg hover:bg-blue-700 transition">Get Lifetime Access</a>
                </div>
            </div>
            <p class="text-center mt-8 text-gray-600 fade-in">Provide your Gmail address at checkout to receive Google Drive access.</p>
            <div class="text-center mt-6 fade-in">
                <p class="text-green-600">Secure Payment via PayPal | 30-Day Money-Back Guarantee</p>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section id="faq" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12 fade-in">Frequently Asked Questions</h2>
            <div class="max-w-2xl mx-auto space-y-4">
                <div class="fade-in">
                    <h3 class="text-xl font-semibold">How do I cancel my subscription?</h3>
                    <p>Simply stop your PayPal subscription. Access will be revoked until you renew.</p>
                </div>
                <div class="fade-in">
                    <h3 class="text-xl font-semibold">Is the library updated regularly?</h3>
                    <p>Yes, our team adds and refines models continuously to keep it fresh.</p>
                </div>
                <div class="fade-in">
                    <h3 class="text-xl font-semibold">What if I need support?</h3>
                    <p>Contact us at igodezin@gmail.com. We respond within 24-48 hours.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-gray-100">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-6 fade-in">Get in Touch</h2>
            <p class="mb-4 fade-in">Email: <a href="mailto:igodezin@gmail.com" class="underline">igodezin@gmail.com</a></p>
            <p class="mb-4 fade-in">Phone: +1-800-555-1234 (Support Hours: 9 AM - 5 PM EST)</p>
            <div class="flex justify-center gap-4 fade-in">
                <a href="#" class="text-blue-600 hover:underline">Facebook</a>
                <a href="#" class="text-blue-600 hover:underline">Instagram</a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-4 text-center">
            <p class="mb-4">Support: <a href="mailto:igodezin@gmail.com" class="underline">igodezin@gmail.com</a> | Phone: +1-800-555-1234</p>
            <p>© 2025 MaxPoly. All rights reserved.</p>
        </div>
    </footer>

    <!-- JavaScript for Fade-In Animations and Countdown -->
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const elements = document.querySelectorAll('.fade-in');
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('visible');
                        observer.unobserve(entry.target);
                    }
                });
            }, { threshold: 0.1 });
            elements.forEach(element => observer.observe(element));

            // Countdown Timer
            const countdown = document.getElementById('countdown');
            const countDownDate = new Date().getTime() + (3 * 24 * 60 * 60 * 1000); // 3 days from now
            const x = setInterval(() => {
                const now = new Date().getTime();
                const distance = countDownDate - now;
                const days = Math.floor(distance / (1000 * 60 * 60 * 24));
                const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
                const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
                const seconds = Math.floor((distance % (1000 * 60)) / 1000);
                countdown.innerHTML = `Special Offer Ends in: ${days}d ${hours}h ${minutes}m ${seconds}s`;
                if (distance < 0) {
                    clearInterval(x);
                    countdown.innerHTML = "Offer Ended";
                }
            }, 1000);
        });
    </script>
</body>
</html>
