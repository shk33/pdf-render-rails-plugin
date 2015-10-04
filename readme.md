#PDF Renderer Rails Plugin

##Usage Example
```ruby
def index
  respond_to do |format|
    format.html
    format.pdf { render pdf: "contents" }
  end
end
```
A simple pdf render plugin for rails from [Crafting Rails 4 Applications: Expert Practices for Everyday Rails Development](http://www.amazon.com/Crafting-Rails-Applications-Practices-Development/dp/1937785556)

![Book Cover](http://ecx.images-amazon.com/images/I/51ZXC4cdrPL._SX415_BO1,204,203,200_.jpg "Book Cover")

