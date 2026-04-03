# ✨ Chandrika Durga - Portfolio Website

> A beautiful personal portfolio website built to showcase skills, experience, and certifications for job interviews and professional networking.

---

## 👋 Hey there!

This is **Chandrika Durga's** personal portfolio website - think of it as a digital resume that's way more interactive and visually appealing than a boring PDF!

When you visit this website, you'll see:
- A stunning **animated galaxy background** with twinkling stars ✨
- Smooth **animations** as you scroll through different sections
- A professional **contact form** that sends emails directly
- Beautiful **gold and black** color theme throughout

---

## 🎯 What This Website Does

### **For Job Interviews:**
This website serves as a "living resume" that Chandrika can share with recruiters and hiring managers. Instead of just sending a PDF, she can send a link like `chandrikadurga.com` and they'll see:

1. **Who she is** - Her name, title, and what she's passionate about
2. **Her background** - Education, interests, and personality
3. **Work experience** - Previous internships and current roles
4. **Skills** - Both soft skills (like communication) and technical skills (like coding)
5. **Projects** - Case studies and simulations she's worked on
6. **Certifications** - Professional certificates she's earned with clickable proof
7. **Contact** - A way for recruiters to reach out directly

---

## 📄 Find My Latest Resume Here!

Hey Chandrika! 👋 Your **newly updated resume** is stored in this repository!

### **Where to Find It:**
📍 **Location:** `public/My_resume.pdf`

### **Direct Link (when website is live):**
Just click the **"Download Resume"** button on the homepage, or access it directly at:
- Local: `http://localhost:5173/My_resume.pdf`
- Live: `https://your-domain.com/My_resume.pdf`

### **To Update Your Resume:**
1. Save your new resume as `My_resume.pdf`
2. Replace the file in the `public/` folder
3. That's it! The website will automatically serve the new version

### **All Your Documents Location:**
| Document | Path |
|----------|------|
| 📄 Resume | `public/My_resume.pdf` |
| 📜 CBRE Certificate | `public/certificates/chandrika durga job simulation-1.pdf` |
| 📜 Siemens Certificate | `public/certificates/chandrika durga job simulation-2.pdf` |
| 📜 Oasis Certificate 1 | `public/certificates/Oasis_infobyte_certificate.jpeg` |
| 📜 Oasis Certificate 2 | `public/certificates/Oasis_infobyte_certificate2.jpeg` |
| 📜 Oasis LOR | `public/certificates/Oasis_infobyte_LOR.jpeg` |
| 📜 CodSoft Certificate | `public/certificates/codsoft_certificate.jpeg` |
| 📜 ADC Offer Letter | `public/certificates/ALGON_Offer_letter.jpeg` |
| 📜 CodSoft Offer | `public/certificates/codsoft.jpeg` |
| 📜 Oasis Offer | `public/certificates/Oasis_infobyte.jpeg` |

---

## 🛠️ Technologies Used (In Simple Terms)

### **The Building Blocks:**

| Technology | What It Does | Simple Explanation |
|------------|--------------|-------------------|
| **React** | Creates the website | Think of it like LEGO blocks - each section (About, Skills, Contact) is a separate block that fits together |
| **Vite** | Makes everything fast | It's like a super-fast chef that prepares your website really quickly when you're building it |
| **JavaScript** | Makes things interactive | The "brain" that makes buttons work, animations play, and forms submit |
| **CSS / UnoCSS** | Makes it pretty | Like choosing paint colors, fonts, and decorations for a house |

### **The Special Effects:**

| Feature | What It Does |
|---------|--------------|
| **Framer Motion** | Creates smooth animations (like how text fades in, buttons bounce when clicked) |
| **Galaxy Background (OGL)** | The beautiful starry background that responds to your mouse movement |
| **EmailJS** | Sends contact form messages directly to Chandrika's email (no server needed!) |

---

## 🌟 Website Sections Explained

### 1. **Hero Section** (The Big Welcome)
The first thing you see - Chandrika's name in big letters with a galaxy background. Has buttons to download her resume or connect on LinkedIn.

### 2. **About Section**
A brief intro about who Chandrika is, her interests, and what drives her. Shows she's not just skills on paper but a real person!

### 3. **Experience Section**
Lists her work experience:
- **Community Manager @ ADC** (Current role)
- **Web Development Intern @ CodSoft**
- **Web Development Intern @ Oasis Infobyte**

Each card has a "View Offer Letter" button to prove it's legit!

### 4. **Skills Section**
Two categories of skills displayed as pretty cards:
- **Product Skills**: Product thinking, business development, stakeholder alignment, etc.
- **Technical Skills**: HTML, CSS, JavaScript, AI tools, graphic design, etc.

### 5. **Projects Section**
Case studies and simulations she's worked on, showing practical application of her skills.

