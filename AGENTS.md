<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

- Preserve the installed TanStack Start/Vite bootstrap and file routes because the hosting runtime requires them; feature UI uses React and Tailwind with no additional libraries.
- Keep portfolio content in a shared browser-only React context with localStorage persistence so demo admin edits appear on public pages without a backend.
- Use locally bundled generated photography and asset pointers for downloaded media so images do not depend on external stock hosts.
