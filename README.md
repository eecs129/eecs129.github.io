# How to Maintain

## Intro

This site is generated with [hugo](https://gohugo.io/). RTFM before you start.

## How to

### Add a person

**Step 1**: Use hugo command to create a new post like:
```bash
hugo new members/active/wangdachui/index.md
```

**Step 2**: Put a photo in the corresponding folder, or remove the resources in front matters.
```yaml
resources:
    - src: photo.jpg
      params:
          weight: -100
```
You can add multiple pictures and they are sorted by weight.

**Step 3**: Preview the site
```bash
hugo server --buildDrafts --watch
```
Make sure everything is working fine.

**Step 4**: Remove draft notation
Remove `draft: true` in front matters.

**Step 5**: Double check and commit

The site building process is completed by github action, the only thing you need to do is edit markdown files and photos.