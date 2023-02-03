# What is ANR and how does it differ from a Crash?

<img src="https://user-images.githubusercontent.com/70295997/216533783-0127c21d-268f-4d73-982d-4a05b7b9174c.png" height=500>


An ANR (Application Not Responding) is different from a crash in that a crash typically occurs when an app encounters an unexpected error or exception and is forced to close. An ANR, on the other hand, occurs when an app is unresponsive but has not crashed. In analogy, an __ANR__ means an app is _comatose_ 😵‍💫, a __Crash__ means an app is _dead_ 😵.

<img src="https://user-images.githubusercontent.com/70295997/216539653-a21450a6-99a3-4db0-9e28-ff83a0040493.png" height=500>

ANRs and crashes are two different types of issues that can occur during mobile testing.

__ANR__ refers to a situation where an _app becomes unresponsive or frozen and is not responding to user input. This can be caused by a variety of factors, such as a long-running operation that is blocking the main thread, or a problem with the app's design or implementation that is causing it to become unresponsive._

__Crashes__, on the other hand, refer to situations where an _app encounters an unexpected error or exception and is forced to close. This can be caused by a variety of factors, such as an unhandled exception, a null pointer reference, or an issue with the app's code or configuration._

To test for ANR and Crashes, developers and testers typically use a combination of manual testing and automated testing tools. Manual testing involves manually interacting with the app and verifying that it behaves as expected, while automated testing involves using testing tools and frameworks to automatically execute a series of tests on the app.

To identify and troubleshoot ANR and crash issues, developers and testers will typically need to analyze the app's logs and performance data to identify the root cause of the problem. This might involve analyzing system logs, profiling the app's performance, and looking for patterns or trends that can help identify the source of the issue.

Overall, ANR issues can be frustrating for users and can negatively impact the user experience of an app. It is important for developers and testers to carefully test and debug their apps to ensure that they are responsive, stable and perform well under a variety of conditions.

----

[ANRs](https://developer.android.com/topic/performance/vitals/anr)

[Crashes](https://developer.android.com/topic/performance/vitals/crash)

[Debug your Android app based on ANR tags in the Crashlytics dashboard](https://firebase.google.com/docs/crashlytics/debug-anr-errors)
