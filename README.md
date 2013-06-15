Missing Ruby & RSpec Snippets for Sublime Text 2
================================================

A.K.A. I'll Never Be Sure Why Sublime Didn't Ship With `do...end`

Start typing the first few letters, and hit tab to complete!

### Install it!

Just clone it into the right folder using

`git clone git://github.com/accessd/sublime-useful-ruby-snippets.git`

+ __Linux__: In your Sublime packages directory, probably `~/.config/sublime-text-2/Packages`
+ __Mac OS X__ (I'm on 10.7 Lion): `~/Library/Application\ Support/Sublime\ Text\ 2/Packages/`.

###### Fun Fact: you don't have to be in the Ruby folder, because each snippet is scoped to be used in `.rb` files.


## Examples

Block with do:

```ruby
  ... do
  end
```

Description rspec block:

```ruby
  describe "description" do ... end
```

FactoryGirl create method:

```ruby
  create(:...)
```

## Complete Inventory

`...` denotes the cursor position immediately after code insertion.

```ruby
  before do
    ...
  end
```

```ruby
  before { ... }
```

```ruby
  create ( :... )
```

```ruby
  describe "..." do
  
  end
```

```ruby
       do
    ...
  end
```

```ruby
  each { |...|  }
```

```ruby
  each_pair { |k,v| ... }
```

```ruby
  each_pair do |k,v|
    ...
  end
```

```ruby
  ...: 
```

```ruby
  it { should... }
```

```ruby
  let(:...) {  }
```

```ruby
  let!(:...) {  }
```

---

[Ruby](http://ruby-lang.org) snippets for [Sublime Text Editor](http://www.sublimetext.com/)