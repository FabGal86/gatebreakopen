GateBreakOpen SEO / Discoverability Update
==========================================

Purpose
-------
This package strengthens the basic discoverability files for GateBreakOpen:
- robots.txt
- sitemap.xml
- SEO_UPDATE_README.txt

These files should be uploaded to the GitHub Pages root directory of the site:
https://www.gatebreakopen.org/

Files included
--------------
1. robots.txt
2. sitemap.xml
3. SEO_UPDATE_README.txt

robots.txt
----------
The robots.txt file now provides:
- public crawl permission for the whole site
- explicit allow rules for the main HTML pages
- explicit allow rules for the archive folder
- explicit allow rules for the 2026 ARK landing page
- explicit allow rule for the Welcome Letter PDF
- protection against accidental indexing of technical, draft, backup, or temporary folders
- a direct sitemap declaration

Canonical robots.txt URL:
https://www.gatebreakopen.org/robots.txt

Sitemap declaration inside robots.txt:
Sitemap: https://www.gatebreakopen.org/sitemap.xml

sitemap.xml
-----------
The sitemap now includes the main public pages of GateBreakOpen, including:
- home page
- GBO Project / index page
- Mission & Ethics
- Call for Papers
- Submission
- Type of Articles
- Areas
- Archives
- Policies
- ARK Policy
- Zero-Cost / No APC page
- No DOI / ARK identification page
- Editorial Integrity / No Manipulation page
- Equal Treatment / No Favoritism page
- Non-Peer-Reviewed Model / No Peer Review page
- Contacts
- Reports
- Useful Links
- 2026 archive index
- Welcome Letter ARK landing page
- Welcome Letter PDF

Canonical sitemap URL:
https://www.gatebreakopen.org/sitemap.xml

Important ARK record included
-----------------------------
Title:
Welcome Letter to Authors and Readers

Author:
Fabio Galli

ARK:
ark:/78326/gbo01welcomeletter

Persistent identifier:
https://n2t.net/ark:/78326/gbo01welcomeletter

Landing page:
https://www.gatebreakopen.org/archives/2026/gbo01welcomeletter.html

PDF:
https://www.gatebreakopen.org/archives/2026/Welcome_Letter_GateBreakOpen.pdf

Recommended upload location
---------------------------
Upload these three files to the root of the GitHub Pages repository:

/
├── robots.txt
├── sitemap.xml
└── SEO_UPDATE_README.txt

Do not upload them inside:
- /archives/
- /archives/2026/
- /assets/
- /docs/

Validation checklist
--------------------
[ ] robots.txt is reachable at https://www.gatebreakopen.org/robots.txt
[ ] sitemap.xml is reachable at https://www.gatebreakopen.org/sitemap.xml
[ ] robots.txt contains the sitemap URL
[ ] sitemap.xml contains the home page
[ ] sitemap.xml contains the main policy pages
[ ] sitemap.xml contains /archives/2026/gbo01welcomeletter.html
[ ] sitemap.xml contains /archives/2026/Welcome_Letter_GateBreakOpen.pdf
[ ] The Welcome Letter PDF file name is exactly Welcome_Letter_GateBreakOpen.pdf
[ ] The ARK landing page file name is exactly gbo01welcomeletter.html
[ ] The ARK landing page links to the correct PDF file name
[ ] The public URLs use the same capitalization as the uploaded files

Suggested next steps
--------------------
1. Upload the three files to the GitHub Pages root.
2. Open https://www.gatebreakopen.org/robots.txt in a browser.
3. Open https://www.gatebreakopen.org/sitemap.xml in a browser.
4. Check that both load without a 404 error.
5. Submit the sitemap in Google Search Console:
   https://www.gatebreakopen.org/sitemap.xml
6. Submit the sitemap in Bing Webmaster Tools:
   https://www.gatebreakopen.org/sitemap.xml
7. Test the ARK landing page:
   https://www.gatebreakopen.org/archives/2026/gbo01welcomeletter.html
8. Test the PDF:
   https://www.gatebreakopen.org/archives/2026/Welcome_Letter_GateBreakOpen.pdf
9. Test the persistent identifier:
   https://n2t.net/ark:/78326/gbo01welcomeletter

Technical notes
---------------
- Keep file names stable after upload.
- Do not rename Welcome_Letter_GateBreakOpen.pdf after it has been published.
- Do not rename gbo01welcomeletter.html after the ARK has been linked.
- The sitemap should use public HTTPS URLs, not local file paths.
- The sitemap should stay in the website root.
- The robots.txt file should stay in the website root.
- If new articles, ARK records, or archive pages are added, update sitemap.xml.
- If new permanent folders are created, update robots.txt only if needed.
- Do not include private drafts or unpublished working files in the sitemap.

End of SEO update record.