### 6. **Certifications Section**
Professional certificates from:
- **CBRE** - Project Management (via Forage)
- **Siemens Mobility** - Project Manager (via Forage)
- **Oasis Infobyte** - Web Development
- **CodSoft** - Web Development

Each has clickable buttons to view the actual certificates!

### 7. **Contact Section**
A form where visitors can:
- Enter their name
- Enter their email
- Write a message
- Hit submit and it goes straight to Chandrika's inbox!

### 8. **Footer**
Social links, copyright info, and a nice finishing touch.

---

## 🎨 Design Choices

### **Color Scheme:**
- **Gold** (`#D4AF37`) - Represents premium, professional quality
- **Black** (`#0A0A0A`) - Creates elegant, dark mode aesthetic
- **White/Gray** - For text readability

### **Why These Choices?**
- **Dark mode** is easier on the eyes and looks modern
- **Gold accents** stand out and feel premium/professional
- **Semi-transparent cards** let the galaxy background peek through

### **Animations:**
- Text fades in as you scroll
- Buttons scale slightly when you hover
- Cards glow gold when you hover over them
- The galaxy stars twinkle and move away from your cursor!

---

## 📁 Folder Structure (How It's Organized)

```
chandrikadurga/
├── 📁 public/                    # Files anyone can access directly
│   ├── 📁 certificates/          # PDF/image files of certificates
│   ├── My_resume.pdf             # Downloadable resume
│   └── logo.png                  # Website logo
│
├── 📁 src/                       # The actual website code
│   ├── 📁 components/            # Each section of the website
│   │   ├── Hero.jsx              # The big welcome section
│   │   ├── About.jsx             # About me section
│   │   ├── Experience.jsx        # Work experience
│   │   ├── Skills.jsx            # Skills showcase
│   │   ├── Projects.jsx          # Projects/case studies
│   │   ├── Certifications.jsx    # Certificates
│   │   ├── Contact.jsx           # Contact form
│   │   ├── Footer.jsx            # Bottom of page
│   │   ├── Navbar.jsx            # Top navigation
│   │   └── Galaxy.jsx            # The starry background
│   │
│   ├── App.jsx                   # Puts all components together
│   ├── App.css                   # Main styling
│   └── main.jsx                  # Starts the app
│
├── .env                          # Secret keys (EmailJS)
├── package.json                  # List of tools/libraries needed
└── README.md                     # This file you're reading!
```

---

## 🚀 How to Run This Website

### **Step 1: Install Node.js**
Node.js is like a translator that helps your computer understand JavaScript. Download it from [nodejs.org](https://nodejs.org/).

### **Step 2: Open Terminal**
On Windows: Press `Win + R`, type `cmd`, press Enter

### **Step 3: Navigate to the folder**
```bash
cd d:\chandrikadurga
```

### **Step 4: Install dependencies**
This downloads all the required tools (only needed once):
```bash
npm install
```

### **Step 5: Start the website**
```bash
npm run dev
```

### **Step 6: View the website**
Open your browser and go to: `http://localhost:5173`

That's it! The website is now running on your computer! 🎉

---

## 📧 How the Contact Form Works

1. Someone fills out the form (name, email, message)
2. They click "Send Message"
3. **EmailJS** (a free service) takes that info
4. It sends an email to `chandrikadurga6@gmail.com`
5. Chandrika sees the message in her inbox!

No complicated server setup needed - it's all done through a free online service!

---

## 🌐 How to Put This Online (Deployment)

To make this website accessible to everyone (not just on your computer):

### **Option 1: Vercel (Recommended - Free!)**
1. Go to [vercel.com](https://vercel.com)
2. Sign up with GitHub
3. Connect this project
4. Click Deploy
5. Get a free URL like `chandrikadurga.vercel.app`

### **Option 2: Netlify (Also Free!)**
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the `dist` folder (after running `npm run build`)
3. Get a free URL

---

## 💝 Why This Website is Special

1. **It's not just a resume** - It's an experience that shows personality
2. **Interactive** - The galaxy responds to your mouse, buttons animate
3. **Professional** - Clean design that looks like it was made by a pro
4. **Proof of work** - Actual certificates can be viewed and verified
5. **Direct contact** - Recruiters can reach out instantly via the form
6. **Mobile-friendly** - Looks great on phones, tablets, and computers

---

## 📝 Quick Reference

| What | Where |
|------|-------|
| Resume | `public/My_resume.pdf` |
| Certificates | `public/certificates/` folder |
| Email settings | `.env` file |
| Change content | `src/components/` folder |
| Colors/styling | `src/App.css` |

---

## 🔐 Important Note About the .env File

The `.env` file contains secret keys for EmailJS. **Never share this file publicly!**

If you need to set it up:
1. Create account at [emailjs.com](https://emailjs.com)
2. Get your Service ID, Template ID, and Public Key
3. Put them in the `.env` file

---
*Last updated: January 2026*
