# Website template
The repository is a template for creating Jekyll-based websites for the ADA Research Group

## Structure of the website

The top level of the repository contains the [landing page](index.html) and the main components of the website ([example](people.html)), which are linked to via the tab bar, among other things

### Folders
- This folder contains subfolders that contain the individual event reports or announcements sorted by year. Each event gets its own folder. See [example](events/2024/Test_News_01/index.html).
- The education folder contains all training courses sorted by semester (each semester has its own folder). Each course has its own folder. See [example](education/exampleSemester/sampleCourse/index.html).
- The Assests folder contains the media used on the site. E.g. [logos](assets/images/logo/AIM_logo.png), [images of employees](assets/images/profiles/mmustermann.jpg) or [general images](assets/images/media/AZnews.png). Furthermore [documents](assets/documents) and [pictures of the collaborators](assets/collaborators/pkerschke/pkerschke.jpg).
- The .github folder contains the files needed to automate the website with Guthub pages.
- The _posts folder contains the individual pages of the blog.
- The _members_past folder contains the profile files of former members.
- The _members folder contains the members' profile files.
- The -layouts folder contains all layouts that are used that do not use the ‘standard’ layout.
- The _includes folder contains small snippets of code that can be reused anywhere on the page (e.g. the [contact field](_includes/contact.html)) or relevant parts of the website such as the [footer](_includes/footer.html).
- The _data folder currently only contains the configuration of the tab bar
- The _collaborators folder contains the profiles for the collaborators.
- The _bibliography folder contains the bib files that are used on the page.

## GitHub pages and Jekyll
- Installed Jekyll-plugins: 'jekyll/scholar' & 'jekyll-remote-theme'
- GitHub pages: The configuration of GitHub pages is done online by accessing the repository settings and visiting the Pages tab. You can find good instructions here: https://jekyllrb.com/docs/continuous-integration/github-actions/
