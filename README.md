# C5_student_profiles
# Class Contributor Gallery 🚀

Welcome to our first open-source project! Follow the steps below to add your personal profile card to our class website gallery. This project will help you practice HTML, CSS, JavaScript, and the standard GitHub workflow.

## 🛠️ Project Setup

1. **Fork** this repository to your own GitHub account using the "Fork" button at the top right.
2. **Clone** your forked repository to your computer:
   ```bash
   git clone https://github.com
   ```
3. Open the `student-profiles` folder in your favorite text editor (like VS Code).

---

## 📝 How to Add Your Card

1. Open the `index.html` file.
2. Scroll down until you find this line:
   ```html
   <!-- NEXT STUDENT ADDS THEIR CARD BELOW THIS LINE -->
   ```
3. Copy the template block below and paste it directly underneath that comment:
   ```html
   <div class="card" onclick="showMessage('Hi! I am [Your Name]. [Add a fun fact or greeting here]!')">
       <h3>[Your Name]</h3>
       <p class="role">[Your Role, e.g., Frontend Learner / Designer]</p>
       <div class="skills">
           <span>HTML</span> <span>CSS</span> <span>Git</span>
       </div>
   </div>
   ```
4. Replace the bracketed placeholders (`[Your Name]`, `[Your Role]`, etc.) with your own information.
5. Save the file and double-click `index.html` on your computer to open it in a browser and test your new card!

---

## 🚀 Submitting Your Changes

Once your card looks good and the click alert works, submit it to the main gallery:

1. Stage your changes:
   ```bash
   git add index.html
   ```
2. Commit your changes with a clear message:
   ```bash
   git commit -m "Add Profile Card for [Your Name]"
   ```
3. Push the changes to your GitHub fork:
   ```bash
   git push origin main
   ```
4. Go back to the original classroom repository on GitHub.
5. Click the **"Compare & pull request"** button that appears.
6. Write a short description and click **"Create pull request"**.

🎉 **That's it!** Once your instructor reviews and approves your Pull Request, your profile card will go live on the site.
