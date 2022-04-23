# Prismic + Next.js Blog

This project was built using [Prismic][prismic] + [Next.js][nextjs] with the Starter Blog from Prismic Community. This uses the Prismic slice machine to build components which is a very nice feature of Prismic.

&nbsp;

### [Live Site][live-demo]

&nbsp;

<img src="https://user-images.githubusercontent.com/8601064/163122284-5b80a81e-a4fd-482e-9bd5-99b22f61175f.png" alt="Screenshots of the site seen on deskop and mobile browsers" />

&nbsp;

To start a new project like this, run the following command in your terminal:

```sh
npx prismic-cli@latest theme \
  --theme-url https://github.com/prismicio-community/nextjs-starter-prismic-blog \
  --conf sm.json
```

### This command does the following:

1. Asks you to log in to Prismic or [create an account][prismic-sign-up].
2. Creates a new Prismic content repository.
3. Starts a new Next.js project using this starter.

To learn more about working with Prismic, [**see the Prismic docs**][prismic-docs].

[prismic]: https://prismic.io/
[prismic-docs]: https://prismic.io/docs/technologies/nextjs
[prismic-sign-up]: https://prismic.io/dashboard/signup
[nextjs]: https://nextjs.org/
[live-demo]: https://nextjs-starter-prismic-blog.vercel.app/
