Site uses Jekyll static generation.

## Dependencies
* Ruby 2.7
* Jekyll 4.0.1
* Bundler 2.1.4
* Bootstrap 4.5

### Developmenet Setup
* Install Ruby `sudo apt install ruby-full`
* Set ruby gems to $HOME rather than root (So we don't need to use Sudo for gems)
```bash
    echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc   # or ~/.zshrc
    echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
    echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
```
* `gem install jekyll bundler` installs jekyll and bundler
* `bundle install`
* `bundle exec jekyll serve` - starts development server

### Build for Prod
`bundle exec jekyll build` - builds to the `_site` directory

## 301.txt
Changes to file path names must be reflected in `301.txt`

# Production automatically builds when pushing to master