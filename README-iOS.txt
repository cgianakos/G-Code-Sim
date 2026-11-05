G-Code Simulator on iPhone and iPad
===================================

Apple only installs apps through the App Store, TestFlight or Xcode, so the iPhone/iPad version
is an offline web app. Once added to the Home Screen it opens full screen like an app and works
without a connection.

STEP 1 - Put the folder "GCodeSimulator-WebApp" on any HTTPS web server (one time)
   Any of these works:
   a) Your company intranet web server: copy the folder to a site folder, for example
      https://intranet.yourcompany.com/gcodesim/
   b) GitHub Pages (free): create a repository, upload the files from the folder,
      then Settings > Pages > Deploy from branch. You get https://<name>.github.io/<repo>/
   c) Netlify Drop (free): drag the folder onto https://app.netlify.com/drop
   The files are static; no server software or database is needed.

STEP 2 - On each iPhone/iPad
   1. Open the address in Safari.
   2. Tap the Share button, then "Add to Home Screen".
   3. Open G-Code Simulator from the Home Screen once while online. After that it works offline.

Opening programs: tap Open and pick the file from Files (iCloud Drive, OneDrive, SharePoint,
On My iPhone, or files saved from email). Tool lists (CSV/Excel) work the same way.

Tips
 - On iPhone, use More > Simulation quality > Draft or Standard.
 - Rotate the iPad to landscape for the side-by-side program view.
 - Updating: replace the files on the server; devices pick up the new version the next time
   they open the app online.

Quick test without hosting: the shared claude.ai link to this app also works in Safari, but it
needs a connection each time and cannot save files.
