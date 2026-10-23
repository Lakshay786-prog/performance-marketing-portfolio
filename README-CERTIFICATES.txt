Certificate image path fix

The HTML uses relative paths such as:
assets/certifications/google-analytics.jpeg

Keep index.html at the repository root and upload the complete assets/certifications folder to GitHub. Do not use the Windows absolute path C:\\Users\\... in HTML; it will not work on Render. These relative paths work in VS Code Live Server and on Render.

Keep your existing profile/project images in the existing assets folder; this package only adds the certifications folder and updated index.html.
