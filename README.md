# Dakota STEM Trails

Static website (Home, About Us, Contact, Our Team) recreating the Dakota STEM Trails Wix site, ready to deploy on Vercel.

## Deploy on Vercel
1. Go to vercel.com, click "Add New Project", and import this GitHub repo.
2. Framework preset: "Other" (no build step needed — it's plain HTML/CSS).
3. Click Deploy. You'll get a free `.vercel.app` URL.

## Customize
- Edit `styles.css` to change colors/fonts.
- Replace the `picsum.photos` placeholder image URLs in each `.html` file with your own photos.
- The contact form on `contact.html` is currently a demo (shows an alert on submit). To actually receive submissions, connect it to a free service like [Formspree](https://formspree.io) by setting the `<form>` tag's `action` attribute to your Formspree endpoint and removing the `onsubmit` demo handler.
