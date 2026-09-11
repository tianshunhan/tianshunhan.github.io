# Tianshun Han's Academic Homepage

This repository contains the source for Tianshun Han's personal academic website. The site presents research interests, publications, research experience, education, awards, and contact information.

The website is built with [Jekyll](https://jekyllrb.com/) and adapted from [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io).

## Local Preview

Install Ruby, Bundler, and the Jekyll build dependencies, then run:

```bash
bundle install
bash run_server.sh
```

Open <http://127.0.0.1:4000> in a browser. Changes to `_config.yml` require restarting the server.

## Deployment

Create a public repository named `tianshunhan.github.io`, push this project to its default branch, and enable GitHub Pages in the repository settings. The published site will be available at <https://tianshunhan.github.io>.

To enable automatic Google Scholar citation updates, add a repository Actions secret named `GOOGLE_SCHOLAR_ID` with the value `wGcEkqwAAAAJ`, then enable GitHub Actions.

## License and Attribution

The underlying template is distributed under the MIT License. See [LICENSE](LICENSE) for details.
