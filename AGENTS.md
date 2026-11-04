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

## Imported application
- Preserve ROUT’s imported TanStack route, provider, asset and MDX structure so source updates remain compatible.
- Keep the source compiler settings for imported code; retain managed project metadata and generated integration files.
- Never copy source credentials or automatically apply the external database migrations; account services require explicit compatible configuration.
