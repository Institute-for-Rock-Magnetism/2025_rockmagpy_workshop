# Discussion of future directions for `rockmagpy`

## Tour of `rockmag.py` and the RockmagPy‑notebooks repository

Let's have a look at where the code for rockmagpy and the book lives on GitHub.

## 🐞 Contributing via GitHub issues, JupyterBook docs, and PmagPy code

Community contributions, feedback, and suggestions are welcome!

- Open an [issue in this repository](https://github.com/PmagPy/RockmagPy-notebooks/issues) or in the [main PmagPy repository](https://github.com/PmagPy/PmagPy/issues) for bug reports, questions, or feature requests.
- To contribute code or documentation, fork the repository, make changes, and submit a pull request.

[This open source guide](https://opensource.guide/how-to-contribute/) provides
some useful insight for why, and how to successfully get involved in open
source projects (like PmagPy/RockmagPy!).

### Hands-on experience with GitHub

#### 1. Create a GitHub account (if needed)
1. Go to [github.com](https://github.com).
2. Click **Sign up**, follow the prompts (email, username, password).
3. Choose the **Free** plan and verify your email.

#### 2. Raise an issue in the RockmagPy‑notebooks repo (or on PmagPy)
1. Navigate to `https://github.com/PmagPy/RockmagPy-notebooks` or `https://github.com/PmagPy/PmagPy`.
2. Click on the **Issues** tab.
3. Select **New issue**.
4. Choose an issue template or start with a blank issue.
5. Title it in a informative manner (e.g., “Feature request: add rockmagpy thermal demag notebook”).
6. Describe your request (e.g. what’s missing or could be improved).
7. Click **Submit new issue**.
8. Anyone can respond to the issue and start a discussion about how to move forward. Watch for comments and continue the conversation.

#### 3. Edit a file directly on GitHub and submit a pull request
1. In the `RockmagPy‑notebooks` repository (or `PmagPy`) the `, browse to the file you’d like to edit (e.g., a markdown `.md` file or a python script `.py` file).
2. Click the **pencil “Edit this file”** icon near the top right.
3. GitHub will prompt: “Create a new branch for this commit...”  
   ✅ Leave the checkbox checked to fork the repo and create a new branch.
4. Make your changes directly in the on‑page editor.
5. Scroll down to **Commit changes**:
   - Add a short title describing your change.
   - (Optional) Add a longer message with more detail.
   - Commit to the new branch.
6. Click **Propose changes**—this creates the fork and a pull request draft.

#### 4. Submit the Pull Request (PR)
1. On the “Open a pull request” page, review your proposed changes.
2. Add a clear PR title, e.g., “Fix typo in intro notebook”.
3. In the description box:
   - Explain what you changed and why.
   - Mention any related issues using `#issue_number` (e.g., “Closes #5”).
4. Click **Create pull request**.

#### 5. Start the PR discussion
1. A rockmagpy contributor will review your changes and could propose further revisions
2. To make changes, edit your forked branch and commit again; updates will automatically appear in the PR.
3. Once the changes are good to go, one of the contributors will merge the PR into `main`.

#### 📝 Summary Flow

| Step | Action |
|------|--------|
| 🔐 | Create GitHub account |
| 📌 | Open an issue |
| ✏️ | Click “Edit” → make change → “Propose changes” |
| 📨 | Finalize & submit PR |
| 💬 | Discuss and revise if needed |
| ✅ | Merged into main branch |

## 💡 Suggestions for feature development

Let's have a conversation about future feature development which can include things that we prioritize as issues.

## 🔌 Designing export workflows from specialized instruments to MagIC

We have focused on export from the IRM database. We recognize that getting data from instrument format into MagIC format with the necessary metadata can present a hurdle. Let's discuss how we can move forward in doing this as a community.