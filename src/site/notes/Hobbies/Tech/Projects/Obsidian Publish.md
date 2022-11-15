---
{"dg-publish":true,"permalink":"/hobbies/tech/projects/obsidian-publish/","tags":"gardenEntry"}
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
- [GitHub - fyears/remotely-save](https://github.com/fyears/remotely-save) - would use this to save to Dropbox and then share the Dropbox link
- This: [Obsidian Publish Notes](https://notes.iamsaravieira.com/notes/oss-obsidian-publish-notes-docsmd)  is publishing to Netlify storing all of the data in Airtable. Seems a bit of a hack and I'm not sure that static CMS is used (maybe custom based on NextJS)
- [Home - Markbase](https://www.markbase.xyz/pages/Home) - this is "unfree" / not self-hosted 
- And try the “Sekund” plug-in - seems to be close but not sure 
- [Obsidian Save as Gist](https://github.com/ghedamat/obsidian-save-as-gist) NB this cannot be public (so limited value)
- [GitHub - oleeskild/obsidian-digital-garden](https://github.com/oleeskild/obsidian-digital-garden) - this seems to be advanced/complete, publishing on Netlify and I may have used it before. So this seems to be pretty good - and recent commits. ==current preference==
- [Scrape the web for data - Share & showcase - Obsidian Forum](https://forum.obsidian.md/t/scrape-the-web-for-data/33520)
- [GitHub - egradman/obsidian-etherpad-lite](https://github.com/egradman/obsidian-etherpad-lite) - for collaboration
- [GitHub - reorx/obsidian-telegraph-publish: Publish your Obsidian note to a Telegraph page.](https://github.com/reorx/obsidian-telegraph-publish) - this quickly shares a note here: [Telegraph](https://telegra.ph/)
- [Publishing your Obsidian Vault Online with Quartz](https://brandonkboswell.com/blog/Publishing-your-Obsidian-Vault-Online-with-Quartz/) - this seems to be using a Hugo site via your own GitHub repo. Bit of work to set up but I think you can exclude files and folders in the way he does it in the tutorial. 
- https://flowershow.app/docs/publish-tutorial - this publishes a vault, or a folder within a vault, to Netlify or wherever - but all the attachments and the public notes would need to be in one folder
- [GitHub - ppeetteerrs/obsidian-zola: A no-brainer solution to turning your Obsidian PKM into a Zola site.](https://github.com/ppeetteerrs/obsidian-zola) - this basically pushes notes to your own Git repo running [Zola](https://www.getzola.org/), but looks to push the whole thing rather than choose notes
- [GitHub - obsidianMkdocs/obsidian-github-publisher: A plugin to easily publish note to github](https://github.com/obsidianMkdocs/obsidian-github-publisher) - it looks like you can set up any GitHub repository - eg Gatsby - and have this push notes of your choosing to the source folder...
- [MindStone](https://mindstone.tuancao.me/note/__Getting++++Started) - runs on Netlify - looks good - although seemingly no title in tab
- [GitHub - mcndt/obsidian-quickshare: 📝 An Obsidian plugin for sharing encrypted Markdown notes on the web. Zero configuration required.](https://github.com/mcndt/obsidian-quickshare) - either use [their webserver](https://noteshare.space/) (deleted after 30 days) - difficult installation for self-hosted. 
- [Obsidian Share](https://share.alan.fyi/572e1ae4a0aeadf5943862d1deaf8fe6.html) - needs a webserver and PHP but easy installation. Links to other shared notes. 


```raindrop
collection: 0
format: table
search: #obsidian #publish
sort: title
```