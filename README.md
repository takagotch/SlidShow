### SlidShow
---
https://github.com/topics/slideshow
```js
```
---
.rb
https://github.com/slideshow-s9/slideshow

```
HTTP_PROZY=http://234.445.454:4341
HTTP_PROXY=http://gerald:topsecret@234.445.454:4341

<div class='slide smaller commandline'>
</div>

<%= Date.today %>
{{ Date.today }}

<% content_for :head do %>
<% end %>

<%= image 'frinedbadge.png' %>

<% code do %>
  class Greeter
    def initialize(name)
      @name = name.capitalize
    end
    def salute
      puts "Hello #{@name}!"
    end
  end
  g = Greeter.new("world")
  g.salute
<% end %>

<%= code 'code/meta/my_ostruct.rb#imp!', class:=>'small' %>
<%= code 'highlight.rb', :engine => 'sh' %>
code-engine: sh
<% sh do %>
  puts 'Hello'
<% end %>
<% uv do %>
<% end %>
<% coderay do %>
  puts 'Hello'
<% end %>
<% sh :lang => 'css', :line_numbers => 'off' do %>
  <%= include 'gradients.css' %>
<% end %>

gradient: top-bottom red black
gradient-colors: green lime
gradient-colors: #0e1f5b #3b5998
gradient: tadial #0e1f5b #3b5998
gradient-theme: repeat
```

```ruby
module MarkdownHelper
  def image( path, alt="", tilte="" )
    %Q{![#[alt]](#{path} "#{title}")}
  end
end

class Slideshow::Gen
  include MarkdownHelper
end

```

```
gem install slideshow
slideshow install s6blank
slideshow list
slideshow build rest.text
slideshow instal s6blank
slideshow install https://raw.github.com/slideshow-templates/slideshow-s6-blank/master/s6blank.txt

cd ~/.slideshow/templates
git clone http://github.com/slideshow-templates/slideshow-reveal.js.git
slideshow list
slideshow ls
slideshow build microformats.text -t s6blank
slideshow build microformats.text -t reveal.js
ruby print.rb

slideshow build tutorial.text
wkhtmltopdf --outline --orientation Landscape tutorial.pdf.html tutorial.pdf

gem install ultraviolet
gem install coderay

slideshow help
slideshow install g5
slideshow install https://raw.github.com/slidshow-templates/slidshow-google-html5-slides/master/g5.txt
```
