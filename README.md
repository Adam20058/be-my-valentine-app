# Be My Valentine App 💝

A simple, interactive, and delightful web-based Valentine's invitation system that lets you create personalized Valentine's cards with dynamic animations and playful interactions.

## ✨ Features

### For the Sender
- Create personalized Valentine invitations
- Add custom messages
- Generate shareable links
- Easy link copying to clipboard
- Mobile-responsive design

### For the Recipient
- Personalized greeting with their name
- Interactive "Yes" and "No" buttons
- Playful "No" button that escapes when hovered
- Progressive animations and messages when clicking "Yes"
- Floating heart animations
- Responsive design for all devices

## 🚀 Quick Start

### Local Testing
1. Download the `index.html` file
2. Open it in a web browser
3. Test the creator mode locally

### Hosting Options

#### GitHub Pages (Recommended)
1. Create a new repository on GitHub
2. Name it `valentine` or your preferred name
3. Upload the `index.html` file
4. Go to Settings > Pages
5. Enable GitHub Pages and select your branch
6. Your site will be available at `https://yourusername.github.io/valentine`

#### Netlify
1. Go to [Netlify Drop](https://app.netlify.com/drop)
2. Drag and drop the `index.html` file
3. Your site will be live instantly with a Netlify subdomain

#### Vercel
1. Fork this repository
2. Connect to Vercel
3. Deploy with default settings

## 💌 How to Use

### Creating an Invitation
1. Visit your hosted website
2. Enter your name in "Your Name"
3. Enter your valentine's name in "Your Valentine's Name"
4. Add an optional custom message
5. Click "Generate Invitation Link"
6. Copy the generated link
7. Share the link with your valentine

### Recipient Experience
When your valentine opens the link, they'll see:
1. A personalized greeting with their name
2. Your custom message (if provided)
3. Interactive "Yes" and "No" buttons
4. Progressive animations and messages when they click "Yes"

## 🎨 Customization

### Messages
You can customize the progression messages in the `messages` array:
```javascript
const messages = [
    "You make every day brighter! ❤️",
    "You're my favorite person to laugh with 💑",
    "Will you be mine forever? 💘"
];
```

### Colors
The main colors can be modified in the CSS:
- Background gradient: `linear-gradient(45deg, #ff6b6b, #ffd3d3)`
- Button color: `#ff4b4b`
- Final button color: `#ff1493`

## 📱 Browser Support
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera
- Mobile browsers

## ⚠️ Notes
- The site uses vanilla JavaScript and CSS, no dependencies required
- All animations are CSS-based for smooth performance
- The link generator requires proper hosting to work effectively
- Mobile-responsive design works on all screen sizes

## 🤝 Contributing
Feel free to fork and enhance! Some ideas for contributions:
- Add more animation variations
- Include background music option
- Add more customization options
- Implement different themes
- Add social sharing buttons

## 📄 License
MIT License - feel free to use and modify for your personal or commercial projects!

---
Made with ❤️ for spreading love!