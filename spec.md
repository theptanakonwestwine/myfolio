Software Requirement Specification (SRS)

Project: One-Page Portfolio Website for Grade 10 Language Program Application

1. Overview & Objectives

Target User: Grade 9 student (ม.3) applying for Grade 10 (ม.4) Special Language Programs (e.g., English-Chinese, English-Japanese, English-French).

Target Audience: High school admission officers, language department teachers, and evaluators.

Primary Goal: Provide a responsive, modern, clean, and interactive one-page digital portfolio highlighting the student's language skills, academic achievements, extracurricular activities, and passion for foreign languages.

2. System Architecture & Tech Stack

Architecture: Single-Page Application (SPA) / One-Page Static Site.

Core Technologies:

HTML5: Semantic markup structure.

CSS3 / Tailwind CSS: Responsive layout, utility-first styling, custom color palette.

JavaScript (Vanilla JS): Mobile menu toggle, dynamic tab filtering for activities, smooth scroll navigation.

Icons & Fonts: Font Awesome / Lucide Icons, Google Fonts (Kanit/Sarabun for Thai, Poppins/Inter for English).

3. Detailed Component Specifications (Sections)

3.1 Sticky Navigation Bar (<header>)

Brand/Logo: Student's Initials or Name (e.g., Ploypailin.P).

Navigation Links: About, Skills, Activities, Language Showcase, Contact.

Mobile View: Hamburger menu toggle button with smooth slide-out or dropdown menu.

Behavior: Sticky positioning (position: sticky / top-0), smooth scrolling anchor links (scroll-behavior: smooth).

3.2 Hero Section (<section id="hero">)

Content:

High-quality profile picture (Student uniform or formal outfit with a friendly smile).

Welcoming headline: "Welcome to My Academic Journey".

Full Name, Nickname, and Target Track (e.g., "Applying for English-Chinese Program").

Actions (CTAs):

Primary Button: "Explore Portfolio" (Scrolls to #about).

Secondary Button: "Download Full PDF Portfolio" (Direct file link).

3.3 About Me & Language Skills (<section id="about">)

Personal Profile: Short biography, current school, GPAX (Cumulative Grade Point Average).

Motto / Quote: Inspirational quote in a target foreign language with Thai translation.

Language Proficiency Meter:

Visual progress bars or badge chips indicating proficiency levels.

Example: Thai (Native), English (Intermediate / B1-B2), Chinese (Basic / HSK 2-3).

3.4 Activities & Certificates (<section id="activities">)

Tab Filter System (Interactive):

Buttons: All, Language & Academic, Volunteering & Competitions.

Grid Layout: Card-based display (3 columns on desktop, 1 column on mobile).

Card Components:

Activity cover image.

Title & Date of completion.

Short description emphasizing key takeaways or learned skills.

Certificate preview modal or direct light-box link.

3.5 Language Showcase (<section id="showcase">)

Video Intro: Embedded YouTube/Drive video player featuring a 1-2 minute self-introduction speech in the target foreign language.

Writing Sample / Creative Work: Accordion or card displaying a short essay, poem, or translated excerpt written by the student.

3.6 Contact Section (<footer id="contact">)

Contact Info Cards: Email, Phone Number, Line ID, Emergency Contact.

Simple Contact Form: Name, Email, Message, and Submit button (Client-side validated).

Footer Copyright: Rights reserved notice & social media links.

4. Non-Functional Requirements & Constraints

4.1 Responsive Web Design (RWD)

Breakpoints:

Mobile: < 640px (Single column, hamburger navigation).

Tablet: 640px - 1024px (Dual column grid).

Desktop: > 1024px (Full 3-column layouts, expanded navbar).

4.2 Performance & Accessibility

Page Load Speed: All assets optimized (Images compressed to .webp, lazy loading enabled for below-the-fold images).

Accessibility (a11y): Semantic HTML tags (<nav>, <main>, <section>, <footer>), alt tags for all images, high contrast color ratios.

4.3 Design Guidelines (Look & Feel)

Color Palette:

Primary Accent: Soft Royal Blue (#2563EB) or Target School Color.

Secondary Accent: Warm Amber/Gold (#F59E0B).

Background: Clean Off-White (#F8FAFC).

Text: Slate Gray (#1E293B).

Typography: Modern, easy-to-read sans-serif fonts.