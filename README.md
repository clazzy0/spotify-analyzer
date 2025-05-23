# spotify-analyzer

Analyze Your Spotify Listening Habits
Developed by CSC572: The Open Source Movement, Spring 2024-2025

## Brief Description

Spotify Analyzer is a web application that allows users to analyze their Spotify listening habits. It provides insights into the user's music preferences, including top genres, artists, and tracks. Specifically, the top 5 artists, the top 5 songs, new artist discoveries, and mood trends are features that are provided. The application uses the Spotify API to fetch user data and presents it in an easy-to-understand format.

The project is built using Next.js and TypeScript, ensuring a modern and efficient development experience. The application is designed to be user-friendly, with a clean and intuitive interface.

![some kind of image or visual](https://via.placeholder.com/600x400.png?text=Spotify+Analyzer)

### Using Spotify Analyzer (as a Dev)

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

First, modify the `.env.local` file by adding these four lines:

`SPOTIFY_CLIENT_ID = your-client-id` <br>
`SPOTIFY_SECRET = your-secret`

These first two lines are created at https://developer.spotify.com/dashboard. You need to create an app and then you can find the client_id and secret.

`NEXTAUTH_SECRET= openssl rand -base64 32` <br>
`NEXTAUTH_URL = http://127.0.0.1:3000`

The nextauth_secret is a `32-digit base64 string`. Also, you need to put `http://127.0.0.1:3000` as the recall address in the Spotify Developer App that you have created. 

Now, run the development server (install node.js using `npm install` if needed):

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Contributing to Spotify Analyzer

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.
Also look at the components in the `app/components` directory. These components are used to build the page and can be modified to change the layout and functionality of the application.
You can also check out the [Next.js documentation](https://nextjs.org/docs) for more information on how to use Next.js.

### Expectations for Contributions

- Use pull requests to propose changes.
- Follow the project's coding style and conventions.
- Write clear and concise commit messages.
- Ensure that your code is well-documented.

### Known Issues

- Sign in page goes to another sign in page.
- Error for finding mood trends.
- New Artist Discovery not fully functional.
- Some features and data may not be displayed correctly due to API limitations.

### Licenses
