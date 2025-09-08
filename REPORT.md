\# 🚀 Project Report: Static Website CI/CD with GitHub Actions \& GitHub Pages  



\## 1. Introduction  

This project demonstrates how to \*\*host and continuously deploy a static website\*\* using \*\*GitHub Actions (CI/CD)\*\* and \*\*GitHub Pages (hosting with HTTPS)\*\*.  

The workflow ensures that every code change committed to the repository is automatically tested, built, and deployed to GitHub Pages.  



---



\## 2. Objectives  

\- Automate deployment of a static HTML/CSS website.  

\- Implement CI/CD using \*\*GitHub Actions\*\*.  

\- Host website securely with \*\*HTTPS\*\* using \*\*GitHub Pages\*\*.  

\- Add an \*\*About page\*\* and site navigation.  

\- Create a reusable project structure for future enhancements.  



---



\## 3. Tools \& Technologies  

\- \*\*GitHub\*\* – Code hosting and version control.  

\- \*\*GitHub Actions\*\* – Automation for build \& deployment.  

\- \*\*GitHub Pages\*\* – Free static site hosting with HTTPS.  

\- \*\*HTML5, CSS3\*\* – Website content and styling.  

\- \*\*Markdown (README.md)\*\* – Documentation with badges.  

\- \*\*PowerShell / Git CLI\*\* – Local development and commit operations.  



---



\## 4. Project Workflow  



\### Step 1: Repository Setup  

\- Created GitHub repository `s3-static-site-demo`.  

\- Initialized with `.gitignore` and `README.md`.  



\### Step 2: Static Website Development  

\- Built `index.html` with project introduction.  

\- Added `style.css` for styling.  

\- Added `about.html` page with navigation.  



\### Step 3: CI/CD Pipeline with GitHub Actions  

\- Created `.github/workflows/deploy.yml` workflow.  

\- Configured workflow to:  

&nbsp; 1. Trigger on \*\*push to main branch\*\*.  

&nbsp; 2. Build and validate website files.  

&nbsp; 3. Deploy automatically to \*\*GitHub Pages\*\*.  



\### Step 4: Hosting on GitHub Pages  

\- Enabled \*\*GitHub Pages\*\* from repository settings.  

\- Configured branch: `main` → root folder `/`.  

\- Enforced \*\*HTTPS\*\* for secure access.  



\### Step 5: Navigation \& User Experience  

\- Added navigation bar for \*\*Home\*\* and \*\*About\*\*.  

\- Verified deployment via Actions logs and website URL.  



---



\## 5. Deliverables  

✅ Live Website with HTTPS:  

🔗 \[https://vyshnavvijayan1131.github.io/s3-static-site-demo/](https://vyshnavvijayan1131.github.io/s3-static-site-demo/)  



✅ CI/CD Workflow file: `.github/workflows/deploy.yml`  

&nbsp; 



✅ Screenshots of website \& GitHub Actions logs.  



---



\## 6. Results \& Learning Outcomes  

\- Implemented \*\*end-to-end CI/CD pipeline\*\* for a static website.  

\- Understood how GitHub Actions automates build \& deployment.  

\- Learned how GitHub Pages provides free hosting with HTTPS.  

\- Practiced best practices: repository structure, README, and automation.  



---



\## 7. Future Enhancements  

\- Integrate \*\*Cloudflare CDN + SSL\*\* for performance.  

\- Add automated tests (HTML validator, link checker).  

\- Extend website with JavaScript-based features.  

\- Implement Terraform for automated infra provisioning.  



---



\## 8. Conclusion  

This project successfully demonstrates the \*\*DevOps principle of automation\*\* in software delivery.  

By leveraging GitHub Actions and GitHub Pages, a static website was continuously deployed with minimal manual intervention.  

The pipeline ensures reliability, reproducibility, and faster iterations for future development.  



