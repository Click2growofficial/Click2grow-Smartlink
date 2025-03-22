# Click2grow-Smartlink
A Vercel-based smart link system for dynamic redirection. Customize links using the USER env variable. Handles bots, devices, and unique user links.


---

### How to Import and Deploy the Project on Vercel

1. **Push the Code to a Git Repository**:
   - Push the project to a Git repository (e.g., GitHub, GitLab, Bitbucket).

2. **Import the Project on Vercel**:
   - Go to the Vercel dashboard: [https://vercel.com](https://vercel.com).
   - Click on **New Project**.
   - Select the Git repository where your project is hosted.
   - Vercel will automatically detect the project structure and configuration.

3. **Set Environment Variables**:
   - During the import process, Vercel will prompt you to set environment variables.
   - Add the `USER` environment variable with the unique identifier for the user (e.g., `user1`, `user2`).

4. **Deploy the Project**:
   - After setting the environment variables, click **Deploy**.
   - Vercel will build and deploy the project.

---

### Example Deployment

#### User 1:
- `USER=1`
- Redirects to: `https://click2grow.in/link/1`

#### User 2:
- `USER=2`
- Redirects to: `https://click2grow.in/link/2`

---

### Summary

- Use environment variables to set the `USER` identifier for each deployment.
- Import the project on Vercel by connecting it to a Git repository.
- Set the `USER` environment variable during the import process.

This approach ensures that each user has their own unique link while sharing the same codebase.
