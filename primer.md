# Primer for Data Curators <br> HTML </br>

|Topic  | Description  |
|-----|-----|
| Extension |.htm or .html |
|MIME Type/Media Type |Text/HTML |
| Structure  | XML document |
| Versions  | Adapt from: [https://en.wikipedia.org/wiki/HTML#HTML_versions_timeline](https://en.wikipedia.org/wiki/HTML#HTML_versions_timeline)|
| Primary fields or areas of use | Multidisciplinary, multipurpose |
|Source and affiliation | Web Hypertext Application Technology Working Group (WHATWG) - [https://html.spec.whatwg.org/](https://html.spec.whatwg.org/) // World Wide Web Consortium (W3C) - [https://www.w3.org/standards/webdesign/htmlcss](https://www.w3.org/standards/webdesign/htmlcss) |
| Metadata |The **< meta >** tag provides metadata about the HTML document. |
|Key questions for curation review | 1.  Who are potential users? What would they require in order to find, access or reuse the file? <br> 2. Is the website still live and does the depositor intend for it to remain that way? <br> 3. Is the file related to other objects? Are these linked objects included in the deposit? |
|Tools for curation review | Internet Browser, TextEditor (Mac), Notepad (PC), [List of HTML editors](https://en.wikipedia.org/wiki/List_of_HTML_editors) |
| Date created | April 20, 2020 |
| Created by | Katrina Shafer and Julia Maxwell <br> **Mentors: Jake Carlson and Susan Borda** </br> |
| Date updated and summary of changes | Version 1 |


### Table of Contents
1. Description of format
2. Key questions to ask yourself
3. Key clarifications to get from researcher
4. Resources for Reviewing Data
5. Preservation actions
6. Metadata
7. What to look for to make sure this file meets FAIR principles
8. Appendix A - Resources
9. Appendix B - user personas
10. Appendix C - dataset examples
<br>

### 1. Description of Format

HyperText Markup Language, or HTML, is a markup language that makes up HTML files: one of the most basic objects that make up a webpage. HTML structures the text that appears on every internet webpage, links web pages between each other, and can display various media. Along with CSS and Javascript, the HTML language is the major player in the way that website content is designed.



The elements of the language have content contained in tags, which are noted as “**< >**,” followed by the webpage text, followed by the closed tag, “**</ >**.” HTML files are usually created in a text editor and opened and viewed in a browser. Those who wish their HTML files to be curated and/or preserved in a database are likely preserving HTML files that were once part of the textual and/or media content of a webpage. These user groups will include researchers and other stakeholders in research projects who have created their own websites and would like them preserved, domain owners of sites with determined justifications for preservation, and those looking to access preserved web pages and files for their own research.

For the purposes of this primer, the intended curation target is the HTML file (containing content written in the HTML language), not the language itself. Although basic knowledge of the language is helpful for curation, the HTML file is the object that is considered data in this case. However, standalone HTML files are rare. Most often HTML files are linked to other HTML files, as would be the case in the preservation of a website. It is important to understand this distinction, as most HTML curation will entail the preservation of several files that once made up a website or webpage.

### 2. Key Questions to Ask Yourself

-   Is there an expected user group for this object? What would they require?

-   Why is this item being submitted as an HTML file? Was it created as an HTML file or converted? What kind of functionality is expected in interacting with the content or website? Would scans of the websites (such as ArchiveIt crawls) or screenshots be equally effective?

-   Is the file related to other objects or a part of a larger website? Can or is it necessary to replicate their relationship(s) for a full understanding of the file or website? Are there dependencies within this HTML that might prevent its ability to standalone (ie. javascript)?

-   If the HTML object was part of a website, does the site remain live on the web? Is the repository agreeing to host or continue to perform upkeep of the site?

### 3. Key Clarifications to Get from Researcher

-   Is this a singular HTML file, or is it a linked number of files that are part of a larger object, such as those that comprise a website or webpage?

-   Was this HTML file ever hosted on an internet website?

	  - **_If yes:_**
		-   Is it still being hosted online?

		-   Are there other versions of the file that have been hosted on the internet?

		-   If so, why is this version being requested for preservation?

		-   Do more than one versions or editions of the file need 	preserving?


		-   Is the file being submitted for curation the same version that is currently online?


			-   **_If yes:_**


				-   Is there a particular reason that this same file needs to be preserved at this time?


			-   **_If no:_**


				-   What was the purpose of this file, if not part of a webpage?




				-   Are there additional files linked in the HTML?


					- _**If yes:**_


						-   What are those files (common examples would be CSS, javascript (and other javascript libraries, like jquery), various photo and video files)? What function do they perform?

						-   Do those files also need curation? Are they being submitted for curation?

					- _**If no:**_


						-   Are there other languages within the HTML file (common other languages include CSS, javascript, jquery)?

						-   Is there a reason that no other materials (media, etc) don’t need to be preserved along with the HTML content? What may be lost if these materials are not preserved?

### 4. Resources for Reviewing Data
As a text markup language HTML can be viewed with simple software that’s pre-installed on PC and Mac operating systems or within a web browser.

In order to view the object with the formatting a user would see with you should open the HTML file in the web browser of your choice (Firefox, Chrome, Safari, etc.). To view the markup and tags behind the website right click and select ‘inspect.’ You can also click “view page source” to view the entire HTML code.


Opening the static HTML file on your own computer can be done with a large number of programs. TextEdit is the default application on Mac computers and Notepad is available on PCs. There are a variety of open-source text and source code editors you may also consider. One is Atom, created by GitHub, which color codes each tag to help increase the file’s backend readability. In addition to software there are online resources, such as [https://html-online.com/editor/](https://html-online.com/editor/), that allow users who to update HTML tags and see the changes to the front end and formatting of the HTML.

### 5. Preservation Actions
**_Determining the HTML version used:_**
-   In your text editor or browser, check the top of the HTML document. This area will signify the version used. For the most common version, HTML5, there will be a **< !DOCTYPE HTML >** signifier. [https://howtocheckversion.com/check-html-version-website/](https://howtocheckversion.com/check-html-version-website/) can help identify other common versions.

![](https://lh4.googleusercontent.com/FMvxb5OFxw8g_TZUqMtvYO5IdqErAq4ubPwgBVehOts1jvh9RqbjInppt86yASFnsNmenFylBTA_b-Wsm2vzfkNMwdEVXpZ3EJDsGiOXbDKbF3vBORsTvB17FVGEuTrv6njD9aXb)
*HTML5 tag example*

_**Creation of a README:**_

-   Generating a README in a .txt file for future users of the preserved file would aid in the ability for dataset users of various experience levels to adequately understand the content of the HTML file.

-   This README should contain instructions to open the file in a web browser, any additional files that also contribute to content (CSS, media files, etc), and any other pertinent information that might affect the usability and understandability of the preserved file by someone with minimal HTML experience.

### 6. Generating Metadata
Although an extensive knowledge of the HTML language is not necessary for preservation, a knowledge of certain tags and the elements contained within them is helpful. One such situation is in developing adequate metadata for access and discovery in a database.

Metadata, in HTML best-practice, should be embedded in a way that it does not discreetly display the code on a webpage. This is ideally achieved using **< meta >** tags. When searching for elements specifically to enter into metadata fields, the **< meta >** tag usually yields the most suitable content.
**![](https://lh4.googleusercontent.com/kB6ROCzWOb-tzpYX6Vv4GJ0RAyj8ywzzS9ZeLQPW5W7an5Bd_auCvnt8Gj3lYBHCbpCkBXv98qFU0hUx_s28JDJI4vxQRQVOtiLIt-pwB6hO470aQdIxnE2CXpjAsCGArG1g1up9)**
_Here, the **< meta >** tag lists the field (called “name”) and description (called “contents”) for each field, making metadata generation for this file fairly straightforward._



Unfortunately, this straightforwardness doesn’t exist in many HTML files, many of which don’t use **< meta >** tags. While some information can be gathered from opening the file in a browser and exploring the file as it would be seen on the web, cursory knowledge of other common HTML tags can help fill in missing metadata gaps:



**< a >** - the **< a >**  tag creates a link in the HTML file that corresponds to a website or another HTML file. Finding that site on the internet or establishing the contents of the linked file can be helpful in establishing authorship, provenance, and other contextual information needed to generate missing metadata.

![](https://lh4.googleusercontent.com/Qfl5-u1LWspz4GcXUhusDUgTYSTdpZsmM0j1fHHIn2k2CvJ7q81237f0K7_mhqOl8YDPTiPPoBkyx1vE-1kD5kBaXZozLvZ8cmWnzdwwJnYnMbLxj6AtfyXVRiqEooZcJX6s07ac)



Headers (**< h1 >**, **< h2 >**, etc) - headers can also be used to establish subject matter and content of the file. They can also be helpful in determining the semantics that the HTML language inherently contains. Header tags signify different amounts of emphasis that the creator of the file wants to denote for those viewing the file in a browser, and seeing the header tag number
(**< h1 >**  being strongest) can help a preservationist understand context and meaning, which can help establish or construct various metadata and descriptive elements.

![](https://lh5.googleusercontent.com/dmGYnWu51XLoX9ZrqLxHjYnFvOJtJ2V7cnQkI4_l2cLAVwaAw7JzXiBkarkEhOAEXzT3pPlB3jOyKI025r_nq_zx0hEoiiLZrCpDPGue8sTJqAmq7I9-moHZEkAyuJIGty0sikmd)

### 7. What to look for to make sure this file meets FAIR principles

#### Findable:

The object’s findability is determined by whether the repository’s larger workflow adheres to [finability principles](https://www.force11.org/group/fairgroup/fairprinciples).

If the object was or remains a live website visitors should be redirected to the repository’s holding.

#### Accessible:

There are a few tags that are important to ensure HTML files remain accessible to screen readers.

Semantic elements such as **< form >**, **< table >**, and **< article >** are preferable to non-semantic tags , such as **< div>** and **< span >**, which do not provide clear descriptions of content.

Heading tags such as **< h1 >, < h2 >, < h3 >**, etc. are used to index websites and provide screen reader users a quick overview of the website’s content.
If images are present the **< alt >** tag should be used to describe the content of the image.
The lang attribute (**< html lang="en" >**) should reflect the language the file is written in order to ensure it is pronounced properly and clearer by the reader.

#### Interoperable:
A ReadMe file should be included to provide details about the object’s initial use and how to access it. Subject to time and tools available, the repository may choose to increase interoperability by including additional scans or screenshots of the object along with the .html object itself.

#### Reusable:

While it is impossible to assess the entirety of potential uses for an object, curators should consult depositors about potential user groups, how each would potentially utilize the object and what they would require.

Regardless of specific potential use cases, detailed metadata and clear tags within the .html file should increase the ability for it to be reused. At minimum, the HTML document should contain a **< title >**  or header tag (ie. **< h1 >, < h2 >**) that communicate the name of the resource and the different sections of the document so that the curator can determine the resource’s subject.

### 8. Appendix A - Resources

[Full List of FAIR Data Principles](https://www.force11.org/group/fairgroup/fairprinciples)



[Sustainability of Digital Formats LOC - HyperText Markup Language (HTML) Format Family](https://www.loc.gov/preservation/digital/formats/fdd/fdd000475.shtml)



[HTML Introduction](https://www.w3schools.com/html/html_intro.asp)



[HTML Living Standard](https://html.spec.whatwg.org/multipage/)



[Metadata for Web Resources](https://www.loc.gov/catdir/bibcontrol/dillon_paper.html)



[Data Types and File Formats for Data Preservation - U Oregon LibGuide](https://guides.library.oregonstate.edu/research-data-services/data-management-types-formats)



[How to Check HTML Version](https://howtocheckversion.com/check-html-version-website/)

### 9. Appendix B - [user personas and dataset examples](https://drive.google.com/drive/folders/1RJgQt1nmKP5Wd7HVNFsPRVJ4HUS_3W8u?usp=sharing)
