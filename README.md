📄 About Me Page – Tailwind CSS (Line-by-Line Explanation)

This README.md explains the structure and utility class choices used in the about.html file for building a clean, responsive About Me page using Tailwind CSS.
✅ 1. HTML Boilerplate

<!DOCTYPE html>

Purpose:
Declares the document type as HTML5. Always needed at the top of every HTML document.

<html lang="en">

Why:
Specifies that the primary language of the document is English. Helps with SEO and accessibility tools like screen readers.
✅ 2. Head Section

<head>
  <meta charset="UTF-8">

Why:
Ensures that the document uses UTF-8 encoding, which supports a wide range of characters, including emojis.

  <meta name="viewport" content="width=device-width, initial-scale=1">

Why:
Makes the layout responsive by scaling it correctly on mobile devices. Essential for mobile-first development.

  <title>About Me - Shibiraj</title>

Why:
Sets the page title visible in the browser tab or search results.

  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@3.4.1/dist/tailwind.min.css" rel="stylesheet">

Why:
Imports the Tailwind CSS framework using a CDN, so no local setup or build process is needed. Great for learning or quick prototyping.
✅ 3. Body Tag with Global Styles

<body class="bg-gray-100 text-gray-800 font-sans">

Why:

    bg-gray-100: Adds a soft light-gray background to the whole page (more modern than plain white).

    text-gray-800: Sets a slightly muted black for better readability.

    font-sans: Applies a modern sans-serif font family across all text.

✅ 4. Hero Section (Profile & CTA)

<section class="bg-white shadow-md rounded-b-3xl p-6 md:p-12 text-center">

Why:

    bg-white: A clean background for contrast.

    shadow-md: Adds a subtle shadow to elevate the card.

    rounded-b-3xl: Rounds only the bottom edges, giving it a unique look.

    p-6 md:p-12: Responsive padding; more padding on medium+ screens.

    text-center: Centers all inner content.

<img src="..." class="mx-auto rounded-full w-32 h-32 border-4 border-indigo-500 mb-4">

Why:

    mx-auto: Centers image horizontally.

    rounded-full: Makes the image circular.

    w-32 h-32: Controls size (128px).

    border-4 border-indigo-500: Stylish colored border.

<h1 class="text-3xl md:text-5xl font-bold text-indigo-600 mb-2">Shibiraj R</h1>

Why:

    Large, bold heading that grows with screen size.

    Indigo color adds branding and visual identity.

<p class="text-lg md:text-xl text-gray-600 mb-4">Full Stack Developer & AI Enthusiast</p>

Why:

    Subtitle with softer gray to not overpower the heading.

    Slightly larger font for readability.

<div class="flex justify-center gap-4">
  <a href="#" class="bg-indigo-600 text-white px-5 py-2 rounded-xl hover:bg-indigo-700 transition">LinkedIn</a>
  <a href="#" class="border border-indigo-600 text-indigo-600 px-5 py-2 rounded-xl hover:bg-indigo-100 transition">GitHub</a>
</div>

Why:

    flex justify-center gap-4: Aligns buttons side by side and adds spacing.

    Different styles for buttons (filled vs outlined) improve visual hierarchy and accessibility.

✅ 5. About Me Section

<section class="max-w-4xl mx-auto mt-10 px-6">
  <div class="bg-white p-6 md:p-10 rounded-3xl shadow-lg">

Why:

    max-w-4xl: Restricts width for better reading.

    mx-auto: Centers the container.

    mt-10: Adds vertical space from previous section.

    rounded-3xl shadow-lg: Modern card look.

<h2 class="text-2xl md:text-3xl font-bold text-indigo-700 mb-4">👋 About Me</h2>

Why:

    Proper heading structure (h2) for section title.

    Uses emoji to add personality.

    Responsive font size and indigo accent color.

<p class="text-gray-700 text-base md:text-lg leading-relaxed">

Why:

    text-gray-700: Slightly muted for body text.

    text-base md:text-lg: Scales with screen size.

    leading-relaxed: Improves line spacing for readability.

✅ 6. Skills Section

<section class="max-w-5xl mx-auto mt-10 px-6">
  <h2 class="text-2xl font-bold text-indigo-700 mb-4">🚀 Skills</h2>
  <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 gap-4">

Why:

    Responsive layout: 2 columns on mobile, 3 on tablet, 4 on desktop.

    gap-4: Adds uniform spacing between skills.

<span class="bg-white py-3 px-4 rounded-xl text-center shadow hover:scale-105 transition">Tailwind CSS</span>

Why:

    White card with padding, rounded edges, and subtle shadow.

    hover:scale-105 transition: Adds hover animation for interactivity.

✅ 7. Timeline / Experience

<ul class="space-y-4 border-l-4 border-indigo-500 pl-4">

Why:

    border-l-4: Left-side line creates a timeline effect.

    space-y-4: Adds vertical spacing between list items.

    pl-4: Padding to separate text from the border.

<div class="text-sm text-gray-500">2022 - Present</div>
<div class="font-semibold text-gray-800">Freelancer & Tech Mentor</div>

Why:

    Dates are in small, muted text.

    Roles are highlighted in darker, bolder text.

✅ 8. Quote Section

<blockquote class="text-xl italic text-gray-600 border-l-4 border-indigo-500 pl-4">

Why:

    Italicized and styled like a classic blockquote.

    Indigo left border gives emphasis without needing images or icons.

✅ 9. Footer

<footer class="text-center mt-16 mb-4 text-sm text-gray-500">
  © 2025 Shibiraj R — Built with ❤️ and Tailwind CSS
</footer>

Why:

    Small text, centered, soft gray.

    Final branding or sign-off line — minimal but elegant.

📌 Summary

This code teaches:

    How to use Tailwind utility classes to build a structured page.

    Why we use responsive, modern layouts with visual hierarchy.

    That everything is intentional — from padding to font choices.
