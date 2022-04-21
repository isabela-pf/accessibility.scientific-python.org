Image Descriptions
==================

How to use this document
------------------------

This section is divided into two sections: a high-level overview and a
more specific reference section.

The high level overview of includes `Main Principles`__, `Style Guide`__, 
and `Per-Project Guidelines`__. The reference section can be found under 
`Reference`__ with sub-sections for recommendations by image trait. 

Main Principles
---------------

Understanding the goals behind why we write alt text can be helpful in
figuring out how to write appropriate descriptions and to navigate other
recommendations in this document.

On the most foundational level, alt text needs to be: 
* Transformable
* Complete
* Contextual
* Formatted properly

Transformable
~~~~~~~~~~~~~

The core motivation behind writing image descriptions is to ensure that 
information can be conveyed in multiple forms so that it can be accessed by 
all people regardless of what form they need. Text is the cornerstone of this 
and similarprocesses because it can be the most straightforward to transform 
into other communication styles (like audio, digital Braille, a different 
language, or others).

This doesn’t mean that text representations are the only way to make something 
more accessible. In fact, having information in a variety of forms means more 
chances to accommodate more people. For the sake of scoping this 
recommendation, we will be discussing text exclusively.


Complete
~~~~~~~~

Just as not all images are the same, not all alt text is the same. What
types of alt text makes sense for an image depends on the images’
content and context.

In terms of content, images can be - Decorative (does not add meaningful
content) - Functional (adds content with a use, often interactive) -
Informative (adds or illustrates content) - Complex (adds a large amount
of content)

For guidance on determining an image’s role as content and writing
appropriate alt text, refer to the `W3’s alt decision
tree <https://www.w3.org/WAI/tutorials/images/decision-tree/>`__.

In terms of context, alt text needs to fit into the content that
surrounds it. It can be helpful to ask questions like the following to
determine what information needs to be prioritized when describing that
image:

-  Is the image demonstrating something described in the text preceding
   it?
-  Is the image adding content that hasn’t been mentioned previously?
-  Does the image have a caption?
-  Does the image match one used elsewhere in the same media?
-  What information do I need from this image to understand the media as
   a whole? What information do I not need?

Contextual
~~~~~~~~~~

Just as not all images are the same, not all alt-text is the same. What
types of alt-text makes sense for an image depends on the images’
content and context.

In terms of content, images can be - Decorative (does not add meaningful
content) - Functional (adds content with a use, often interactive) -
Informative (adds or illustrates content) - Complex (adds a large amount
of content)

For guidance on determining an image’s role as content and writing
appropriate alt text, refer to the `W3’s alt decision
tree <https://www.w3.org/WAI/tutorials/images/decision-tree/>`__.

In terms of context, alt-text needs to fit into the content that
surrounds it. It can be helpful to ask questions like the following to
determine what information needs to be prioritized when describing that
image: - Is the image demonstrating something described in the text
preceding it? - Is the image adding content that hasn’t been mentioned
previously? - Does the image have a caption? - Does the image match one
used elsewhere in the same media? - What information do I need from this
image to understand the media as a whole? What information do I not
need? - ### Formatted Properly Having an image description won’t help if
it’s formatted in a way that someone can’t access it or doesn’t know how
to find it. There are a few standard methods for web content that are
reliable.

Formatted Properly
~~~~~~~~~~~~~~~~~~

Having an image description won't help if it's formatted in a way that someone 
can't access it or doesn't know how to find it. There are a few standard 
methods for web content that are reliable.


Alt text
^^^^^^^^

Alt text is the most frequently used style of image description on the internet.

This is the best place to start for describing images or similar
visualization content. It derives its name from the HTML ``alt`` element
used to modify images. Because of its prominence, many resources on
proper image descriptions may use the term alt text to describe best
practices that could benefit other image descriptions as well.

For web-based content, this is the default. All images need alt text
even if they employ additional descriptions.

For more information on the ``alt`` element, refer to `MDN’s alt
documentation <https://developer.mozilla.org/en-US/docs/Web/API/HTMLImageElement/alt>`__.

For examples of this in use, refer to [list of links to image types or
content later in the document] `Logos <>`__, `Images of People <>`__,
`Images of Interfaces <>`__.

Linking to long content
^^^^^^^^^^^^^^^^^^^^^^^

Linking to long or detailed descriptions is an additional method best
suited for complex, info-heavy, or text-heavy images where descriptions
must exceed the recommended length for alt text. Linking should not be
used in place of alt text, only to supplement it.

Practices for linking to long content may vary based on project. Some
examples include: - Having a webpage that contains all the long
descriptions used throughout that website in one place. - Having a
end-of-page list of long descriptions below the images they describe,
similar to endnotes. - Creating a Gist for each image and linking each
image to that (not recommended because it relies on a single GitHub user
account, but may be a good stopgap until a more permanent solution can
be set in place).

For examples of this in use, refer to [list of links to image types or
content later in the document] `Sequential Images <>`__ or
`Diagrams <>`__.

