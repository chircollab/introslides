## Customized configuration

While you are welcome to modify the `params` section of the slide deck's YAML header directly, you have the option of writing a customized YAML configuration file in this directory if you do not wish to put the values in version control.  This configuration will be imported via the [`{config}`](https://github.com/rstudio/config) package.  Create a file called `config.yml` in this directory with syntax similar to below if you wish to use this feature:

```yaml
default:
  collab_short: "Your R Collab"
  collab_long: "Your R Collaborative"
  collab_github: "https://github.com/repo_owner/repo_name"
  coc_link: "https://yourdomain.github.io/coc/"
  collab_email: "your_collab_email@somewhere.com"
  coc_report_link: "https://your_report_link.com"
  collab_slack_faq: "#collab-faq"
  collab_schedule_link: "https://your_schedule_link.com"
```
