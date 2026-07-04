# Social Preview

GitHub's repository social preview image is configured from the repository web UI:

```text
Settings -> General -> Social preview
```

Use this source asset:

```text
.github/social-preview.svg
```

Recommended export size:

```text
1280 x 640
```

GitHub CLI currently supports repository description, homepage, and topics through `gh repo edit`, but it does not expose a stable flag for uploading the social preview image.

