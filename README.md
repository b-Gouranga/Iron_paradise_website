# Iron Paradise Gym - Official Website

A lightweight, responsive, accessible static website built for **Iron Paradise Gym**. Crafted with vanilla HTML5, CSS3, and JavaScript, designed for hosting on Netlify and supporting Meta business verification.

---

## Verified Business Profile Information

The website is fully configured with the official gym credentials:

| Field | Configured Value |
|---|---|
| **Business Name** | Iron Paradise Gym |
| **Gym Address** | Jail Road, Kakoti Gaon, Tarajan, Jorhat, Assam |
| **Direct Telephone** | +91 8638709454 (`tel:+918638709454`) |
| **Operating Hours** | Monday to Saturday: 6:00 AM – 10:00 PM, Sunday: Closed |
| **Instagram** | [https://www.instagram.com/ironparadise87/?hl=en](https://www.instagram.com/ironparadise87/?hl=en) |
| **Facebook** | [https://www.facebook.com/profile.php?id=61594430799786](https://www.facebook.com/profile.php?id=61594430799786) |
| **Schema Data (JSON-LD)** | Active `ExerciseGym` LocalBusiness schema in `<head>` with `sameAs` entity links |

---

## Local Preview

You can preview the website locally using any standard HTTP server:

```bash
# Option 1: Python 3 built-in server (recommended)
python3 -m http.server 8080

# Then open in your browser:
# http://localhost:8080
```

```bash
# Option 2: Node.js npx serve
npx serve .
```

---

## Deployment to Netlify

1. **Publish directory**: `.` (the project root folder)
2. **Build command**: *None* (leave empty)
3. **Configuration file**: Pre-configured in `netlify.toml` with security headers and 404 routing.

---

## Project Structure

```text
├── index.html       # Main landing page (Header, Hero, About, Facilities, Why Visit, Contact, Footer)
├── styles.css       # Complete responsive CSS design system (Dark Charcoal & Crimson Red theme)
├── script.js        # Vanilla JS for accessible mobile nav, smooth scroll, and dynamic year
├── 404.html         # Custom branded static 404 error page
├── netlify.toml     # Netlify publishing and security header configuration
└── README.md        # Documentation and pre-launch checklist
```
