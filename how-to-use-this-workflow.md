# Build and Publish Your Docker Image to Github  🐳

This workflow is triggered when commit messages include the word `deploy`

## Set Visibility to Public 
Push the image once using your GitHub Action

Go to: [https://github.com/users/<your-username>/packages](https://github.com/users/<your-username>/packages)

- Click your image package (e.g., your-api). It should have the same name as your repo
- Click the ⚙️ Settings tab
  - Under "Package Settings", set visibility to Public

Done. All future `:latest` pushes will be public.
