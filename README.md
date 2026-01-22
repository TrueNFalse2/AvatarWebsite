# 🌐 Avatar Website Project by Lior Rimon

This project is a multi-page website that allows users to build and view their own avatar profiles, leave feedback, and navigate between various interactive pages.

## 🔧 Files Structure

- `index.html` — **Homepage** with links to explore elements, videos, and other pages.
- `SecondWebsite.html` — **Avatar Creation Form** where users input data and upload their avatar.
- `profile.html` — **User Profile Page** generated from the form data.
- `ThirdWebsite.html` — **Visitor Feedback Page** where users can rate the site and leave comments.
- `styles.css` — Shared stylesheet that adds animation, layout, responsiveness, and color.
- `default-avatar.png` — Placeholder image used if the user does not upload their own avatar.


## 📌 How It Works

1. **User visits `index.html`**  
   - Introduction to the site with navigation to the avatar form and feedback.

2. **User goes to `SecondWebsite.html`**  
   - Fills out a form with name, email, location, bio, and avatar type.
   - Uploads an avatar image (optional).
   - Data is saved in `localStorage`.

3. **User is redirected to `profile.html`**  
   - Shows the profile with data loaded from `localStorage`.
   - Includes a reset button to clear saved data.

4. **User navigates to `ThirdWebsite.html`**  
   - Submits feedback and rating.
   - All feedback is stored and displayed using `localStorage`.

## ▶️ How to Run

1. Open `index.html` in your browser to start.
2. Make sure all files are in the **same folder**.
3. Use a modern browser (Chrome/Edge/Firefox).
4. Avatar images and feedback are stored using the browser's `localStorage`.

## 🧠 Technologies Used

- HTML5
- CSS3 (with animations)
- JavaScript (DOM, localStorage)
- Responsive design techniques

## ✅ Features

- Avatar creation and preview
- Profile page with stored data
- Animated design and interactive layout
- Feedback form with local persistence
- Navigation between pages



## ✍️ Author

**Lior Rimon**  
Project for educational and portfolio purposes.
