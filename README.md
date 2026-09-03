# Ungur Group Website

This repository contains the source code for the [Ungur Group](https://ungur.org) website, built using Jekyll and hosted on GitHub Pages.

## Getting Started

To run the site locally:

1. Ensure you have [Ruby](https://www.ruby-lang.org/) and [Bundler](https://bundler.io/) installed.
2. Ensure [Git LFS](https://git-lfs.com/) is installed and enabled:
   ```bash
   git lfs install
   ```
   Without this, binary assets (PDFs, images, crystal structures) will appear as small placeholder text files.
3. Install dependencies:
   ```bash
   bundle install
   ```
4. Serve the site:
   ```bash
   bundle exec jekyll serve
   ```
5. Visit `http://localhost:4000` in your browser.

## Contributing

We welcome contributions from group members! Please see our [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to add publications, update team members, and follow our project conventions. Note that pull requests are disabled; please commit changes directly to the `main` branch.

## License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for details.
