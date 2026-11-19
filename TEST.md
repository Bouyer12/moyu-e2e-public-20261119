# Test sequence

1. In MoYu, open **添加仓库** and add `Bouyer12/moyu-e2e-public-20261119`.
2. Confirm it is labelled public and that its runtime is prepared without changing the other repository.
3. Clone it locally with HTTPS or SSH.
4. Edit `STATUS.md`: increment `revision` and add a unique local marker.
5. Commit and push to `main`.
6. In MoYu, start/refresh a task and verify the frozen base commit matches the pushed commit.
7. Add the same repository again and confirm the UI reports a duplicate instead of creating a second instance.
