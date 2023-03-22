## === Refactoring Hireseon.com-Adding Semantic HTML 5 markups and removing unwanted elements ===

this readme document and HTML5 format is based upon the format outlined in DONT CODE TIRED “Redesigning DontCodeTired.com (Part 4) – Adding Semantic HTML5 Markup and Removing Unwanted Elements” blog [Redesigning DontCodeTired.com part 4]( http://dontcodetired.com/blog/post/Redesigning-DontCodeTiredCom-%28Part-4%29-Adding-Semantic-HTML-5-Markup-and-Removing-Unwanted-Elements)

the main markups uses divs to organise the layout

HTML5 tags has been refactored to the markup to provide semantics elements to conform with today’s best practices

the following HTML5 elements has been added to the markup

# Title Bar

title bar description has been added to optimise SEO search and provide a more descriptive function for the website.

the title message is chosen to limit the number of characters to 55-60 maximum characters to minimise the lost of messaging with the message displayed in the front end of the title as outlined in [<title>: The Document Title element]( https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title)

# Alt Text

<alt> text added for banner graphics and images within the main content. Benefits alt text is left out as they are descriptive images as outlined [Write good Alt Text to describe images]( https://accessibility.huit.harvard.edu/describe-content-images)

# Header

<header> that contains a <h1> heading for the logo and a <nav> navigation bar for site navigation through <a>

# Hero

web banner contained in a separate <section>. A static graphic currently occupies this space which can be further developed into image carousels or slider to make the website more interesting

# Main Content

the content of the site is contained in the <main> that is further divided into different <article> containing its own <h2> headings and <p> elements with descriptive paragraphs of Hireseon services provided

the right hand “benefits” panel is made up of a <aside> containing different <section> having its own <h3> headings and <p> elements with descriptive paragraphs outlining the benefits. This benefit panel of having a combination of <aside> and <section> is chosen to differentiate between the main content combination of <main> and <article>

<footer> applied as page footer with its own <h4> heading and <p> elements

website to be viewed at 1,260px width in live server with inspect panel opened in google chrome. Website responsiveness can improve site browsing experience for future development








