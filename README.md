Threat Arena: Security Principles Lab
Deployment Status: GitHub Pages

Platform Compatibility: TryHackMe Static Site

Organization: GDG Maseno

Project Overview
Threat Arena: Security Principles Lab is an interactive, high-fidelity cybersecurity training module designed for CTF (Capture The Flag) events. This lab challenges participants to validate their understanding of fundamental security frameworks through a tactical drag-and-drop interface.

This module is specifically engineered to be embedded as a Static Site within TryHackMe rooms. It focuses on the primary pillars of information security, requiring participants to match definitions to their correct categories to unlock a system-generated flag.

Key Learning Objectives
The CIA Triad: Confidentiality, Integrity and Availability.

The Parkerian Hexad: Expanding foundations with Utility, Possession and Authenticity.

Features
Strict Validation Logic: The arena utilizes real-time verification to reject incorrect tactical placements with visual feedback, preventing brute-force guesswork.

Professional UI: Styled with a dark-mode aesthetic consistent with industry-standard platforms such as TryHackMe and HackTheBox.

Anti-Cheat Mechanisms: The flag is secured via Base64 obfuscation and is only rendered in the DOM after the logic validates all six security pillars.

Responsive Design: Optimized for desktop and mobile viewing, specifically for split-screen deployment.

Technical Stack
Frontend: HTML5, CSS3 (Grid & Flexbox implementation).

Logic: Vanilla JavaScript (DOM Manipulation & Drag-and-Drop API).

Authentication Simulation: Base64 encoding/decoding for secure flag delivery.

Installation and Deployment
Clone the Repository
Bash
git clone https://github.com/jomboi8/ThreatArena.git
Local Preview
To view the lab locally, open the index.html file in any modern web browser.

GitHub Pages Deployment
Push the source code to your GitHub repository.

Navigate to Settings > Pages.

Select the main branch and /root folder as the source.

The lab will be accessible at: https://jomboi8.github.io/ThreatArena/.

Usage in TryHackMe
To integrate this module into a TryHackMe room:

Create a task and set the Task Type to Static Site.

Input the deployment URL into the Static Site URL field.

Participants can then initialize the module via the View Site button to open the Arena in a side-by-side panel.
