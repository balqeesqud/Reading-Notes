 ## Location

 1. What are the benefits and downfalls of using the ‘getLastLocation()’ method to get your device’s location?
    #### Benefits:
    - **Quick Retrieval:** `getLastLocation()` is a quick and convenient method to obtain the last known location of the
      device without the need for continuous location updates.
    - **Low Power Consumption:** Since it relies on the last known location, it doesn't require continuous use of GPS, 
      resulting in lower power consumption.

    #### Downfalls:
    - **Possibly Outdated:** The main drawback is that the last known location might be outdated, especially if the 
      device has been stationary for a while or if the location provider is disabled.
    - **No Real-time Updates:** It does not provide real-time updates, making it unsuitable for scenarios requiring 
      up-to-the-moment location data.

 2. What about the `getCurrentLocation()` method?
    #### Benefits:
    - **Real-time Updates:** `getCurrentLocation()` is useful when you need real-time updates of the device's location.
    - **Customization:** It allows you to specify location request parameters such as update interval, priority, and 
      accuracy, giving you more control over the location updates.

    #### Downfalls:
    - **Higher Power Consumption:** Continuous location updates can lead to higher power consumption, which might be a
      concern for battery-sensitive applications.
    - **Increased Resource Usage:** Frequent location updates can utilize system resources, potentially impacting the 
      performance of the app and other running processes.

    #### General Considerations:
    - **Permission Requirements:** Both methods require appropriate location permissions declared in the
      AndroidManifest.xml file.
    - **Fallback Strategies:** It's often beneficial to implement fallback strategies, combining both methods.
      For example, start with `getLastLocation()` for a quick initial position and then switch to `getCurrentLocation()`
      for real-time updates if needed.

