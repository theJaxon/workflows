# workflows
Contains github actions reusable worfklows to avoid duplication.

### trivy-scan
- Uses [Trivy scanner]() for scanning container images.
- Defaults to scanning images with `latest` tags from github registry.
- Requires `image_name` as an input.

---

### References
1. [Reusing workflows](https://docs.github.com/en/actions/sharing-automations/reusing-workflows)
