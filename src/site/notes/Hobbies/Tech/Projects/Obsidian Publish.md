
---
Priority: 4
Added: 2021-12-28
dg-home: true
dg-publish: true
---


# Obsidian Publish
#obsidian #gatsby

This is the command to sync the files to the Gatsby directory:
`rsync -a --include="Presents*.md" --exclude="*" /Users/christyrush/Library/Mobile\ Documents/iCloud\~md\~obsidian/Documents/Notes/Home/ /Users/christyrush/Dev/site/src`

Then we will need to set it up so that this runs whenever I wake up my Mac: [How to run script at wake? - Ask Different](https://apple.stackexchange.com/questions/376203/how-to-run-script-at-wake)

## Alternatives

- publish to Wordpress: [](https://github.com/devbean/obsidian-wordpress)
- Mac sync (r sync?) one file to a Dropbox folder 
- [obs2mk · PyPI](https://pypi.org/project/obs2mk/)
- [GitHub - fyears/remotely-save](https://github.com/fyears/remotely-save)
- This seems to be basically it: [Obsidian Publish Notes](https://notes.iamsaravieira.com/notes/oss-obsidian-publish-notes-docsmd)  
- And try the “Sekund” plug-in - seems to be close but not sure 
- [Obsidian Save as Gist](https://github.com/ghedamat/obsidian-save-as-gist)
- [GitHub - oleeskild/obsidian-digital-garden](https://github.com/oleeskild/obsidian-digital-garden)
- [Scrape the web for data - Share & showcase - Obsidian Forum](https://forum.obsidian.md/t/scrape-the-web-for-data/33520)