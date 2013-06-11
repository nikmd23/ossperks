# OSS Perks 
A listing of tools & services freely available to open source projects at [ossPerks.com](http://ossperks.com/)

## How to Add Your Favorite Perk
* Fork the repository
* Use the following template to create an additional perk.

```html
<li>
    <div class="product-overview">
        <div class="product-title">
            <h2><a href="{URL to Tool/Service Page}">{Name of Tool/Service}</a></h2> 
            by <div class="tag company"><a href="{URL to Vendor Site}">{Name of Vendor}</a></div>
        </div>
        <div class="tag platform">{Platform}</div>
    </div>
    <div class="product-description">
        {Description of Tool/Service}
    </div>
    <div class="tag category">{Category Tag}</div> <!-- This node can be repeated for multiple tags -->
    <div class="clear"></div>
</li> 
```
* Add the results to the `<ul class="product-listing reset">` within `<section class="products">` on `index.html`.
* Make a pull request

### Notes

* Try to use `{URL to Tool/Service Page}` that points to information about what is needed to qualify for a free license.
* `{Platform}` is a development platform like `.Net`, `Java`, `JavaScript` or `Ruby`. 
  * For non-platform specific tools, enter `any`, not an operating system. 

## About ossperks.com
The long rerm plan is to build something big and beautiful that provides value for open source projects, consisting of 
a community edited information source. But for starters we're keeping it simple while taking the pulse of the 
community. Is there any interest? What are the needs?
