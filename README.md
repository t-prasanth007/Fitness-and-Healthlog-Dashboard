### Fitness HealthLog Pro 🏋️‍♂️🥗

A frontend web application designed to help users log daily health metrics, track water intake, set fitness targets, and manage nutrition goals. This project forms part of the 3-month internship curriculum. 

### 📂 Project Structure

The project components are organized as follows: 

text

├── login_page.html             # Secure-facing user portal & entry point<br>
├── health.html                 # Main user dashboard for daily telemetry<br>
├── goals.html                  # Interface for target setting & benchmarks<br>
├── goals_example.html          # Reference layout for pre-configured goals<br>
├── heallthlog.js               # Application logic, data retention, & state management<br>
├── fitness.css                 # Base design system and layout configuration<br>
├── alignment_screen.css        # Adaptive viewports and container scaling properties<br>
├── nutrition.css               # Specific styling for macro/diet logging modules<br>
└── assets/                     # Graphic resources (health.avif, logos, etc.)

### ✨ Key Features

* **Session Persistent Login:** Simple onboarding form that stores the user session locally across pages.
* **Dynamic Health Dashboard:** Displays custom greetings, real-time tracking metrics, and goal compliance.
* **Metric Trackers:** Interactive logging modules for daily hydration (ml targets) and active tasks.
* **Goal Setting Interface:** Dedicated section for initializing, modifying, and updating fitness benchmarks.
* **Modular Style Architecture:** Separated style sheets (fitness.css, nutrition.css, alignment_screen.css) ensuring clean code isolation and easy UI maintenance.

### 🛠️ Tech Stack & Concepts Used

* **HTML5:** Semantic structure ensuring clear layout boundaries between the navigation, dashboard, and interactive forms.
* **CSS3 Grid & Flexbox:** Implemented responsive design across viewports (fitness.css) to align metrics panels beautifully.

## 📸 Screenshot


### 🚀 How to Run the Project Locally

1. Clone or download this project directory to your local environment.
2. Locate the root folder fitness healthlog pro...
3. Launch the application by opening **login_page.html** in any modern web browser (Chrome, Edge, Safari, Firefox).
4. Enter your profile name to initialize your state session and navigate directly to your live dashboard.

### 📈 Future Enhancements

* Integrate chart libraries (like Chart.js) to display progress over weekly/monthly timelines.
* Expand the nutrition.css framework into a comprehensive breakfast, lunch, and dinner calorie counter.
* Add dark mode toggles via CSS variables.
