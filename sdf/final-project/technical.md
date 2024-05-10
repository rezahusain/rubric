# SDF Final Project Rubric - Technical
This is intended to be filled out by staff members of DPI Tech Apprenticeship program.

- Date/Time:
- Trainee Name:
- Project Name:
- Reviewer Name:

## Documentation
- [ ] **Clarity and Completeness**: Is the README clear, well-written, and comprehensive? Does it effectively explain the project's purpose, features, and limitations?
- [ ] **Setup and Installation Instructions**: Does the documentation include detailed setup and installation instructions, ensuring a new developer can get the project running locally without external help?
- [ ] **Contribution Guidelines**: Are there clear contribution guidelines? Do they outline how developers can contribute to the project, including coding conventions, branch naming conventions, and the pull request process?
- [ ] **Markdown**: Is the README formatted using Markdown?
- [ ] **Naming**: Is the repository name relevant to the project?

### Bonus (max 2pts)
- [ ] **Visual Aids**: Does the documentation include visual aids such as screenshots, diagrams (e.g., architecture diagrams, ERDs), or GIFs to clarify complex concepts or demonstrate features?
- [ ] **FAQs or Troubleshooting**: Is there an FAQs or Troubleshooting section that addresses common issues, questions, or obstacles users or new contributors might face?
- [ ] **API Documentation (if applicable)**: For projects with an API, is there clear and detailed API documentation, including endpoints, request/response formats, and authentication methods?


### Score (/5):

### Notes:

## Version Control
- [ ] **Use of Version Control System**: Is the project using a version control system such as Git?
- [ ] **Repository Management**: Is the repository hosted on a platform like GitHub, GitLab, or Bitbucket, making it accessible for collaboration and review?
- [ ] **Branching and Merging Strategy**: Does the project employ a clear branching and merging strategy, such as Git Flow, to organize development and feature integration? (at least once)
- [ ] **Commit Quality**: Does the project have regular commits with clear, descriptive messages?
- [ ] **Issue Tracking and Pull Requests**: Is the project utilizing issue tracking to manage tasks and bugs, and are these issues linked to pull requests (PRs)? (at least once)

### Bonus (max 2)
- [ ] **Project Board**: Does the project utilize a project board (e.g., GitHub Projects or Trello) to manage and prioritize work items?
- [ ] **Code Review Process**: Is there evidence of a code review process, with pull requests reviewed by peers or mentors before merging, ensuring code quality and collaborative learning?
- [ ] **Continuous Integration/Continuous Deployment (CI/CD)**: Has the project implemented CI/CD pipelines (using tools like GitHub Actions) to automate testing and deployment?

### Score (/5):

### Notes:

