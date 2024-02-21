## The MERN Stack Challenge: Day 06 - User Experience & Security Enhancements 🪴

**Building a Full Stack MERN App in Just 10 Days!**

This README details the progress made on Day 06, focusing on improving user experience and implementing security measures. 

**Key Focus Areas:**

* **Authentication-based View Restrictions:**
    - Replaced generic 'login/logout' options with dynamic ones based on user authentication status.
    - Ensured only relevant features are accessible depending on authentication.
* **Personalized Greetings:**
    - Replaced generic welcome messages with personalized greetings using the user's username.
* **isLoggedIn Middleware:**
    - Created a middleware function to verify user authentication with Passport.js.
    - Utilized this middleware to restrict access to certain views based on login status.
* **Session Expiry:**
    - Configured session expiry for enhanced security and user management.
    - Set sessions to expire after 7 days to mitigate inactive session risks.
* **User Role Selection:**
    - Introduced the ability for users to select their role (Seller/Buyer) during signup.
    - This lays the foundation for role-based access control and personalized experiences.
* **Role-based Access Control:**
    - Implemented middleware functions:
        - `isSeller`: Verifies if the user is a seller, granting access to relevant features.
        - `isProductAuthor`: Ensures only the product author can edit/delete it.
    - Utilized `equals()` for secure ObjectID comparison in access control logic.

**Benefits:**

- Improved user experience with personalized greetings and relevant feature access.
- Enhanced security through authentication-based restrictions and session expiry.
- Foundation laid for more granular control with role-based access control.

**Stay Connected:**

- Follow this repository for ongoing updates and insights on the 10-day MERN Stack challenge!
- Share your thoughts and feedback to contribute to this journey.
- Let's connect and exchange ideas on LinkedIn! Visit https://www.linkedin.com/in/balram-kusharam/ .

**Additional Notes:**

- For detailed code examples, refer to the specific task sections within the repository.
- This README provides a high-level overview, and the code itself may contain additional configurations and logic.
- Consider exploring further enhancements like additional security measures and more refined role-based access control rules.
 
