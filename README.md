# Clean reading filters
This is a filter list for [uBlock Origin](https://github.com/gorhill/uBlock), to filter out irrelevant content from page. Such as recommond for you, page footer or navigation, only keep the main content for better reading experience.

You may wonder why not use reading mode or apps like Instapaper, the problem is some pages has unique layout, the reading mode and RIL(read it later) app didn't handle the layout properly. For example, in medium, there are some hightlights and comments I'd like to read as well. This filter will keep the origin website layout and design. But I need to manually handle every website, yes, And I like the feeling of control tools I'm using.

I use this filters work with [SingleFile](https://github.com/gildas-lormeau/SingleFile), to download the webpage so I can read it later, literally offline reading. With this filters, the downloaded file size reduced 2-5x, will save lots storage space.

## How to use
1. Install [uBlock Origin](https://github.com/gorhill/uBlock)
2. In uBlock Origin settings > Filter lists tab, sroll down to the bottom of page
   you'll find the **Import...** section, paste `https://raw.githubusercontent.com/jay1803/clean-reading-filters/main/filters.txt` to the field then click **[Apply changes]**
3. Then you'll saw the Clean reading filters appears in the Custom section.
