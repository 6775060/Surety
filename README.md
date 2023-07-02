
## Setting up your font

* **New repositories.** Hit the green button above ("Use this template") to create your own repository. We then need to update the workflow permissions. Go to Settings > Actions > General > Workflow permissions and enable "Read and write permissions". Finally, rerun the failed github action by going to Actions > Initial commit > Re-run jobs > Re-run all jobs.

*Please note that a Github Action job will be executed once you've created the repository which will populate the readme and build dependencies. This job will fail because it was executed with incorrect permissions. The steps above will fix the permissions issue and rerun the job. Please wait for the job to complete and pass before pulling the repo to your local system.*

* **Updating a repository.** To update your font repository to bring in the latest best-practices from the Google Fonts Project Template, run `make update-project-template` from the command line.

* Replace the font sources in the `sources` directory with your own font sources. These sources may be either in Glyphs format or UFO/Designspace formats.\
\
Unlike many open source distributors, Google Fonts is **curated**. Fonts shipped to the platform have to match the [Google Fonts Specifications](https://github.com/googlefonts/gf-docs/tree/main/Spec). Please read them carefully.\
\
*(The sample font provided in this template is [Rubik](https://github.com/googlefonts/rubik/) by Philipp Hubert, Sebastian Fischer, and contributors.)*

* Then reference the sources in the file `sources/config.yaml`, as well as making any other changes you would like to make based on the instructions in the [Google Fonts Builder documentation](https://github.com/googlefonts/gftools/blob/main/Lib/gftools/builder/__init__.py).


* Add yourself to the `AUTHORS.txt` and `CONTRIBUTORS.txt` files.

* Update the first line of the OFL.txt (year and project name). Update also the Copyright string in the sources, it has to be the same as the OFL.txt. The `.glyphs` file in this repo gives you required base charset and font info.

* Finally, add and commit any files you have modified (i.e. `README.md`, `AUTHORS.txt`, `CONTRIBUTORS.txt`, the font sources, and `sources/config.yaml`) to git, then push to GitHub. Please be aware that Github Actions may take a few minutes to build your font family. It is worthwhile inspecting the progress in the "Actions" tab.

* Fill out `DESCRIPTION.en_us.html` with a description about your font.

* If Github Actions has successfully built the family, you will find the font binaries in the Actions tab. The official Github Actions documentation provides further [information](https://docs.github.com/en/actions/managing-workflow-runs/downloading-workflow-artifacts).

* Once you are happy with your font, add promotional assets in the documentation directory. Make it different from the pic you use in this README. You can get inspired by existing tweet @googlefonts like: https://twitter.com/googlefonts/status/1415562928657416192.

* Google Fonts uses Github Releases to manage font families. If you feel your font project has hit a milestone, you must create a new release for it. In order to do this, go to the releases page and hit the "Draft a new release button". You must provide a tag number and title which can only be a decimal number e.g 0.100, 1.000 etc. For the body text, mention what has changed since the last release. Once you are done, hit the "Publish release" button. Here is an example which fulfills the requirements, https://github.com/m4rc1e/test-ufr-family/releases/tag/2.019. For more info regarding Github release, please see the official Github Release [documentation](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository). **Please note that Github Actions must be able to build the fonts before you can make a release. Once you have made a release, the fonts and tests assets will be attached to the release automatically. This may take a while since the fonts and tests will be built from scratch so please be patient.**

* Remove this section from the readme. :-)
----


# The surety font project

[![][Fontbakery]](https://6775060.github.io/Surety/fontbakery/fontbakery-report.html)
[![][Universal]](https://6775060.github.io/Surety/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://6775060.github.io/Surety/fontbakery/fontbakery-report.html)
[![][Outline Correctness]](https://6775060.github.io/Surety/fontbakery/fontbakery-report.html)
[![][Shaping]](https://6775060.github.io/Surety/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2F6775060%2FSurety%2Fgh-pages%2Fbadges%2Foverall.json
[GF Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2F6775060%2FSurety%2Fgh-pages%2Fbadges%2FGoogleFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2F6775060%2FSurety%2Fgh-pages%2Fbadges%2FOutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2F6775060%2FSurety%2Fgh-pages%2Fbadges%2FShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2F6775060%2FSurety%2Fgh-pages%2Fbadges%2FUniversal.json

a versatile font with a stylish and versatile skeleton, on the one hand it contains movement and cuts that herald energy and determination, on the other hand it has wonderful sensitivity and charisma, these qualities give it the ability to influence "Aravat" is the workhorse suitable for a wide range of uses
!![Surety_fonts](https://github.com/6775060/Surety/assets/41392424/e37705eb-f166-4fc7-9bbe-4bb70deb1cb6)
![Surety_fonts2](https://github.com/6775060/Surety/assets/41392424/51a816fa-cf27-40e2-bd9c-a7b82a5eccc6)
[Surety_fonts3](https://github.com/6775060/Surety/assets/41392424/024cb8d2-5e92-4c15-8881-9018904f1528)
![Surety_fonts4](https://github.com/6775060/Surety/assets/41392424/c9d5973d-fcc7-4de8-ab82-51b91f9d078f)
![Surety_fonts5](https://github.com/6775060/Surety/assets/41392424/64257505-4570-49dd-b5e1-212f82d77322)
![Surety_fonts6](https://github.com/6775060/Surety/assets/41392424/c37247a3-e65b-4f3e-a197-2de2d1af04d5)
![Surety_fonts7](https://github.com/6775060/Surety/assets/41392424/e5c36c1d-b153-4d1f-b015-18e29a76791d)
![Surety_fonts8](https://github.com/6775060/Surety/assets/41392424/ac49050b-a652-4a4f-abfa-79550ec17b16)
![Surety_fonts9](https://github.com/6775060/Surety/assets/41392424/1638846e-0edd-4e6c-b116-f118dc3d5045)
----


## About
I am Dayan Shoki, the founder of the font shop fontshok.co.il
Designer identity for brands with intelligent typefaces.
Proud to present the Surety project: a multilingual font project that includes Latin, Hebrew and Tamil languages, a font that contains an intriguing combination of contrasts of presence on the one hand and sensitivity on the other.

## Specifications
surety is a variable font with 518 glyphs, including Hebrew, Latin, Tamil.
Improved kerning feature, contains 9 meticulous weights:
# 100 - Thin
# 140 - ExtraLight
# 200 - Light
# 300 - Medium
# 400 - Regular
# 600 - SemiBold
# 700 - Bold
# 800 - ExtraBold
# 900 - Black

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at https://6775060.github.io/Surety.

## Changelog

When you update your font (new version or new release), please report all notable changes here, with a date.
[Font Versioning](https://github.com/googlefonts/gf-docs/tree/main/Spec#font-versioning) is based on semver. 
Changelog example:

**26 May 2021. Version 2.13**
- MAJOR Font turned to a variable font.
- SIGNIFICANT New Stylistic sets added.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
