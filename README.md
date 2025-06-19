# Bytefix Homepage

This repository contains the HTML code for the Bytefix organization's homepage, designed to be a clean, modern, and dark-themed website with blue/purple highlights. Bytefix is a non-profit organization focused on helping people fix tech issues by connecting them to volunteers and building computer literacy in communities.

## Description

The homepage provides key information about Bytefix, including:

* **What We Are About:** Details the organization's mission to bridge the digital divide through accessible tech support and computer literacy initiatives.

* **Our Goals:** Outlines specific, measurable metrics Bytefix aims to achieve, such as the number of fixes per year, workshop attendees per month, and new city expansions.

* **Where We Are Available:** Lists current operating locations and mentions virtual support options, along with a call to action for expanding reach.

* **Contact Information:** A simple section for users to get in touch.

## Features

* **Responsive Design:** Built with Tailwind CSS, ensuring optimal viewing and functionality across various devices (mobile, tablet, desktop).

* **Dark Theme:** A sleek and modern dark background color scheme (`#1A1A2E`, `#2D2D44`, etc.) provides a sophisticated look.

* **Blue/Purple Highlights:** Strategic use of blue/purple accent colors (`#8D8DAA`, `#A2A2D0`) for headings, calls to action, and key metrics to provide visual interest and highlight important information.

* **Clear Navigation:** A simple header navigation allows users to quickly jump to different sections of the page.

* **Clean Layout:** Utilizes a structured layout with clear sections and cards for easy readability and information absorption.

## Technologies Used

* **HTML5:** For the page structure and content.

* **Tailwind CSS:** A utility-first CSS framework for rapid UI development and responsive design. Loaded via CDN for ease of use.

* **Google Fonts (Inter):** Used for modern and legible typography.

## Setup and Usage

To view this homepage locally:

1. Save the provided HTML code into a file named `index.html`.

2. Open the `index.html` file in your web browser.

No special build steps or dependencies are required beyond a modern web browser.

## Customization

You can easily customize this homepage by editing the `index.html` file:

* **Content:** Modify the text within each section (`#about`, `#goals`, `#availability`, `#contact`) to reflect your organization's specific details.

* **Colors:** Adjust the hexadecimal color codes in the `<style>` block within the `<head>` section, or directly in the Tailwind classes (`bg-[#...]`, `text-[#...]`) throughout the HTML, to change the theme.

  * `background-color: #1A1A2E;` (Primary dark background)

  * `color: #8D8DAA;` (Section headings/primary accent)

  * `background-color: #2D2D44;` (Card backgrounds)

  * `border-color: #4A4A6A;` (Card borders)

  * `color: #A2A2D0;` (Subtle accent text)

* **Images:** Update the `src` attribute of the `<img>` tags to use your own images. The current `placehold.co` URLs are placeholders.

* **Navigation:** Add or remove navigation links in the `<header>` section as needed.