An example Chef project
---

This is a simple project that demonstrates how to test a Chef cookbook with Cyclid.

### A note about Test Kitchen

This example uses the kitchen-docken plugin to run Test Kitchen on top of Docker. This works fine if you're running Cyclid with any of the Cloud builders like Google Compute Engine or Digitalocean, but might not work so well if you're using Docker or LXD based build hosts. So just be aware that if you're testing your own Cyclid installation: it may be easier if you remove or disable running Test Kitchen in this example!