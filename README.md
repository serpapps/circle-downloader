# Circle Downloader (Browser Extension for Chrome, Firefox, Edge, Opera)

The **Circle Downloader** browser extension makes it simple to save Circle community videos, coaching calls, and embedded content directly to your computer — in their original quality — for offline access anytime. Whether you're a student, professional, or course creator, this tool ensures you'll never lose access to valuable learning material again.

Unlike struggling with manual recording tools or juggling multiple services, this extension works **right inside your browser**, automatically detecting videos on any Circle post and providing a clean, one-click download experience. No re-encoding, no watermarks, and no unnecessary tracking.


<a href="https://www.youtube.com/watch?v=_8XKKHj0eLs" target="_blank">
<img src="https://raw.githubusercontent.com/devinschumacher/uploads/refs/heads/main/images/how-to-download-circle-so-videos-for-free-hls-m3u8-streams.jpg" width="700px">
</a>


### Why It's Different

* **Fast downloads, no waiting** – files are saved directly, without quality loss or re-processing
* **Original quality preserved** – download in 480p, 720p, 1080p, or higher depending on source video
* **Works everywhere** – public, embedded (YouTube, Vimeo, Wistia, Loom), and private Circle posts
* **Member-only content support** – uses your existing Circle login to access restricted posts securely
* **Lightweight & transparent** – minimal permissions, no hidden data collection, privacy-first design
* **Offline freedom** – watch lessons, coaching calls, and recordings without buffering or internet access

### Who It's For

* 🎓 **Students & course members** – save lecture replays and cohort recordings before they expire
* 🎥 **Content creators & instructors** – back up course material, member content, and client projects
* 🧑‍💼 **Business professionals** – keep access to training, onboarding, and team meetings offline
* 📚 **Team leaders** – organize video libraries of company training with meaningful filenames
* 🌍 **Traveling professionals** – enjoy your favorite courses and materials offline while commuting

### Key Features

* 🔎 Auto-detects Circle videos, YouTube, Vimeo, Wistia, and Loom embeds on any post
* 📺 Supports member-only and private community content with automatic authentication
* ⬇️ Download in original quality with smart quality selector showing bitrate and file size
* 🖼 Preserves video metadata, titles, and descriptions for organized archiving
* ⚡ Fast & reliable downloads with automatic HLS/DASH stream merging
* 🛡 Privacy-first design with all processing on your device, zero tracking
* ⏳ Real-time progress tracking with speed, time remaining, and download status
* 🔄 Batch download queue – add multiple lessons and process them automatically
* 📲 Desktop notifications alert you when downloads complete or fail
* 🎯 Concurrent downloads – run up to 3 at once with unlimited queuing
* 🗂 Custom folder selection for organized file storage and archiving
* 🔐 Respects Circle authentication – member-only videos download securely

### Privacy Commitment

We designed this extension with **user privacy at the core**:

* No data sharing with third parties
* Only the minimal permissions needed for downloads and authentication
* Preferences, quality settings, and download history stored locally on your device only
* Transparent documentation for every requested permission
* All video processing happens on-device, never sent to external servers

---

## 🔗 Links

