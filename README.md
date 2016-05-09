# How to use?

Create an article
```
bundle exec middleman article "The title"
```

Then edit the new file created in `source/blog`

Publish your site
```
rake publish
```

In case the publish goes wrong, delete the `build` folder
```
rm -rf build
```

