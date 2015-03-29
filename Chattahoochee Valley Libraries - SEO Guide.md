![Library Logo](http://www.cvlga.org/sites/default/files/cvl_logo2_0.png)

# Chattahoochee Valley Libraries - SEO Guide


Hello! I'm Stephen Finney, a participant in the recent [HackTheLibrary](https://www.facebook.com/events/343943735771406/) event at the Columbus Public Library. I've written this guide for you so that the library's website will be easier to find on Google, look better on Google's search results, and have improved loading times.

Search Engine Optimization (SEO) is a vital part of every website. This process is what helps you "get Googled" more often and with better results. I'll explain more a little later.

This guide is for the Library staff to look over, but also for the library website's future web developers. It contains simple, one-line changes that can be made now and more advanced SEO concepts that should be implemented when the website gets redesigned. I recommend that you consider **all** of these changes.

I've tried to make this guide accessible to everyone. However, if you need help or clarification at any time, please don't hesitate to email me at [ssfinney92@gmail.com](mailto:ssfinney92@gmail.com). I'll be happy to help.

Let's get started!

## Table of Contents
 * [Why do we need SEO?](#why-do-we-need-seo)
 * [How is our SEO right now?](#how-is-our-seo-right-now)
 * [The Goal](#the-goal)
 * [Getting Started](#getting-started)
  * [Simple changes](#simple-easy-changes)
  * [Getting a little more advanced](#getting-a-little-more-advanced)
  * [Harder changes (for the redesigned site)](#harder-changes-for-the-redesigned-site)
 * [Regular content is important](#regular-content-is-important)
 * [Linking to your website from other places (backlinks)](#linking-to-your-website-from-other-places)
 * [Resources](#resources)

 <br>
 <br>
 

## Why do we need SEO?

SEO is [Search Engine Optimization](https://en.wikipedia.org/wiki/Search_engine_optimization). This is what makes your site easy to Google. As you know, most of the world uses Google when searching for something, so we want to make sure that the library's website comes up first (and looks really good) when someone searches for "columbus ga library" or even simply "columbus library".

Below is a search that comes up with the library in Columbus, OH. Look at all the "extras" on the page. There are sub-links to other parts of the site, a map on the right with directions, and a "snippet" describing the library. There are even reviews from real people who visited the library.

![Non-GA Search Shortened](https://www.dropbox.com/s/d9v5j0ungvy6m40/Non%20GA%20Search%20-%20Shortened.png?dl=1)

I want the Chattahoochee Valley Libraries to have this same search result. It doesn't just look nice; it's helpful, informative, and raises awareness for important parts of the site.

With all that said, **there is no silver bullet for SEO.** However, with these suggestions on a well-maintained website, we can make it as easy as we can for Google to work its magic.

<br>

## How is our SEO right now?

I found a free tool that scans your website and tells you how good its SEO is. You can see the report for your website [by clicking here](http://seositecheckup.com/checkup/result/d3e08a947a388445ba3fb92ffe7a56ea?url=www.cvlga.org). The report has a number of suggestions for us.

This tool gives your developers some tips about how to improve the website's SEO. I've used most of its suggestions in this guide.


## The Goal
Let's take a look at a Google search for "columbus library".


![Non-GA Search](https://www.dropbox.com/s/de5iwcg01jbrad3/Non%20GA%20Search.png?dl=1)

<br>
<br>
<br>
<br>

Depending on where you are, you might get the Chattahoochee Valley website as the first result or you may get the Columbus, OH library first. In this case, I'm searching as if I was in Alabama at the time. It appears that the Columbus, OH library is first.

Now let's look at a search for "columbus library" from within Georgia.

![GA Search](https://www.dropbox.com/s/punctarx07eclqo/GA%20Search.png?dl=1)

Google knows that I'm in Columbus, GA right now, so it has changed the order of the search results for me. This library comes up first, but look at the differences. The description "snippet" references the Columbus, OH library. Also notice that the branch locations come up in the search result, but there are no links to other parts of the site (like the Teen section, or eBooks).

The goal of our SEO efforts will be:
 1. To make Chattahoochee Valley Libraries appear first for a search for "columbus library".
 2. To have sub-links to important parts of the website. This could be links to a "Locations" page, an "eBooks" page, the "Teen" section of the website, or even a link to the "Get a Library Card" page.
 3. To make sure that the website's [PageRank](https://en.wikipedia.org/wiki/PageRank) is as high as possible. A website's "PageRank" is Google's measure of how important the site is to people when they search for something).



<br>
<br>
<br>

## Getting Started

### Simple changes

There are a few things that can be done now to improve the website's SEO. These things won't take much time to do, but will have **the most** impact.

#### Page Titles

Page titles are perhaps __the most important__ thing about SEO for your website. This is what Google displays on search results. Google also uses these titles to determine if your website is what users are looking for.

##### Homepage Title
Let's take a look at the page title on the homepage.

The homepage's page title is: "Home | cvlga.org". When Google looks at your page, this is what it prints out in the search results:

![Page title](https://www.dropbox.com/s/wu8k5go59t6uw8y/Screenshot%202014-10-26%2014.32.04.png?dl=1)

People probably don't immediately know what "cvlga" is until they visit your website. I suggest that we change the page title on the homepage to be something a little more descriptive. In addition, I really, **really** want to include Columbus, GA in the title. That would avoid much of the confusion when people search for "columbus library" and see your page.

I suggest this: "Chattahoochee Valley Libraries - Serving the Columbus, GA valley area". That may seem long, but it's more important to get the correct information on your title than to leave things out. It *would* be nice for it to be shorter, but I believe that including "Columbus, GA" is vital and should be included at all costs. Of course, please change this as you see fit, but that gives you an idea of how users will see your page on Google.com.

Here's an example of what the search result might look like:

![New title](https://www.dropbox.com/s/3gkdw2mfr8c8743/Screenshot%202014-10-26%2014.41.53.png?dl=1)

<br>

The title is cut-off a little bit, but this will improve search results by a large margin since it contains relevant information.

Here's the line of HTML code to put on the homepage:

```html
<title>Chattahoochee Valley Libraries - Serving the Columbus, GA valley area</title>
```

##### Page Titles for other pages
The page titles for the other pages look good to me. I would only suggest the following change. Change the "cvlga.org" in the title to be "Chattahoochee Valley Libraries". That will ensure that anyone searching for "Chattahoochee libraries" will also find your pages. It's more descriptive than the simple "cvlga.org".

For example, the "Books" page would be: "Books - Chattahoochee Valley Libraries" instead of "Books | cvlga.org".

Here's the HTML:

```html
<title>Books - Chattahoochee Valley Libraries</title>
```


#### Page description tag
There is another HTML tag that is **very** useful for Google when it looks at your page. It's just simple, 2-3 sentence description of the current webpage. Google may use this description when people search on Google.com.

For example, right now, Google's description for the cvlga.org home page is: 

"Contact Us. Chattahoochee Valley Libraries. 3000 Macon Road Columbus, GA 31906. Phone: (706) 243-2669. Toll Free: 1-800-652-0782. Administrative Staff."

That includes some good information, but it could be more human-readable if we gave Google a better description. Here's a suggestion for a good description for the homepage, at about 145 characters.

"Chattahoochee Valley Libraries serve the Columbus, GA valley area. We offer tutoring and training courses. We also have eBooks and music downloads"

Again, change this as you see fit. This description needs to present the top 1-2 things you want people to know about the library. I know that is difficult, but it will help your search results.

Put the following HTML in the \<head\> tag of the website:

```html
<meta name="description" content="Chattahoochee Valley Libraries serve the Columbus, GA valley area. We offer tutoring and training courses. We also have eBooks and music downloads">
```
<br>

It would be great to have this description tag for every page on the website, but someone will have to sit down and make one for each page. At the very least, please consider making one for the homepage.

#### "Alt" text for images
When Google scans your website, it can't see images the way humans do. Instead, it relies on something called "alt" text (short for "alternate" text) to understand what an image is and why it's on your site. That will allow it to catalog the images and match searches on Google to your images.

In addition, the visually-impaired rely on alt text on websites for the same reason: to understand what an image means without seeing it.

For both these reasons, we should use alt text on the website's images.

Let's look at the "Free Wifi" image on the website. This is what it looks like to Google:

```html
<img src="/sites/default/files/logos/wifi_free.png">
```

There isn't any text associated with "Free wifi" on the page, so Google doesn't know you offer that at the library. Visually impaired visitors won't know that either.

Let's add some "alt" text to the image:

```html
<img alt="All our locations offer free wifi" src="/sites/default/files/logos/wifi_free.png">
```

Easy!

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

### Getting a little more advanced

#### Canonical URLs
Don't let that term scare you! It's not as complicated as it sounds.

Look at the following website addresses:
 * http://www.cvlga.org
 * www.cvlga.org
 * cvlga.org
 * cvlga.org/

They all look like the same thing, right? Google doesn't treat them the same way, though. When Google monitors visitors to your website, it thinks that people who type in "cvlga.org" and others who type in "www.cvlga.org" are going to 2 different places.
 
Because of this, your website's PageRank goes down since it gets "split" between these different websites. Remember, PageRank is important for Google to match your website with Google searches.

We can change that with a one-line addition to each web page on the website. On each page, we need a new HTML tag inside the \<head\> tag. In it, we will decide on the format to force everyone to use when they visit your website.

Let's use "http://www.cvlga.org" for the homepage. The following line will force everyone to go to "http://www.cvlga.org", and not any of the other variants.

```html
<link rel="canonical" href="http://www.cvlga.org" />
```

Likewise, for the "Books" page, there should be an HTML line like this:
```html
<link rel="canonical" href="http://www.cvlga.org/books" />
```
<br />

Do this for each page on your website.

<br />
<br />
<br />
<br />
<br />

#### Page Content

These days, page content is just as important as many of the other tips we've seen so far. In short, you want to have all the text on your web page that you want Google to use (and other people to search for). Ideally, you want *regular, original* content on the website. If your website is being updated often, then Google will be crawling it often too.

I think it's great that the homepage has regular content posted on it. That's exactly what should keep happening. The "Events" page is great too. Everything looks good.

#### Structured Data

With *structured* data (such as events), Google sometimes makes a list underneath a search result. Here's an example:

![Event markup](https://www.google.com/help/hc/images/webmasters/webmasters_164506_richsnippets_multipleevent_en.gif)

The events at this venue are listed below the search result.

To make this happen for us, we need to use some special HTML on these events.

This special HTML is from www.schema.org. Google even has a nice tool to help you add this HTML to your website at: https://www.google.com/webmasters/markup-helper.

Let's take an event from the page at www.cvlga.org/events and include the extra HTML.

Here's the original HTML:

```html
<div class="views-row views-row-1 views-row-odd views-row-first">
	<div class="views-field views-field-title">
		<span class="field-content">
			<a href="http://meetings.cvrls.net/evanced/lib/eventsignup.asp?ID=14589">Beginner's Internet Class</a>
		</span>
	</div>  
	<div class="views-field views-field-description">
		<span class="field-content">
			<b>When:</b> Friday, December 12, 2014 - 10:30 AM - 12:00 PM<br>
			<b>Where:</b> North Columbus Public Library at Small Conference Room<br><br>
			This class teaches what the Internet is about. What it consists of, how to get on the Internet and search for and navigate websites.<br>
			Class size is limited, so prior registration is required for all computer classes. Please contact the North Columbus Public Library staff at 706-748-2855 to confirm your spot.<br>
		</span>
	</div>
</div>
```

Here's the HTML with that added markup:

```html
<div class="views-row views-row-1 views-row-odd views-row-first" itemscope itemtype="http://schema.org/Event">
	<div class="views-field views-field-title">
		<span class="field-content">
			<a itemprop="url" href="http://meetings.cvrls.net/evanced/lib/eventsignup.asp?ID=14589">Beginner's Internet Class</a>
		</span>
	</div>  
	<div class="views-field views-field-description">
		<span class="field-content">
			<b>When:</b> 
			<span itemprop="startDate" content="2014-12-12T10:30">
				Friday, December 12, 2014
			</span>
			 - 10:30 AM - 12:00 PM<br/>
			<b>Where:</b>
			<span itemprop="location" itemscope itemtype="http://schema.org/Place"> 
				<span itemprop="name">
					North Columbus Public Library at Small Conference Room
				</span>
			</span><br/><br/>
			<span itemprop="description">
				This class teaches what the Internet is about. What it consists of, how to get on the Internet and search for and navigate websites.<br/>
				Class size is limited, so prior registration is required for all computer classes. Please contact the North Columbus Public Library staff at 706-748-2855 to confirm your spot
			</span>.<br/>
		</span>
	</div>
</div>
<meta itemprop="url" content="http://meetings.cvrls.net/evanced/lib/eventsignup.asp?ID=14589">
```

I know, there's a lot of extra code here. You'll have to decide if this is right for you, but this is a good example of structured data in HTML.

Here's a breakdown of the changes:
 * The ```<div>``` tag that contains the event information has this added to it: ```itemscope itemtype="http://schema.org/Event"```
 * The ```<a>``` tag holding the URL for the event has ```itemprop="url"``` added to it.
 * Each important part of the date's data is wrapped in a ```<span>``` with some custom attributes (like itemprop, itemscope, etc).
 * At the very bottom, I've added a new ```<meta>``` tag to let Google know what the event's URL is on the website.

 

# Thank you!
 
Thanks for reading. I'll keep updating this as I have time, but you can always find an open-source copy of this PDF on GitHub at: [https://github.com/ssfinney/CVLGA-SEO-Guide](https://github.com/ssfinney/CVLGA-SEO-Guide).