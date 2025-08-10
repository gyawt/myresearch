# How to Document

1. Run the discovery script to get an up-to-date inventory of public items:
   - `scripts/discover-public-apis.sh`
2. For each public function/class/type, create a page under `docs/api/` using `api-template.md`.
3. For each public component, create a page under `docs/components/` using `component-template.md`.
4. Add examples under `docs/examples/` and link from the relevant API/component pages.
5. Keep docs close to code changes. Update docs in the same PR as the code.

Style guide:
- Prefer clear, task-oriented explanations
- Include at least one minimal and one realistic example
- Document parameters, return types, errors, and edge cases
- Note stability and breaking changes