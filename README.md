An example Chef project
---

This is a simple project that demonstrates how to test a Chef cookbook with Cyclid.

### A note about Test Kitchen

We love Test Kitchen, but you'll note that the Cyclid job doesn't actually run it. That's because Test Kitchen needs to create its own virtual machines or containers to run the tests.

Perhaps you use something like the kitchen-google driver to create Test Kitchen instances in the cloud, but this simple example can't assume you have a Google account; even if it did, we can't provide all of the login details & keys needed here.

So while it's possible, we didn't want to over-complicate this example.