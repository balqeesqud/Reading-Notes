## Intent Filters

 1. **What are the three criteria an acticity’s intent filter must fulfill in order for a system to send an intent to 
    that activity?**
    - Action: Describes the general action to be performed, such as ACTION_VIEW for viewing data or ACTION_SEND for 
      sending data.
    - Data: Specifies the type of data to be acted upon, such as a specific MIME type, URI, or a certain data scheme.
    - Category: Represents additional information about the kind of component that should handle the intent, such-as-  
      CATEGORY_LAUNCHER for the main entry point of the application.
 2. **How does an activity retrieve the Intent that it was started by?**
    In Android, an activity can retrieve the intent that started it by calling getIntent() method. This method returns 
    the Intent that started the activity.
 3. **Explain intents to a non-technical friend.**
    Think of an intent as a message or a request that one part of an Android app (or even different apps) sends to 
    another part. It's like asking another component to perform a specific action or provide some information. 
    For example, when you tap on an email app icon, it sends an intent to the activity responsible for composing emails,
    telling it to open up and let you write a new email.

## Implicit vs. Explicit Intents

 1. **Compare and contrast implicit and explicit intents.**
    
    - **Explicit Intents:**
      1. Specify the target component (activity, service, etc.) by its class name.
      2. Used for intra-application communication.
      3. Directly invoke a specific component within the app.
      
    - **Implicit Intents:**
      1. Do not specify the target component's name.
      2. Used for inter-application communication.
      3. Describe a general action, and the Android system determines the appropriate component to fulfill that action
         based on the device's installed apps and their declared intent filters.
 2. **What is the primary information contained within an Intent?**
      - **Action:** Describes what to do, like opening a web page or dialing a phone number.
      - **Data:** Specifies the type of data on which the action should be performed, such as a URL or a contact.
      - **Extras:** Additional information passed as key-value pairs, providing more details for the action.
      - **Component:** For explicit intents, the target component (e.g., the class name of an activity).

