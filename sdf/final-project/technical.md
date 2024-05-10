# SDF Final Project Rubric - Technical
This is intended to be filled out by staff members of DPI Tech Apprenticeship program.

- Date/Time:
- Trainee Name:
- Project Name:
- Reviewer Name:

## Technical Score (/80):
- Readme (/10):
- Version Control (/10):
- Patterns of Enterprise Applications (/15):
- Frontend (/10):
- Backend (/10):
- Security and Authorization (/5):
- Ambitious Features (/10):
- Enrichment (/10):

## Additional overall comments for the entire review may be added below:
&nbsp;  
&nbsp;  
&nbsp;  

## Readme (max: 10 points)
- [ ] **Markdown**: Is the README formatted using Markdown?
- [ ] **Naming**: Is the repository name relevant to the project?
- [ ] **1-liner**: Is there a 1-liner briefly describing the project?
- [ ] **Instructions**: Are there detailed setup and installation instructions, ensuring a new developer can get the project running locally without external help?
- [ ] **Configuration**: Are configuration instructions provided, such as environment variables or configuration files that need to be set up?
- [ ] **Contribution**: Are there clear contribution guidelines? Do they outline how developers can contribute to the project, including coding conventions, branch naming conventions, and the pull request process?
- [ ] **ERD**: Does the documentation include visual an ERD?
- [ ] **Troubleshooting**: Is there an FAQs or Troubleshooting section that addresses common issues, questions, or obstacles users or new contributors might face?
- [ ] **Screenshots**: Are there screenshots of the application in the README?
- [ ] **API Documentation (if applicable)**: For projects with an API, is there clear and detailed API documentation, including endpoints, request/response formats, and authentication methods? 
<!-- is this for projects using external APIs or projects that are APIs? ^ -->

### Notes:

## Version Control (max: 10 points)
- [ ] **Version Control**: Is the project using a version control system such as Git?
- [ ] **Repository Management**: Is the repository hosted on a platform like GitHub, GitLab, or Bitbucket, making it accessible for collaboration and review?
- [ ] **Commit Quality**: Does the project have regular commits with clear, descriptive messages?
- [ ] **Pull Requests**: Does the project employ a clear branching and merging strategy, such as Git Flow, to organize development and feature integration?
- [ ] **Issues**: Is the project utilizing issue tracking to manage tasks and bugs?
- [ ] **Linked Issues**: Are these issues linked to pull requests (PRs)? (at least once)
- [ ] **Project Board**: Does the project utilize a project board (e.g., GitHub Projects or Trello) to manage and prioritize work items?
- [ ] **Code Review Process**: Is there evidence of a code review process, with pull requests reviewed by peers or mentors before merging, ensuring code quality and collaborative learning?
- [ ] **Branch Protection**: Are the main branches (e.g., master, main) protected to prevent direct commits and ensure code quality?
- [ ] **Continuous Integration/Continuous Deployment (CI/CD)**: Has the project implemented CI/CD pipelines (using tools like GitHub Actions) to automate testing and deployment?

### Notes:

