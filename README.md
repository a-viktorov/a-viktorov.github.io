require 'github/markup'
GitHub::Markup.render('README.markdown', "* One\n* Two")

gem install github-markup


```ruby
require 'github/markup'
GitHub::Markup.render('README.markdown', "* One\n* Two")
```

Or, more realistically:

```ruby
require 'github/markup'
GitHub::Markup.render(file, File.read(file))
```
