# Bright XDR 
__BrightXDR__ is a proof-of-concept implementation that demonstrates how to upscale display content to XDR/HDR extra brightness on macOS. This is a demo showing one of possible implementations.

> The main idea behind this project is to provide an open source and free-to-use alternative to existing apps that offer similar functionality for a price of up to &euro;20. I believe that everyone should have access to powerful tools that enhance their display experience, regardless of their budget.

## About 
The app uses MetalKit to overlay the CIImage with a transparent color in EDR color space over the display windows while applying color blending filter.

## Preview 
> Screen captured on maximum system brightness with __Apple XDR (P3-1600 nits)__ display preset.
<img src="https://user-images.githubusercontent.com/21260939/228393300-34f48989-ba81-45a0-9364-3b66252f6a36.jpg" alt="Screenshot" width="400">

## Requirements
Supported devices: Apple MacBook Pro with 14 or 16 inches and Apple Pro Display XDR.

## TODO
- __Fullscreen & System-wide__ - The app currently works on a selected part of the display only. It needs to be extended to support fullscreen and system-wide overlay.
- __Forward touches__ - Pass all touches/events through a window.
- __Performance__ - The app needs to be optimized for better performance and to reduce resource usage.

## Literature

If you're interested in learning more about the technologies used in this app, check out these articles and videos:
- [Generating an Animation with a Core Image Render Destination](https://developer.apple.com/documentation/coreimage/generating_an_animation_with_a_core_image_render_destination)
- [WWDC 2022 Session 10114: Display EDR content with Core Image, Metal, and SwiftUI](https://developer.apple.com/videos/play/wwdc2022/10114/)
- [WWDC 2022 Session 10113: Explore EDR on iOS](https://developer.apple.com/videos/play/wwdc2022/10113/)

## Alternatives

If you're looking for alternative applications that provide similar functionality, you might want to check out:
- [Vivid](https://www.getvivid.app/)
- [Lunar](https://github.com/alin23/Lunar)
- [BetterDisplay](https://github.com/waydabber/BetterDisplay)
- [TotalXDR](https://junebytes.com/totalxdr)
