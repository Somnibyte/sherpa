# iOS App Store Submission Checklist

If you need some quick advice, check out this [App Submission](https://drive.google.com/a/intrepid.io/file/d/0B6c_wNPk_qCbQjBSNzFBMi1sOTQ/view?usp=sharing) video tutorial. The tutorial takes you from creating a new Xcode project to submitting a build to iTunes Connect. Otherwise follow these steps:

- Sign up for Apple Developer Program account (requires DUNS number for businesses)
- If the app communicates with custom hardware, send hardware to Apple to use while they review the app.
- Gather certificates
    - Create an iOS distribution certificate using the Apple Developer Portal
    - Create prodution APNS certificates
    - Upload APNS certificates to push notification provider (e.g. Urban Airship, Localytics)
- Create an App ID that matches the project’s bundle identifier, with proper entitlements (push, game center, etc.) using the Apple Developer Portal
- Metadata
    - App title
        - Not the same as springboard title (on phone)
        - Good to add keywords here
        - Unlimited character count, though titles will be truncated
    - App version (must match version number in binary)
    - App SKU (really not used for anything; usually “appname_date”)
    - App description as it will appear in the app store
    - App store category & optional subcategory
    - Price (or free)
    - Country availability
    - What’s new description (only for updates, not first-time submission)
    - Localized non-english descriptions if applicable
    - Keywords (100 characters)
        - Don’t add spaces after commas separating keywords
    - Large app icon (1024 x 1024)
    - At least one screenshot to appear in the app store for each platform (640x1126 iPhone, 2048x1536 iPad)
        - Best to have several, annotated shots
    - WatchKit icon & screenshots (if applicable)
    - EULA (if different from the default)
    - Demo account information for Apple reviewers
    - Extra instructions for Apple reviewers (if applicable)