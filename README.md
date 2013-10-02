![MVP Perks](/images/logo.png)
---
A listing of tools & services freely available to Microsoft MVP's at [http://xavierdecoster.github.io/mvpperks](http://xavierdecoster.github.io/mvpperks).

## How to Add a Perk
* Fork the repository
* Use the following [YAML](http://www.yaml.org/) template to create an additional perk.

```yml
  #name of the company & the uri to apply for an MVP license
- perk: {company: "Microsoft", uri: "http://mvp.microsoft.com/"}
  #product/service description
  description: "MSDN Ultimate Subscription"
  #the products/services offered to MVP's
  products: ["Visual Studio", "Windows Azure Subscription"]
```
* Add the results to the `perks:` list at the top of `index.html`.
* Submit a pull request

### Notes

* Try to use `{URL to Product/Service Page}` that points to information about what is needed to qualify for the MVP license.
* `products:` is a list of tools provided by the company like `Visual Studio` or `Windows Azure benefits`.
  * If the company offers licenses to any tool of choice, enter `Any`.

## About mvpperks
This is a fork of [http://ossperks.com](http://ossperks.com). The long term plan is to build something big and beautiful that provides value for any developer community, whether open source, Microsoft MVP, user group sponsoring offers, etc. But for starters we're keeping it simple while taking the pulse of the community. Is there any interest? What are the needs?