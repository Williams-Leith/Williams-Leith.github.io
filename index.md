---
title: Common Transit Convention Traders API roadmap
weight: 1
description: Software developers, designers, product owners or business analysts - see how you can integrate your software with Common Transit Convention Traders API.
---

# Common Transit Convention Traders API roadmap

## Overview

We are creating the Common Transit Convention (CTC) Traders API to allow traders to send and receive Arrival and Departure Notifications to customs and border offices in the UK and the EU.  

The roadmap shows you our development plans as well endpoints and projects we have finished. We are an Agile team and we will be updating this roadmap as we complete items and start working on new ones.

We are now in [Beta](https://www.gov.uk/help/beta). Some endpoints are ready for you to test in HMRC’s sandbox environment. More will follow.



## Key dates


| **Delivery** | **Description** |**Date** |
|------|-------------|--------|
|**Switch from using Test Support API to Trader Test**| This will allow you to request authentic messages from the NCTS | October 2020 |   
|**Release to production environment**| Traders can now use the API to send and receive messages to and from the offices of departure and arrivals|Late spring 2021|


### [What we have released](https://github.com/Williams-Leith/Williams-Leith.github.io/blob/Road-map/released.md)

See what we have released, either to the HMRC's sandbox environment or to live production.


### [What we're developing now](https://github.com/Williams-Leith/Williams-Leith.github.io/blob/master/developing-now.md)

Have a look at present tasks so have an idea about what we will release next.

### [In our backlog](https://github.com/Williams-Leith/Williams-Leith.github.io/blob/Road-map/in-our-backlog.md)

Check our to do list. We're not developing these items now, but we will, as soon as we get to them.



## Related API documentation
<!--- Section owner: MTD Programme --->

  * [Service Guide](https://developer.service.hmrc.gov.uk/guides/common-transit-convention-traders-service-guide/)
  * [CTC Traders API specifications](https://developer.service.hmrc.gov.uk/api-documentation/docs/api/service/common-transit-convention-traders/1.0)

## Changelog
<!--- Section owner: MTD Programme --->

Version 1.0

15 July 2020

What changed:

* First release




# **Williams doing a GitHub page**

### Purpose
This page is mostly for me, Matthew Williams, to teach myself `Markdown` and some basics about GitHub.
This page might be interesting if you're trying to master Markdown yourself. 

To start with I'm mostly trying to import a picture of my dog. 

![Branston](https://raw.githubusercontent.com/Williams-Leith/images/master/IMG_0567.jpg "Branston") 

Not easy, because GitHub is complicated. **But I did it.** *Actually that's a lie. My friend Chris told me to add this link:*

<https://raw.githubusercontent.com/Williams-Leith/images/master/IMG_0567.jpg>

[See it here](https://raw.githubusercontent.com/Williams-Leith/images/master/IMG_0567.jpg)

The `raw` and `githubusercontent.com` bits weren't in the github training, which was **_lacking_**. 

When I told him it worked, he said,
> Cool. I've never even used this before!

_emoticon fail!_

~~I keep making mistakes.~~ I'm getting the hang of this. You can only import `jpegs`. **Note** I've added `alt text`. Hover mouse over pictures to reveal vital details.

![Take me back](https://raw.githubusercontent.com/Williams-Leith/images/master/IMG_takemeback.jpg "Take me back!")

## **Backwards and downwards!**

- [x] Let's do a list
- [ ] Organise things I want to do
- [x] Do a table
- [x] Try a link.
- [x] Mess about with syntax
- [x] Pretend I can write `code`

``` 
Python. My son can do stuff on python on his raspberry. 
Maybe I should subcontract him. 
```

#### Posh Tables

|Aspiration   | Effort | Reality |
|:----------- |:------:| -------:|
|Hard tables  | Max    | Fail    |
|Easy tables  | Min    | Fail    |

#### Lazy Tables

Aspiration | Effort | Reality |
--- | --- | --- 
Hard tables | Max | Fail
Easy tables | Min | Fail


#### Lahdida Tables

Task | Done | Confidence |
--- | --- | --- 
Dog pic | [x] | Still confused by links
Code highlight | [x]| Not bad
Tables | [x]| Pushing it

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

[Talk to me](../email.html)

<details>
<summary>Heading</summary>

+ markdown list 1
    + nested list 1
    + nested list 2
+ markdown list 2

</details>


 
   <html lang = "en">
     <head>
       <meta charset = "UTF-8" />
     </head>
     <body>
       <h1>Form Demo</h1>
       <form>
          <fieldset>
             <legend>Selecting elements</legend>
             <p>
                <label>Select list</label>
                <select id = "myList">
                  <option value = "1">one</option>
                  <option value = "2">two</option>
                  <option value = "3">three</option>
                  <option value = "4">four</option>
                </select>
             </p>
          </fieldset>
       </form>
     </body>
   </html>
   
   <html>
<head>
<title>Test page</title>
</head>
<body>

  <form method="POST">
    <select name="drop_menu">
      <option value="dog">Dog</option>
      <option value="cat">Cat</option>
      <option value="duck">Duck</option>
    </select>
    <input type="submit" value="Send Form" />
  </form>
</body>
</html>

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

<div id="sample">
<h2>Contact Form</h2>
<p>Please complete the information below and click Submit.</p>
<form id="my-form" action="/cgi-bin/umbrella.pl" method="post">
<div id="align">
<input type="hidden" name="required" value="name,phone,email" />
<input type="hidden" name="title" value="Thank you for contacting Keynote Support" />
<input type="hidden" name="return_link_url" value="
https://www.keynotesupport.com/index.shtml" />
<input type="hidden" name="return_link_title" value="Go to the Homepage" />
<label for="name">NAME:</label><br />
<span><input type="text" name="name" id="name" class="data-entry" /></span><br /><br />
<label for="phone">PHONE:</label><br />
<span><input type="tel" name="phone" id="phone" class="data-entry" /></span><br /><br />
<label for="email">E-MAIL ADDRESS:</label><br />
<span><input type="email" name="email" id="email" class="data-entry" /></span><br /><br />
<p>COMPUTER (Choose one):</p>
<select name="product1" size="3">
<select name="drop_menu">
<option value="coding response issues">Technical coding issues</option>
<option value="policy">Business impact issues</option>
<option value="timing">Implementation issues</option>
</select><br /><br />
<p>OPERATING SYSTEM:</p>
<label for="comments2">COMMENTS:</label><br />
<span><textarea name="comments" id="comments2" rows="10" cols="30"></textarea></span><br /><br />
<span><input type="reset" class="button" value="RESET" />
<input type="button" class="button" value="SUBMIT" onclick="window.alert ('This is a sample form only');" /></span><br />
</div><!--end div align-->
</form>
</div><!--end div sample-->

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Williams-Leith/Williams-Leith.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
