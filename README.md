# jekyll-class-blog

This template was created to accompany the session

> Hosting a Public-facing Class Blog with GitHub pages and Jekyll

presented by [Matthew Andres Moreno](https://mmore500.com) and [Acacia Ackles](https://alackles.github.io/) at [Enriching Scholarship 2024](https://ttc.iss.lsa.umich.edu/ttc/).

## Live Demo

<https://mmore500.com/jekyll-class-blog>

## How to Create a Blog Post

1. Use the `Add File > Create new file` button to add a new file `_posts/year-mm-dd-slug.md` where `year-mm-dd` is today's date and "`slug`" a keyword or two (containing only alphanumeric, `-`, and`_` characters).
2. Paste in the following boilerplate and fill in your desired content.
   ```
   ---
   layout: post
   author: Your name goes here
   title: Title goes here
   ---
   
   Blog post content goes here.
   ```
3. Click `Commit changes` in the upper right.
   Then you have two choices:
   a. to immediately add the post to the blog, use the `Commit directly to the main branch` option.
   b. to begin a review process before posting (i.e., for peer feedback), use the `Create a new branch for this commit and start a pull request` option.
4. If you posted the content for immediate release, wait about one minute for site build and deploy to complete.
   You can monitor this process from the `Actions` pane of the repository page (`https://github.com/yourusername/repository-name/actions`).
   Otherwise, your pull request should be visible on the `Pull requests` pane of the repository page (`https://github.com/yourusername/repository-name/pulls`).
   The blog entry will be posted once you click `Merge pull request` at the bottom of your pull request's page.

## How to Set up Your Own Blog

1. Click `Use this template > Create a new repository` on GitHub or click [here](https://github.com/new?template_name=jekyll-class-blog&template_owner=mmore500).
2. Set the `Repository name` with the URL where the blog should appear.
   For example, choosing `repository-name` would result in the blog being served at `https://yourusername.github.io/repository-name`.
3. Click `Create Repository` at the bottom right of the repository creation page.
4. Navigate to the new repository's page, `https://github.com/yourusername/repository-name`
5. Click the `_config.yaml` file to open it.
   Then, click the pencil icon in the upper right ("Edit this file") to edit.
6. Change `url` field to `https://yourusername.github.io/repository-name` (substituting your username and repository name).
7. Click the `Commit Changes` button in the top right, then `Commit Changes` on the confirmation panel that appears.
8. Navigate to the `Settings > Pages` pane of your repository page (`https://github.com/yourusername/repository-name/settings/pages`).
9. Set your deployment branch as `main` and your deployment directory as `/ (root)`.
10. Click the `enforce https` checkbox.
11. Wait about one minute for site build and deploy to complete.
   You can monitor this process from the `Actions` pane of the repository page (`https://github.com/yourusername/repository-name/actions`)
12. Once the deployment completes (green checkmark), your page should be available at `https://yourusername.github.io/repository-name`.

## More Information

For more information, see our slide deck at <https://hopth.ru/cs>.
