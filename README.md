## Local Development

1. Install rbenv to manage the local ruby versions:
- `brew install rbenv ruby-build`
2. Add `eval "$(rbenv init -)"` to `~/.zshrc` and source it:
- `source ~/.zshrc`
3. Install ruby 3.0.6:
- `rbenv install 3.0.6`
4. Set it globally:
- `rbenv global 3.0.6`
5. Verify that the right version is used: ruby -v                          
- `sudo gem update --system`
6. Install Jekyll as user:
- `gem install jekyll --user-install`
7. Install the dependencies:
- `bundle install`
8. Serve the site locally (Port 4000):
- `bundle exec jekyll serve`
