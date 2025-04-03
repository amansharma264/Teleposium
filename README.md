# Teleposium



<section id="events" class="section">
            <h2>Our Events</h2>
            <div class="events-grid">
                <div class="event-card">
                    <h3>CIRCUIT DEBUGGING</h3>
                    <p> Identify and fix errors in electronic circuits to test your troubleshooting skills.</p>
                    <div class="event-actions">
                    <a href="#register" class="event-btn register-btn">Register Now</a>
                    <a href="./events/circuitdebugging/index.html" class="event-btn rules-btn">Rule Book</a>
                </div>
                </div>
                
                <div class="event-card">
                    <h3>ROBOTHON</h3>
                    <p> Build and program robots to complete challenging tasks in a competitive setting.</p>
                    <div class="event-actions">
                    <a href="#register" class="event-btn register-btn">Register Now</a>
                    <a href="./events/robothon/index.html" class="event-btn rules-btn">Rule Book</a>
                </div>
                </div>
                
                <div class="event-card">
                    <h3>TECHNICAL QUIZ</h3>
                    <p>Showcase your technical knowledge with rapid-fire questions on engineering and technology.</p>
                    <div class="event-actions">
                    <a href="#register" class="event-btn register-btn">Register Now</a>
                    <a href="./events/TechnicalQuiz/index.html" class="event-btn rules-btn">Rule Book</a>
                </div>
                </div>
                
                <div class="event-card">
                    <h3>DIGITAL ADVENTURE</h3>
                    <p>Solve puzzles and challenges in a virtual environment using logical and analytical thinking.</p>
                    <div class="event-actions">
                    <a href="#register" class="event-btn register-btn">Register Now</a>
                    <a href="./events/DigitalAdventure/index.html" class="event-btn rules-btn">Rule Book</a>
                </div>
                </div>
                
                <div class="event-card">
                    <h3>PAPER PRESENTATION</h3>
                    <p>Present innovative research and ideas on technical topics to impress a panel of judges.</p>
                    <div class="event-actions">
                    <a href="#register" class="event-btn register-btn">Register Now</a>
                    <a href="./events/PaperPresentation/index.html" class="event-btn rules-btn">Rule Book</a>
                </div>
                </div>
                
                <div class="event-card">
                    <h3>TREASURE HUNT</h3>
                    <p>Decode clues and navigate through multiple rounds to uncover the final prize.</p>
                    <div class="event-actions">
                    <a href="#register" class="event-btn register-btn">Register Now</a>
                    <a href="./events/TreasureHunt/index.html" class="event-btn rules-btn">Rule Book</a>
                </div>
                </div>
                
                <div class="event-card">
                    <h3>WEB/APP DEV.</h3>
                    <p>Design and develop a functional and creative web or mobile application within a given timeframe.</p>
                    <div class="event-actions">
                    <a href="#register" class="event-btn register-btn">Register Now</a>
                    <a href="./events/Web&AppDev/index.html" class="event-btn rules-btn">Rule Book</a>
                </div>
                </div>
                
                <div class="event-card">
                    <h3>MINI PROJECT</h3>
                    <p>Build a working prototype or project that demonstrates engineering skills and innovation.</p>
                    <div class="event-actions">
                    <a href="#register" class="event-btn register-btn">Register Now</a>
                    <a href="./events/MiniProject/index.html" class="event-btn rules-btn">Rule Book</a>
                </div>
                </div>
                
                <div class="event-card">
                    <h3>JAM</h3>
                    <p>Speak fluently and spontaneously on a given topic for one minute without hesitation.</p>
                    <div class="event-actions">
                    <a href="#register" class="event-btn register-btn">Register Now</a>
                    <a href="./events/Jam/index.html" class="event-btn rules-btn">Rule Book</a>
                </div>
                </div>
                
                <div class="event-card">
                    <h3>TURNCOATS</h3>
                    <p>Debate from both sides of an argument, switching perspectives dynamically during the discussion.</p>
                    <div class="event-actions">
                    <a href="#register" class="event-btn register-btn">Register Now</a>
                    <a href="./events/TurnCoat/index.html" class="event-btn rules-btn">Rule Book</a>
                </div>
                </div>
                
            </div>
        </section>




/* Events Section */
.events-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
    max-width: 1200px;
    margin: 0 auto;
}

.event-card {
    background: rgba(255, 255, 255, 0.1);
    padding: 30px;
    border-radius: 15px;
    transition: all 0.3s ease;
    border: 1px solid rgba(255, 0, 0, 0.3);
}

.event-card:hover {
    transform: translateY(-10px);
    background: rgba(255, 0, 0, 0.1);
    box-shadow: 0 10px 30px rgba(255, 0, 0, 0.2);
}

.event-card h3 {
    color: #ff0000;
    margin-bottom: 15px;
    font-size: 1.5rem;
}

.contact-card{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
    max-width: 1200px;
    margin: 0 auto;
}

.event-card p {
    margin-bottom: 20px;
    flex-grow: 1;
}

.event-actions {
    display: flex;
    gap: 15px;
    margin-top: auto;
}

.event-btn {
    display: inline-block;
    padding: 10px 15px;
    border-radius: 50px;
    font-weight: 600;
    text-decoration: none;
    transition: all 0.3s ease;
    text-align: center;
    flex: 1;
    font-size: 0.9rem;
}

.register-btn {
    background: #ff0000;
    color: white;
    border: 2px solid #ff0000;
}

.register-btn:hover {
    background: rgba(255, 0, 0, 0.2);
    color: white;
    transform: translateY(-3px);
    box-shadow: 0 5px 15px rgba(255, 0, 0, 0.4);
}

.rules-btn {
    background: transparent;
    color: white;
    border: 2px solid white;
}

.rules-btn:hover {
    background: rgba(255, 255, 255, 0.1);
    transform: translateY(-3px);
    box-shadow: 0 4px 10px rgba(255, 255, 255, 0.2);
}

