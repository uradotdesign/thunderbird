# thunderbird

This is the repository containing the Thunderbird Style Guide, which is based on [Firefox Photon's Design System](https://design.firefox.com/photon/). The technology used to create this website is [Jekyll](https://jekyllrb.com), a static website generator.

The Firefox Photon system has been modified and adapted for use for Thunderbird. There are some sections hidden from the main view as they are do not apply to Thunderbird meanwhile some sections have been modified slightly, such as links to docs, social accounts etc.

# Building

Before you can modify the contents, you need to have Ruby and Jekyll installed.
You can do that by running the following command.

`gem install bundler jekyll`

After you install Jekyll, you need to clone the repo on your system.
You can do that by running the command.

`git clone $REPO`

After you have cloned the repo on your system, start by installing the bundle using the following command.

`bundle install`

Afterwards, execute the following command to build the project and to be able to browse it locally on your browser.

`bundle exec jekyll serve`

That's it! Now you can begin to modify the files and they will be automatically built and displayed on your localhost upon a page refresh.

When you're done with the changes, press Ctrl+C to stop the localhost process.
