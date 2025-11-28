# Asymptote

Repo for our [blog site](https://asymptote-4k2.pages.dev/).

## Contributing

### Setup

1. Clone the repo.  

    ```bash
    git clone https://github.com/passionately-curious/asymptote.git
    ```  

2. Install hugo using this [guide](https://gohugo.io/installation/).

3. Initialize and update the submodules

    ```bash
    git submodule update --init --recursive
    ```

4. Run hugo server to check if the setup worked

    ```bash
    hugo server
    ```

### Development

To write a new blog post,

1. Start by switching to new branch.

2. Create a new blog post.

    ```bash
    hugo new content content/posts/blog-name.md
    ```

3. Run `hugo server -D` to preview the site before commiting.

4. Stage and commit the changes.

5. Push your changes to the branch created for that specific post.

## Some useful links

- [Hugo docs](https://gohugo.io/documentation/)
- [PaperMod docs](https://github.com/adityatelange/hugo-PaperMod/wiki/Features#regular-mode-default-mode)
