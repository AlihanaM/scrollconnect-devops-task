# ScrollConnect - DevOps Task (Day 2)

## Branching Strategy
- **main**: Production branch (stores stable release code).
- **development**: Integration branch (all features are merged and tested here).
- **feature/***: Individual developer branches for specific tasks/features.

## Contribution & Collaboration Workflow
1. **Create Branch**: Always branch off from `development`:
   `git switch -c feature/<your-feature-name>`
2. **Make Changes & Commit**:
   `git add <files>`
   `git commit -m "feat: description of work"`
3. **Push to Remote**:
   `git push -u origin feature/<your-feature-name>`
4. **Open Pull Request (PR)**: Create PR towards `development` branch with proper title and description.
5. **Peer Review & Merge**: Get changes reviewed by team members before merging into `development`.
6. **Conflict Resolution**: If merge conflicts occur, resolve conflicting lines locally, stage the files, and complete the merge commit.
