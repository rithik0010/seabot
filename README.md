Project Description: SEACET AI Assistant Chatbot
Project Overview

The SEACET AI Assistant is a web-based chatbot integrated into the SEA College of Engineering & Technology website, designed to provide instant, accurate, and user-friendly responses to queries about the institution. Built with HTML, CSS, and JavaScript, the chatbot leverages a comprehensive knowledge base to assist prospective students, current students, and other stakeholders with information about courses, admissions, fees, departments, facilities, placements, events, and contact details. The project aims to enhance user experience, streamline information access, and showcase the college’s commitment to technological innovation.

Key Features

Interactive Chat Interface:
A clean, responsive UI with a chat history displaying user and AI messages.
AI messages are styled in blue (#e3f2fd), and user messages in orange (#f97316), aligning with the website’s color scheme.
Supports formatted responses, including lists and tables, for clear presentation of complex information (e.g., course details, fee structures).
Comprehensive Knowledge Base:
Contains detailed information about SEACET, sourced from https://seacet.edu.in, covering:
About: College history, vision, mission, affiliation, and accreditation.
Courses: Undergraduate (B.E.), postgraduate (M.E.), and diploma programs with duration and intake.
Departments: Faculty, labs, specializations, and achievements for CSE, ECE, EEE, Mechanical, and Civil Engineering.
Admissions: Eligibility, process, and important dates.
Fees: Tuition, hostel, and scholarship details.
Facilities: Academic, hostel, sports, and other amenities.
Placements: Statistics, top recruiters, packages, and training programs.
Events: Technical, cultural, and other activities.
Contact: Address, phone, email, website, and social media links.
Word Prediction System:
Dynamically suggests up to five relevant questions as users type, based on a predefined database of triggers (e.g., “course” suggests “What engineering courses are offered?”).
Enhances usability by helping users formulate queries quickly.
Seamless Website Integration:
Integrated into the SEACET website as a dedicated chatbot.html page, accessible via the navigation bar.
Matches the website’s design with the Poppins font, blue/orange color scheme (#1e3a8a, #f97316), and fade-in animations.
Uses Bootstrap 5.3 and Tailwind CSS for responsive layout, ensuring compatibility with mobile, tablet, and desktop devices.
User-Friendly Functionality:
Supports input via a textarea with a “Send” button or Enter key.
Displays a loading indicator (spinner) during response generation, simulating AI processing with a random delay (800–1600ms).
Automatically scrolls to the latest message in the chat history.
Hides word predictions when clicking outside the input area or after selecting a suggestion.
Accessibility and Performance:
Uses semantic HTML and aria-label for screen reader compatibility (e.g., navbar toggler).
Optimized with minified CDN resources (Bootstrap, Tailwind, Font Awesome) and custom scrollbar styling.
Includes .hintrc configuration to disable no-inline-styles linting, ensuring development flexibility.
Technical Details

Frontend:
HTML: Structured with Bootstrap’s grid system and semantic elements.
CSS: Custom styles in chatbot.html (embedded <style> tag) for the chat interface, with Tailwind utilities for layout and Bootstrap for navigation/footer.
JavaScript: Handles chatbot logic, including initialization, response generation, word predictions, and event listeners for user interactions.
Dependencies:
Bootstrap 5.3 (CSS/JS) for navigation and responsive design.
Tailwind CSS 2.2.19 for utility-first styling.
Font Awesome 6.4.0 for icons (e.g., send button).
Google Fonts (Poppins) for typography.
Linting: Configured with .hintrc to support inline styles, aligning with development needs.
File Structure:
chatbot.html: Main chatbot page with HTML, CSS, and JavaScript.
.hintrc: Linting configuration.
Integrated with the main website’s index.html via navigation link.
Purpose and Impact

The SEACET AI Assistant serves as a virtual guide, reducing the need for manual inquiries and improving access to critical information. It caters to diverse users, including prospective students seeking admission details, current students exploring facilities or events, and recruiters interested in placement statistics. By providing instant responses, the chatbot enhances user engagement, supports the college’s digital presence, and demonstrates its adoption of AI-driven solutions in education.

Future Enhancements

Floating Widget: Implement a toggleable chat widget across all website pages for seamless access.
Backend Integration: Connect to a server (e.g., Node.js, Flask) or AI API (e.g., Dialogflow) for dynamic responses and natural language processing.
Analytics: Track user queries with Google Analytics to identify common questions and optimize the knowledge base.
Multilingual Support: Add support for regional languages (e.g., Kannada, Hindi) to cater to a broader audience.
Voice Input: Integrate speech-to-text for hands-free operation, enhancing accessibility.
Conclusion

The SEACET AI Assistant is a robust, user-centric tool that elevates the SEA College of Engineering & Technology website by providing an interactive and informative experience. Its integration with the website’s design, comprehensive knowledge base, and intuitive features make it a valuable asset for stakeholders, reflecting the institution’s commitment to excellence and innovation in technical education.
