bLugar Suits: Luxury Menswear E-Commerce Platform (WEDE5020 POE Submission)

Student Information

Student Name: Omolemo Tau

Student Number: ST10470186 (Placeholder - Please update)

Module Code: WEDE5020

Project Overview

This repository contains the single-file web application (index.html) for the Lugar Suits proposal, a luxury menswear boutique specialising in bespoke and off-the-rack formalwear. The project adheres to a Minimalist Luxury Aesthetic using a Black, Gold, and White color palette.

Compliance with Proposal B Requirements

Feature

Proposal Requirement

Implementation Status in index.html

Rubric Alignment

Aesthetic

Black, White, Gold, Slate Grey. Montserrat/Lato fonts.

Achieved using custom CSS/Tailwind classes and font imports.

CSS Styling & Typography

Catalogue

Shop page with categories (Suits, Shirts, Ties).

Implemented in the Shop Categories section with descriptive cards.

HTML Structure & Content

Booking System

Appointment booking form (Google Calendar API integration).

Implemented as a functional form (#booking-form) with JavaScript validation/confirmation.

Interactive Elements

Testimonials

Customer testimonials and style galleries.

Implemented in the Gallery/Testimonials section.

Sufficient Content Added

Live Chat

WhatsApp chat widget integration.

Implemented via a direct WhatsApp link in the Contact section.

Functionality

Interactive Map

Contact page with Google Maps.

Implemented with a Google Maps iframe placeholder in the Contact section.

Interactive Maps

Lightbox

Image gallery with lightbox functionality.

Implemented with a functional JavaScript Lightbox modal for gallery images.

Gallery Lightbox

SEO

SEO-optimised product descriptions, titles, and meta-tags.

Comprehensive meta tags and descriptive title are included in the <head>.

Meta-Tags & Title Tags

Responsiveness

Mobile-friendly browsing and shopping.

Fully responsive using extensive Tailwind CSS breakpoints (sm:, md:, lg:).

Responsive Design (10 Marks)

Technical Details

Languages and Frameworks Used

HTML5: Semantic structure for logical organization (<header>, <main>, <section>, <footer>).

CSS3 (via Tailwind CSS): Used for all styling, ensuring a clean, modern, and fully responsive layout across all screen sizes.

JavaScript (JS): Used for client-side interactivity, specifically for the Gallery Lightbox and the Appointment Booking Form logic.

File Structure and Code Quality

Single File Mandate: All code (HTML, CSS, JS) is contained within index.html.

Comments: Multiple descriptive comments are made regularly throughout the code to fully explain development, logic, and component sections.

Semantic HTML: Correct tags (e.g., <nav>, <section>, <h1>) are used for organization and accessibility.

Interactivity Implemented (Functional Elements)

Appointment Booking Form: The form prevents default submission, validates input presence, and displays a dynamic confirmation message using JavaScript when submitted successfully.

Gallery Lightbox: Clicking any image in the gallery triggers a JavaScript function that displays the image in a full-screen modal (lightbox). Clicking outside the image closes the modal.

Mobile Navigation: A button toggles the visibility of the mobile dropdown menu, enhancing user experience on touch devices.

Submission Checklist

File/Folder Structure: Local folder is correctly named (Lugar-Suits_ST10470186).

Webfile: index.html is complete and functional.

README: This file is detailed and resides in the root directory.

GitHub:

Initialize the repository.

Add and commit all files (index.html, README.md).

Push the local repository to your GitHub remote.

Git Commands for Submission:

# 1. Initialize (if not already done)
git init
# 2. Add files
git add .
# 3. Commit with a descriptive message
git commit -m "Final POE Submission - Lugar Suits Website and Documentation"
# 4. Push to your remote repository
git push -u origin main 


References:

Tailwind CSS Documentation (For responsive utility classes)

Google Maps Embed API (For map placeholder)

Google Fonts (Montserrat and Lato)

WhatsApp API Documentation (For live chat)