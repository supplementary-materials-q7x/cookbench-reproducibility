# Anonymous CookBench reproducibility site

This directory is a self-contained static web page made from the supplied environment-configuration material. It intentionally excludes the following from the original material:

- private repository addresses and collaboration instructions;
- names, assignments, account identifiers, personal Windows paths, and routing screenshots;
- API keys, email credentials, mail-notification setup, and service endpoints;
- obsolete binary versions and the third-party MelonLoader installer.

## Local preview

Open `index.html` in a browser. No build tool, server, analytics, or external stylesheet is required.

## Publish anonymously and publicly

1. Create a **new public anonymous repository or static-hosting project**. Do not fork an identifiable repository and do not reuse an account/profile that reveals the authorship of the submission.
2. Upload the contents of this directory. The `downloads/cookbench-environment-integration.zip` file must remain public.
3. Configure the host to serve `index.html` at the root (for GitHub Pages, deploy this directory from the repository root or a Pages source directory).
4. Add the real public anonymous repository URL for the benchmark code, task definitions, prompts, and evaluation scripts in the `Release boundary and public artifacts` section of `index.html`.
5. Open the hosted URL in a logged-out/private browser window. Verify that the page, download, repository link, and page source reveal no author identity, private URL, secret, local path, or publishing-account profile.
6. Place the final static-site URL—not an editable or private share link—in the rebuttal.

With GitHub Pages, the direct binary URL will be:

```
https://<anonymous-account>.github.io/<repository>/integration-package/CS_CamDump.dll
```

The page also links this file directly and provides a ZIP capsule at `downloads/cookbench-environment-integration.zip`.

Do not claim complete replayability for the commercial game or external model APIs. The page should state their separate licensing/access boundary exactly as written.
