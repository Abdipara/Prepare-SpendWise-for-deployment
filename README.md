# SpendWise

## Project Description
**SpendWise** is a lightweight, user-friendly web application designed to help individuals track their daily expenses, manage budgets, and monitor their financial habits with ease. Built with clean and responsive web technologies, it provides an intuitive interface to add, categorize, and review financial transactions seamlessly.

## Technologies Used
* **HTML5** – For structuring the web application pages and forms.
* **CSS3** – For styling, layout design, and responsive styling across devices.
* **JavaScript (ES6+)** – For handling application logic, expense calculations, form validation, and dynamic DOM manipulation.
* **Git & GitHub** – For version control and collaborative code management.
* **Netlify** – For continuous deployment and hosting the live application.

## Links
* **GitHub Repository:** [SpendWise Repository](https://github.com/Abdipara/SpendWise) *(Update with your exact repo link)*
* **Live Netlify Website URL:** [SpendWise Live App](https://your-site-name.netlify.app) *(Update with your Netlify site URL)*

## Deployment Process Summary
The project was deployed using the following steps:
1. **Version Control Setup:** Initialized a local Git repository in the project root folder, staged all source files, and committed the code.
2. **GitHub Repository Creation:** Created a new public repository on GitHub named `SpendWise` and pushed the local `main` branch to the remote repository.
3. **Netlify Integration:** Connected the GitHub repository to Netlify via the "Import an existing project" workflow. 
4. **Build & Deploy:** Configured Netlify to deploy directly from the `main` branch with default static site settings, generating an automated production build.
5. **Continuous Deployment:** Set up continuous deployment so that any future `git push` updates to the `main` branch automatically trigger a fresh rebuild and deploy on Netlify.

## Challenges Encountered During Deployment
* **Relative Pathing:** Ensuring that internal asset paths (such as stylesheets and JavaScript source files) used correct relative paths so assets loaded correctly once hosted under the Netlify domain structure.
* **Branch Configuration:** Verifying that Netlify targeted the correct production branch (`main`) to ensure automated deployments matched local changes.

## Lessons Learned
* Gained hands-on experience setting up production-ready static site hosting via Netlify.
* Reinforced best practices for structuring web projects with clean relative paths for seamless hosting compatibility.
* Understood how continuous deployment streamlines the workflow from local code edits to instant public updates.
