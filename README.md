**Keshika Website — Developer Reference Sheet**

This homepage is built around a clean navbar with seven links — **Home, About, Initiatives, Writing, Journey, Fun, Contact** — and the HTML structure and styling are split between your final `index.html` and your current `style.css`. The page uses a fixed visual language: dark blue-gold gradient background, floating blurred blobs, a sticky translucent navbar, a cinematic hero section, glassmorphism-style cards, and responsive layout behavior.  

---

## 1. What this homepage is trying to do

This is not meant to be a “full resume dump.”
It is a **landing page**.

Its job is:

* introduce Keshika quickly
* establish the vibe and brand
* highlight strongest work
* send visitors to the correct deeper pages

That is why the page is organized into:

* navbar
* hero
* highlights
* about preview
* featured spotlight
* explore grid
* footer 

---

## 2. Navbar — what each tab is doing

The navbar contains:

* `Home`
* `About`
* `Initiatives`
* `Writing`
* `Journey`
* `Fun`
* `Contact` 

### **Home**

This is the landing page.
It gives the first impression, shows the hero image and intro, and acts as the central entry point to the rest of the site.

### **About**

This should contain the fuller personal story.
The homepage only gives a short intro, while the About page is where someone learns who Keshika is in more depth — background, values, personality, and bigger life narrative.

* Also Include Recommendations

### **Initiatives**

This is the “what she has built or led” page.
It is broader than just projects. It should include:

* Digital Disha
* innovation work
* leadership-led initiatives
* major programs and build efforts
* All the old things from the "Projects" section

Think of this tab as the **builder / operator / founder** page.

### **Writing**

This is the ideas page.
It should contain:

* essays
* reflections
* articles
* selected written work
* possibly book-related material
* All the previous articles from the "Articles" section

Think of this tab as the **writer / thinker** page.

### **Journey**

This is the structured achievements-and-growth page.
It should include:

* academics
* awards
* milestones
* leadership timeline
* extracurriculars if needed
* Everything of the achievements, leadership, academics, extracurriculars

Think of this tab as the **timeline / progression** page.

### **Fun**

This is the more human, lighter page.
It can hold:

* gallery
* personality
* memories
* playful content
* more colorful styling than the rest of the site

This is the one place where the site can feel more experimental and less formal.

### **Contact**

This is the final “reach out” page.
It should include:

* LinkedIn
* email
* optional social links
* any simple contact pathway

* also include current roles

This tab exists so people do not have to search around the site for how to reach her.

---

## 3. How the homepage itself is structured

### **Hero section**

This is the first screen users see.
It contains:

* mini identity line: `BUILDER • WRITER • CREATOR`
* large name
* short descriptor
* short paragraph
* 2 CTA buttons
* one strong portrait image 

### Why it exists

This section is trying to answer, in a few seconds:

* who is Keshika?
* what kind of person is she?
* what should I click next?

### Main classes involved

* `.hero`
* `.hero-text`
* `.hero-mini`
* `.hero-description`
* `.hero-buttons`
* `.hero-image`

---



### **About preview section**

This section gives a short personal summary and links onward to the full About page. It is intentionally short so the homepage does not become overwhelming. 

### Why it exists

The hero gives the quick brand.
The About preview gives the human layer.

### Main classes involved

* `.about-preview-section`
* `.about-panel`
* `.about-panel-text`
* `.panel-label`
* `.text-link`

---

### **Spotlight section**

This is a featured area currently dedicated to **Digital Disha**, with a stronger presentation than a normal card. It includes a title, short description, CTA button, and badge-style visual. 

### Why it exists

This section tells the visitor:
“this one thing matters enough to get special space.”

### Main classes involved

* `.spotlight-section`
* `.spotlight-panel`
* `.spotlight-content`
* `.spotlight-visual`
* `.spotlight-badge`

---

### **Explore section**

This is the navigation bridge section near the bottom of the homepage. It gives users four clean paths:

* Initiatives
* Writing
* Journey
* Fun 

### Why it exists

Not everyone uses the navbar.
This section repeats the core site architecture inside the page.

### Main classes involved

* `.explore-section`
* `.explore-grid`
* `.explore-card`

---

### **Footer**

The footer contains:

* copyright
* short signature line
* LinkedIn link 

### Why it exists

It closes the page cleanly and keeps at least one contact route available at all times.

---

## 4. What the stylesheet is doing overall

Your stylesheet controls:

* reset and default box sizing
* page background
* floating animated color blobs
* subtle grid overlay
* sticky navbar
* hero layout
* buttons
* cards
* footer
* responsive behavior on smaller screens

The design system is centered around:

* deep blue / navy base
* warm gold accent
* soft cool blue accent
* off-white text
* translucent cards and blur effects 

---

## 5. Style guide for anyone editing this code

### **Background**

The body background is not meant to be flat. It uses layered gradients plus blurred animated blobs to create movement and atmosphere. This is one of the main things that gives the site life. 

### **Navbar**

The navbar is sticky and semi-transparent, so it stays visible while scrolling and keeps the site feeling modern. Hover underlines and gold-blue accents help indicate interactivity. 

### **Hero**

The hero is the most important visual section. It should stay spacious, text-led, and image-supported. Avoid overcrowding it.

### **Cards**

Cards are used for:

* highlights
* explore links
* possibly future sections

They should remain:

* rounded
* softly translucent
* dark-toned
* hover-elevated
* clean and readable 

### **Buttons**

Primary button = action emphasis
Secondary button = softer action

The primary button uses the gold gradient, so it should be reserved for the main CTA of a section. 

---

## 6. Responsive behavior

The stylesheet already adapts for smaller screens:

* hero collapses from 2 columns to 1
* nav becomes a toggle menu
* grids collapse into a single column
* typography and image sizes reduce for mobile readability 

That means new sections should be added with responsiveness in mind from the start.

---

## 7. Important editing rules for a new developer / intern

### Rule 1

Do not treat the homepage like a resume page.
It should stay curated.

### Rule 2

If adding a new big topic, first ask:
“Does this belong on the homepage, or on one of the deeper tabs?”

### Rule 3

Preserve the current visual language from the active stylesheet — deep blue background, gold accents, cool blue secondary glow, blur, and soft card depth. The stylesheet you uploaded is the one to build on going forward. 

### Rule 4

Use the existing section pattern when possible:

* `section`
* `section-shell`
* card/panel inside

### Rule 5

Do not overcrowd the hero.
Only one image.
Short text.
Strong CTA.

---

## 8. If someone is trying to understand the page quickly

Here is the shortest explanation:

* **Navbar** = site map
* **Hero** = first impression
* **Highlights** = strongest proof points
* **About preview** = personality + short story
* **Spotlight** = one featured initiative
* **Explore** = shortcuts to core pages
* **Footer** = closing + contact

---

## 9. Best formal title for this document

Pick one of these:

* **Developer Onboarding Sheet**
* **Codebase Overview**
* **Frontend Handoff Doc**
* **Website Architecture Reference**
* **Homepage Reference Sheet**

My pick for you:
**Keshika Website V2 — Frontend Handoff Doc**

If you want, I can turn this into a much cleaner **README-style version** next, with headings like “Purpose”, “File Structure”, “Section Map”, “Styling Rules”, and “Editing Guidelines.”
