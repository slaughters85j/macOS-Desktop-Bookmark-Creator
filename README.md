# macOS Desktop Bookmark Creator
 - Mimics the same ability when using Safari in iOS to save a webpage to the home screen (iOS) Desktop (macOS) so it can be launched like an application.    Only tested on Apple Silicon M1 but imagine it will work on Intel too since I created it with Apple Script.
 - Working on attemping to capture the primary favicon for the website and adding it as the application wrapper.

# Environment
- Browser: Safari v16.x
- macOS: Ventura v13.x

# Built Application Use
Apple Script Application pre-assembled should work by downloading and running from any location.  I have mine in the the applicaiton directory.  When first used, Apple Security will/should prompt you to accept permissions to access the Desktop folder.  Once you grant the access rights, it should continue to work without any issues.

# Building the Application Yourself
# The Apple Script file does not contain any user specific directories
1. Clone repo or download Apple Script as .applescript extension
2. Double-click the .applescript file to open it in Script Editor
3. Click the Hammer (build icon) to build the Apple Script and check for syntax errors
4. Chose File --> Export --> Application and name the application with whatever and wherever you want.