- 🎁 Get it [here](https://serp.ly/circle-downloader)
- 🔒 View [Permissions Justification](PERMISSIONS.md)
- ❓ Check FAQs [here](https://github.com/orgs/serpapps/discussions/categories/faq)
- 🐛 Report bugs [here](https://github.com/serpapps/circle-downloader/issues)
- 🆕 Request features [here](https://github.com/serpapps/circle-downloader/issues)

### Resources

- 💬 [Community](https://serp.ly/@serp/community)
- 💌 [Newsletter](https://serp.ly/@serp/email)
- 🛒 [Shop](https://serp.ly/@serp/store)
- 🎓 [Courses](https://serp.ly/@serp/courses)

## Table of Contents
- [Solving these problems](#solving-these-problems)
- [Perfect for](#perfect-for)
- [Live & Planned Features](#live--planned-features)
- [Permissions & Privacy](#permissions--privacy)
- [Installation Instructions](#installation-instructions)

## Solving these problems

- Community courses disappear before you finish them
- Coaching calls and cohort recordings expire without warning
- Videos buffer, freeze, or fail on slow internet connections
- Need to rewatch lessons offline but there's no built-in download button
- Platforms that don't let you organize and archive your learning materials
- Mixed embedded content (YouTube, Vimeo, Loom) scattered across one post
- Member-only content that you own but can't access offline

## Perfect for

- Students saving course material and lectures before posts disappear
- Course creators backing up member-only content and cohort recordings
- Coaches preserving training material and client calls offline
- Professionals downloading team onboarding and training videos
- Anyone wanting offline access to their invested learning materials

## Live & Planned Features

- ✅ Works Everywhere (Circle, YouTube, Vimeo, Wistia, Loom)
- ✅ Privacy Focus (no tracking, local processing only)
- ✅ Auto-detect Videos (intelligently finds all media on posts)
- ✅ Member-Only Support (uses your Circle login securely)
- ✅ Concurrent Downloads (run up to 3 simultaneously)
- ✅ Batch Queue System (add multiple videos, process automatically)
- ✅ Quality Selector (choose resolution and bitrate)
- ✅ Download Progress Tracking (real-time speed and ETA)
- ✅ Community Support (active GitHub discussions)
- ✅ Bug Reporting & Feature Requests (GitHub issues)
- ✅ Zero Ads (clean, distraction-free experience)
- ✅ Regular Updates (kept current with Circle changes)
- ✅ Desktop Notifications (alerts when files are ready)

## Permissions & Privacy

We believe in transparency and minimal permissions. Our extension only requests the permissions absolutely necessary for core functionality:

- **Privacy First**: No data tracking, no analytics, no personal information collection
- **Minimal Permissions**: Only 12 permissions required, each with clear justification
- **Local Storage**: Your preferences, quality settings, and download history stay on your device
- **Transparent**: Full documentation of why each permission is needed


## Permissions Justifications

### downloads
Required to programmatically initiate and manage video file downloads to your computer. The extension needs to trigger downloads of processed Circle videos and tracked download progress for the queue system.

### activeTab
Needed to access and analyze the currently active Circle tab to detect video content, extract video metadata, and inject necessary scripts for video detection.

### storage
Used to persist user preferences (quality settings, download location), download history, authentication tokens, and temporary video processing data across browser sessions.

### tabs
Necessary to query and interact with browser tabs to detect Circle community pages, inject content scripts for video detection, and manage the download queue across multiple tabs.

### scripting
Required to inject content scripts into Circle pages for video detection, extract video metadata from native uploads and embedded players, and communicate between the extension and web page content.

### offscreen
Used to create offscreen documents for complex video processing tasks (HLS/DASH parsing, stream merging) that require additional computational resources without blocking the main UI.

### notifications
Sends desktop notifications when downloads complete, encounter errors, or when queue status changes. Helps you track progress without keeping the popup open.

### contextMenus
Adds quick download options to Circle posts so you can save videos directly from the post context menu without opening the popup every time.

### host_permissions
Grants controlled access to Circle domains (circle.com, circle.so) and video CDN services (vimeo.com, youtube.com, wistia.com, loom.com, and their CDN partners) to extract video streams and metadata.

### cookies
Needed to access your Circle authentication cookies to download member-only or password-protected videos that require user authentication.

### offscreen
Handles complex video stream processing in the background without freezing the user interface during HLS/DASH segment merging.

---

## How to Download Circle Videos for Private Communities

The **Circle Downloader** extension respects your existing Circle login and permissions. If you can view a post in your community — whether it's public, member-only, or restricted — the extension can download it using your authentication.

**Key Points:**
- Your existing Circle login is used automatically in the background
- No separate passwords or credentials needed
- Works for private communities, restricted posts, and member-exclusive lessons
- Downloads happen entirely on your device with no data sent to third parties

---

## Frequently Asked Questions

### What videos can I download?

Circle Downloader captures Circle native video uploads and embedded players from YouTube, Vimeo, Wistia, and Loom. You can download content from any Circle post you have access to—including member-only and private community posts. The extension automatically detects all available media when you're viewing a post.

### How many videos can I download at once?

You can run up to 3 simultaneous downloads. Additional videos are added to an automatic queue that starts processing as soon as a download slot opens up. This keeps your device responsive while letting you batch-queue an entire lesson series.

### What quality options are available?

Circle Downloader displays every quality rendition provided by the video source. Each option shows the resolution, bitrate, and estimated file size so you can choose based on your storage space and bandwidth. The extension remembers your quality preference and applies it automatically to future downloads.

### Does downloading preserve the original quality?

Yes. For adaptive streams (HLS/DASH), the extension downloads segments and merges them into a single MP4 file without re-encoding. This means you get the exact quality provided by the platform. Direct MP4 uploads are saved at full quality instantly.

### Where do my downloaded files go?

You can choose any folder on your computer. The extension lets you set a default download location, and you can override it for individual downloads. Files are saved with clean, descriptive titles.

### Can I download member-only or private content?

Yes. If you can view the post in Circle, the extension can download it using your existing Circle login. You don't need separate credentials—authentication happens automatically in the background.

### Is there a free trial?

Circle Downloader is a paid extension with no free trial period. Once purchased, you get lifetime access with all future updates included. All sales are final, but we stand behind the product and include email support.

### What about my privacy?

All processing happens locally on your device. Nothing is sent to external servers except the download requests to the original video hosts (Circle, YouTube, Vimeo, etc.). Your Circle login credentials are never shared. Download history and preferences are stored only in your browser.

### Which browsers are supported?

Circle Downloader works on Chrome, Edge, Firefox, Brave, and Opera. It's available for Windows, macOS, and Linux.

### Is this legal?

See our detailed [Legal & Compliance Guide](#legal--compliance) section below for important information.

---

## Legal & Compliance

### Terms of Service Compliance

#### Circle.so Terms Key Points:
- **Personal Use**: Downloads for personal, non-commercial use generally allowed for content you own or have permission to access
- **Copyright**: Respect copyright and intellectual property rights
- **Redistribution**: Prohibited without explicit permission from the copyright holder
- **Commercial Use**: Requires proper licensing agreements with content creators
- **Member-Only Content**: Access and download only within scope of your membership

#### Best Practices:
- Only download content you created, own, or have explicit permission from the rights holder to access
- Respect platform terms of service and community guidelines
- Use reasonable download speeds and respect rate limits
- Protect your privacy by using a reputable VPN before initiating downloads
- Respect creator intellectual property—downloaded content is for personal use unless you have broader rights

### Content Protection

#### Handling Member-Only Content:
- Download only content from communities you're a member of
- Respect access restrictions and membership-only content policies
- Do not share or redistribute member-only videos
- Honor any restrictions placed by community creators

#### Privacy Considerations:
- Use a VPN for additional privacy during downloads
- Clear your download history if needed
- Be mindful of what you download and store locally
- Respect platform privacy policies

**DISCLAIMER:** We are not attorneys and cannot provide legal advice. Laws vary significantly by country, platform, and content type. Please consult a qualified legal professional about your specific situation.

---

## Troubleshooting

### Videos Not Detecting

**Problem**: The extension isn't detecting videos on Circle posts.

**Solutions:**
1. Refresh the Circle post page
2. Make sure you're logged into your Circle community
3. Try clearing browser cache and reloading
4. Check that JavaScript is enabled in your browser
5. Disable browser extensions that might interfere (ad blockers, etc.)

### Download Failures

**Problem**: Downloads are stopping or failing midway.

**Solutions:**
1. Check your internet connection stability
2. Try downloading in a lower quality
3. Reduce concurrent downloads to 1
4. Ensure you have sufficient disk space
5. Try a different browser to rule out browser-specific issues

### Authentication Issues

**Problem**: "Not authenticated" or member-only content won't download.

**Solutions:**
1. Make sure you're logged into Circle in your browser
2. Refresh the page and try again
3. Check that cookies are enabled
4. Log out and log back into Circle
5. Clear browser cookies for circle.so and try again

### File Playback Issues

**Problem**: Downloaded MP4 files won't play.

**Solutions:**
1. Try a different video player (VLC, Windows Media Player, QuickTime)
2. Check file format—should be .mp4
3. Ensure download completed fully (check file size)
4. Update your video player to the latest version
5. Try re-downloading the video

---



## Related
- [Circle Downloader](https://github.com/serpapps/circle-downloader)
- [How to download circle videos for free](https://gist.github.com/devinschumacher/5910965cbff1e563e120dbd2df06d4ba)
