Hullo

	<head>
		<!-- Created using Storyline 360 - http://www.articulate.com  --> 
		<!-- version: 3.43.22859.0 --> 

    <style>
      @font-face {
        font-family: "Open Sans Full";
        font-style: normal;
        font-weight: 400;
        src: local("Open Sans"),
             local("OpenSans"),
             url(html5/lib/stylesheets/mobile-fonts/open-sans-regular.woff) format("woff")
      }
      body {
        background-color: #F7F7F7;
      }
      h1 {
        color: #636363;
        font-family: "Open Sans Full", Helvetica, sans-serif;
        font-size: 150%;
        margin-bottom: 92px;
        padding-bottom: 0;
      }

      button {
        background-color: #FFF;
        border: 1px solid #636363;
        border-radius: 80px;
        box-shadow: 2px 3px 4px 1px rgba(39, 39, 39, 0.33);
        color: #636363;
        font-family: "Open Sans Full", Helvetica, sans-serif;
        font-size: 100%;
        padding: 20px 50px;
      }
      img {
        height: 15px;
        width: 15px;
        margin-left: 8px;
      }
    </style>
		<script>
			
			/******************************************************************************/
			//
			// NOTE TO DEVELOPERS:
			// The following code should be integrated with your web page in order to open
			// the presentation in a new window.  To launch the presentation immediately, 
			// simply copy the code below into your web page.  To launch the presentation
			// when a button or link is clicked, call LaunchPresentation when the onClick
			// event is triggered.
			//
			/******************************************************************************/		
		
		
			var Safari =  (navigator.appVersion.indexOf("Safari") >= 0);
			
			var g_bChromeless = false;
			var g_bResizeable = false;
			var g_nContentWidth = 1044;
			var g_nContentHeight = 1294;
			var g_strStartPage = "story.html" + document.location.search;
			var g_strBrowserSize = "optimal";
		
			function LaunchContent()
			{
				var nWidth = screen.availWidth;
				var nHeight = screen.availHeight;

				if (nWidth > g_nContentWidth && nHeight > g_nContentHeight && g_strBrowserSize != "fullscreen")
				{
					nWidth = g_nContentWidth;
					nHeight = g_nContentHeight;
					
					if (!Safari && !g_bChromeless)
					{
						nWidth += 17;
					}
				}

				// Build the options string
				var strOptions = "width=" + nWidth +",height=" + nHeight;
				if (g_bResizeable)
				{
					strOptions += ",resizable=yes"
				}
				else
				{
					strOptions += ",resizable=no"
				}

				if (g_bChromeless)
				{
					strOptions += ", status=0, toolbar=0, location=0, menubar=0, scrollbars=0";
				}
				else
				{
					strOptions += ", status=1, toolbar=1, location=1, menubar=1, scrollbars=1";
				}

				// Launch the URL
				if (Safari)
				{
					var oWnd = window.open("", "_blank", strOptions);
					oWnd.location = g_strStartPage;
				}
				else
				{
					window.open(g_strStartPage , "_blank", strOptions);
				}
			}

			
			
		</script>
		
	</head>

<center>
			<table width="100%" height="100%" border="0" cellpadding="0" cellspacing="0">
				<tr>
					<td>
						<center>
              <h1 tabIndex="-1">Digital Dexterity</h1>
							<button onclick="LaunchContent()" aria-label="Launch course: opens in new window">Launch course <img src="story_content/external_window.png" style="border-style: none; height: 14px; width: 14px;" tabIndex="-1" aria-hidden="true"/></button>
						</center>
					</td>
				</tr>
			</table>
		</center>

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/leahgust/test_pages/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

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

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/leahgust/test_pages/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
