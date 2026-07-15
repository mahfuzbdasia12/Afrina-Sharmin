# Master Prompt — Graphic Designer Portfolio Website (HTML/CSS)

আমাকে একটা **single-page professional portfolio website** বানিয়ে দাও, pure **HTML + CSS (+ হালকা vanilla JS animation/interactivity-র জন্য)** দিয়ে। রেফারেন্স হিসেবে `iamrana.com` এর লেআউট/সেকশন স্ট্রাকচার ফলো করবে, কিন্তু কনটেন্ট ও ডিজাইন নিচের persona অনুযায়ী কাস্টমাইজ করবে।

### 👤 Persona
- নাম: **[Afrina Sharmin]**
- পেশা: Professional Graphic Designer
- Tagline: "Creative Visual Storyteller | Brand & Digital Design Specialist"
- Short bio: একজন female graphic designer, যিনি branding, illustration, motion graphics ও AI-assisted design workflow-এ দক্ষ। ২-৩ লাইনের একটা professional bio লিখবে (placeholder/lorem ipsum ব্যবহার করবে না, real sounding bio লিখবে)।

### 🎨 Color Scheme
- Primary: **Dark Blue** (`#0A1F44` / `#0D1B4C` ধরনের গাঢ় নেভি)
- Secondary: **Blue** (`#1E5AFF` / `#2563EB` ধরনের ব্রাইট ব্লু, accent হিসেবে ব্যবহার হবে)
- Accent: **Red** (`#E63946` / `#D62839` ধরনের bold red, CTA বাটন, হাইলাইট, hover effect-এ ব্যবহার হবে)
- Background: সাদা / off-white (`#FAFAFA`) light section-এর জন্য, আর dark navy sections-এর জন্য ওপরের dark blue
- টেক্সট: dark navy বা কালো headings-এর জন্য, gray body text-এর জন্য
- মোট প্যালেট যেন feminine-professional, bold কিন্তু elegant দেখায় — কর্পোরেট ব্লু-এর সাথে red accent দিয়ে energy আনবে।

### 🛠 Skills (Skills সেকশনে progress bar / circular skill bar দিয়ে দেখাবে)
- Adobe Illustrator — 95%
- Adobe Photoshop — 93%
- Adobe InDesign — 88%
- Adobe After Effects — 80%
- Adobe Premiere Pro — 75%
- Canva — 90%
- Midjourney — 85%
- Leonardo AI — 82%

(প্রতিটা skill-এর একটা icon/logo বসানোর জায়গা রাখবে — আমি নিজে পরে ছবি বসাবো)

### 🧩 Website Sections (এই অর্ডারে, iamrana.com এর মতো)

1. **Preloader / Loading animation** (হালকা, ছোট)
2. **Header/Navbar** — Logo (নাম দিয়ে), menu: Home, About, Resume, Services, Skills, Projects, Contact, Blog + "Let's Talk" CTA বাটন
3. **Hero Section**
   - বামে: "Hello, I'm [Afrina Sharmin]" + বড় heading "Graphic Designer" + short subtitle + দুইটা বাটন ("Hire Me", "Download Resume/CV")
   - ডানে: designer-এর ছবি/portrait বসানোর জায়গা (transparent PNG স্টাইল, blue/red geometric shape background)
   - নিচে stats: Years of Experience, Projects Completed, Client Satisfaction (%)
4. **About Me** — professional bio + email/phone card + "Branding & Design", "Digital Marketing", "Product Design", "AI-Assisted Design" — এই কয়েকটা highlight bullet
5. **Resume / Experience Timeline** — কাল্পনিক realistic experience দাও (যেমন freelance + agency + institute) কিন্তু placeholder হিসেবে চিহ্নিত করে দিবে যেন আমি এডিট করতে পারি
6. **Services** — 6টা service card:
   - Brand Identity Design
   - Print & Packaging Design
   - Social Media Design
   - Illustration & Digital Art
   - Motion Graphics & Video Editing
   - AI-Generated Concept Art
7. **Skills** — উপরে দেওয়া ৮টা skill, progress bar আকারে
8. **Portfolio/Projects Gallery** — কমপক্ষে ৬টা project card (image placeholder + category ট্যাগ + title), filter category বাটন সহ (Branding / Illustration / Social Media / Motion)
9. **Testimonials** — client feedback slider/carousel, ২-৩টা placeholder testimonial card
10. **Pricing (optional)** — চাইলে রাখবে, ৩টা প্যাকেজ (Basic/Standard/Premium)
11. **Contact Section** — contact form (Name, Email, Subject, Message) + email/phone/address info + social icons
12. **Blog (optional, 3 card)** 
13. **Footer** — quick links, address, social icons, copyright

### 🎬 Style/Design Requirements
- Modern, clean, feminine-professional aesthetic — bold typography, generous white space
- Smooth scroll animation, fade-in on scroll (CSS/JS দিয়ে)
- Fully **responsive** (mobile, tablet, desktop)
- Google Fonts থেকে একটা elegant heading font (যেমন Poppins/Playfair Display) + readable body font (যেমন Inter/Roboto)
- Buttons ও hover states-এ red accent color ব্যবহার হবে
- Section আলাদা আলাদা ভাবে alternate background (dark navy / white) দিয়ে visually break করবে যেমন iamrana.com করে

### 📁 Output Format
- একটাই `index.html` ফাইলে HTML দাও, আর CSS আলাদা `style.css` ফাইলে (অথবা বললে single file-এ inline `<style>`)
- সব image-এর জায়গায় placeholder (`https://via.placeholder.com/...` বা `<!-- IMAGE HERE -->` কমেন্ট) রাখবে, আমি পরে real ছবি বসাবো
- কোডে সব সেকশনে কমেন্ট দিয়ে বুঝিয়ে দিবে কোনটা কী সেকশন

---