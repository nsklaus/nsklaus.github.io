
## My site

it uses lb from [luke smith](https://github.com/LukeSmithxyz/lb). it's a bash script that let you build a blog and publish articles.
see upstream for more info.
## Usage

```sh
./lb n(ew)      # Make a new blog post draft.
./lb e(edit)    # Edit a draft of an entry.
./lb t(rash)    # Delete a draft of an entry.
./lb p(ublish)  # Finalize/publish a blog post draft.
./lb d(elete)   # Delete a published blog post.
./lb r(evise)   # Revise an already published entry ( republish it with `lb p` when done)
```

## Info

- The blog entries are stored in `blog/` in your websites root directory. Drafts are in `blog/.drafts`.
- `blog/.htaccess` acts as a "database" file. `lb` stores filenames with their corresponding proper names and publishing dates there.
- The other files in this repo just illustrate how you can use `lb`. Only the `lb` script itself is necessary.
- Your `$EDITOR` variable should be set to your preferred text editor, vim will be assumed if you don't have one set.
