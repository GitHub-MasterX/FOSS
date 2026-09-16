# FOSS SRM Trichy Team Photos

Drop your team photos into this folder:
- `lead.jpg` (or `.png`)
- `tech.jpg`
- `operations.jpg`
- `design.jpg`

Then reference them in `src/pages/about.astro` inside the `teamMembers` array:
```javascript
{
  name: "Your Name",
  role: "Lead Organizer",
  image: "/team/lead.jpg",
  github: "https://github.com/...",
  linkedin: "https://linkedin.com/in/...",
  instagram: "https://instagram.com/..."
}
```
If `image` is left blank (`""`), a modern neon developer avatar will automatically be displayed!
