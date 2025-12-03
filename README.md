DEVELOPMENT INSTRUCTIONS
Project Type: Clean, minimal, dark-theme responsive website
Pages: Home, About, Contact, Events, Login, (Gallery optional)

1. Global Rules

Layout: nav-wrapper > navbar → container → footer
Colors: Primary #1E201E, Hover #252725, Highlight #ECDFCC, Text white/dark bg & black/light bg
Font: Helvetica, Arial, sans-serif
Shadows: Normal 4px 4px 6px rgba(0,0,0,0.3), Hover 4px 8px 12px rgba(0,0,0,0.4)
Border Radius: 12–25px depending on boxes

2. Navbar

Desktop: Horizontal, left: Home/About/Events/Contact, right: Login, gap ~50px, hover lift + color
Tablet/Mobile: Gap 25px/15px, login centered on mobile, wrap allowed

3. Pages
Home:
Logo + heading row, intro box, bottom content box
Desktop: logo left/text right; Mobile: stacked center
Hover lift on top-section, logo, boxes

About:
Title + 1–2 info boxes, optional Mission/Team
Boxes use .box, text white, responsive stacking

Contact:
Heading + form (Name, Email, Message) + submit
Light box #ECECEC, dark bg, radius 25px
Tablets: reduced padding, Mobile: 90% width

Events:
Heading + 3–6 event cards (image, title, desc, date, optional CTA)
Dark card #262724, soft shadow, hover scale + shadow
Cards wrap on small screens

Login:
Centered card, dark box #1E201E
Inputs light, width: Desktop 350px, Tablet 70%, Mobile 90%
Signup link below

4. Footer
Theme color #1E201E, height: Desktop 10vh, Mobile 8vh
Centered text, hover slightly darker

5. Responsive Rules
Tablet max-width: 900px, boxes 95%, navbar gap 25px
Mobile max-width: 600px, navbar wraps, logo 120–150px, compact boxes/form

6. Animations
Allowed: hover lift 2–4px, color fade, scale, box-shadow transition (0.3–0.4s)
Not allowed: heavy/excessive/auto animations

7. Folder Structure
project/
│── index.html
│── style.css
│── about.html
│── sbout.css
│── contacts.html
│── contacts.css
│── events.html
│── events.css
│── login.html
│── login.css
│── ecell logo.png
│── user.png

9. Dev Rules
Clean, semantic HTML
Consistent class names
Strict color palette & layout consistency
