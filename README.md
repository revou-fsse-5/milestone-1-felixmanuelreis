# Explore Responsibly

## Description

Explore Responsibly is a website dedicated to promoting community-based tourism and reducing plastic waste in communities around the world. It showcases various tours and experiences, our impact, and ways to get involved.

## Features

- Responsive design with a hamburger menu for mobile devices
- Animations for images on hover
- Sections for Home, About Us, Tours & Experiences, Our Impact, and Get Involved

## Technologies Used

- HTML
- CSS
- JavaScript
- GitHub for version control
- Netlify for deployment

## Preparation Process

1. **HTML Structure**:
    - Created the main structure of the website in `index.html`.
    - Included sections for Home, About Us, Tours & Experiences, Our Impact, and Get Involved.

2. **CSS Styling**:
    - Designed the layout and styles in `style.css`.
    - Added media queries for responsiveness.
    - Implemented animations for images.

3. **JavaScript Functionality**:
    - Added a script to toggle the hamburger menu on mobile devices.

## Deployment Process

### GitHub

1. **Create a GitHub Repository**:
    - Create a new repository on GitHub.
    - Clone the repository to your local machine.

    ```bash
    git clone https://github.com/your-username/explore-responsibly.git
    ```

2. **Add and Commit Changes**:
    - Add your project files to the repository.
    - Commit the changes.

    ```bash
    git add .
    git commit -m "Initial commit"
    ```

3. **Push to GitHub**:
    - Push the changes to the GitHub repository.

    ```bash
    git push origin main
    ```

### Netlify

1. **Deploy the Website on Netlify**:
    - Log in to Netlify and select "New site from Git".
    - Connect your GitHub repository.
    - Configure the build settings and deploy the site.

2. **Link Custom Domain**:
    - After deployment, go to the "Domain settings" in Netlify.
    - Add my custom domain `mountainmor.online`.

## Linking Existing Web Domain

To link the existing domain `mountainmor.online` to the new website on Netlify, I followed these steps:

1. **Unlink Previous Website**:
    - Go to your my registrar, Niagahoster, and log in to my account.
    - Navigate to the domain management section and unlink the previous website from the domain.

    ![Unlink Previous Website](images/hitu.jpg)

2. **Link New Website**:
    - In Netlify, go to "Domain Management".
    - Click on "Add custom domain" and enter `mountainmor.online`.
    - Follow the prompts to configure the DNS settings as provided by Netlify.

    ![Link New Website](images/ualu.jpg)

3. **Update DNS Settings**:
    - Go back to your domain registrar and update the DNS settings to point to Netlify's nameservers.

    ![Update DNS Settings](images/sia.jpg)

## Conclusion

The website is now live and linked to the domain `mountainmor.online`. Any changes pushed to the GitHub repository will automatically trigger a new build and deployment on Netlify.

## Screenshots

![Unlink Previous Website](images/hitu.jpg)
![Link New Website](images/ualu.jpg)
![Update DNS Settings](images/sia.jpg)

## License

This project is licensed under the MIT License. See the LICENSE file for details.
