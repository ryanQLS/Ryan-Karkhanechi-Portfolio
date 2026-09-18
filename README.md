# Ryan Karkhanechi — Film portfolio

## Put your website online (no coding or software installation)

1. Download the ZIP. On Windows, right-click it and choose **Extract All**.
2. On GitHub, create a **new public repository** named **film-portfolio**. Tick **Add a README file**, then create it.
3. In the repository, choose **Add file → Upload files**.
4. Open the extracted folder. Select **index.html**, **film.mp4**, **preview.mp4**, and **poster.jpg** and drag those four files into GitHub. Upload the files themselves, not the ZIP or the enclosing folder. The file list in GitHub must show index.html directly at the top level.
5. Choose to commit directly to **main**, then click **Commit changes**.
6. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**. Set the branch to **main** and the folder to **/(root)**. Click **Save**.
7. Wait for deployment, then refresh Settings → Pages and click the website link GitHub displays.

For account ryanQLS and repository film-portfolio, the expected address is https://ryanQLS.github.io/film-portfolio/ after deployment succeeds.

## Preview before uploading

Double-click **index.html** inside the extracted folder. Keep all four site files together. Click **Play film** to watch with sound. The background preview is muted. Some browsers block background autoplay; the poster remains visible and the main film can still be played.

## What is included

- index.html — the complete site, including design and project information
- film.mp4 — your full 1080p video, compressed for browser upload with its audio
- preview.mp4 — a short silent background loop
- poster.jpg — a still extracted from your video
- README.md — these instructions; uploading this file is optional

Your film is temporarily titled **Timeline 1**, matching the uploaded filename. No individual production credits have been invented. The contact email is ryan.karkhanechi@gmail.com.

## Rename your film later

On GitHub, open index.html and click the pencil to edit. Find `"title": "Timeline 1"` near the bottom and change only the words inside those quotes. Commit the change. GitHub Pages will update automatically.

## Add another film later

Upload another browser-ready MP4 and JPG (each below 25 MiB for GitHub browser uploads). In index.html, find the script with id="project-data". Add another comma-separated object inside its square brackets, using the new filenames. Fields are title, category, role, poster, video, and optional preview. Leave role blank unless you want your credit shown. Use unique filenames so the original film is preserved. You can also send the next video here for an updated package.

## Official GitHub instructions

Uploading files: https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
GitHub Pages: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
