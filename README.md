Project Documentation: "Next to Go"

Introduction

The "Next to Go" Android app is developed to provide users with a time-ordered list of upcoming horse, harness, and greyhound races. The app fetches race data from an API and ensures that users always see 5 races sorted in ascending order by their advertised start time. Races that are one minute past the start time are automatically removed from the list. The app allows users to filter races by category, displays countdown timers for each race, and supports automatic data refresh. The app is built using Jetpack Compose and Kotlin, adhering to scalable layouts and material design principles.

Features

2.1. Time-Ordered Race List

The app presents a list of races that are always sorted by their advertised start time in ascending order. This ensures that users can easily identify the upcoming races based on their scheduled start time.

2.2. Exclusion of Races Past Start Time

Races that are one minute past their advertised start time are automatically removed from the list. This prevents users from seeing races that have already started or are no longer relevant.

2.3. Category Filtering

Users can filter the race list into three categories: horse racing, harness racing, and greyhound racing. This feature allows users to view races from specific categories according to their preferences.

2.4. Deselecting Filters

Users have the option to deselect all filters, resulting in the display of the next 5 races from all racing categories. This provides flexibility in exploring races without category restrictions.

2.5. Countdown Timers

For each race in the list, the app displays a countdown timer that indicates the time remaining until the race's advertised start. This feature helps users quickly assess when each race will begin. 2.6. Always Showing 5 Races
The app ensures that users always see a list of 5 races. If there are fewer than 5 races available, the app will display the available races and fill the remaining slots with placeholder entries.

2.7. Automatic Data Refresh

The app automatically refreshes the race data at regular intervals, ensuring that users have the most up-to-date information about the next races. This feature provides a seamless and real-time experience for users.

Technical Details

3.1. Jetpack Compose and Kotlin

The app is developed using Jetpack Compose, a modern UI toolkit for building Android apps, and Kotlin, a statically typed programming language. Jetpack Compose simplifies UI development by providing a declarative approach, while Kotlin offers concise and expressive code.

3.2. Testing

The app includes testing for key files to ensure their functionality and reliability. Although full coverage is not necessary, important components and features are adequately tested to maintain code quality.

3.3. Scalable Layouts

The app utilizes scalable layouts to accommodate changes in font scale. This ensures that the app's UI remains visually appealing and usable across different devices and font settings.

3.4. Material Design Elements

Material design principles and elements are employed in the app's UI to create a consistent and intuitive user experience. By leveraging material design, the app adheres to industry best practices and provides familiarity to users.

3.5. Optional Features

The app includes optional features such as data binding.
 
Dependencies and References

The app utilizes the following dependencies and references:

4.1. Retrofit

Retrofit is used as the API client library for making network requests and retrieving race data from the provided API. It simplifies the network communication process.

4.2. Gson

Gson is employed for parsing JSON responses received from the API. It facilitates the conversion of JSON data into Kotlin objects for easier data handling.

4.3. Interceptor

The OkHttp logging interceptor is used to log network requests and responses for debugging and troubleshooting purposes.

4.4. LazyColumn (RecyclerView)

The LazyColumn component in Jetpack Compose is utilized to create a scrollable list of races. It offers optimized performance by rendering only the visible items on the screen.

4.5. Material Design for Android

Material Design guidelines and components provided by the Android Developers website are referenced to ensure the app follows the established design principles and offers a cohesive user experience.

Conclusion

The "Next to Go" Android app effectively fulfills the requirements by providing users with a time-ordered list of upcoming races. With its features such as race sorting, exclusion of races past start time, category filtering, countdown timers, and automatic data refresh, the app delivers a convenient and engaging racing experience. Developed using Jetpack Compose and Kotlin, the app adheres to scalable layouts and material design principles, ensuring a visually appealing and user-friendly interface. The inclusion of optional features such as data binding enhances the app's functionality.
