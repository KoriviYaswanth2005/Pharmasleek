PharmaSleek Medicals
A responsive pharmacy and healthcare landing-page project built with HTML, Bootstrap, and popular front-end libraries. The website introduces pharmacy services, showcases health and wellness products, highlights offers and articles, and provides contact information.
Features
- Pharmacy-themed homepage and navigation
- About section introducing PharmaSleek Medicals
- Pharmacy and wellness service highlights
- Featured health products and new-arrival sections
- Offers and blog sections
- Contact section
- Responsive layout built with Bootstrap 5
- Icons from Font Awesome
- Product carousel support with Swiper
- Date-picker styling support with Flatpickr
- Google Fonts typography using Inter and Poppins
Technologies Used
- HTML5
- CSS3
- Bootstrap 5.3
- Swiper
- Flatpickr
- Font Awesome
- Google Fonts
Project Structure
Pharmasleek-main/
├── index.html        # Main website page
└── pharmasleek.jpg   # Pharmacy image/logo asset
Run the Website Locally
This is a static front-end project and does not require a backend or package installation.
1. Download or clone this repository.
2. Open the project folder.
3. Open index.html in a web browser.
For local development, you can open the folder in Visual Studio Code and use the Live Server extension.
Deploy with GitHub Pages
1. Upload the project files to a GitHub repository.
2. Open the repository and select Settings.
3. Select Pages in the sidebar.
4. Under Build and deployment, choose Deploy from a branch.
5. Select the main branch and the / (root) folder.
6. Click Save and wait for the deployment to finish.
7. Open the published URL displayed in the Pages section.
Before Publishing
- Check the stylesheet: index.html references styles.css, but that file was not included in the uploaded project archive. Add the stylesheet or remove/update the reference so the website displays as intended.
- Check the favicon filename: the HTML refers to Pharmasleek.jpg, while the included file is named pharmasleek.jpg. GitHub Pages uses case-sensitive paths, so make the names match exactly.
- The page loads several libraries, fonts, and product images from external CDNs and URLs, so an internet connection is needed for those assets.
- Review contact details, product information, prices, and service claims before publishing.
- If this site will be used by a real pharmacy, ensure all medicine-related content and services are reviewed by qualified professionals and comply with applicable local regulations.
Disclaimer
This repository is a front-end website template/demo. Product listings and service descriptions should not be treated as medical advice or as confirmation that a pharmacy provides the listed services.
Contributing
Suggestions and improvements are welcome. You can improve accessibility, mobile responsiveness, page performance, content accuracy, and project organization through a branch or pull request.
