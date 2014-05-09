# 'Share' widget for GNU social

This adds links/buttons to your page so that visitors can share it on
GNU social.

## Usage

You can use this in a few different ways. In all cases, the "title"
and "URL" parameters are optional. If omitted, the widget will share
the current page with the document's title.

### HTML

Add one of the following where you want the links/buttons to appear.

#### With server-side fallback

    <div class="gs-share">
      <a href="share.php?url=URL-from-href&amp;title=TITLE-from-href" class="js-gs-share">Share on GNU social</a>
    </div>

#### JavaScript only

    <div class="gs-share">
      <button data-url="URL-from-data" data-title="TITLE-from-data" class="js-gs-share">Share on GNU social</button>
    </div>

### JavaScript

Add the following at the bottom of your page.
(Optional if you're using the "server-side fallback" method above).

    <script src="gs-share.js"></script>

### CSS

Add the following in the `<head>` of your page.

    <link rel="stylesheet" href="styles.css" />

## Demo

http://chromic.org/articles/project-autonomous/#share