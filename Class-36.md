# Authentication With Cognito


 1. **Where in your application should you check the current auth session?**
      - Before accessing protected resources: If your application has areas or features that require authentication,
        check the auth session before allowing access to these resources.
      - During app initialization: You might want to check the auth session when your app starts to determine whether 
        the user is already signed in.
 2. **What is the command that is used to push your changes to the cloud?**

      `amplify push`
 3. **What does Amplify Auth do for your application?**
      - Provides authentication services for your application. It includes a set of pre-built UI components and an 
        easy-to-use API for common authentication workflows. Amplify Auth with Cognito supports features such as:

          - User sign-up and sign-in: Allowing users to create accounts and sign in securely.
          - User attributes: Managing additional user data beyond basic authentication, such as email, phone number, etc.
          - Password recovery: Enabling users to reset their passwords if forgotten.
          - Multi-factor authentication (MFA): Adding an extra layer of security with options like SMS or Time-based One-Time
            Password (TOTP).
         - Social identity providers: Integrating with social logins like Google, Facebook, and others.