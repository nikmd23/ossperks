![MVP Perks](/images/logo.png)
---
A listing of tools & services freely available to Microsoft MVP's at [mvpPerks.com](http://mvpperks.com/).

## How to Add a Perk
* Fork the repository
* Use the following [YAML](http://www.yaml.org/) template to create an additional perk.

```yml
  #name of the product/service & the uri to apply for an MVP license
- perk: {name: "Microsoft", uri: "http://mvp.microsoft.com/"}
  #product/service description
  description: "MSDN Ultimate Subscription"
  #categories the produce/service fits in
  categories: ["IDE", "Cloud"]
  #the products/services offered to MVP's
  products: ["Visual Studio", "Windows Azure Subscription"]
  #name of the product/service vendor & the uri to their site
  company: {name: "Microsoft", uri: 'http://www.microsoft.com/'}
```
* Add the results to the `perks:` list at the top of `index.html`.
* Submit a pull request

### Notes

* Try to use `{URL to Product/Service Page}` that points to information about what is needed to qualify for the MVP license.
* `products:` is a list of tools provided by the company like `Visual Studio` or `Windows Azure benefits`.
  * If the company offers licenses to any tool of choice, enter `Any`.

## About mvpperks.com
This is a fork of ossperks.com. The long term plan is to build something big and beautiful that provides value for any developer community, whether open source, Microsoft MVP, user group sponsoring offers, etc. But for starters we're keeping it simple while taking the pulse of the community. Is there any interest? What are the needs?