# Portal for DigiBP 2018 @ GitHub

This is the DigiBP 2018 portal source code hosted on [https://digibp.github.io/digibp-portal-2018/](https://digibp.github.io/digibp-portal-2018/).

> Note: This is a fork of the IBM portal hosted on [http://ibm.github.io](http://ibm.github.io). The original version is published under an MIT license.

### Adding a new repo to the listing

In order to have your repository show up, a minor change to [orgs.js](assets/js/orgs.js) is required.

* To add a single repository add a new entry to [orgs.js](assets/js/orgs.js), specify the Github organization name and the repository name (separate them with a `/`), and set the `type` to `repo`, an example can be seen below:

```JSON
{
    "name": "DigiBP/digibp-pizza",
    "type": "repo"
}
```

* To add all the repositories in a Github organization add a new entry to [orgs.js](assets/js/orgs.js), specify the Github organization name, and set the `type` to `org`, an example can be seen below:

```JSON
{
    "name": "DigiBP",
    "type": "org",
    "link": "https://github.com/DigiBP"
}
```