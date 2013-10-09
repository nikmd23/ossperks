![OSS Perks](/images/logo.png) 
--- 
A listing of tools & services freely available to open source projects at [ossPerks.com](http://ossperks.com/). 
For updates, be sure to follow [@ossPerks](https://twitter.com/ossperks) on Twitter.

## How to Add Your Favorite Perk
* Fork the repository
* Use the following [YAML](http://www.yaml.org/) template to create an additional perk.

```yml
  #name of the product/service & the uri to apply for a license
- perk: {name: GitHub, uri: 'http://github.com/'} 
  #product/service description
  description: Powerful collaboration, review, and code management for open source and private development projects. 
  #categories the produce/service fits in
  categories: [Source Control, Issue Management]
  #the development platform the product/service is for
  platforms: [Any]
  #name of the product/service vendor & the uri to their site
  company: {name: GitHub, uri: 'http://github.com/'}
```
* Add the results to the `perks:` list at the top of `index.html`.
* Submit a pull request

### Notes

* Try to use `{URL to Product/Service Page}` that points to information about what is needed to qualify for a free license.
* `platforms:` is a development platform like `.net`, `Java`, `JavaScript` or `Ruby`. 
  * For non-platform specific tools, enter `Any`, not an operating system. 
* Do not submit freeware or shareware to be listed, those aren't really *perks* :wink:

## About ossperks.com
The long term plan is to build something big and beautiful that provides value for open source projects, consisting of 
a community edited information source. But for starters we're keeping it simple while taking the pulse of the 
community. Is there any interest? What are the needs?
