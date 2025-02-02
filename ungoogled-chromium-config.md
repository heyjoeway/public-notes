## First Steps
Follow the first run (<chrome://ungoogled-first-run/>) steps.

If running from a flatpak, dictionary goes here:
```
~/.var/app/io.github.ungoogled_software.ungoogled_chromium/config/chromium/Dictionaries/
```

Make sure [Chromium Web Store](https://github.com/NeverDecaf/chromium-web-store/releases) is installed.

## Google Search
[To quote @sudo-nautilus:](https://github.com/ungoogled-software/ungoogled-chromium/discussions/1488#discussioncomment-619116)
> To get Google Search Engine, Do the Following:
> - Go to <chrome://settings/searchEngines>
> - Click Add Button near Other search engines
> - Add Google In Search Engine input box
> - Add google.com in Keyword input box
> - Add https://www.google.com/search?q=%s&{google:RLZ}{google:originalQueryForSuggestion}{google:assistedQueryStats}{google:searchFieldtrialParameter}{google:iOSSearchLanguage}{google:prefetchSource}{google:searchClient}{google:sourceId}{google:contextualSearchVersion}ie={inputEncoding} in URL with %s in place of query input box
> - Add https://www.google.com/complete/search?client=chrome&q=%s in Suggestions URL with %s in place of query input box
> - Click The Blue Save Button
> - Click the three dot menu near Google and select Make default

## Extensions
- [uBlock Origin Lite](https://chromewebstore.google.com/detail/ublock-origin-lite/ddkjiahejlhfcafbddmgiahcphecmpfh])
- [SponsorBlock](https://chromewebstore.google.com/detail/sponsorblock-for-youtube/mnjggcdmjocbbbhaepdhchncahnbgone)
- [DeArrow](https://chromewebstore.google.com/detail/dearrow-better-titles-and/enamippconapkdmgfgjchkhakpfinmaj)
- [Midnight Lizard](https://chromewebstore.google.com/detail/midnight-lizard/pbnndmlekkboofhnbonilimejonapojg)
- [2FAS](https://chromewebstore.google.com/detail/2fas-two-factor-authentic/dbfoemgnkgieejfkaddieamagdfepnff)
- [AutoplayStopper](https://chromewebstore.google.com/detail/autoplaystopper/ejddcgojdblidajhngkogefpkknnebdh)
- [Floccus](https://chromewebstore.google.com/detail/floccus-bookmarks-sync/fnaicdffflnofjppbagibeoednhnbjhg?hl=en)
- [My Start Page](https://github.com/heyjoeway/startpage)
  - Go to <https://github.com/heyjoeway/startpage/actions/workflows/main.yml> and run a workflow.
  - Download `dist`, save at `~/Downloads/dist.zip`
  - ```
    mkdir -p ~/extensions/startpage
    cd ~/extensions/startpage
    mv ~/Downloads/dist.zip .
    unzip dist.zip
    rm dist.zip
    ```
    Then add in <chrome://extensions> using `Developer mode`.
