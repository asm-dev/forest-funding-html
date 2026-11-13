# Reforestation in Galicia - HTML Structure

This project contains the HTML of a website designed to promote reforestation in Galicia, a region severely affected by forest fires. It is a crowdfunding page whose main purpose is to raise awareness about the importance of environmental recovery by collecting donations that enable the reforestation of burned Galician forests.

> The website includes no real data or projects. It is an educational mockup with demonstrative purposes

The creation of this website is part of the activity program of the UEM MS in Web Development. This repository only contains the HTML structure of the site, but it is iterated on by adding styles and interactivity here:

1. [CSS](https://github.com/asm-dev/forest-funding-css)
2. [JS](https://github.com/asm-dev/forest-funding-js)

&nbsp;

## Goals

- **Inform**. Spread information about the problem of forest fires in Galicia and the need to reforest.
- **Raise awareness**. Educate the community about the importance of sustainability and biodiversity preservation.
- **Make action easy**. Create an easy-to-use online tool to simplify the collective donation process.

&nbsp;

## Site map

It is a single page or Home made up of the following elements:

1. **Home**:

   - Introduction to the fire problem.
   - Call to action using an image of a reforested forest.

2. **About Us**:

   - The mission and goals are detailed.
   - Includes information about the team responsible for the project.

3. **Projects**:

   - Description of key initiatives such as the reforestation in As Fragas do Eume.
   - Description of awareness actions such as environmental education workshops in Galician schools.

4. **Call to action**:

   - Fundraising request for an ongoing reforestation action.
   - Image carousel to encourage donations and convey the reality of the fire.
   - Progress tracker in the form of a counter and percentage raised with respect to the set goal.

5. **Donate**:

   - Form to make contributions.
   - Information on how donations are used (transparency policy).

6. **Contact**:
   - Contact information and office location.
   - Link to Google Maps to simplify access.

![image](https://github.com/user-attachments/assets/c9b7986f-7f6c-4a13-ae53-d5065c7ac0aa)


&nbsp;

## Technical design

Semantic HTML has been used to ensure accessibility and a clear structure:

- **Simple navigation**. The user can access all sections by _scrolling_ or by using the site's main navigation.
- **Semantic tags**. Tags such as `<header>`, `<main>`, `<section>`, `<article>` and `<footer>` are used instead of `<div>`, since the latter provides no additional meaning. This contributes to code readability, but also optimizes SEO and UX with screen readers.
- **Accessibility**. All images include descriptive `alt` attributes for visually impaired people. In addition, the form uses clear labels and required fields.
- **Loading efficiency**. Images have been optimized to reduce their weight without compromising visual quality. This ensures minimal resource consumption.
