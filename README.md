<div align="center">
<img src="public/media/cover.png" alt="Ignite Lab"  />
</div>
<br />

## 🛠 Skills

![react][react] ![graphql][graphql] ![apollo client][apollo] ![sass][sass] ![tailwind css][tailwind] ![vite][vite]

## 📄 Roadmap

- [] Use **Sass** ( `.scss`) and use the  `@apply`from **Tawildin CSS** to avoid longer `classNames` on **JSX**;
- [x] Use same layout as home page (without form) to show on route ´/event` when user don't select any lesson;
- [] Protect coming soon lessons;
    - If user try access the `/event/lesson/:slug` route manually, is redirected to previous route;
    - The lesson card renders a `div` instead a `Link` for coming soon lessons.
- [x] Storage event details on **GraphCMS**
- [] **Docker** files (`docker-compose.yaml` and `Dockerfile`) to run project inside Docker, but in development mode;
- [ ] Implement Loading screens;
- [ ] Make it responsive;
- [ ] Use **React Hook Forms** with **Yup** to improve register form validations;
- [] **ESLint** configuration;
- [] Add **Husky** and **Lint Staged** to run on each commit;
- [] Add **Commit Lint** to follow the guidelines on commit messages;

## 💾 Environment Variables

To run this project, you will need to add the following environment variables to your `.env` file:

- **`VITE_APP_API_URL`:** **GraphCMS** API Link (used on **Apollo Client**)
- **`VITE_APP_API_TOKEN`:** **GraphCMS** Token (used on **Apollo Client** to)

## 🌐 Live Version

[![vercel](https://img.shields.io/badge/vercel-000?style=for-the-badge&logo=vercel&logoColor=white)](https://event-plataform-nu.vercel.app/)

## 🌠 Screenshots

<img src="public/media/mockups/mockup-home.png" alt="home" />

<img src="public/media/mockups/mockup-no-lesson.png" alt="Event (No Lesson)" /> 

<img src="public/media/mockups/mockup-lesson.png" alt="Event (No Lesson)" />

## 🔗 More About Me

[
![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)
](https://linkedin.com/in/ruanlandrade)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/ruanlandrade)
[![instragram](https://img.shields.io/badge/instragram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/ruanlandrade)


[react]: https://img.shields.io/badge/react-1E4174?style=for-the-badge&logo=react&logoColor=white

[graphql]: https://img.shields.io/badge/graphql-1E4174?style=for-the-badge&logo=graphql&logoColor=white

[apollo]: https://img.shields.io/badge/apollo%20client-1E4174?style=for-the-badge&logo=apollographql&logoColor=white

[tailwind]: https://img.shields.io/badge/tailwind%20css-1E4174?style=for-the-badge&logo=tailwindcss&logoColor=white

[vite]: https://img.shields.io/badge/vite-1E4174?style=for-the-badge&logo=vite&logoColor=white