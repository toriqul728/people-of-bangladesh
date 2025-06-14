# 📸 People of Bangladesh

A visually immersive public gallery showcasing the rich lives and stories of the people of Bangladesh. Built with HTML, Tailwind CSS, and vanilla JavaScript, this lightweight website highlights photojournalism and visual storytelling with a modern aesthetic.

## 🌍 Live Preview

Coming soon – deploy to GitHub Pages or any static hosting platform.

## 🧩 Features

- 🖼️ **Dynamic Gallery Layout** using Macy.js for responsive Pinterest-style grid
- ✨ **Smooth Animations** (fade-in + slide-up on image load)
- 🧑‍💻 **About Section Overlay** with a profile and contact info
- 📆 **Image Metadata** including title, location, capture date, and a short story
- 🌓 **Dark Mode Design** using Tailwind + custom styles
- 📱 **Responsive Design** for all screen sizes
- 📧 **Contact & Social Links** in footer
- 📸 **Modal Viewer** for full image preview with story context

## 🛠️ Technologies Used

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- Macy.js (for masonry grid layout)
- Font Awesome (for icons)
- Google Fonts (`Poppins` & `Source Sans 3`)
- Google Analytics (optional – included in code)

## 📁 Folder Structure
├── index.html <br>
├── assets/<br>
│ ├── site profile.png # Logo/Favicon<br>
│ ├── Profile.png # About section profile photo<br>
│ ├── thumb1.jpg # Gallery images (example)<br>
│ ├── thumb2.jpg<br>
│ └── ...


## 📸 Sample Gallery Data (from `galleryData`)

<pre>```js
{
  thumb: "assets/thumb1.jpg",
  full: "assets/thumb1.jpg",
  title: "Tea Vendor in Old Dhaka",
  location: "Old Dhaka, Bangladesh",
  displayDate: "February 14, 2025 – 4:15 PM",
  sortDate: "2025-02-14T16:15:00",
  story: "In the narrow alleys of Old Dhaka..."
}</pre>

🚀 Getting Started
1. Clone this Repository
bash
Copy
Edit
git clone https://github.com/your-username/people-of-bangladesh.git
cd people-of-bangladesh
2. Add Your Own Photos
Place your image files inside the assets/ folder and update the galleryData array in the <script> section of index.html accordingly.

3. Open in Browser
Open index.html in any modern browser (works offline too).

4. Deploy
You can deploy this on:

GitHub Pages

Netlify

Vercel

Firebase Hosting

Or run it locally without any server

📝 Customization
Change Logo or Profile Picture: Replace site profile.png or Profile.png in assets/

Update Fonts/Colors: Modify the Tailwind config or inline styles in <style>

Add Social Links: Edit the <footer> section

📌 Roadmap
 Image upload/submission system

 Donation method integration (BD and International)

 Language toggle (Bangla/English)

 Image license labels

🧑 Author
Toriqul Islam
Instagram · Email

📜 License
All images belong to their respective photographers. You may reuse with attribution.
This code is open-sourced under the MIT License.
