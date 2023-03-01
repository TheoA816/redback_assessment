# Brainstorming

Part 1
 - only pop last brace causing error, nothing fancy

Part 3
 - implementation involves clicking on logo to toggle on/off, with layout change according to screen width (landscape to portrait)
 - because of animation, bug exists where if switching from portrait to landscape layout, the meter which is supposed to be off screen zooms past

Part 4 (React jest)
 - React test not implemented perfectly
 - Temperature color changes from yellow to dark orange depending on value (red if erroneous) but over a certain interval so color change is smooth
 - Do not know how to make wait a certain interval for color change to occur

Part 4 (Docker)
 - Docker gets built and push
 - But when trying to run data-emulator locally (set its port to 12000 same with streaming-service)
 - Get ECONNREFUSED error, regardless of whether streaming-service is running or not
 - Other 2 (streaming-service and battery-ui) works fine