## Code Hygiene
- [ ] **Consistent Indentation**: Is the code indentation consistent throughout the application?
- [ ] **Clear Naming Conventions**: Are variables, methods, and classes named clearly and descriptively? Names should accurately reflect the purpose or functionality of the entity they represent.
- [ ] **Casing Conventions**: Does the code follow language-specific casing conventions? (e.g., snake_case for Ruby variables and methods, CamelCase for classes).
- [ ] **DRY Principles**: Are there examples of adherence to the DRY (Don't Repeat Yourself) principle? (eg queries are abstracted to model methods instead of view templates for reusability/readability)
- [ ] **Code Clarity**: Is the code easy to read and understand? Look for simple, straightforward implementations and avoid unnecessary complexity. Does the code include inline comments that explain "why" behind non-obvious logic? Over-commenting should be avoided; code should be self-explanatory wherever possible. Unused code should be deleted (not commented out).

### Score (/5):

### Notes:

## Frontend
- [ ] **Semantic HTML**: Is the project making effective use of semantic HTML elements to structure the content, ensuring that it's both accessible and SEO-friendly?
- [ ] **Styling**: Does the frontend employ CSS or CSS frameworks (like Bootstrap) for styling?
- [ ] **Template Usage for Reusability**: Are partial templates used to promote code reusability and maintainability for common UI components (e.g., navigation bars, forms, lists)?
- [ ] **Client-Side Interactivity**: Is JavaScript or JavaScript frameworks/libraries (e.g., jQuery) utilized to enhance the UI with dynamic content and interactive elements, reducing unnecessary page reloads?
- [ ] **Rails View Helpers**: Does the project leverage Rails view helpers (link_to, form_with, etc.) to streamline the generation of view code and enforce best practices in form and link creation?

### Bonus (max 2pts)
- [ ] **Responsive Design**: It looks and works great on all different devices (seamless user experience across desktop, tablet, and mobile)
- [ ] **Accessibility Considerations**: Are accessibility features (such as alt tags for images, ARIA roles) implemented to support users with disabilities and to comply with web accessibility standards?
- [ ] **Enhanced Navigation and Feedback**: Are breadcrumbs used to enhance site navigation? Are styled flashes or toasts implemented to provide clear, user-friendly feedback? (in a partial)


### Score (/5):

### Notes:

## Backend
- [ ] **Project Onboarding and Readability**: Is the project structured in a way that allows new developers to quickly understand and contribute? (For instance, is there a sample_data rake task, clear documentation, migrations run without error, and adherence to standard CRUD and MVC patterns?)
- [ ] **Data Model Design**: Is the data model well-designed, clear, and efficient, facilitating easy data manipulation and retrieval, while avoiding redundancy and promoting data integrity?
- [ ] **Security Practices**: Are security best practices followed, including secure storage of API keys and sensitive information (using .env or Rails credentials), enforcing HTTPS (config.force_ssl = true), and safeguarding against common vulnerabilities?
- [ ] **Association and Query Optimization**: Does the application efficiently use Rails association methods (belongs_to, has_many, etc.) and scopes to organize data relationships and perform optimized database queries?
- [ ] **Authorization and Access Control**: Is an authorization framework (such as Pundit) employed to manage user permissions and ensure secure access control across the application?

### Bonus (max 2pts)
- [ ] **Advanced Data Modeling**: Has the application utilized advanced ActiveRecord features, such as concerns, Active Record callbacks for model lifecycle management, or polymorphic associations to encapsulate business logic?
- [ ] **Business Logic**: Does the application abstract logic into service objects when appropriate?
- [ ] **Background Processing**: Are background jobs (eg ActiveJob) implemented for time-consuming processes, improving app performance and user experience?
- [ ] **API Development**: Does the project provide a well-documented JSON API for integration with other services or frontend frameworks?
- [ ] **Performance Optimization**: Is the Bullet gem (or similar) used in development to detect and reduce N+1 queries and other common performance bottlenecks?
- [ ] **Database Management**: Are additional features such as file upload (CSV) or custom rake tasks for database management included?

### Score (/5):

### Notes:

## Features (max 5pts)
- [ ] **Cloud Storage Integration**: Integration with cloud storage services (e.g., AWS S3) for handling file uploads and storage.
- [ ] **Payment Processing**: Implementation of a payment gateway (e.g., Stripe) for secure online transactions.
- [ ] **Custom Email Functionality**: Use of mailers (either through Devise or custom implementations) to send emails for account confirmation, password recovery, notifications, etc.
- [ ] **Advanced Search and Filtering**: Incorporation of advanced search and filtering capabilities (e.g., using Ransack) to improve data retrieval and user experience.
- [ ] **Mapping and Geolocation**: Use of mapping or geocoding libraries (e.g., Mapbox, Geocoder) to add location-based features to the application.
- [ ] **Hotwire**: Implementation of Hotwire, Turbo, or Stimulus to create a dynamic, highly interactive user interface without relying heavily on traditional full-page reloads.
- [ ] **Pagination**: Use of pagination libraries (e.g., Kaminari, will_paginate) to manage large sets of data efficiently on the UI.
- [ ] **Data Visualization**: Integration of charts, graphs, or other visual representations of data (e.g., using Chartkick) to provide insightful views of data to the user.
- [ ] **Dynamic Meta Tags**: Dynamic generation of meta tags for social media previews and SEO optimization, enhancing the application's presence on the web.
- [ ] **Web Scraping Capabilities**: Incorporation of web scraping functionality to extract data from external websites.
- [ ] **Chat GPT or AI Integration**: Implementation of Chat GPT or other AI services to provide intelligent responses or features. 
- [ ] **Internationalization (i18n)**: Support for multiple languages using internationalization techniques, making the app accessible to a global audience.
- [ ] **Admin and/or Business Insights Dashboard**: Creation of an admin panel and/or insights dashboard to provide valuable business intelligence or administrative capabilities.

### Score (/5):

### Notes:

## Technical Score (/30):
- Documentation (/5):
- Version Control (/5):
- Code Hygiene (/5):
- Frontend (/5):
- Backend (/5):
- Features (/5):
---
- Total: 

## Additional overall comments for the entire review may be added below:
