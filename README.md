# Simulation-Cyshield
Simulate the Cyshield's website based on their request for an interview.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.3.9.
# The main webste : 
 https://cylogz.cyshield.com/
# Test the functionality of the main website
**Website Functionality Test Report for CYLOGZ**

**Testing Period**: 19th December 2024 – 21nd December 2024  
**Tested By**:saeed osama  
**Website**: [CYLOGZ](https://cylogz.cyshield.com/)
---
**1. Objective**
The main objective of this testing was to perform functionality testing on the CYLOGZ website to ensure that key features work as expected.

---

**2. Features Tested**
- **Homepage**
- **Login/Sign-In**
- **Dashboard**
- **Logs View**
- **Reports**
- **Manage**
- **Logout**
- **Add Domain**
---
 **3. Testing Results**
 Issues Found:
1. **Sign-In Mobile Number Input**: The input field for the mobile number was dynamic (counter) rather than static.
2. **Vertical Navbar Routing**: Links in the vertical navbar do not work when the navbar is closed.
3. **Navbar Buttons**: "Account" and "Report" buttons in the vertical navbar are not functional.
4. **Form Autofill and Accessibility**: Issues with autofill functionality and accessibility of forms.
5. **API Key Error**: Missing API key for Google services, causing errors in Geocoding API functionality.
6. **Responsiveness Issues**: The website is not fully responsive. Some buttons are overlapping on the navbar, and other elements are mispositioned. The navbar does not close automatically.
---
 **4. Critical Issues**
- Routing problems with navbar buttons not working.
- Responsiveness issues, particularly with button overlap and navbar positioning.
---
 **5. Error Messages**
- **API Request Error**: The API request is missing a valid API key for authentication, which affects the Geocoding API. Resolving this requires adding a valid API key from Google Cloud Console.
---
 **6. Recommendations**
- **Fix Routing**: Ensure all links and navbar buttons work properly and navigation is seamless.
- **Improve Responsiveness**: Use media queries to ensure the website is mobile-friendly and test across different devices.
- **Add API Key**: Ensure a valid API key is added for external services.
- **Optimize Performance**: Compress images and scripts to improve page load times.
- **Enhance Accessibility**: Improve contrast, add alt text for images, and use proper HTML tags.
- **User Testing**: Conduct real user testing to identify additional issues or improvements.
---
 **7. Conclusion**
The website has functional issues, especially with routing and responsiveness. Immediate attention is required to fix the issues related to buttons not working and overlapping content in mobile views. After addressing these critical problems, further testing and optimization should be performed to ensure a smooth user experience before the website’s release.


## create the project
ng new Simulation-Cyshield
## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