A note on ``longdesc``
''''''''''''''''''''''

``longdesc`` is a deprecated HTML element meant to provide long
descriptions for images. It may still appear in other recommendations,
but because there is no longer browser support for it it should not be
used.

The common practice is now to link to long descriptions (more in the
prior section).

For more information on the ``longdesc`` element, refer to `MDN’s
longdesc
documentation <https://developer.mozilla.org/en-US/docs/Web/API/HTMLImageElement/longDesc>`__.

Empty attribute
^^^^^^^^^^^^^^^

For decorative images, meaning they either aren’t needed to understand
content or are represented in full elsewhere, use an empty ``alt``
element. Having the ``alt`` element is still necessary.

The only way to know if an image is decorative is based on the context
it is used in.

For more information on decorative images, refer to .

For examples of this in use, refer to [list of links to image types or
content later in the document] . #### Captions

Captions and image descriptions are not the same, and if both are used
they should support one another. Captions do this thing alt text does
another

For more information on captions, refer to .

For examples of this in use, refer to [list of links to image types or
content later in the document] . #### ARIA Label

{acronym}, ARIA, is an additive accessibility tool for web content.

ARIA is powerful and often needed, but proper HTML is the preferred
method whenever possible. Please don’t use ARIA labels without first
ensuring that proper HTML tags cannot suffice.

For more information on ARIA, refer to .

For examples of this in use, refer to [list of links to image types or
content later in the document] `Variable visuals <>`__.

Style Guide
-----------

Consistently formatting alt text helps its readability whether or not it
is read by assistive technology.

These guidelines supplement the writing style guides a project may
already have present, especially in documentation. Defer to a project’s
style guide before these guidelines. ### Basics

Here are some simple alt text guidelines to start with:

-  Avoid beginning descriptions with “an image of” or similar phrases.
   That is already represented by proper HTML.
-  Check your spelling. You can always write alt text somewhere with
   spellcheck and transfer it to your main workspace.
-  Write with `plain
   language <https://www.plainlanguage.gov/guidelines/>`__
-  Acronyms are the only things that need - all-caps.
-  Text in an image needs to be written as text somewhere else. If it is
   short, it can be in the alt text.

Punctuation
~~~~~~~~~~~

Write alt text as complete sentences. This means it needs to include a
complete thought that can be understood on its own.

Just like other complete sentences, alt text needs punctuation.
Appropriate commas and periods are the most important to include for alt
text.

Capitalization
~~~~~~~~~~~~~~

Alt text uses `sentence
case <https://en.wikipedia.org/wiki/Letter_case#Sentence_case>`__.

Character count
~~~~~~~~~~~~~~~

These guidelines do not limit alt text to a specific character count
even though some other guidelines do.

It is still important to know that alt text should be as brief and
direct as possible. If a short sentence or three does not cover all the
information, refer to the links in `Main Principles: Formatted
Properly <>`__ for different types and methods of describing images.

Color and directional words
~~~~~~~~~~~~~~~~~~~~~~~~~~~

Alt text can be used by people who are anywhere on the spectrum from
blind to sighted. Colors and directions (like left or right) are
visual-rooted descriptions. While they can be used, do so only when
relevant to the context of the image.

Consider if - The image is using colors with meaning, like color-coding
- The placement of an element contributes to its relationship to other
elements (like in documentation, when a screen shot shows where to find
a button or menu) - The colors or directions matter in the scope of the
content as a whole (for example, if they are referenced elsewhere)

Per-Project Guidelines
----------------------

.. _reference-1:

Reference
---------

By Image Type
~~~~~~~~~~~~~

For reference, the following section has a list of common image types
with a guideline and examples for each. These are designed to follow the
above principles while providing help with specific applications.

This list is not exhaustive. If you can’t find an image type you are
looking for or don’t think the guideline fits your case, refer to the
Main Principles section and ensure your solution meets those needs. -
Graphs - Diagrams - Things with people - Interactive visuals - Varying
visuals - Autogenerated visuals - Logos - Screenshots - Image of
interfaces - Gifs

Graphs
^^^^^^

There are a key principles that apply across all graphs: - Identify the
graph type - Describe the axis - Describe the general shape - Describe
any characteristics - Describe the general changes or pattern

Bar Charts
''''''''''

Using the key principles, we can write alt-text for bar charts…

Images with people
~~~~~~~~~~~~~~~~~~

Like all other alt text, context is key to deciding what to write.
Writing about people, especially in cases where the people in the photo
aren’t known, takes care.

The most general guideline is to avoid making assumptions about the
people in the photos. Make choices based information in the surrounding
content or an external source if relevant.

If the people in a photo are known and it is relevant to the content,
put their name in the alt text. Other descriptions aren’t usually
necessary once the name is used.

It is also best to \* Use gender-neutral language (unless a subject’s
gender is known) \* Avoid describing physical features unless it is
necessary for supporting the content \* Use general terms for a group of
people rather than describing each individual