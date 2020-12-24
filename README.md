# Police News

This repo contains an archive of news stories from all the UK Police forces. To save space each page has be converted to Markdown. However, most header meta data has been saved and some extract data extracted from the text.

## Extracted data

I've been able to extract some meaningful data from the original HTML and subsequent Markdown. This has been placed in a [YAML](https://yaml.org) code block at the top:

```yaml
area: Scotland
incident:
  day: '23'
  month: November
  reference: '2228'
index: http://www.scotland.police.uk/what-s-happening/news/2020/november/
publish:
  month: november
  year: '2020'
title: Appeal after man indecently exposed himself on Formartine Road, Aberdeen
url: http://www.scotland.police.uk/what-s-happening/news/2020/november/appeal-after-man-indecently-exposed-himself-on-formartine-road-aberdeen/
```

