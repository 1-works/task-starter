# Publishing the 1Works starter template (one-time, by a 1Works GitHub org admin)

This folder is the content of the **1Works task starter**. It is NOT part of the app.

1. Create a repository in the 1Works GitHub organisation, for example `1works-ai/task-starter`
   (public, so learners can create repos from it).
2. Copy the files in this folder (without this PUBLISH.md) into it and commit them.
3. On GitHub, open the repo's Settings and tick **Template repository**.
4. Set `NEXT_PUBLIC_GITHUB_TASK_TEMPLATE=1works-ai/task-starter` in the front end's environment
   and rebuild. Until it is set, the guides ask the learner to tick "Add a README file" instead.

Pin the dev container image to a specific version when you publish if you want a fully stable
environment, and add task-type variants (Python, Node) as separate templates later.