## Patterns of Enterprise Applications (max: 15 points)
- [ ] **Indentation**: Is the code consistently indented throughout the project?
- [ ] **Naming Conventions**: Are naming conventions (e.g., variable names, method names, class names) clear, consistent, and descriptive?
- [ ] **Casing Conventions**: Are casing conventions (e.g., camelCase, snake_case, PascalCase) consistent throughout the project?
- [ ] **Layouts**: Is the code making good use of Rails' layouts to provide consistent and reusable templates for the application's views?
- [ ] **Code Clarity**: Is the code easy to read and understand? Look for simple, straightforward implementations and avoid unnecessary complexity. 
- [ ] **Domain Driven Design**: Does the application follow domain-driven design principles, with clear separation of concerns and a focus on the core domain logic?
- [ ] **Advanced Data Modeling**: Has the application utilized Active Record callbacks for model lifecycle management?
- [ ] **Component-Based View Templates**: Does the application use component-based view templates (partials) to promote reusability and maintainability?
- [ ] **Modules**: Does the application use modules (concerns) to encapsulate related functionality and promote code organization?
- [ ] **Service Objects**: Does the application abstract logic into service objects when appropriate?
- [ ] **Polymorphism**: Does the application use polymorphism to create flexible and maintainable code?
- [ ] **Comment Quality**: Does the code include inline comments that explain "why" behind non-obvious logic? Over-commenting should be avoided; code should be self-explanatory wherever possible. 
- [ ] **Minimal Unused Code**: Unused code should be deleted (not commented out).
- [ ] **Overall Separation of Concerns**: Are the concerns of the application (e.g., data access, business logic, presentation) separated effectively, with each layer focused on its specific responsibilities?
- [ ] **Overall DRY Principle**: Does the application follow the DRY (Don't Repeat Yourself) principle, with code reuse and minimal redundancy?

### Notes:

## Frontend (max: 10 points)
- [ ] **Mobile Design**: It looks and works great on mobile (using media queries or CSS framework). Layouts should be responsive and user-friendly, not only shrunk down versions of the desktop site.
- [ ] **Tablet Design**: It looks and works great on tablet (using media queries or CSS framework). Layouts should be responsive and user-friendly, not only shrunk down versions of the desktop site.
- [ ] **Desktop Design**: It looks and works great on desktop.
- [ ] **Styling**: Does the frontend employ CSS or CSS frameworks (like Bootstrap) for styling? Inline CSS should not be overrused.
- [ ] **Semantic HTML**: Is the project making effective use of semantic HTML elements to structure the content, ensuring that it's both accessible and SEO-friendly (e.g., using `<header>`, `<footer>`, `<nav>`, or `<main>` when applicable)?
- [ ] **Feedback**: Are styled flashes or toasts implemented in a partial to provide clear, user-friendly feedback?
- [ ] **Client-Side Interactivity**: Is JavaScript or JavaScript frameworks/libraries (e.g., jQuery) utilized to reduce unnecessary page reloads for key features of the app?
- [ ] **Form Validation**: Does the project include client-side form validation to provide immediate feedback to users and reduce server requests?
- [ ] **Accessibility: alt tags**: Are alt tags implemented to support users with disabilities and to comply with web accessibility standards?
- [ ] **Accessibility: ARIA roles**: Are ARIA roles implemented to support users with disabilities and to comply with web accessibility standards?

### Notes:

## Backend (max: 10 points)
- [ ] **CRUD**: Does the application implement at least one resource with full CRUD functionality?
- [ ] **MVC pattern**: Does the application follow the Model-View-Controller pattern, with skinny controllers and fat models?
- [ ] **RESTful Routes**: Are the routes RESTful, with clear and consistent naming conventions?
- [ ] **DRY queries**: Are database queries primarily implemented in the controller layer rather than in the views, following the principle of keeping views lightweight and focused on presentation logic?
- [ ] **Data Model Design**: Is the data model well-designed, clear, and efficient, facilitating easy data manipulation and retrieval, while avoiding redundancy and promoting data integrity?
- [ ] **Associations**: Does the application efficiently use Rails association methods (belongs_to, has_many, etc.) to organize data relationships?
- [ ] **Validations**: Are validations implemented to ensure data integrity and consistency?
- [ ] **Query Optimization**: Does the application use scopes to perform optimized database queries?
- [ ] **Database Management**: Are additional features such as file upload (CSV) or custom rake tasks for database management included?
- [ ] **Testing**: Does the project include a comprehensive test suite (e.g., RSpec, Minitest) that covers models, controllers, and other critical components?
<!-- is the below redundant with the README API doc? -->
<!-- - [ ] **API Development**: Does the project provide a well-documented JSON API for integration with other services or frontend frameworks? -->

### Notes:

## Security and Authorization (max: 5 points)
- [ ] **Security: credentials**: Are API keys and sensitive information securely stored (using .env or Rails credentials)?
- [ ] **Security: HTTPS**: Is HTTPS enforced? (config.force_ssl = true)?
- [ ] **Security: Controllers and Strong Params**: Are strong parameters used to prevent mass assignment vulnerabilities? Are sensitive attributes assigned in the controller when necessary?
- [ ] **Security: SQL injection**: Are ActiveRecord query methods (e.g., where, find_by) used to prevent SQL injection attacks?
- [ ] **Authorization**: Is an authorization framework (such as Pundit) employed to manage user permissions and ensure secure access control across the application?

### Notes:

## Ambitious Features (each: 2 points - max: 10 points)
- [ ] **Receiving**: Implementation of ActiveMailbox to receive emails within the application.
- [ ] **Web Scraping Capabilities**: Incorporation of web scraping functionality to extract data from external websites.
- [ ] **Background Processing**: Are background jobs (eg ActiveJob) implemented for time-consuming processes, improving app performance and user experience?
- [ ] **Mapping and Geolocation**: Use of mapping or geocoding libraries (e.g., Mapbox, Geocoder) to add location-based features to the application.
- [ ] **Cloud Storage Integration**: Integration with cloud storage services (e.g., AWS S3) for handling file uploads and storage.
- [ ] **Chat GPT or AI Integration**: Implementation of Chat GPT or other AI services to provide intelligent responses or features. 
- [ ] **Payment Processing**: Implementation of a payment gateway (e.g., Stripe) for secure online transactions.
- [ ] **Hotwire**: Implementation of Hotwire, Turbo, or Stimulus to create a dynamic, highly interactive user interface without relying heavily on traditional full-page reloads.
- [ ] **OAuth**: Implementation of OAuth for secure, third-party authentication.
- [ ] **Other**: Any other features or functionalities that enhance the application's value and user experience (specify in notes below).

### Notes:

## Enrichment (each: 1 point - max: 10 points)
- [ ] **Sending Email**: Does the application send transactional emails (e.g., welcome emails, password reset emails) to users?
- [ ] **Building for Mobile**: Implementation of a Progressive Web App (PWA) to provide a mobile app-like experience on the web.
- [ ] **Advanced Search and Filtering**: Incorporation of advanced search and filtering capabilities (Ransack or similar) to improve data retrieval and user experience.
- [ ] **Data Visualization**: Integration of charts, graphs, or other visual representations of data (Chartkick or similar) to provide insightful views of data to the user.
- [ ] **Dynamic Meta Tags**: Dynamic generation of meta tags for social media previews and SEO optimization, enhancing the application's presence on the web.
- [ ] **Pagination**: Use of pagination libraries (Kaminari, will_paginate, or similar) to manage large sets of data efficiently on the UI.
- [ ] **Internationalization (i18n)**: Support for multiple languages using internationalization techniques, making the app accessible to a global audience.
- [ ] **Admin Dashboard**: Creation of an admin panel to provide valuable administrative capabilities (Rails Admin or similar).
- [ ] **Business Insights Dashboard**: Creation of an insights dashboard to provide valuable business intelligence capabilities (Blazer or similar).
- [ ] **Enhanced Navigation**: Are breadcrumbs (or similar) used to enhance site navigation?
- [ ] **Performance Optimization**: Is the Bullet gem (or similar) used in development to detect and reduce N+1 queries and other common performance bottlenecks?
- [ ] **Other**: Any other features or functionalities that enhance the application's value and user experience (specify in notes below).

### Notes:
