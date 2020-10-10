This is a fork of [damiencaselli/hugo-journal](https://github.com/damiencaselli/hugo-journal).

## Configuration

A few parameters should be adjusted in the site config:

```toml
[params]
  description = "Blog meta description."
  githubUsername = "your_gh_username"
  twitterUsername = "your_twitter_handle"
  tagline = "Blog tagline. Shown under index title."
[params.work]
  jobTitle = "occupation"
  company = "the company"
  companyUrl = "https://the.company.url/"
[params.gpg]
  key = "0x1111111111111111"
  fingerprint = "0000 0000 0000 0000 0000  0000 0000 0000 0000 0000"
  link = "https://pgp.mit.edu/pks/lookup?op=get&search=0x1111111111111111"
```

