# Grav Tinker
Every commit shows a diffrent example. Use git log to find a specific example and use 'git checkout'. Read this readme again.

All examples assume you are run this theme on a fresh grav installation.

## Select a Background Image from Admin Panel
This example shows how to create a filepicker which enables the user to pick a file as a background. See the qoute.yaml and the qoute.html.twig.

1. Create a modular page
2. Create a qoute module
3. Start a test server (you can use 'npm run live')
3. Find the module in the admin panel -> pages -> %your-modular-page% -> qoute
4. Upload an image via the media order and select it as background image
5. Navigate to your modular maybe some thing like this 'https://127.0.0.1:8000/%your-modular-page%'
6. Inspect code