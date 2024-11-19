# Sci-fi Tech

Deploying a project from GitHub to **Vercel** is straightforward. Here’s a step-by-step guide:

---

### **Step 1: Prepare Your GitHub Repository**
1. **Push Your Code to GitHub**:
   - Ensure your code is committed and pushed to a GitHub repository.
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```
2. Confirm your repository has all the necessary files (e.g., `index.html`, `README.md`, etc.).

---

### **Step 2: Create a Vercel Account**
1. Go to [Vercel's website](https://vercel.com/).
2. Sign up or log in using your **GitHub**, **GitLab**, or **Bitbucket** account.

---

### **Step 3: Import Your GitHub Repository**
1. **Connect GitHub to Vercel**:
   - During setup, authorize Vercel to access your GitHub repositories.
   - This allows Vercel to import and deploy your project.

2. Click the **"New Project"** button on your Vercel dashboard.

3. Select your **GitHub Repository**:
   - Search for and click on the repository containing your project.

---

### **Step 4: Configure Project Settings**
1. **Build Settings**:
   - For simple HTML/CSS/JS projects, you don’t need a build step.
   - Vercel will automatically detect that this is a static project.

2. **Framework Preset**:
   - If prompted, select "None" (for static sites).

3. **Root Directory**:
   - If your project files are in the root directory, leave this field empty.
   - Otherwise, specify the directory where your `index.html` file is located.

---

### **Step 5: Deploy**
1. Click **"Deploy"**.
2. Vercel will start the deployment process. You’ll see logs as the site is being built.

---

### **Step 6: Get Your Live URL**
1. Once deployment is complete, Vercel provides a live URL (e.g., `https://your-project-name.vercel.app`).
2. You can also add a custom domain if needed.

---

### **Step 7: Manage Future Updates**
1. Every time you push changes to the connected GitHub branch (e.g., `main`), Vercel will automatically redeploy your site.
2. To manually trigger a redeployment, go to your project on Vercel and click **"Redeploy"**.

---

**That's it!** 🎉 Your project is now live on Vercel!
