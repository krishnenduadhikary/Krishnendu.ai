# Krishnendu.ai 🤖

Meet Krishnendu.ai – A sleek and responsive AI assistant interface built with Next.js, powered by Google's Gemini API, and styled using the `assistant-ui` library. Experience seamless AI conversations in a modern UI.

**✨ Live Demo:** [**https://krishnendu-ai.vercel.app**](https://krishnendu-ai.vercel.app) ✨

---

## 🚀 Features

*   **Conversational AI:** Engage in natural, intelligent conversations powered by the Google Gemini API.
*   **Clean & Modern UI:** Leverages the intuitive and customizable chat components from `assistant-ui`.
*   **Next.js Foundation:** Built on the robust Next.js framework for optimal performance and developer experience (SSR/SSG).
*   **Responsive Design:** Adapts flawlessly to various screen sizes, ensuring a great experience on desktop and mobile.
*   **Vercel Ready:** Optimized for easy and fast deployment on the Vercel platform.
*   **(Optional: Add more specific features like streaming responses, message history, code highlighting etc.)**

---

## 📸 Application Preview

Here's a glimpse of Krishnendu.ai in action:

![image](https://github.com/user-attachments/assets/738e2213-dce0-48c7-abf2-3308213b21d8)

---

## 🛠️ Tech Stack

*   **Framework:** [Next.js](https://nextjs.org/) (React)
*   **UI Components:** [assistant-ui](https://github.com/Yurt-AI/assistant-ui)
*   **AI Model:** [Google Gemini API](https://ai.google.dev/)
*   **Styling:** **[Specify your styling solution: e.g., Tailwind CSS / CSS Modules / Styled Components / assistant-ui default styles]**
*   **Language:** TypeScript / JavaScript (Specify which one you primarily used)
*   **Deployment:** [Vercel](https://vercel.com/)

---

## ⚙️ Getting Started

To run this project locally, follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/krishnenduadhikary/Krishnendu.ai.git
    cd Krishnendu.ai
    ```

2.  **Install Dependencies:**
    Choose your preferred package manager:
    ```bash
    npm install
    # or
    yarn install
    # or
    pnpm install
    ```

3.  **Set Up Environment Variables:**
    *   You'll need a Google Gemini API key. Get one from [Google AI Studio](https://aistudio.google.com/app/apikey).
    *   Create a file named `.env.local` in the root directory of the project.
    *   Add your API key to this file:
    ```env
    # .env.local
    GEMINI_API_KEY=YOUR_GOOGLE_GEMINI_API_KEY
    ```
    🔒 **Note:** The `.env.local` file is listed in `.gitignore` and should never be committed to your repository.

4.  **Run the Development Server:**
    ```bash
    npm run dev
    # or
    yarn dev
    # or
    pnpm dev
    ```
    🚀 Your application should now be running on [http://localhost:3000](http://localhost:3000).

---

## ☁️ Deployment

This application is perfectly suited for deployment using [Vercel](https://vercel.com/).

**Steps:**

1.  **Push:** Push your code to your GitHub repository.
2.  **Import:** Import your repository into Vercel (you can use the button below).
3.  **Configure:** Add the `GEMINI_API_KEY` environment variable in your Vercel project settings (use the same key as in your `.env.local`).
4.  **Deploy:** Vercel will automatically build and deploy your site. Future pushes to the connected branch will trigger automatic redeployments.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fkrishnenduadhikary%2FKrishnendu.ai)

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions or find a bug, please open an issue or submit a pull request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the `LICENSE` file for details.

*(Remember to add a `LICENSE` file to your repository if you haven't already!)*

---

## 🙏 Acknowledgements

*   Huge thanks to the creators of [assistant-ui](https://github.com/Yurt-AI/assistant-ui).
*   Powered by [Google Gemini](https://ai.google.dev/).
*   Built with [Next.js](https://nextjs.org/).
*   Deployed on [Vercel](https://vercel.com/).

---
