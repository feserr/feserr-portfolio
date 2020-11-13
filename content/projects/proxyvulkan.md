{
  "title": "Proxy Vulkan",
  "date": "2020-06-24T12:41:05-05:00",
  "image": "",
  "link": "https://github.com/feserr/proxy-vulkan",
  "description": "Proxy Vulkan is an open source to send local Vulkan calls to the cloud.",
  "tags": ["C++","Vulkan", "TCP-IP", "CMake", "Cap'n Proto", "RPC"],
  "fact": "",
  "featured":true
}

Proxy Vulkan is an open source to send local Vulkan calls to the cloud.

Use the "proxy library" technique to override the Vulkan library so an application will use this one instead of the real. This give us the ability to intercept all the call to the original API and send them to the cloud to run in there.

In contrast to tipical game streaming system that you send the user inputs and the cloud returns you the result image, this system run the application locally but the Vulkan calls are executed at a cloud.

You will be able to execute any Vulkan application with the power of the cloud.
