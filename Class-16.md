# Creating User Accounts and Authenticating Users

## Spring Security overview

   1. What does it mean to authenticate a user?
      To authenticate a user means to verify and confirm the identity of an individual or entity trying to access a
      system, application, or resource. Authentication ensures that the user is who they claim to be. It typically 
      involves the user providing some form of credentials, such as a username and password, biometric data, or a 
      token, which are then checked against stored or trusted information. Successful authentication grants the user 
      access to the requested system or resource.

   2. What does it mean to authorize a user?
      To authorize a user means to determine and grant permissions or access rights to an authenticated user based on
      their identity and the actions they are allowed to perform within a system, application, or resource. 
      Authorization ensures that authenticated users only have access to the specific functionalities or data that they 
      are permitted to use. It involves defining and enforcing access control policies, such as role-based access 
      control (RBAC) or attribute-based access control (ABAC), to specify what actions a user can take.

   3. What are the three possible outcomes of the AuthenticationManager’s authenticate() method?
      - **Successful Authentication:** returns an Authentication object with authenticated=true.
      - **Failed Authentication:** his outcome occurs when the user provides incorrect or invalid credentials, and the 
        system cannot verify their identity. Authentication fails, and the user is denied access.
      - **Indeterminate Authentication:** returns null. This outcome happens when the authentication manager cannot
        decisively determine the authentication status based on the provided input.

## Spring Auth cheat sheet 
   ![Spring Auth Cheat Sheet](SpringAuthCheatSheet.md)


##  Things I want to know more about

- Authentication and Authorization Basics: 
  Understand the fundamental difference between authentication (verifying identity) and authorization
  (granting access rights).
- User Authentication:
  Understand how to authenticate users using Spring Security's authentication mechanisms.
