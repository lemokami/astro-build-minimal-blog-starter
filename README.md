![Thumbnail](thumbnail.png) 
Unwrapped minimal blog template with Astro
# Repo:
- https://github.com/michael-andreuzza/astro-build-minimal-blog-starter
# Preview:
- https://unwrapped-minimal-blog-template.netlify.app/
# Unwrapped minimal Blog template.
Features:
- β SEO-friendly setup with canonical URLs and OpenGraph data
- β Full Markdown support
## π Project Structure
Inside of your Astro project, you'll see the following folders and files:
```
βββ README.md
βββ astro.config.mjs
βββ package.json
βββ public
βΒ Β  βββ favicon.ico
βΒ Β  βββ social.jpg
βΒ Β  βββ social.png
βββ src
βΒ Β  βββ components
βΒ Β  βΒ Β  βββ Author.astro
βΒ Β  βΒ Β  βββ BlogHead.astro
βΒ Β  βΒ Β  βββ BlogPost.astro
βΒ Β  βΒ Β  βββ BlogPostPreview.astro
βΒ Β  βΒ Β  βββ Heading.astro
βΒ Β  βΒ Β  βββ Paragraph.astro
βΒ Β  βββ layouts
βΒ Β  βΒ Β  βββ BlogPost.astro
βΒ Β  βββ pages
βΒ Β  βΒ Β  βββ index.astro
βΒ Β 
βββ tsconfig.jsonΒ Β 
βββ tailwind.config
```
Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.
There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.
Any static assets, like images, can be placed in the `public/` directory.
## π§ Commands
All commands are run from the root of the project, from a terminal:
| Command           | Action                                       |
|:----------------  |:-------------------------------------------- |
| `npm install`     | Installs dependencies                        |
| `npm run dev`     | Starts local dev server at `localhost:3000`  |
| `npm run build`   | Build your production site to `./dist/`      |
| `npm run preview` | Preview your build locally, before deploying |
## π Want to learn more?
Feel free to check [Astro's documentation](https://docs.astro.build) or jump into their [Discord server](https://astro.build/chat).

If you have any question feel free to contact me on Twitter at twitter.com/Mike_Andreuzza