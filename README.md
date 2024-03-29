# PictoAI📸
https://picto-ai.vercel.app/
## Your very own AI powered platform to create and share images developed by the DALL-E model!

<p>
  A MERN stack web app that develops images with the DALL-E model through OpenAI's API. This project leverages React and Tailwind CSS for the frontend, alongside Node.js, Express.js and MongoDB for the backend, and the images generated by the DALL-E model are stored in Cloudinary.
</p>

**Let's take a look at how it works:**

https://github.com/Kaven-Raj/PictoAI/assets/63968001/9fc92da9-5f1c-4028-b724-640d4a88bd32

### Steps to reproduce:

1. Clone the repository locally:

```
git clone https://github.com/Kaven-Raj/PictoAI.git
```

2. Install dependencies for both the frontend and backend:

```
cd client
npm install
cd ../server
npm install
```

3. Create a `.env` file in the backend directory and add the following:

```
OPENAI_API_KEY=<Enter your OpenAI api key>
MONGODB_URI=<Enter your mongodb cluster name>
CLOUDINARY_CLOUD_NAME=<Enter cloudinary cloud name>
CLOUDINARY_API_KEY=<Enter your cloudinary api key>
CLOUDINARY_API_SECRET=<Enter your cloudinary api secret>
```

4. Replace backend endpoints:

Change URLs from `https://picto-ai-backend.vercel.app/` to `http://localhost:8080`

5. Start the backend:

```
cd server
npm start
```

6. Start the frontend:

```
cd client
npm run dev
```
