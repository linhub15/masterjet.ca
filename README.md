Site uses Jekyll static generation.

### Developmenet Setup
* Install Ruby `apt install ruby-full build-essential zlib1g-dev`
* Set ruby gems to $HOME rather than root
```
    echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
    echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
    echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
    source ~/.bashrc
```
* Install Jekyll & bundler `gem install jekyll bundler`
* Run locally dev server `bundle exec jekyll serve`

### Missing Gems
`bundle install`

## 301.txt
Changes to file path names must be reflected in 301.txt

# Cloud cannon automatically builds when pushing to master