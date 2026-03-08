# Kartikeya-Rindani-Quiz-Scorer
🏛️ Kartikeya Rindani Quiz Arena

The digital brain behind the prestigious Kartikeya Rindani Memorial Competitions at MODERN COLLEGE OF ARTS SCIENCE AND COMMERCE (Autonomous), Shivajinagar, Pune 05.

This system transforms the traditional quiz scoreboard into a high-octane "Digital Battlefield," blending ancient scholarly themes with a modern command-center interface optimized for auditorium projectors.

🎯 Core Concept

Five legendary teams compete through six intellectual battlegrounds. The system handles all complex calculations, including time-sensitive rounds and strategic point scaling, allowing judges and the audience to focus purely on the competition.

✨ Key Features

⚔️ Advanced Scoring Engine

Dynamic Passing Logic: Point values automatically scale down as questions are passed (10 → 7 → 5 → 3 → 1).

Think and Guess Sub-Structure: Support for 3 sub-questions per team turn (5 marks each).

Rapid Recall Timer: A 60-second pressure round with a high-visibility timer that automatically stops upon an incorrect answer.

Penalty Management: Automatic deduction logic for specific rounds to maintain competitive tension.

🎨 Premium Visual Identity

Dual-Theme Engine: Switch between Vedic Night (Deep Navy & Gold) and Parchment Day (Aged Paper & Terracotta) for different lighting environments.

Projector Optimized: Ultra-large leaderboard occupying 60% of the screen with pure white high-contrast text for round names.

Institutional Branding: Integrated KRE (Modern College) logos and official color schemes.

Olympic Finale: A dramatic medal ceremony screen for Gold, Silver, and Bronze winners.

📱 Responsive Architecture

Single-File Portability: Runs purely as a standalone index.html using React via CDN—no installation or Node.js required.

Device Aware: Features a specialized "Judging Dashboard" for mobile/tablet use while keeping a dominant leaderboard for the main projector display.

🛠️ Technology Stack

Frontend: React (v18)

Styling: Tailwind CSS

Icons: Lucide React

Typography: Cinzel (Ancient titles) & Plus Jakarta Sans (Modern UI)

🚀 Deployment

Since this project is a single-file application, it is perfectly suited for GitHub Pages.

Upload index.html to your repository.

Enable GitHub Pages in the repository settings.

Your Arena is live!

⚙️ Configuration

To customize the visuals for your specific event, edit the configuration block at the top of the <script> tag in index.html:

const COLLEGE_LOGO_URL = "your_logo.png";
const TEAMS = [
    { id: 'takshshila', name: 'TAKSHASHILA', banner: "banner1.jpg" },
    // ...
];


Developed for the Kartikeya Rindani Memorial Program.
Modern College of Arts Science and Commerce, Shivajinagar, Pune 05
