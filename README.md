# Hypothes.is Search Engine Integration

**This Project has been merged into [MetaSearch](https://github.com/mjysci/MetaSearch).**

## Description

This Violentmonkey UserScript enhances your web browsing experience by letting you search through your Hypothes.is annotations across multiple search engines. With this script, you can quickly find and access your annotations while searching on popular platforms like Google, Bing, DuckDuckGo, and more.

![Hypothes.is Search Screenshot](https://cdn.jsdelivr.net/gh/mjysci/imgs@master/blog/hypothesisSearch_screenshot.png)

## Features

- **Search Integration**: Fetch and display your Hypothes.is annotations directly in the search results of major search engines.
- **Custom Settings**: Configure your Hypothes.is username and API token for secure access to your annotations.
- **Tag Filtering**: Exclude specific tags from your search results to refine which annotations are visible.
- **Merge Annotations**: Option to merge annotations by their URIs to prevent duplicates.
- **Pagination**: Navigate through your annotations with pagination controls for easier browsing.
- **Stylish Interface**: A clean, modern UI that integrates smoothly into your search experience.

## Installation

1. **Install Violentmonkey**: Make sure the Violentmonkey extension is installed in your browser. You can download it from [here](https://violentmonkey.github.io/).

2. **Install Script**: Click [here](https://github.com/mjysci/hypothesis-search/raw/refs/heads/main/hypothesisSearch.user.js) to open Violentmonkey's Userscript installation page, then click `Install`.

3. **Generate Hypothes.is API Token**: Visit [here](https://hypothes.is/account/developer) to generate an API token.

4. **Settings**: After installation, search for anything on a supported search engine. The `Hypothes.is Settings` panel will appear on the first run. Input your Hypothes.is username and API token.

## Usage

1. **Open a Search Engine**: Go to a supported search engine (e.g., Google, Bing, DuckDuckGo).

2. **Search for a Term**: Enter your search term. The script will automatically fetch related Hypothes.is annotations.

3. **View Annotations**: Annotations will appear in a panel alongside the search results, and you can click on links to view each annotation in detail.

4. **Settings**: Click the settings icon (⚙️) in the annotations panel to configure your Hypothes.is username, API token, excluded tags, and merging options for annotations by URI.

## Example

When you search for "climate change" on Google, the script will display any relevant annotations from your Hypothes.is account, providing a quick way to reference your notes alongside the search results.

## Requirements

- A valid Hypothes.is account.
- Your Hypothes.is API token, which can be obtained from [your account settings](https://hypothes.is/account/developer).

## Contributing

We welcome suggestions or bug reports! To submit a pull request:

1. Check the Issues tab; if there’s no relevant issue, feel free to create one.

2. Submit your PR and link it to a related issue.

## License

This project is licensed under the GPL-3.0 License. See the [LICENSE](https://github.com/mjysci/hypothesis-search/blob/main/LICENSE) file for more information.

---

If you have any questions or feedback, please reach out! Enjoy exploring your annotations!
