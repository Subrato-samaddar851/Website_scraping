```python
! pip install requests
```

    Requirement already satisfied: requests in d:\users\lib\site-packages (2.32.2)
    Requirement already satisfied: charset-normalizer<4,>=2 in d:\users\lib\site-packages (from requests) (2.0.4)
    Requirement already satisfied: idna<4,>=2.5 in d:\users\lib\site-packages (from requests) (3.7)
    Requirement already satisfied: urllib3<3,>=1.21.1 in d:\users\lib\site-packages (from requests) (2.2.2)
    Requirement already satisfied: certifi>=2017.4.17 in d:\users\lib\site-packages (from requests) (2024.7.4)
    


```python
! pip install beautifulsoup4

```

    Requirement already satisfied: beautifulsoup4 in d:\users\lib\site-packages (4.12.3)
    Requirement already satisfied: soupsieve>1.2 in d:\users\lib\site-packages (from beautifulsoup4) (2.5)
    


```python
! pip install selenium
```

    Collecting selenium
      Downloading selenium-4.25.0-py3-none-any.whl.metadata (7.1 kB)
    Requirement already satisfied: urllib3<3,>=1.26 in d:\users\lib\site-packages (from urllib3[socks]<3,>=1.26->selenium) (2.2.2)
    Collecting trio~=0.17 (from selenium)
      Downloading trio-0.26.2-py3-none-any.whl.metadata (8.6 kB)
    Collecting trio-websocket~=0.9 (from selenium)
      Downloading trio_websocket-0.11.1-py3-none-any.whl.metadata (4.7 kB)
    Requirement already satisfied: certifi>=2021.10.8 in d:\users\lib\site-packages (from selenium) (2024.7.4)
    Requirement already satisfied: typing_extensions~=4.9 in d:\users\lib\site-packages (from selenium) (4.11.0)
    Requirement already satisfied: websocket-client~=1.8 in d:\users\lib\site-packages (from selenium) (1.8.0)
    Collecting attrs>=23.2.0 (from trio~=0.17->selenium)
      Downloading attrs-24.2.0-py3-none-any.whl.metadata (11 kB)
    Requirement already satisfied: sortedcontainers in d:\users\lib\site-packages (from trio~=0.17->selenium) (2.4.0)
    Requirement already satisfied: idna in d:\users\lib\site-packages (from trio~=0.17->selenium) (3.7)
    Collecting outcome (from trio~=0.17->selenium)
      Downloading outcome-1.3.0.post0-py2.py3-none-any.whl.metadata (2.6 kB)
    Requirement already satisfied: sniffio>=1.3.0 in d:\users\lib\site-packages (from trio~=0.17->selenium) (1.3.0)
    Requirement already satisfied: cffi>=1.14 in d:\users\lib\site-packages (from trio~=0.17->selenium) (1.16.0)
    Collecting wsproto>=0.14 (from trio-websocket~=0.9->selenium)
      Downloading wsproto-1.2.0-py3-none-any.whl.metadata (5.6 kB)
    Requirement already satisfied: pysocks!=1.5.7,<2.0,>=1.5.6 in d:\users\lib\site-packages (from urllib3[socks]<3,>=1.26->selenium) (1.7.1)
    Requirement already satisfied: pycparser in d:\users\lib\site-packages (from cffi>=1.14->trio~=0.17->selenium) (2.21)
    Requirement already satisfied: h11<1,>=0.9.0 in d:\users\lib\site-packages (from wsproto>=0.14->trio-websocket~=0.9->selenium) (0.14.0)
    Downloading selenium-4.25.0-py3-none-any.whl (9.7 MB)
       ---------------------------------------- 0.0/9.7 MB ? eta -:--:--
       ---------------------------------------- 0.0/9.7 MB ? eta -:--:--
       ---------------------------------------- 0.0/9.7 MB ? eta -:--:--
       ---------------------------------------- 0.0/9.7 MB ? eta -:--:--
       ---------------------------------------- 0.0/9.7 MB ? eta -:--:--
       ---------------------------------------- 0.0/9.7 MB ? eta -:--:--
       ---------------------------------------- 0.0/9.7 MB ? eta -:--:--
       ---------------------------------------- 0.0/9.7 MB 186.2 kB/s eta 0:00:52
       ---------------------------------------- 0.0/9.7 MB 186.2 kB/s eta 0:00:52
       ---------------------------------------- 0.1/9.7 MB 252.2 kB/s eta 0:00:39
       ---------------------------------------- 0.1/9.7 MB 269.5 kB/s eta 0:00:36
       ---------------------------------------- 0.1/9.7 MB 269.5 kB/s eta 0:00:36
       ---------------------------------------- 0.1/9.7 MB 269.5 kB/s eta 0:00:36
       ---------------------------------------- 0.1/9.7 MB 242.7 kB/s eta 0:00:40
       ---------------------------------------- 0.1/9.7 MB 242.7 kB/s eta 0:00:40
        --------------------------------------- 0.1/9.7 MB 218.3 kB/s eta 0:00:44
        --------------------------------------- 0.1/9.7 MB 218.3 kB/s eta 0:00:44
        --------------------------------------- 0.1/9.7 MB 218.3 kB/s eta 0:00:44
        --------------------------------------- 0.1/9.7 MB 213.0 kB/s eta 0:00:45
        --------------------------------------- 0.1/9.7 MB 213.0 kB/s eta 0:00:45
        --------------------------------------- 0.2/9.7 MB 204.8 kB/s eta 0:00:47
        --------------------------------------- 0.2/9.7 MB 205.6 kB/s eta 0:00:47
        --------------------------------------- 0.2/9.7 MB 218.4 kB/s eta 0:00:44
        --------------------------------------- 0.2/9.7 MB 241.3 kB/s eta 0:00:40
       - -------------------------------------- 0.3/9.7 MB 290.1 kB/s eta 0:00:33
       - -------------------------------------- 0.3/9.7 MB 327.6 kB/s eta 0:00:29
       - -------------------------------------- 0.3/9.7 MB 327.6 kB/s eta 0:00:29
       - -------------------------------------- 0.3/9.7 MB 327.6 kB/s eta 0:00:29
       - -------------------------------------- 0.3/9.7 MB 287.2 kB/s eta 0:00:33
       - -------------------------------------- 0.4/9.7 MB 305.1 kB/s eta 0:00:31
       - -------------------------------------- 0.4/9.7 MB 305.1 kB/s eta 0:00:31
       - -------------------------------------- 0.4/9.7 MB 305.1 kB/s eta 0:00:31
       - -------------------------------------- 0.4/9.7 MB 305.1 kB/s eta 0:00:31
       - -------------------------------------- 0.4/9.7 MB 275.5 kB/s eta 0:00:34
       - -------------------------------------- 0.4/9.7 MB 275.5 kB/s eta 0:00:34
       - -------------------------------------- 0.4/9.7 MB 274.9 kB/s eta 0:00:34
       - -------------------------------------- 0.4/9.7 MB 283.7 kB/s eta 0:00:33
       -- ------------------------------------- 0.5/9.7 MB 307.9 kB/s eta 0:00:30
       -- ------------------------------------- 0.6/9.7 MB 349.8 kB/s eta 0:00:27
       -- ------------------------------------- 0.7/9.7 MB 395.5 kB/s eta 0:00:23
       --- ------------------------------------ 0.8/9.7 MB 451.0 kB/s eta 0:00:20
       --- ------------------------------------ 0.9/9.7 MB 487.1 kB/s eta 0:00:19
       ---- ----------------------------------- 1.0/9.7 MB 559.2 kB/s eta 0:00:16
       ---- ----------------------------------- 1.2/9.7 MB 616.6 kB/s eta 0:00:14
       ----- ---------------------------------- 1.3/9.7 MB 692.7 kB/s eta 0:00:13
       ------ --------------------------------- 1.5/9.7 MB 760.3 kB/s eta 0:00:11
       ------ --------------------------------- 1.7/9.7 MB 839.7 kB/s eta 0:00:10
       ------- -------------------------------- 1.9/9.7 MB 900.4 kB/s eta 0:00:09
       -------- ------------------------------- 2.1/9.7 MB 982.9 kB/s eta 0:00:08
       --------- ------------------------------ 2.3/9.7 MB 1.0 MB/s eta 0:00:08
       --------- ------------------------------ 2.4/9.7 MB 1.1 MB/s eta 0:00:07
       ---------- ----------------------------- 2.6/9.7 MB 1.2 MB/s eta 0:00:07
       ----------- ---------------------------- 2.8/9.7 MB 1.2 MB/s eta 0:00:06
       ------------ --------------------------- 3.0/9.7 MB 1.3 MB/s eta 0:00:06
       ------------ --------------------------- 3.1/9.7 MB 1.3 MB/s eta 0:00:05
       ------------- -------------------------- 3.3/9.7 MB 1.4 MB/s eta 0:00:05
       -------------- ------------------------- 3.5/9.7 MB 1.4 MB/s eta 0:00:05
       --------------- ------------------------ 3.8/9.7 MB 1.5 MB/s eta 0:00:04
       ---------------- ----------------------- 4.0/9.7 MB 1.5 MB/s eta 0:00:04
       ----------------- ---------------------- 4.2/9.7 MB 1.6 MB/s eta 0:00:04
       ------------------ --------------------- 4.4/9.7 MB 1.7 MB/s eta 0:00:04
       ------------------- -------------------- 4.7/9.7 MB 1.7 MB/s eta 0:00:03
       -------------------- ------------------- 4.9/9.7 MB 1.8 MB/s eta 0:00:03
       --------------------- ------------------ 5.2/9.7 MB 1.8 MB/s eta 0:00:03
       ---------------------- ----------------- 5.4/9.7 MB 1.9 MB/s eta 0:00:03
       ----------------------- ---------------- 5.7/9.7 MB 2.0 MB/s eta 0:00:03
       ------------------------ --------------- 6.0/9.7 MB 2.0 MB/s eta 0:00:02
       ------------------------- -------------- 6.3/9.7 MB 2.1 MB/s eta 0:00:02
       --------------------------- ------------ 6.6/9.7 MB 2.2 MB/s eta 0:00:02
       ---------------------------- ----------- 6.9/9.7 MB 2.2 MB/s eta 0:00:02
       ----------------------------- ---------- 7.1/9.7 MB 2.3 MB/s eta 0:00:02
       ------------------------------ --------- 7.4/9.7 MB 2.3 MB/s eta 0:00:01
       ------------------------------- -------- 7.6/9.7 MB 2.4 MB/s eta 0:00:01
       -------------------------------- ------- 7.8/9.7 MB 2.4 MB/s eta 0:00:01
       --------------------------------- ------ 8.0/9.7 MB 2.4 MB/s eta 0:00:01
       ---------------------------------- ----- 8.3/9.7 MB 2.5 MB/s eta 0:00:01
       ----------------------------------- ---- 8.6/9.7 MB 2.5 MB/s eta 0:00:01
       ------------------------------------ --- 8.8/9.7 MB 2.5 MB/s eta 0:00:01
       ------------------------------------- -- 9.1/9.7 MB 2.6 MB/s eta 0:00:01
       -------------------------------------- - 9.4/9.7 MB 2.6 MB/s eta 0:00:01
       ---------------------------------------  9.6/9.7 MB 2.7 MB/s eta 0:00:01
       ---------------------------------------- 9.7/9.7 MB 2.7 MB/s eta 0:00:00
    Downloading trio-0.26.2-py3-none-any.whl (475 kB)
       ---------------------------------------- 0.0/476.0 kB ? eta -:--:--
       ----------------------- ---------------- 276.5/476.0 kB 8.6 MB/s eta 0:00:01
       ---------------------------------------- 476.0/476.0 kB 6.0 MB/s eta 0:00:00
    Downloading trio_websocket-0.11.1-py3-none-any.whl (17 kB)
    Downloading attrs-24.2.0-py3-none-any.whl (63 kB)
       ---------------------------------------- 0.0/63.0 kB ? eta -:--:--
       -------------------------- ------------- 41.0/63.0 kB ? eta -:--:--
       -------------------------- ------------- 41.0/63.0 kB ? eta -:--:--
       ---------------------------------------- 63.0/63.0 kB 484.0 kB/s eta 0:00:00
    Downloading wsproto-1.2.0-py3-none-any.whl (24 kB)
    Downloading outcome-1.3.0.post0-py2.py3-none-any.whl (10 kB)
    Installing collected packages: wsproto, attrs, outcome, trio, trio-websocket, selenium
      Attempting uninstall: attrs
        Found existing installation: attrs 23.1.0
        Uninstalling attrs-23.1.0:
          Successfully uninstalled attrs-23.1.0
    Successfully installed attrs-24.2.0 outcome-1.3.0.post0 selenium-4.25.0 trio-0.26.2 trio-websocket-0.11.1 wsproto-1.2.0
    

      WARNING: Retrying (Retry(total=4, connect=None, read=None, redirect=None, status=None)) after connection broken by 'ReadTimeoutError("HTTPSConnectionPool(host='files.pythonhosted.org', port=443): Read timed out. (read timeout=15)")': /packages/48/be/a9ae5f50cad5b6f85bd2574c2c923730098530096e170c1ce7452394d7aa/trio_websocket-0.11.1-py3-none-any.whl.metadata
    


```python
import requests
from bs4 import beautifulsoup
```


    ---------------------------------------------------------------------------

    ImportError                               Traceback (most recent call last)

    Cell In[7], line 2
          1 import requests
    ----> 2 from bs4 import beautifulsoup
    

    ImportError: cannot import name 'beautifulsoup' from 'bs4' (D:\Users\Lib\site-packages\bs4\__init__.py)



```python
! pip install beautifulsoup

```

    Collecting beautifulsoup
      Downloading BeautifulSoup-3.2.2.tar.gz (32 kB)
      Preparing metadata (setup.py): started
      Preparing metadata (setup.py): finished with status 'error'
    

      error: subprocess-exited-with-error
      
      python setup.py egg_info did not run successfully.
      exit code: 1
      
      [7 lines of output]
      Traceback (most recent call last):
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\subra\AppData\Local\Temp\pip-install-ow9seh7o\beautifulsoup_0ac20e96ca5945b9b5796fe9d868ecf8\setup.py", line 3
          "You're trying to run a very old release of Beautiful Soup under Python 3. This will not work."<>"Please use Beautiful Soup 4, available through the pip package 'beautifulsoup4'."
                                                                                                         ^^
      SyntaxError: invalid syntax
      [end of output]
      
      note: This error originates from a subprocess, and is likely not a problem with pip.
    error: metadata-generation-failed
    
    Encountered error while generating package metadata.
    
    See above for output.
    
    note: This is an issue with the package mentioned above, not pip.
    hint: See above for details.
    


```python
import requests
from bs4 import beautifulsoup
```


    ---------------------------------------------------------------------------

    ImportError                               Traceback (most recent call last)

    Cell In[11], line 2
          1 import requests
    ----> 2 from bs4 import beautifulsoup
    

    ImportError: cannot import name 'beautifulsoup' from 'bs4' (D:\Users\Lib\site-packages\bs4\__init__.py)



```python
url=requests.get("https://en.wikipedia.org/wiki/List_of_active_Indian_military_aircraft",headers={"user-agent":"Mozilla/5.0"})
```


```python
print(url)

```

    <Response [200]>
    


```python
print(url.text)

```

    <!DOCTYPE html>
    <html class="client-nojs vector-feature-language-in-header-enabled vector-feature-language-in-main-page-header-disabled vector-feature-sticky-header-disabled vector-feature-page-tools-pinned-disabled vector-feature-toc-pinned-clientpref-1 vector-feature-main-menu-pinned-disabled vector-feature-limited-width-clientpref-1 vector-feature-limited-width-content-enabled vector-feature-custom-font-size-clientpref-1 vector-feature-appearance-pinned-clientpref-1 vector-feature-night-mode-enabled skin-theme-clientpref-day vector-toc-available" lang="en" dir="ltr">
    <head>
    <meta charset="UTF-8">
    <title>List of active Indian military aircraft - Wikipedia</title>
    <script>(function(){var className="client-js vector-feature-language-in-header-enabled vector-feature-language-in-main-page-header-disabled vector-feature-sticky-header-disabled vector-feature-page-tools-pinned-disabled vector-feature-toc-pinned-clientpref-1 vector-feature-main-menu-pinned-disabled vector-feature-limited-width-clientpref-1 vector-feature-limited-width-content-enabled vector-feature-custom-font-size-clientpref-1 vector-feature-appearance-pinned-clientpref-1 vector-feature-night-mode-enabled skin-theme-clientpref-day vector-toc-available";var cookie=document.cookie.match(/(?:^|; )enwikimwclientpreferences=([^;]+)/);if(cookie){cookie[1].split('%2C').forEach(function(pref){className=className.replace(new RegExp('(^| )'+pref.replace(/-clientpref-\w+$|[^\w-]+/g,'')+'-clientpref-\\w+( |$)'),'$1'+pref+'$2');});}document.documentElement.className=className;}());RLCONF={"wgBreakFrames":false,"wgSeparatorTransformTable":["",""],"wgDigitTransformTable":["",""],"wgDefaultDateFormat":"dmy",
    "wgMonthNames":["","January","February","March","April","May","June","July","August","September","October","November","December"],"wgRequestId":"8ef1d1bb-a151-4240-8cd8-f88596b73970","wgCanonicalNamespace":"","wgCanonicalSpecialPageName":false,"wgNamespaceNumber":0,"wgPageName":"List_of_active_Indian_military_aircraft","wgTitle":"List of active Indian military aircraft","wgCurRevisionId":1250455700,"wgRevisionId":1250455700,"wgArticleId":2192619,"wgIsArticle":true,"wgIsRedirect":false,"wgAction":"view","wgUserName":null,"wgUserGroups":["*"],"wgCategories":["Wikipedia semi-protected pages","Articles with short description","Short description is different from Wikidata","Use dmy dates from October 2019","Indian Air Force","Indian military aircraft","Lists of military aircraft","Indian military-related lists","India aviation-related lists"],"wgPageViewLanguage":"en","wgPageContentLanguage":"en","wgPageContentModel":"wikitext","wgRelevantPageName":"List_of_active_Indian_military_aircraft",
    "wgRelevantArticleId":2192619,"wgIsProbablyEditable":false,"wgRelevantPageIsProbablyEditable":false,"wgRestrictionEdit":["autoconfirmed"],"wgRestrictionMove":[],"wgNoticeProject":"wikipedia","wgCiteReferencePreviewsActive":false,"wgFlaggedRevsParams":{"tags":{"status":{"levels":1}}},"wgMediaViewerOnClick":true,"wgMediaViewerEnabledByDefault":true,"wgPopupsFlags":0,"wgVisualEditor":{"pageLanguageCode":"en","pageLanguageDir":"ltr","pageVariantFallbacks":"en"},"wgMFDisplayWikibaseDescriptions":{"search":true,"watchlist":true,"tagline":false,"nearby":true},"wgWMESchemaEditAttemptStepOversample":false,"wgWMEPageLength":40000,"wgULSCurrentAutonym":"English","wgRelatedArticlesCompat":[],"wgCentralAuthMobileDomain":false,"wgEditSubmitButtonLabelPublish":true,"wgULSPosition":"interlanguage","wgULSisCompactLinksEnabled":false,"wgVector2022LanguageInHeader":true,"wgULSisLanguageSelectorEmpty":false,"wgWikibaseItemId":"Q6604953","wgCheckUserClientHintsHeadersJsApi":["architecture","bitness",
    "brands","fullVersionList","mobile","model","platform","platformVersion"],"GEHomepageSuggestedEditsEnableTopics":true,"wgGETopicsMatchModeEnabled":false,"wgGEStructuredTaskRejectionReasonTextInputEnabled":false,"wgGELevelingUpEnabledForUser":false};RLSTATE={"ext.globalCssJs.user.styles":"ready","site.styles":"ready","user.styles":"ready","ext.globalCssJs.user":"ready","user":"ready","user.options":"loading","ext.cite.styles":"ready","skins.vector.search.codex.styles":"ready","skins.vector.styles":"ready","skins.vector.icons":"ready","jquery.tablesorter.styles":"ready","jquery.makeCollapsible.styles":"ready","ext.wikimediamessages.styles":"ready","ext.visualEditor.desktopArticleTarget.noscript":"ready","ext.uls.interlanguage":"ready","wikibase.client.init":"ready","ext.wikimediaBadges":"ready"};RLPAGEMODULES=["ext.cite.ux-enhancements","mediawiki.page.media","site","mediawiki.page.ready","jquery.tablesorter","jquery.makeCollapsible","mediawiki.toc","skins.vector.js",
    "ext.centralNotice.geoIP","ext.centralNotice.startUp","ext.gadget.ReferenceTooltips","ext.gadget.switcher","ext.urlShortener.toolbar","ext.centralauth.centralautologin","mmv.head","mmv.bootstrap.autostart","ext.popups","ext.visualEditor.desktopArticleTarget.init","ext.visualEditor.targetLoader","ext.echo.centralauth","ext.eventLogging","ext.wikimediaEvents","ext.navigationTiming","ext.uls.interface","ext.cx.eventlogging.campaigns","ext.cx.uls.quick.actions","wikibase.client.vector-2022","ext.checkUser.clientHints","ext.quicksurveys.init","ext.growthExperiments.SuggestedEditSession","wikibase.sidebar.tracking"];</script>
    <script>(RLQ=window.RLQ||[]).push(function(){mw.loader.impl(function(){return["user.options@12s5i",function($,jQuery,require,module){mw.user.tokens.set({"patrolToken":"+\\","watchToken":"+\\","csrfToken":"+\\"});
    }];});});</script>
    <link rel="stylesheet" href="/w/load.php?lang=en&amp;modules=ext.cite.styles%7Cext.uls.interlanguage%7Cext.visualEditor.desktopArticleTarget.noscript%7Cext.wikimediaBadges%7Cext.wikimediamessages.styles%7Cjquery.makeCollapsible.styles%7Cjquery.tablesorter.styles%7Cskins.vector.icons%2Cstyles%7Cskins.vector.search.codex.styles%7Cwikibase.client.init&amp;only=styles&amp;skin=vector-2022">
    <script async="" src="/w/load.php?lang=en&amp;modules=startup&amp;only=scripts&amp;raw=1&amp;skin=vector-2022"></script>
    <meta name="ResourceLoaderDynamicStyles" content="">
    <link rel="stylesheet" href="/w/load.php?lang=en&amp;modules=site.styles&amp;only=styles&amp;skin=vector-2022">
    <meta name="generator" content="MediaWiki 1.43.0-wmf.26">
    <meta name="referrer" content="origin">
    <meta name="referrer" content="origin-when-cross-origin">
    <meta name="robots" content="max-image-preview:standard">
    <meta name="format-detection" content="telephone=no">
    <meta name="viewport" content="width=1120">
    <meta property="og:title" content="List of active Indian military aircraft - Wikipedia">
    <meta property="og:type" content="website">
    <link rel="preconnect" href="//upload.wikimedia.org">
    <link rel="alternate" media="only screen and (max-width: 640px)" href="//en.m.wikipedia.org/wiki/List_of_active_Indian_military_aircraft">
    <link rel="apple-touch-icon" href="/static/apple-touch/wikipedia.png">
    <link rel="icon" href="/static/favicon/wikipedia.ico">
    <link rel="search" type="application/opensearchdescription+xml" href="/w/rest.php/v1/search" title="Wikipedia (en)">
    <link rel="EditURI" type="application/rsd+xml" href="//en.wikipedia.org/w/api.php?action=rsd">
    <link rel="canonical" href="https://en.wikipedia.org/wiki/List_of_active_Indian_military_aircraft">
    <link rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/deed.en">
    <link rel="alternate" type="application/atom+xml" title="Wikipedia Atom feed" href="/w/index.php?title=Special:RecentChanges&amp;feed=atom">
    <link rel="dns-prefetch" href="//meta.wikimedia.org" />
    <link rel="dns-prefetch" href="//login.wikimedia.org">
    </head>
    <body class="skin--responsive skin-vector skin-vector-search-vue mediawiki ltr sitedir-ltr mw-hide-empty-elt ns-0 ns-subject page-List_of_active_Indian_military_aircraft rootpage-List_of_active_Indian_military_aircraft skin-vector-2022 action-view"><a class="mw-jump-link" href="#bodyContent">Jump to content</a>
    <div class="vector-header-container">
    	<header class="vector-header mw-header">
    		<div class="vector-header-start">
    			<nav class="vector-main-menu-landmark" aria-label="Site">
    				
    <div id="vector-main-menu-dropdown" class="vector-dropdown vector-main-menu-dropdown vector-button-flush-left vector-button-flush-right"  >
    	<input type="checkbox" id="vector-main-menu-dropdown-checkbox" role="button" aria-haspopup="true" data-event-name="ui.dropdown-vector-main-menu-dropdown" class="vector-dropdown-checkbox "  aria-label="Main menu"  >
    	<label id="vector-main-menu-dropdown-label" for="vector-main-menu-dropdown-checkbox" class="vector-dropdown-label cdx-button cdx-button--fake-button cdx-button--fake-button--enabled cdx-button--weight-quiet cdx-button--icon-only " aria-hidden="true"  ><span class="vector-icon mw-ui-icon-menu mw-ui-icon-wikimedia-menu"></span>
    
    <span class="vector-dropdown-label-text">Main menu</span>
    	</label>
    	<div class="vector-dropdown-content">
    
    
    				<div id="vector-main-menu-unpinned-container" class="vector-unpinned-container">
    		
    <div id="vector-main-menu" class="vector-main-menu vector-pinnable-element">
    	<div
    	class="vector-pinnable-header vector-main-menu-pinnable-header vector-pinnable-header-unpinned"
    	data-feature-name="main-menu-pinned"
    	data-pinnable-element-id="vector-main-menu"
    	data-pinned-container-id="vector-main-menu-pinned-container"
    	data-unpinned-container-id="vector-main-menu-unpinned-container"
    >
    	<div class="vector-pinnable-header-label">Main menu</div>
    	<button class="vector-pinnable-header-toggle-button vector-pinnable-header-pin-button" data-event-name="pinnable-header.vector-main-menu.pin">move to sidebar</button>
    	<button class="vector-pinnable-header-toggle-button vector-pinnable-header-unpin-button" data-event-name="pinnable-header.vector-main-menu.unpin">hide</button>
    </div>
    
    	
    <div id="p-navigation" class="vector-menu mw-portlet mw-portlet-navigation"  >
    	<div class="vector-menu-heading">
    		Navigation
    	</div>
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			<li id="n-mainpage-description" class="mw-list-item"><a href="/wiki/Main_Page" title="Visit the main page [z]" accesskey="z"><span>Main page</span></a></li><li id="n-contents" class="mw-list-item"><a href="/wiki/Wikipedia:Contents" title="Guides to browsing Wikipedia"><span>Contents</span></a></li><li id="n-currentevents" class="mw-list-item"><a href="/wiki/Portal:Current_events" title="Articles related to current events"><span>Current events</span></a></li><li id="n-randompage" class="mw-list-item"><a href="/wiki/Special:Random" title="Visit a randomly selected article [x]" accesskey="x"><span>Random article</span></a></li><li id="n-aboutsite" class="mw-list-item"><a href="/wiki/Wikipedia:About" title="Learn about Wikipedia and how it works"><span>About Wikipedia</span></a></li><li id="n-contactpage" class="mw-list-item"><a href="//en.wikipedia.org/wiki/Wikipedia:Contact_us" title="How to contact Wikipedia"><span>Contact us</span></a></li>
    		</ul>
    		
    	</div>
    </div>
    
    	
    	
    <div id="p-interaction" class="vector-menu mw-portlet mw-portlet-interaction"  >
    	<div class="vector-menu-heading">
    		Contribute
    	</div>
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			<li id="n-help" class="mw-list-item"><a href="/wiki/Help:Contents" title="Guidance on how to use and edit Wikipedia"><span>Help</span></a></li><li id="n-introduction" class="mw-list-item"><a href="/wiki/Help:Introduction" title="Learn how to edit Wikipedia"><span>Learn to edit</span></a></li><li id="n-portal" class="mw-list-item"><a href="/wiki/Wikipedia:Community_portal" title="The hub for editors"><span>Community portal</span></a></li><li id="n-recentchanges" class="mw-list-item"><a href="/wiki/Special:RecentChanges" title="A list of recent changes to Wikipedia [r]" accesskey="r"><span>Recent changes</span></a></li><li id="n-upload" class="mw-list-item"><a href="/wiki/Wikipedia:File_upload_wizard" title="Add images or other media for use on Wikipedia"><span>Upload file</span></a></li>
    		</ul>
    		
    	</div>
    </div>
    
    </div>
    
    				</div>
    
    	</div>
    </div>
    
    		</nav>
    			
    <a href="/wiki/Main_Page" class="mw-logo">
    	<img class="mw-logo-icon" src="/static/images/icons/wikipedia.png" alt="" aria-hidden="true" height="50" width="50">
    	<span class="mw-logo-container skin-invert">
    		<img class="mw-logo-wordmark" alt="Wikipedia" src="/static/images/mobile/copyright/wikipedia-wordmark-en.svg" style="width: 7.5em; height: 1.125em;">
    		<img class="mw-logo-tagline" alt="The Free Encyclopedia" src="/static/images/mobile/copyright/wikipedia-tagline-en.svg" width="117" height="13" style="width: 7.3125em; height: 0.8125em;">
    	</span>
    </a>
    
    		</div>
    		<div class="vector-header-end">
    			
    <div id="p-search" role="search" class="vector-search-box-vue  vector-search-box-collapses vector-search-box-show-thumbnail vector-search-box-auto-expand-width vector-search-box">
    	<a href="/wiki/Special:Search" class="cdx-button cdx-button--fake-button cdx-button--fake-button--enabled cdx-button--weight-quiet cdx-button--icon-only search-toggle" title="Search Wikipedia [f]" accesskey="f"><span class="vector-icon mw-ui-icon-search mw-ui-icon-wikimedia-search"></span>
    
    <span>Search</span>
    	</a>
    	<div class="vector-typeahead-search-container">
    		<div class="cdx-typeahead-search cdx-typeahead-search--show-thumbnail cdx-typeahead-search--auto-expand-width">
    			<form action="/w/index.php" id="searchform" class="cdx-search-input cdx-search-input--has-end-button">
    				<div id="simpleSearch" class="cdx-search-input__input-wrapper"  data-search-loc="header-moved">
    					<div class="cdx-text-input cdx-text-input--has-start-icon">
    						<input
    							class="cdx-text-input__input"
    							 type="search" name="search" placeholder="Search Wikipedia" aria-label="Search Wikipedia" autocapitalize="sentences" title="Search Wikipedia [f]" accesskey="f" id="searchInput"
    							>
    						<span class="cdx-text-input__icon cdx-text-input__start-icon"></span>
    					</div>
    					<input type="hidden" name="title" value="Special:Search">
    				</div>
    				<button class="cdx-button cdx-search-input__end-button">Search</button>
    			</form>
    		</div>
    	</div>
    </div>
    
    			<nav class="vector-user-links vector-user-links-wide" aria-label="Personal tools">
    	<div class="vector-user-links-main">
    	
    <div id="p-vector-user-menu-preferences" class="vector-menu mw-portlet emptyPortlet"  >
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			
    		</ul>
    		
    	</div>
    </div>
    
    	
    <div id="p-vector-user-menu-userpage" class="vector-menu mw-portlet"  >
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			<li id="ca-sitesupport" class="mw-list-item user-links-collapsible-item"><a data-mw="interface" href="https://donate.wikimedia.org/wiki/Special:FundraiserRedirector?utm_source=donate&amp;utm_medium=sidebar&amp;utm_campaign=C13_en.wikipedia.org&amp;uselang=en" title="Support us by donating to the Wikimedia Foundation" class=""><span>Donate</span></a>
    </li>
    
    			
    		</ul>
    		
    	</div>
    </div>
    
    	<nav class="vector-appearance-landmark" aria-label="Appearance">
    		
    <div id="vector-appearance-dropdown" class="vector-dropdown "  title="Change the appearance of the page&#039;s font size, width, and color" >
    	<input type="checkbox" id="vector-appearance-dropdown-checkbox" role="button" aria-haspopup="true" data-event-name="ui.dropdown-vector-appearance-dropdown" class="vector-dropdown-checkbox "  aria-label="Appearance"  >
    	<label id="vector-appearance-dropdown-label" for="vector-appearance-dropdown-checkbox" class="vector-dropdown-label cdx-button cdx-button--fake-button cdx-button--fake-button--enabled cdx-button--weight-quiet cdx-button--icon-only " aria-hidden="true"  ><span class="vector-icon mw-ui-icon-appearance mw-ui-icon-wikimedia-appearance"></span>
    
    <span class="vector-dropdown-label-text">Appearance</span>
    	</label>
    	<div class="vector-dropdown-content">
    
    
    			<div id="vector-appearance-unpinned-container" class="vector-unpinned-container">
    				
    			</div>
    		
    	</div>
    </div>
    
    	</nav>
    	
    <div id="p-vector-user-menu-notifications" class="vector-menu mw-portlet emptyPortlet"  >
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			
    		</ul>
    		
    	</div>
    </div>
    
    	
    <div id="p-vector-user-menu-overflow" class="vector-menu mw-portlet"  >
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			<li id="pt-createaccount-2" class="user-links-collapsible-item mw-list-item user-links-collapsible-item"><a data-mw="interface" href="/w/index.php?title=Special:CreateAccount&amp;returnto=List+of+active+Indian+military+aircraft" title="You are encouraged to create an account and log in; however, it is not mandatory" class=""><span>Create account</span></a>
    </li>
    <li id="pt-login-2" class="user-links-collapsible-item mw-list-item user-links-collapsible-item"><a data-mw="interface" href="/w/index.php?title=Special:UserLogin&amp;returnto=List+of+active+Indian+military+aircraft" title="You&#039;re encouraged to log in; however, it&#039;s not mandatory. [o]" accesskey="o" class=""><span>Log in</span></a>
    </li>
    
    			
    		</ul>
    		
    	</div>
    </div>
    
    	</div>
    	
    <div id="vector-user-links-dropdown" class="vector-dropdown vector-user-menu vector-button-flush-right vector-user-menu-logged-out"  title="Log in and more options" >
    	<input type="checkbox" id="vector-user-links-dropdown-checkbox" role="button" aria-haspopup="true" data-event-name="ui.dropdown-vector-user-links-dropdown" class="vector-dropdown-checkbox "  aria-label="Personal tools"  >
    	<label id="vector-user-links-dropdown-label" for="vector-user-links-dropdown-checkbox" class="vector-dropdown-label cdx-button cdx-button--fake-button cdx-button--fake-button--enabled cdx-button--weight-quiet cdx-button--icon-only " aria-hidden="true"  ><span class="vector-icon mw-ui-icon-ellipsis mw-ui-icon-wikimedia-ellipsis"></span>
    
    <span class="vector-dropdown-label-text">Personal tools</span>
    	</label>
    	<div class="vector-dropdown-content">
    
    
    		
    <div id="p-personal" class="vector-menu mw-portlet mw-portlet-personal user-links-collapsible-item"  title="User menu" >
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			<li id="pt-createaccount" class="user-links-collapsible-item mw-list-item"><a href="/w/index.php?title=Special:CreateAccount&amp;returnto=List+of+active+Indian+military+aircraft" title="You are encouraged to create an account and log in; however, it is not mandatory"><span class="vector-icon mw-ui-icon-userAdd mw-ui-icon-wikimedia-userAdd"></span> <span>Create account</span></a></li><li id="pt-login" class="user-links-collapsible-item mw-list-item"><a href="/w/index.php?title=Special:UserLogin&amp;returnto=List+of+active+Indian+military+aircraft" title="You&#039;re encouraged to log in; however, it&#039;s not mandatory. [o]" accesskey="o"><span class="vector-icon mw-ui-icon-logIn mw-ui-icon-wikimedia-logIn"></span> <span>Log in</span></a></li>
    		</ul>
    		
    	</div>
    </div>
    
    <div id="p-user-menu-anon-editor" class="vector-menu mw-portlet mw-portlet-user-menu-anon-editor"  >
    	<div class="vector-menu-heading">
    		Pages for logged out editors <a href="/wiki/Help:Introduction" aria-label="Learn more about editing"><span>learn more</span></a>
    	</div>
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			<li id="pt-anoncontribs" class="mw-list-item"><a href="/wiki/Special:MyContributions" title="A list of edits made from this IP address [y]" accesskey="y"><span>Contributions</span></a></li><li id="pt-anontalk" class="mw-list-item"><a href="/wiki/Special:MyTalk" title="Discussion about edits from this IP address [n]" accesskey="n"><span>Talk</span></a></li>
    		</ul>
    		
    	</div>
    </div>
    
    	
    	</div>
    </div>
    
    </nav>
    
    		</div>
    	</header>
    </div>
    <div class="mw-page-container">
    	<div class="mw-page-container-inner">
    		<div class="vector-sitenotice-container">
    			<div id="siteNotice"><!-- CentralNotice --></div>
    		</div>
    		<div class="vector-column-start">
    			<div class="vector-main-menu-container">
    		<div id="mw-navigation">
    			<nav id="mw-panel" class="vector-main-menu-landmark" aria-label="Site">
    				<div id="vector-main-menu-pinned-container" class="vector-pinned-container">
    				
    				</div>
    		</nav>
    		</div>
    	</div>
    	<div class="vector-sticky-pinned-container">
    				<nav id="mw-panel-toc" aria-label="Contents" data-event-name="ui.sidebar-toc" class="mw-table-of-contents-container vector-toc-landmark">
    					<div id="vector-toc-pinned-container" class="vector-pinned-container">
    					<div id="vector-toc" class="vector-toc vector-pinnable-element">
    	<div
    	class="vector-pinnable-header vector-toc-pinnable-header vector-pinnable-header-pinned"
    	data-feature-name="toc-pinned"
    	data-pinnable-element-id="vector-toc"
    	
    	
    >
    	<h2 class="vector-pinnable-header-label">Contents</h2>
    	<button class="vector-pinnable-header-toggle-button vector-pinnable-header-pin-button" data-event-name="pinnable-header.vector-toc.pin">move to sidebar</button>
    	<button class="vector-pinnable-header-toggle-button vector-pinnable-header-unpin-button" data-event-name="pinnable-header.vector-toc.unpin">hide</button>
    </div>
    
    
    	<ul class="vector-toc-contents" id="mw-panel-toc-list">
    		<li id="toc-mw-content-text"
    			class="vector-toc-list-item vector-toc-level-1">
    			<a href="#" class="vector-toc-link">
    				<div class="vector-toc-text">(Top)</div>
    			</a>
    		</li>
    		<li id="toc-Air_Force"
    		class="vector-toc-list-item vector-toc-level-1 vector-toc-list-item-expanded">
    		<a class="vector-toc-link" href="#Air_Force">
    			<div class="vector-toc-text">
    				<span class="vector-toc-numb">1</span>
    				<span>Air Force</span>
    			</div>
    		</a>
    		
    		<ul id="toc-Air_Force-sublist" class="vector-toc-list">
    		</ul>
    	</li>
    	<li id="toc-Army_Aviation_Corps"
    		class="vector-toc-list-item vector-toc-level-1 vector-toc-list-item-expanded">
    		<a class="vector-toc-link" href="#Army_Aviation_Corps">
    			<div class="vector-toc-text">
    				<span class="vector-toc-numb">2</span>
    				<span>Army Aviation Corps</span>
    			</div>
    		</a>
    		
    		<ul id="toc-Army_Aviation_Corps-sublist" class="vector-toc-list">
    		</ul>
    	</li>
    	<li id="toc-Naval_Air_Arm"
    		class="vector-toc-list-item vector-toc-level-1 vector-toc-list-item-expanded">
    		<a class="vector-toc-link" href="#Naval_Air_Arm">
    			<div class="vector-toc-text">
    				<span class="vector-toc-numb">3</span>
    				<span>Naval Air Arm</span>
    			</div>
    		</a>
    		
    		<ul id="toc-Naval_Air_Arm-sublist" class="vector-toc-list">
    		</ul>
    	</li>
    	<li id="toc-Coast_Guard"
    		class="vector-toc-list-item vector-toc-level-1 vector-toc-list-item-expanded">
    		<a class="vector-toc-link" href="#Coast_Guard">
    			<div class="vector-toc-text">
    				<span class="vector-toc-numb">4</span>
    				<span>Coast Guard</span>
    			</div>
    		</a>
    		
    		<ul id="toc-Coast_Guard-sublist" class="vector-toc-list">
    		</ul>
    	</li>
    	<li id="toc-See_also"
    		class="vector-toc-list-item vector-toc-level-1 vector-toc-list-item-expanded">
    		<a class="vector-toc-link" href="#See_also">
    			<div class="vector-toc-text">
    				<span class="vector-toc-numb">5</span>
    				<span>See also</span>
    			</div>
    		</a>
    		
    		<ul id="toc-See_also-sublist" class="vector-toc-list">
    		</ul>
    	</li>
    	<li id="toc-References"
    		class="vector-toc-list-item vector-toc-level-1 vector-toc-list-item-expanded">
    		<a class="vector-toc-link" href="#References">
    			<div class="vector-toc-text">
    				<span class="vector-toc-numb">6</span>
    				<span>References</span>
    			</div>
    		</a>
    		
    		<ul id="toc-References-sublist" class="vector-toc-list">
    		</ul>
    	</li>
    	<li id="toc-External_links"
    		class="vector-toc-list-item vector-toc-level-1 vector-toc-list-item-expanded">
    		<a class="vector-toc-link" href="#External_links">
    			<div class="vector-toc-text">
    				<span class="vector-toc-numb">7</span>
    				<span>External links</span>
    			</div>
    		</a>
    		
    		<ul id="toc-External_links-sublist" class="vector-toc-list">
    		</ul>
    	</li>
    </ul>
    </div>
    
    					</div>
    		</nav>
    			</div>
    		</div>
    		<div class="mw-content-container">
    			<main id="content" class="mw-body">
    				<header class="mw-body-header vector-page-titlebar">
    					<nav aria-label="Contents" class="vector-toc-landmark">
    						
    <div id="vector-page-titlebar-toc" class="vector-dropdown vector-page-titlebar-toc vector-button-flush-left"  >
    	<input type="checkbox" id="vector-page-titlebar-toc-checkbox" role="button" aria-haspopup="true" data-event-name="ui.dropdown-vector-page-titlebar-toc" class="vector-dropdown-checkbox "  aria-label="Toggle the table of contents"  >
    	<label id="vector-page-titlebar-toc-label" for="vector-page-titlebar-toc-checkbox" class="vector-dropdown-label cdx-button cdx-button--fake-button cdx-button--fake-button--enabled cdx-button--weight-quiet cdx-button--icon-only " aria-hidden="true"  ><span class="vector-icon mw-ui-icon-listBullet mw-ui-icon-wikimedia-listBullet"></span>
    
    <span class="vector-dropdown-label-text">Toggle the table of contents</span>
    	</label>
    	<div class="vector-dropdown-content">
    
    
    							<div id="vector-page-titlebar-toc-unpinned-container" class="vector-unpinned-container">
    			</div>
    		
    	</div>
    </div>
    
    					</nav>
    					<h1 id="firstHeading" class="firstHeading mw-first-heading"><span class="mw-page-title-main">List of active Indian military aircraft</span></h1>
    							
    <div id="p-lang-btn" class="vector-dropdown mw-portlet mw-portlet-lang"  >
    	<input type="checkbox" id="p-lang-btn-checkbox" role="button" aria-haspopup="true" data-event-name="ui.dropdown-p-lang-btn" class="vector-dropdown-checkbox mw-interlanguage-selector" aria-label="Go to an article in another language. Available in 2 languages"   >
    	<label id="p-lang-btn-label" for="p-lang-btn-checkbox" class="vector-dropdown-label cdx-button cdx-button--fake-button cdx-button--fake-button--enabled cdx-button--weight-quiet cdx-button--action-progressive mw-portlet-lang-heading-2" aria-hidden="true"  ><span class="vector-icon mw-ui-icon-language-progressive mw-ui-icon-wikimedia-language-progressive"></span>
    
    <span class="vector-dropdown-label-text">2 languages</span>
    	</label>
    	<div class="vector-dropdown-content">
    
    		<div class="vector-menu-content">
    			
    			<ul class="vector-menu-content-list">
    				
    				<li class="interlanguage-link interwiki-ml mw-list-item"><a href="https://ml.wikipedia.org/wiki/%E0%B4%AD%E0%B4%BE%E0%B4%B0%E0%B4%A4%E0%B5%80%E0%B4%AF_%E0%B4%B5%E0%B4%BE%E0%B4%AF%E0%B5%81%E0%B4%B8%E0%B5%87%E0%B4%A8_%E0%B4%89%E0%B4%AA%E0%B4%AF%E0%B5%8B%E0%B4%97%E0%B4%BF%E0%B4%95%E0%B5%8D%E0%B4%95%E0%B5%81%E0%B4%A8%E0%B5%8D%E0%B4%A8_%E0%B4%B5%E0%B4%BF%E0%B4%AE%E0%B4%BE%E0%B4%A8%E0%B4%99%E0%B5%8D%E0%B4%99%E0%B5%BE" title="ഭാരതീയ വായുസേന ഉപയോഗിക്കുന്ന വിമാനങ്ങൾ – Malayalam" lang="ml" hreflang="ml" data-title="ഭാരതീയ വായുസേന ഉപയോഗിക്കുന്ന വിമാനങ്ങൾ" data-language-autonym="മലയാളം" data-language-local-name="Malayalam" class="interlanguage-link-target"><span>മലയാളം</span></a></li><li class="interlanguage-link interwiki-ta mw-list-item"><a href="https://ta.wikipedia.org/wiki/%E0%AE%87%E0%AE%A8%E0%AF%8D%E0%AE%A4%E0%AE%BF%E0%AE%AF_%E0%AE%87%E0%AE%B0%E0%AE%BE%E0%AE%A3%E0%AF%81%E0%AE%B5%E0%AE%A4%E0%AF%8D%E0%AE%A4%E0%AE%BF%E0%AE%B2%E0%AF%8D_%E0%AE%9A%E0%AF%86%E0%AE%AF%E0%AE%B2%E0%AF%8D%E0%AE%AA%E0%AE%BE%E0%AE%9F%E0%AF%8D%E0%AE%9F%E0%AE%BF%E0%AE%B2%E0%AF%8D_%E0%AE%89%E0%AE%B3%E0%AF%8D%E0%AE%B3_%E0%AE%B5%E0%AE%BE%E0%AE%A9%E0%AF%82%E0%AE%B0%E0%AF%8D%E0%AE%A4%E0%AE%BF%E0%AE%95%E0%AE%B3%E0%AE%BF%E0%AE%A9%E0%AF%8D_%E0%AE%AA%E0%AE%9F%E0%AF%8D%E0%AE%9F%E0%AE%BF%E0%AE%AF%E0%AE%B2%E0%AF%8D" title="இந்திய இராணுவத்தில் செயல்பாட்டில் உள்ள வானூர்திகளின் பட்டியல் – Tamil" lang="ta" hreflang="ta" data-title="இந்திய இராணுவத்தில் செயல்பாட்டில் உள்ள வானூர்திகளின் பட்டியல்" data-language-autonym="தமிழ்" data-language-local-name="Tamil" class="interlanguage-link-target"><span>தமிழ்</span></a></li>
    			</ul>
    			<div class="after-portlet after-portlet-lang"><span class="wb-langlinks-edit wb-langlinks-link"><a href="https://www.wikidata.org/wiki/Special:EntityPage/Q6604953#sitelinks-wikipedia" title="Edit interlanguage links" class="wbc-editpage">Edit links</a></span></div>
    		</div>
    
    	</div>
    </div>
    </header>
    				<div class="vector-page-toolbar">
    					<div class="vector-page-toolbar-container">
    						<div id="left-navigation">
    							<nav aria-label="Namespaces">
    								
    <div id="p-associated-pages" class="vector-menu vector-menu-tabs mw-portlet mw-portlet-associated-pages"  >
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			<li id="ca-nstab-main" class="selected vector-tab-noicon mw-list-item"><a href="/wiki/List_of_active_Indian_military_aircraft" title="View the content page [c]" accesskey="c"><span>Article</span></a></li><li id="ca-talk" class="vector-tab-noicon mw-list-item"><a href="/wiki/Talk:List_of_active_Indian_military_aircraft" rel="discussion" title="Discuss improvements to the content page [t]" accesskey="t"><span>Talk</span></a></li>
    		</ul>
    		
    	</div>
    </div>
    
    								
    <div id="vector-variants-dropdown" class="vector-dropdown emptyPortlet"  >
    	<input type="checkbox" id="vector-variants-dropdown-checkbox" role="button" aria-haspopup="true" data-event-name="ui.dropdown-vector-variants-dropdown" class="vector-dropdown-checkbox " aria-label="Change language variant"   >
    	<label id="vector-variants-dropdown-label" for="vector-variants-dropdown-checkbox" class="vector-dropdown-label cdx-button cdx-button--fake-button cdx-button--fake-button--enabled cdx-button--weight-quiet" aria-hidden="true"  ><span class="vector-dropdown-label-text">English</span>
    	</label>
    	<div class="vector-dropdown-content">
    
    
    					
    <div id="p-variants" class="vector-menu mw-portlet mw-portlet-variants emptyPortlet"  >
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			
    		</ul>
    		
    	</div>
    </div>
    
    				
    	</div>
    </div>
    
    							</nav>
    						</div>
    						<div id="right-navigation" class="vector-collapsible">
    							<nav aria-label="Views">
    								
    <div id="p-views" class="vector-menu vector-menu-tabs mw-portlet mw-portlet-views"  >
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			<li id="ca-view" class="selected vector-tab-noicon mw-list-item"><a href="/wiki/List_of_active_Indian_military_aircraft"><span>Read</span></a></li><li id="ca-viewsource" class="vector-tab-noicon mw-list-item"><a href="/w/index.php?title=List_of_active_Indian_military_aircraft&amp;action=edit" title="This page is protected.&#10;You can view its source [e]" accesskey="e"><span>View source</span></a></li><li id="ca-history" class="vector-tab-noicon mw-list-item"><a href="/w/index.php?title=List_of_active_Indian_military_aircraft&amp;action=history" title="Past revisions of this page [h]" accesskey="h"><span>View history</span></a></li>
    		</ul>
    		
    	</div>
    </div>
    
    							</nav>
    				
    							<nav class="vector-page-tools-landmark" aria-label="Page tools">
    								
    <div id="vector-page-tools-dropdown" class="vector-dropdown vector-page-tools-dropdown"  >
    	<input type="checkbox" id="vector-page-tools-dropdown-checkbox" role="button" aria-haspopup="true" data-event-name="ui.dropdown-vector-page-tools-dropdown" class="vector-dropdown-checkbox "  aria-label="Tools"  >
    	<label id="vector-page-tools-dropdown-label" for="vector-page-tools-dropdown-checkbox" class="vector-dropdown-label cdx-button cdx-button--fake-button cdx-button--fake-button--enabled cdx-button--weight-quiet" aria-hidden="true"  ><span class="vector-dropdown-label-text">Tools</span>
    	</label>
    	<div class="vector-dropdown-content">
    
    
    									<div id="vector-page-tools-unpinned-container" class="vector-unpinned-container">
    						
    <div id="vector-page-tools" class="vector-page-tools vector-pinnable-element">
    	<div
    	class="vector-pinnable-header vector-page-tools-pinnable-header vector-pinnable-header-unpinned"
    	data-feature-name="page-tools-pinned"
    	data-pinnable-element-id="vector-page-tools"
    	data-pinned-container-id="vector-page-tools-pinned-container"
    	data-unpinned-container-id="vector-page-tools-unpinned-container"
    >
    	<div class="vector-pinnable-header-label">Tools</div>
    	<button class="vector-pinnable-header-toggle-button vector-pinnable-header-pin-button" data-event-name="pinnable-header.vector-page-tools.pin">move to sidebar</button>
    	<button class="vector-pinnable-header-toggle-button vector-pinnable-header-unpin-button" data-event-name="pinnable-header.vector-page-tools.unpin">hide</button>
    </div>
    
    	
    <div id="p-cactions" class="vector-menu mw-portlet mw-portlet-cactions emptyPortlet vector-has-collapsible-items"  title="More options" >
    	<div class="vector-menu-heading">
    		Actions
    	</div>
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			<li id="ca-more-view" class="selected vector-more-collapsible-item mw-list-item"><a href="/wiki/List_of_active_Indian_military_aircraft"><span>Read</span></a></li><li id="ca-more-viewsource" class="vector-more-collapsible-item mw-list-item"><a href="/w/index.php?title=List_of_active_Indian_military_aircraft&amp;action=edit"><span>View source</span></a></li><li id="ca-more-history" class="vector-more-collapsible-item mw-list-item"><a href="/w/index.php?title=List_of_active_Indian_military_aircraft&amp;action=history"><span>View history</span></a></li>
    		</ul>
    		
    	</div>
    </div>
    
    <div id="p-tb" class="vector-menu mw-portlet mw-portlet-tb"  >
    	<div class="vector-menu-heading">
    		General
    	</div>
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			<li id="t-whatlinkshere" class="mw-list-item"><a href="/wiki/Special:WhatLinksHere/List_of_active_Indian_military_aircraft" title="List of all English Wikipedia pages containing links to this page [j]" accesskey="j"><span>What links here</span></a></li><li id="t-recentchangeslinked" class="mw-list-item"><a href="/wiki/Special:RecentChangesLinked/List_of_active_Indian_military_aircraft" rel="nofollow" title="Recent changes in pages linked from this page [k]" accesskey="k"><span>Related changes</span></a></li><li id="t-upload" class="mw-list-item"><a href="/wiki/Wikipedia:File_Upload_Wizard" title="Upload files [u]" accesskey="u"><span>Upload file</span></a></li><li id="t-specialpages" class="mw-list-item"><a href="/wiki/Special:SpecialPages" title="A list of all special pages [q]" accesskey="q"><span>Special pages</span></a></li><li id="t-permalink" class="mw-list-item"><a href="/w/index.php?title=List_of_active_Indian_military_aircraft&amp;oldid=1250455700" title="Permanent link to this revision of this page"><span>Permanent link</span></a></li><li id="t-info" class="mw-list-item"><a href="/w/index.php?title=List_of_active_Indian_military_aircraft&amp;action=info" title="More information about this page"><span>Page information</span></a></li><li id="t-cite" class="mw-list-item"><a href="/w/index.php?title=Special:CiteThisPage&amp;page=List_of_active_Indian_military_aircraft&amp;id=1250455700&amp;wpFormIdentifier=titleform" title="Information on how to cite this page"><span>Cite this page</span></a></li><li id="t-urlshortener" class="mw-list-item"><a href="/w/index.php?title=Special:UrlShortener&amp;url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FList_of_active_Indian_military_aircraft"><span>Get shortened URL</span></a></li><li id="t-urlshortener-qrcode" class="mw-list-item"><a href="/w/index.php?title=Special:QrCode&amp;url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FList_of_active_Indian_military_aircraft"><span>Download QR code</span></a></li><li id="t-wikibase" class="mw-list-item"><a href="https://www.wikidata.org/wiki/Special:EntityPage/Q6604953" title="Structured data on this page hosted by Wikidata [g]" accesskey="g"><span>Wikidata item</span></a></li>
    		</ul>
    		
    	</div>
    </div>
    
    <div id="p-coll-print_export" class="vector-menu mw-portlet mw-portlet-coll-print_export"  >
    	<div class="vector-menu-heading">
    		Print/export
    	</div>
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			<li id="coll-download-as-rl" class="mw-list-item"><a href="/w/index.php?title=Special:DownloadAsPdf&amp;page=List_of_active_Indian_military_aircraft&amp;action=show-download-screen" title="Download this page as a PDF file"><span>Download as PDF</span></a></li><li id="t-print" class="mw-list-item"><a href="/w/index.php?title=List_of_active_Indian_military_aircraft&amp;printable=yes" title="Printable version of this page [p]" accesskey="p"><span>Printable version</span></a></li>
    		</ul>
    		
    	</div>
    </div>
    
    <div id="p-wikibase-otherprojects" class="vector-menu mw-portlet mw-portlet-wikibase-otherprojects emptyPortlet"  >
    	<div class="vector-menu-heading">
    		In other projects
    	</div>
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			
    		</ul>
    		
    	</div>
    </div>
    
    </div>
    
    									</div>
    				
    	</div>
    </div>
    
    							</nav>
    						</div>
    					</div>
    				</div>
    				<div class="vector-column-end">
    					<div class="vector-sticky-pinned-container">
    						<nav class="vector-page-tools-landmark" aria-label="Page tools">
    							<div id="vector-page-tools-pinned-container" class="vector-pinned-container">
    				
    							</div>
    		</nav>
    						<nav class="vector-appearance-landmark" aria-label="Appearance">
    							<div id="vector-appearance-pinned-container" class="vector-pinned-container">
    				<div id="vector-appearance" class="vector-appearance vector-pinnable-element">
    	<div
    	class="vector-pinnable-header vector-appearance-pinnable-header vector-pinnable-header-pinned"
    	data-feature-name="appearance-pinned"
    	data-pinnable-element-id="vector-appearance"
    	data-pinned-container-id="vector-appearance-pinned-container"
    	data-unpinned-container-id="vector-appearance-unpinned-container"
    >
    	<div class="vector-pinnable-header-label">Appearance</div>
    	<button class="vector-pinnable-header-toggle-button vector-pinnable-header-pin-button" data-event-name="pinnable-header.vector-appearance.pin">move to sidebar</button>
    	<button class="vector-pinnable-header-toggle-button vector-pinnable-header-unpin-button" data-event-name="pinnable-header.vector-appearance.unpin">hide</button>
    </div>
    
    
    </div>
    
    							</div>
    		</nav>
    					</div>
    				</div>
    				<div id="bodyContent" class="vector-body" aria-labelledby="firstHeading" data-mw-ve-target-container>
    					<div class="vector-body-before-content">
    							<div class="mw-indicators">
    		<div id="mw-indicator-pp-default" class="mw-indicator"><div class="mw-parser-output"><span typeof="mw:File"><a href="/wiki/Wikipedia:Protection_policy#semi" title="This article is semi-protected until January 16, 2026 at 09:19 UTC."><img alt="Page semi-protected" src="//upload.wikimedia.org/wikipedia/en/thumb/1/1b/Semi-protection-shackle.svg/20px-Semi-protection-shackle.svg.png" decoding="async" width="20" height="20" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/en/thumb/1/1b/Semi-protection-shackle.svg/30px-Semi-protection-shackle.svg.png 1.5x, //upload.wikimedia.org/wikipedia/en/thumb/1/1b/Semi-protection-shackle.svg/40px-Semi-protection-shackle.svg.png 2x" data-file-width="512" data-file-height="512" /></a></span></div></div>
    		</div>
    
    						<div id="siteSub" class="noprint">From Wikipedia, the free encyclopedia</div>
    					</div>
    					<div id="contentSub"><div id="mw-content-subtitle"></div></div>
    					
    					
    					<div id="mw-content-text" class="mw-body-content"><div class="mw-content-ltr mw-parser-output" lang="en" dir="ltr"><p class="mw-empty-elt">
    </p>
    <div class="shortdescription nomobile noexcerpt noprint searchaux" style="display:none">Current aircraft of the Indian Armed Forces</div>
    <p>
    This article provides a <b>list of active Indian military aircraft</b> currently in service with the <a href="/wiki/Indian_Armed_Forces" title="Indian Armed Forces">Indian Armed Forces</a>, as well as aircraft on order. For a list of historical <a href="/wiki/Military_aircraft" title="Military aircraft">military aircraft</a> used by the Indian military, see <a href="/wiki/List_of_historical_aircraft_of_the_Indian_Air_Force" title="List of historical aircraft of the Indian Air Force">list of historical aircraft of the Indian Air Force</a>.
    </p>
    <meta property="mw:PageProp/toc" />
    <div class="mw-heading mw-heading2"><h2 id="Air_Force">Air Force</h2></div>
    <style data-mw-deduplicate="TemplateStyles:r1236090951">.mw-parser-output .hatnote{font-style:italic}.mw-parser-output div.hatnote{padding-left:1.6em;margin-bottom:0.5em}.mw-parser-output .hatnote i{font-style:normal}.mw-parser-output .hatnote+link+.hatnote{margin-top:-0.5em}@media print{body.ns-0 .mw-parser-output .hatnote{display:none!important}}</style><div role="note" class="hatnote navigation-not-searchable">Further information: <a href="/wiki/Indian_Air_Force" title="Indian Air Force">Indian Air Force</a> and <a href="/wiki/Future_of_the_Indian_Air_Force" title="Future of the Indian Air Force">Future of the Indian Air Force</a></div>
    <figure class="mw-default-size" typeof="mw:File/Thumb"><a href="/wiki/File:Tejas_MK1_TarangShakti24.jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/d/d2/Tejas_MK1_TarangShakti24.jpg/220px-Tejas_MK1_TarangShakti24.jpg" decoding="async" width="220" height="147" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/d/d2/Tejas_MK1_TarangShakti24.jpg/330px-Tejas_MK1_TarangShakti24.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/d/d2/Tejas_MK1_TarangShakti24.jpg/440px-Tejas_MK1_TarangShakti24.jpg 2x" data-file-width="1280" data-file-height="853" /></a><figcaption><a href="/wiki/HAL_Tejas" title="HAL Tejas">HAL Tejas</a> at TarangShakti 2024</figcaption></figure>
    <figure class="mw-default-size" typeof="mw:File/Thumb"><a href="/wiki/File:RB005_-_Dassault_Rafale_-_Indian_Air_Force_-_50976863128.jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/0/08/RB005_-_Dassault_Rafale_-_Indian_Air_Force_-_50976863128.jpg/220px-RB005_-_Dassault_Rafale_-_Indian_Air_Force_-_50976863128.jpg" decoding="async" width="220" height="140" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/0/08/RB005_-_Dassault_Rafale_-_Indian_Air_Force_-_50976863128.jpg/330px-RB005_-_Dassault_Rafale_-_Indian_Air_Force_-_50976863128.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/0/08/RB005_-_Dassault_Rafale_-_Indian_Air_Force_-_50976863128.jpg/440px-RB005_-_Dassault_Rafale_-_Indian_Air_Force_-_50976863128.jpg 2x" data-file-width="3780" data-file-height="2411" /></a><figcaption>IAF <a href="/wiki/Rafale" class="mw-redirect" title="Rafale">Rafale</a> take off from <a href="/wiki/Dassault_Aviation" title="Dassault Aviation">Dassault Aviation</a> Facility, <a href="/wiki/Bordeaux%E2%80%93M%C3%A9rignac_Airport" title="Bordeaux–Mérignac Airport">Merignac</a>, France.</figcaption></figure>
    <figure class="mw-default-size" typeof="mw:File/Thumb"><a href="/wiki/File:Su-30_MKI_firing_Brahmos-ER.jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/5/52/Su-30_MKI_firing_Brahmos-ER.jpg/220px-Su-30_MKI_firing_Brahmos-ER.jpg" decoding="async" width="220" height="147" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/5/52/Su-30_MKI_firing_Brahmos-ER.jpg/330px-Su-30_MKI_firing_Brahmos-ER.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/5/52/Su-30_MKI_firing_Brahmos-ER.jpg/440px-Su-30_MKI_firing_Brahmos-ER.jpg 2x" data-file-width="660" data-file-height="440" /></a><figcaption>A Su-30MKI firing Brahmos ER</figcaption></figure>
    <figure class="mw-default-size mw-halign-right" typeof="mw:File/Thumb"><a href="/wiki/File:DRDO_AEW%26C_Embraer_ERJ_145.JPG" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/f/fa/DRDO_AEW%26C_Embraer_ERJ_145.JPG/220px-DRDO_AEW%26C_Embraer_ERJ_145.JPG" decoding="async" width="220" height="144" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/f/fa/DRDO_AEW%26C_Embraer_ERJ_145.JPG/330px-DRDO_AEW%26C_Embraer_ERJ_145.JPG 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/f/fa/DRDO_AEW%26C_Embraer_ERJ_145.JPG/440px-DRDO_AEW%26C_Embraer_ERJ_145.JPG 2x" data-file-width="1334" data-file-height="876" /></a><figcaption>Netra AEW&amp;C on Embraer ERJ 145 platform</figcaption></figure>
    <figure class="mw-default-size mw-halign-right" typeof="mw:File/Thumb"><a href="/wiki/File:IAF-C-17.jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/3/30/IAF-C-17.jpg/220px-IAF-C-17.jpg" decoding="async" width="220" height="157" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/3/30/IAF-C-17.jpg/330px-IAF-C-17.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/3/30/IAF-C-17.jpg/440px-IAF-C-17.jpg 2x" data-file-width="2100" data-file-height="1500" /></a><figcaption><a href="/wiki/Boeing_C-17_Globemaster_III" title="Boeing C-17 Globemaster III">C-17 Globemaster III</a> in service</figcaption></figure>
    <figure class="mw-default-size" typeof="mw:File/Thumb"><a href="/wiki/File:C-295_Indian_Air_Force.jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/9/95/C-295_Indian_Air_Force.jpg/220px-C-295_Indian_Air_Force.jpg" decoding="async" width="220" height="124" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/9/95/C-295_Indian_Air_Force.jpg/330px-C-295_Indian_Air_Force.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/9/95/C-295_Indian_Air_Force.jpg/440px-C-295_Indian_Air_Force.jpg 2x" data-file-width="1024" data-file-height="576" /></a><figcaption><a href="/wiki/EADS_CASA_C-295" title="EADS CASA C-295">C-295</a> is replacing HS-748</figcaption></figure>
    <figure class="mw-default-size" typeof="mw:File/Thumb"><a href="/wiki/File:HAL_Prachand_(cropped).jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/c/c9/HAL_Prachand_%28cropped%29.jpg/220px-HAL_Prachand_%28cropped%29.jpg" decoding="async" width="220" height="146" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/c/c9/HAL_Prachand_%28cropped%29.jpg/330px-HAL_Prachand_%28cropped%29.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/c/c9/HAL_Prachand_%28cropped%29.jpg/440px-HAL_Prachand_%28cropped%29.jpg 2x" data-file-width="3815" data-file-height="2526" /></a><figcaption><a href="/wiki/HAL_Prachand" title="HAL Prachand">HAL Prachand</a></figcaption></figure>
    <table class="wikitable">
    <tbody><tr>
    <th style="text-align:center; background:#acc;">Aircraft
    </th>
    <th style="text-align: center; background:#acc;">Origin
    </th>
    <th style="text-align: center; background:#acc;">Type
    </th>
    <th style="text-align:left; background:#acc;">Variant
    </th>
    <th style="text-align:center; background:#acc;">In service
    </th>
    <th style="text-align: center; background:#acc;">Notes
    </th></tr>
    <tr>
    <th style="align: center; background: lavender;" colspan="6"><a href="/wiki/Military_aircraft#Combat_aircraft" title="Military aircraft">Combat Aircraft</a>
    </th></tr>
    <tr>
    <td rowspan="2"><a href="/wiki/Dassault_Rafale" title="Dassault Rafale">Dassault Rafale</a>
    </td>
    <td rowspan="2"><a href="/wiki/France" title="France">France</a>
    </td>
    <td rowspan="2"><a href="/wiki/Multirole_combat_aircraft" title="Multirole combat aircraft">Multirole</a>
    </td>
    <td><a href="/wiki/Dassault_Rafale#Variants" title="Dassault Rafale">DH</a>
    </td>
    <td>8<sup id="cite_ref-:1_1-0" class="reference"><a href="#cite_note-:1-1"><span class="cite-bracket">&#91;</span>1<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Dassault_Rafale#Variants" title="Dassault Rafale">EH</a>
    </td>
    <td>28<sup id="cite_ref-:1_1-1" class="reference"><a href="#cite_note-:1-1"><span class="cite-bracket">&#91;</span>1<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td rowspan="3"><a href="/wiki/HAL_Tejas" title="HAL Tejas">HAL Tejas</a>
    </td>
    <td rowspan="3"><a href="/wiki/India" title="India">India</a>
    </td>
    <td><a href="/wiki/Multirole_combat_aircraft" title="Multirole combat aircraft">Multirole</a>
    </td>
    <td><a href="/wiki/HAL_Tejas#Variants" title="HAL Tejas">Mk.1</a>
    </td>
    <td>31<sup id="cite_ref-2" class="reference"><a href="#cite_note-2"><span class="cite-bracket">&#91;</span>2<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-3" class="reference"><a href="#cite_note-3"><span class="cite-bracket">&#91;</span>3<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Trainer_aircraft#Operational_conversion" title="Trainer aircraft">Conversion trainer</a>
    </td>
    <td><a href="/wiki/HAL_Tejas#Variants" title="HAL Tejas">Mk.1 Trainer</a>
    </td>
    <td>2<sup id="cite_ref-4" class="reference"><a href="#cite_note-4"><span class="cite-bracket">&#91;</span>4<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-5" class="reference"><a href="#cite_note-5"><span class="cite-bracket">&#91;</span>5<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>Used for training; 16 more on order<sup id="cite_ref-:11_6-0" class="reference"><a href="#cite_note-:11-6"><span class="cite-bracket">&#91;</span>6<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Multirole_combat_aircraft" title="Multirole combat aircraft">Multirole</a>
    </td>
    <td><a href="/wiki/HAL_Tejas#Variants" title="HAL Tejas">Mk.1A</a>
    </td>
    <td>
    </td>
    <td>73 on order, 97 more approved<sup id="cite_ref-:11_6-1" class="reference"><a href="#cite_note-:11-6"><span class="cite-bracket">&#91;</span>6<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-7" class="reference"><a href="#cite_note-7"><span class="cite-bracket">&#91;</span>7<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Sukhoi_Su-30MKI" title="Sukhoi Su-30MKI">Sukhoi Su-30MKI</a>
    </td>
    <td><a href="/wiki/Russia" title="Russia">Russia</a>
    </td>
    <td><a href="/wiki/Multirole_combat_aircraft" title="Multirole combat aircraft">Multirole</a>
    </td>
    <td><a href="/wiki/Sukhoi_Su-30#Su-30MKI_and_derivatives" title="Sukhoi Su-30">Su-30MKI Flanker H</a>
    </td>
    <td>259<sup id="cite_ref-8" class="reference"><a href="#cite_note-8"><span class="cite-bracket">&#91;</span>8<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-9" class="reference"><a href="#cite_note-9"><span class="cite-bracket">&#91;</span>9<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>12 more cleared.<sup id="cite_ref-10" class="reference"><a href="#cite_note-10"><span class="cite-bracket">&#91;</span>10<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td rowspan="2"><a href="/wiki/Mikoyan_MiG-29" title="Mikoyan MiG-29">Mikoyan MiG-29</a>
    </td>
    <td rowspan="2"><a href="/wiki/Soviet_Union" title="Soviet Union">Soviet Union</a>
    </td>
    <td rowspan="2"><a href="/wiki/Multirole_combat_aircraft" title="Multirole combat aircraft">Multirole</a>
    </td>
    <td><a href="/wiki/Mikoyan_MiG-29#Variants" title="Mikoyan MiG-29">Fulcrum</a>
    </td>
    <td>53<sup id="cite_ref-:1_1-2" class="reference"><a href="#cite_note-:1-1"><span class="cite-bracket">&#91;</span>1<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-11" class="reference"><a href="#cite_note-11"><span class="cite-bracket">&#91;</span>11<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>Including 12 <a href="/wiki/Mikoyan_MiG-29#Variants" title="Mikoyan MiG-29">MiG-29UPG</a>.
    </td></tr>
    <tr>
    <td><a href="/wiki/Mikoyan_MiG-29#Variants" title="Mikoyan MiG-29">Fulcrum B</a>
    </td>
    <td>7<sup id="cite_ref-:1_1-3" class="reference"><a href="#cite_note-:1-1"><span class="cite-bracket">&#91;</span>1<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td rowspan="2"><a href="/wiki/Dassault_Mirage_2000" title="Dassault Mirage 2000">Dassault Mirage 2000</a>
    </td>
    <td rowspan="2"><a href="/wiki/France" title="France">France</a>
    </td>
    <td rowspan="2"><a href="/wiki/Multirole_combat_aircraft" title="Multirole combat aircraft">Multirole</a>
    </td>
    <td><a href="/wiki/Dassault_Mirage_2000#Variants" title="Dassault Mirage 2000">-2000H</a>
    </td>
    <td>37<sup id="cite_ref-:1_1-4" class="reference"><a href="#cite_note-:1-1"><span class="cite-bracket">&#91;</span>1<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Dassault_Mirage_2000#Variants" title="Dassault Mirage 2000">-2000TH</a>
    </td>
    <td>10<sup id="cite_ref-:1_1-5" class="reference"><a href="#cite_note-:1-1"><span class="cite-bracket">&#91;</span>1<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>Used for training.
    </td></tr>
    <tr>
    <td rowspan="3"><a href="/wiki/SEPECAT_Jaguar" title="SEPECAT Jaguar">SEPECAT Jaguar</a>
    </td>
    <td rowspan="3"><a href="/wiki/United_Kingdom" title="United Kingdom">United Kingdom</a>
    </td>
    <td rowspan="3"><a href="/wiki/Attack_aircraft" title="Attack aircraft">Attack</a>
    </td>
    <td><a href="/wiki/SEPECAT_Jaguar#Variants" title="SEPECAT Jaguar">IB</a>
    </td>
    <td>28<sup id="cite_ref-:1_1-6" class="reference"><a href="#cite_note-:1-1"><span class="cite-bracket">&#91;</span>1<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>Used for training.
    </td></tr>
    <tr>
    <td><a href="/wiki/SEPECAT_Jaguar#Variants" title="SEPECAT Jaguar">IS</a>
    </td>
    <td>79<sup id="cite_ref-:1_1-7" class="reference"><a href="#cite_note-:1-1"><span class="cite-bracket">&#91;</span>1<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/SEPECAT_Jaguar#Variants" title="SEPECAT Jaguar">IM</a>
    </td>
    <td>8<sup id="cite_ref-:1_1-8" class="reference"><a href="#cite_note-:1-1"><span class="cite-bracket">&#91;</span>1<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>Maritime strike aircraft carrying <a href="/wiki/Sea_Eagle_(missile)" title="Sea Eagle (missile)">Sea Eagle</a> missile.
    </td></tr>
    <tr>
    <td><a href="/wiki/Mikoyan-Gurevich_MiG-21" title="Mikoyan-Gurevich MiG-21">Mikoyan-Gurevich MiG-21</a>
    </td>
    <td><a href="/wiki/Soviet_Union" title="Soviet Union">Soviet Union</a>
    </td>
    <td><a href="/wiki/Interceptor_aircraft" title="Interceptor aircraft">Interceptor</a>
    </td>
    <td><a href="/wiki/List_of_Mikoyan-Gurevich_MiG-21_variants" title="List of Mikoyan-Gurevich MiG-21 variants">MiG-21 <i>Bison</i></a>
    </td>
    <td>40<sup id="cite_ref-12" class="reference"><a href="#cite_note-12"><span class="cite-bracket">&#91;</span>12<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>Being phased out.<sup id="cite_ref-13" class="reference"><a href="#cite_note-13"><span class="cite-bracket">&#91;</span>13<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Airborne_early_warning_and_control" title="Airborne early warning and control">AEW&amp;CS</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Embraer_R-99" title="Embraer R-99">Embraer R-99</a>
    </td>
    <td><a href="/wiki/Brazil" title="Brazil">Brazil</a>
    </td>
    <td><a href="/wiki/Airborne_early_warning_and_control" title="Airborne early warning and control">AEW&amp;C</a>
    </td>
    <td><a href="/wiki/DRDO_AEW%26CS#Platforms" title="DRDO AEW&amp;CS">Netra Mk1</a>
    </td>
    <td>3<sup id="cite_ref-:12_14-0" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>equipped with a <a href="/wiki/DRDO_AEW%26CS" title="DRDO AEW&amp;CS"> Netra AEW&amp;CS</a>.
    </td></tr>
    <tr>
    <td><a href="/wiki/Beriev_A-50" title="Beriev A-50">Beriev A-50</a>
    </td>
    <td>Soviet Union
    </td>
    <td>AEW&amp;C
    </td>
    <td><a href="/wiki/Beriev_A-50#Variants" title="Beriev A-50">A-50EI</a>
    </td>
    <td>3<sup id="cite_ref-:12_14-1" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>equipped with the <a href="/wiki/EL/W-2090" title="EL/W-2090">EL/W-2090</a> radar. 2 more planned.<sup id="cite_ref-15" class="reference"><a href="#cite_note-15"><span class="cite-bracket">&#91;</span>15<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-16" class="reference"><a href="#cite_note-16"><span class="cite-bracket">&#91;</span>16<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Reconnaissance_aircraft" title="Reconnaissance aircraft">Reconnaissance</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Boeing_707" title="Boeing 707">Boeing 707</a>
    </td>
    <td><a href="/wiki/United_States" title="United States">United States</a>
    </td>
    <td><a href="/wiki/Signals_intelligence" title="Signals intelligence">SIGINT</a> / <a href="/wiki/ELINT" class="mw-redirect" title="ELINT">ELINT</a>
    </td>
    <td>707-337C Phalcon
    </td>
    <td>1<sup id="cite_ref-:12_14-2" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td rowspan="4">Operated by <a href="/wiki/Aviation_Research_Centre" title="Aviation Research Centre">Aviation Research Centre</a> (ARC) of <a href="/wiki/Research_and_Analysis_Wing" title="Research and Analysis Wing">R&amp;AW</a>.<sup id="cite_ref-17" class="reference"><a href="#cite_note-17"><span class="cite-bracket">&#91;</span>17<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-18" class="reference"><a href="#cite_note-18"><span class="cite-bracket">&#91;</span>18<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Bombardier_Global_Express" title="Bombardier Global Express">Global 5000</a>
    </td>
    <td>United States
    </td>
    <td><a href="/wiki/Signals_intelligence" title="Signals intelligence">SIGINT</a> / <a href="/wiki/ELINT" class="mw-redirect" title="ELINT">ELINT</a>
    </td>
    <td>
    </td>
    <td>2<sup id="cite_ref-:12_14-3" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Gulfstream_III" title="Gulfstream III">Gulfstream III</a>
    </td>
    <td>United States
    </td>
    <td><a href="/wiki/Signals_intelligence#Electronic_signals_intelligence" title="Signals intelligence">ELINT</a>
    </td>
    <td><a href="/wiki/Gulfstream_III#Variants" title="Gulfstream III">SRA</a><sup id="cite_ref-19" class="reference"><a href="#cite_note-19"><span class="cite-bracket">&#91;</span>19<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>3<sup id="cite_ref-:12_14-4" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Gulfstream_G100" title="Gulfstream G100">Gulfstream G100</a>
    </td>
    <td><a href="/wiki/Israel" title="Israel">Israel</a>
    </td>
    <td><a href="/wiki/Surveillance_aircraft" title="Surveillance aircraft">surveillance</a>
    </td>
    <td><a href="/wiki/Gulfstream_G100#Variants" title="Gulfstream G100">1125 Astra</a>
    </td>
    <td>2<sup id="cite_ref-:12_14-5" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Aerial_refueling" title="Aerial refueling">Tanker</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Ilyushin_Il-78" title="Ilyushin Il-78">Ilyushin Il-78</a>
    </td>
    <td>Soviet Union
    </td>
    <td>aerial refuelling
    </td>
    <td><a href="/wiki/Ilyushin_Il-78#Variants" title="Ilyushin Il-78">Il-78MKI</a>
    </td>
    <td>6<sup id="cite_ref-:12_14-6" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Military_transport_aircraft" title="Military transport aircraft">Transport</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Boeing_777" title="Boeing 777">Boeing 777</a>
    </td>
    <td>United States
    </td>
    <td>VIP transport
    </td>
    <td><a href="/wiki/777-300ER" class="mw-redirect" title="777-300ER">777-300ER</a>
    </td>
    <td>2<sup id="cite_ref-20" class="reference"><a href="#cite_note-20"><span class="cite-bracket">&#91;</span>20<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>Used as <a href="/wiki/Air_India_One" title="Air India One">Air India One</a> for presidential flight
    </td></tr>
    <tr>
    <td><a href="/wiki/Boeing_737" title="Boeing 737">Boeing 737</a>
    </td>
    <td>United States
    </td>
    <td><a href="/wiki/Air_transports_of_heads_of_state_and_government" title="Air transports of heads of state and government">VIP transport</a>
    </td>
    <td><a href="/wiki/Boeing_737#Boeing_Business_Jet_(BBJ)" title="Boeing 737">737-700</a>
    </td>
    <td>3<sup id="cite_ref-21" class="reference"><a href="#cite_note-21"><span class="cite-bracket">&#91;</span>21<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Embraer_Legacy_600" title="Embraer Legacy 600">Embraer Legacy 600</a>
    </td>
    <td>Brazil
    </td>
    <td><a href="/wiki/Air_transports_of_heads_of_state_and_government" title="Air transports of heads of state and government">VIP transport</a>
    </td>
    <td>
    </td>
    <td>4<sup id="cite_ref-22" class="reference"><a href="#cite_note-22"><span class="cite-bracket">&#91;</span>22<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Boeing_C-17_Globemaster_III" title="Boeing C-17 Globemaster III">Boeing C-17</a>
    </td>
    <td>United States
    </td>
    <td><a href="/wiki/Strategic_airlifter" class="mw-redirect" title="Strategic airlifter">strategic airlifter</a>
    </td>
    <td>
    </td>
    <td>11<sup id="cite_ref-:12_14-7" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Ilyushin_Il-76" title="Ilyushin Il-76">Ilyushin Il-76</a>
    </td>
    <td>Soviet Union
    </td>
    <td>strategic airlifter
    </td>
    <td><a href="/wiki/Ilyushin_Il-76#Military_variants" title="Ilyushin Il-76">Il-76MD</a>
    </td>
    <td>17<sup id="cite_ref-:12_14-8" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Lockheed_Martin_C-130J_Super_Hercules" title="Lockheed Martin C-130J Super Hercules">C-130J Super Hercules</a>
    </td>
    <td>United States
    </td>
    <td><a href="/wiki/Airlift#Tactical_airlift" title="Airlift">tactical airlifter</a>
    </td>
    <td><a href="/wiki/C-130J#Variants" class="mw-redirect" title="C-130J">C-130J-30</a><sup id="cite_ref-23" class="reference"><a href="#cite_note-23"><span class="cite-bracket">&#91;</span>23<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>12<sup id="cite_ref-:12_14-9" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Airbus_A321" title="Airbus A321">Airbus A321</a>
    </td>
    <td><a href="/wiki/Europe" title="Europe">Europe</a>
    </td>
    <td>transport
    </td>
    <td><a href="/wiki/A321-200" class="mw-redirect" title="A321-200">A321-200</a>
    </td>
    <td>4<sup id="cite_ref-:12_14-10" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Antonov_An-32" title="Antonov An-32">Antonov An-32</a>
    </td>
    <td>Soviet Union
    </td>
    <td><a href="/wiki/Airlift#Tactical_airlift" title="Airlift">tactical airlifter</a>
    </td>
    <td>
    </td>
    <td>103<sup id="cite_ref-:12_14-11" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>53 are the <a href="/wiki/Antonov_An-32#Variants" title="Antonov An-32">32RE</a> variant<sup id="cite_ref-fg-27nov15_24-0" class="reference"><a href="#cite_note-fg-27nov15-24"><span class="cite-bracket">&#91;</span>24<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/EADS_CASA_C-295" title="EADS CASA C-295">EADS CASA C-295</a>
    </td>
    <td><a href="/wiki/Spain" title="Spain">Spain</a>
    </td>
    <td><a href="/wiki/Airlift#Tactical_airlift" title="Airlift">tactical airlifter</a>
    </td>
    <td><a href="/wiki/EADS_CASA_C-295#Variants" title="EADS CASA C-295">C-295MW</a>
    </td>
    <td>5<sup id="cite_ref-25" class="reference"><a href="#cite_note-25"><span class="cite-bracket">&#91;</span>25<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>51 more on order - <a href="/wiki/Hawker_Siddeley_HS_748" title="Hawker Siddeley HS 748">HS 748</a> replacement<sup id="cite_ref-26" class="reference"><a href="#cite_note-26"><span class="cite-bracket">&#91;</span>26<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Hawker_Siddeley_HS_748" title="Hawker Siddeley HS 748">Hawker Siddeley HS 748</a>
    </td>
    <td>United Kingdom
    </td>
    <td><a href="/wiki/Airlift#Tactical_airlift" title="Airlift">tactical airlifter</a>
    </td>
    <td>
    </td>
    <td>57<sup id="cite_ref-:12_14-12" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>To be replaced by <a href="/wiki/EADS_CASA_C-295" title="EADS CASA C-295">EADS CASA C-295</a>
    </td></tr>
    <tr>
    <td><a href="/wiki/Dornier_228" title="Dornier 228">Dornier Do 228</a>
    </td>
    <td><a href="/wiki/Germany" title="Germany">Germany</a>
    </td>
    <td><a href="/wiki/Airlift#Tactical_airlift" title="Airlift">tactical airlifter</a>
    </td>
    <td>228-201
    </td>
    <td>58<sup id="cite_ref-:12_14-13" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>license built by <a href="/wiki/Hindustan_Aeronautics_Limited" title="Hindustan Aeronautics Limited">HAL</a><sup id="cite_ref-jawa-04_27-0" class="reference"><a href="#cite_note-jawa-04-27"><span class="cite-bracket">&#91;</span>27<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Helicopters" class="mw-redirect" title="Helicopters">Helicopters</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Boeing_AH-64_Apache" title="Boeing AH-64 Apache">Boeing AH-64</a>
    </td>
    <td><a href="/wiki/United_States" title="United States">United States</a>
    </td>
    <td>attack
    </td>
    <td><a href="/wiki/Boeing_AH-64_Apache#AH-64E" title="Boeing AH-64 Apache">AH-64E</a>
    </td>
    <td>22<sup id="cite_ref-:12_14-14" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Mil_Mi-24" title="Mil Mi-24">Mil Mi-24</a>
    </td>
    <td>Russia
    </td>
    <td><a href="/wiki/Attack_helicopter" title="Attack helicopter">attack</a>
    </td>
    <td><a href="/wiki/List_of_Mil_Mi-24_variants" title="List of Mil Mi-24 variants">Mi-24/25/35</a>
    </td>
    <td>15<sup id="cite_ref-:12_14-15" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Light_Combat_Helicopter" class="mw-redirect" title="HAL Light Combat Helicopter">HAL Prachand</a>
    </td>
    <td>India
    </td>
    <td>attack
    </td>
    <td>
    </td>
    <td>10<sup id="cite_ref-:2_28-0" class="reference"><a href="#cite_note-:2-28"><span class="cite-bracket">&#91;</span>28<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>66 on order<sup id="cite_ref-:3_29-0" class="reference"><a href="#cite_note-:3-29"><span class="cite-bracket">&#91;</span>29<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Rudra" title="HAL Rudra">HAL Rudra</a>
    </td>
    <td>India
    </td>
    <td>attack
    </td>
    <td>
    </td>
    <td>16
    </td>
    <td>50 on order.<sup id="cite_ref-30" class="reference"><a href="#cite_note-30"><span class="cite-bracket">&#91;</span>30<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Boeing_CH-47_Chinook" title="Boeing CH-47 Chinook">CH-47 Chinook</a>
    </td>
    <td>United States
    </td>
    <td>transport
    </td>
    <td><a href="/wiki/Boeing_CH-47_Chinook#CH-47F" title="Boeing CH-47 Chinook">CH-47F</a>
    </td>
    <td>15<sup id="cite_ref-:12_14-16" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Mil_Mi-17" title="Mil Mi-17">Mil Mi-17</a>
    </td>
    <td>Russia
    </td>
    <td>utility
    </td>
    <td><a href="/wiki/Mil_Mi-17#Variants" title="Mil Mi-17">Mi-17V-5</a>
    </td>
    <td>222<sup id="cite_ref-:12_14-17" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Dhruv" title="HAL Dhruv">HAL Dhruv</a>
    </td>
    <td>India
    </td>
    <td><a href="/wiki/Utility_helicopter" title="Utility helicopter">utility</a>
    </td>
    <td>
    </td>
    <td>95<sup id="cite_ref-:12_14-18" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Light_Utility_Helicopter" title="HAL Light Utility Helicopter">HAL LUH</a>
    </td>
    <td>India
    </td>
    <td>utility
    </td>
    <td>
    </td>
    <td>
    </td>
    <td>6 on order<sup id="cite_ref-31" class="reference"><a href="#cite_note-31"><span class="cite-bracket">&#91;</span>31<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td rowspan="2"><a href="/wiki/A%C3%A9rospatiale_Alouette_III" title="Aérospatiale Alouette III">Alouette III</a>
    </td>
    <td rowspan="2">France/India
    </td>
    <td rowspan="2">liaison
    </td>
    <td><a href="/wiki/HAL_Chetak" class="mw-redirect" title="HAL Chetak">Chetak</a>
    </td>
    <td>77<sup id="cite_ref-:12_14-19" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td rowspan="3">license-built by <a href="/wiki/Hindustan_Aeronautics_Limited" title="Hindustan Aeronautics Limited">HAL</a>. A fleet of around 120 aircraft.<sup id="cite_ref-32" class="reference"><a href="#cite_note-32"><span class="cite-bracket">&#91;</span>32<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Cheetal" class="mw-redirect" title="HAL Cheetal">Cheetal</a>
    </td>
    <td>18<sup id="cite_ref-33" class="reference"><a href="#cite_note-33"><span class="cite-bracket">&#91;</span>33<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/A%C3%A9rospatiale_SA_315B_Lama" title="Aérospatiale SA 315B Lama">SA 315B Lama</a>
    </td>
    <td>France/India
    </td>
    <td>utility
    </td>
    <td><a href="/wiki/A%C3%A9rospatiale_SA_315B_Lama#Variants" title="Aérospatiale SA 315B Lama">Cheetah</a>
    </td>
    <td>18<sup id="cite_ref-:12_14-20" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Trainer_(aircraft)" class="mw-redirect" title="Trainer (aircraft)">Trainer Aircraft</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/BAE_Systems_Hawk" title="BAE Systems Hawk">BAE Hawk</a>
    </td>
    <td>United Kingdom
    </td>
    <td><a href="/wiki/Trainer_aircraft#Advanced_training" title="Trainer aircraft">Advanced trainer</a>
    </td>
    <td><a href="/wiki/BAE_Systems_Hawk#Hawk_132" title="BAE Systems Hawk">Hawk 132</a>
    </td>
    <td>101
    <p><sup id="cite_ref-:12_14-21" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-:8_34-0" class="reference"><a href="#cite_note-:8-34"><span class="cite-bracket">&#91;</span>34<span class="cite-bracket">&#93;</span></a></sup>
    </p>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Kiran" class="mw-redirect" title="HAL Kiran">HAL Kiran</a>
    </td>
    <td>India
    </td>
    <td><a href="/wiki/Trainer_aircraft" title="Trainer aircraft">Intermediate trainer</a>
    </td>
    <td>
    </td>
    <td>77<sup id="cite_ref-:12_14-22" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_HTT-40" title="HAL HTT-40">HAL HTT-40</a>
    </td>
    <td><a href="/wiki/India" title="India">India</a>
    </td>
    <td><a href="/wiki/Trainer_aircraft#Basic_training" title="Trainer aircraft">Basic trainer</a>
    </td>
    <td>
    </td>
    <td>
    </td>
    <td>70 on order <sup id="cite_ref-:12_14-23" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Pilatus_PC-7" title="Pilatus PC-7">Pilatus PC-7</a>
    </td>
    <td><a href="/wiki/Switzerland" title="Switzerland">Switzerland</a>
    </td>
    <td><a href="/wiki/Trainer_aircraft#Basic_training" title="Trainer aircraft">Basic trainer</a>
    </td>
    <td><a href="/wiki/Pilatus_PC-7#Variants" title="Pilatus PC-7">Mk II</a>
    </td>
    <td>75<sup id="cite_ref-:12_14-24" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Pipistrel_Virus" title="Pipistrel Virus">Pipistrel Virus</a>
    </td>
    <td><a href="/wiki/Slovenia" title="Slovenia">Slovenia</a>
    </td>
    <td><a href="/wiki/Ab-initio_trainer" class="mw-redirect" title="Ab-initio trainer">Ab initio trainer</a>
    </td>
    <td>
    </td>
    <td>72<sup id="cite_ref-35" class="reference"><a href="#cite_note-35"><span class="cite-bracket">&#91;</span>35<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Unmanned_aerial_vehicle" title="Unmanned aerial vehicle">UAV</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/IAI_Heron" title="IAI Heron">IAI Heron</a>
    </td>
    <td>Israel
    </td>
    <td><a href="/wiki/Surveillance_drones" class="mw-redirect" title="Surveillance drones">surveillance</a>
    </td>
    <td>Heron 1
    </td>
    <td>47<sup id="cite_ref-36" class="reference"><a href="#cite_note-36"><span class="cite-bracket">&#91;</span>36<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td><sup id="cite_ref-:06_37-0" class="reference"><a href="#cite_note-:06-37"><span class="cite-bracket">&#91;</span>37<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/IAI_Heron" title="IAI Heron">IAI Heron</a> Mk 2
    </td>
    <td>Israel
    </td>
    <td><a href="/wiki/Surveillance_drones" class="mw-redirect" title="Surveillance drones">surveillance</a>
    </td>
    <td>Mk 2
    </td>
    <td>4<sup id="cite_ref-:9_38-0" class="reference"><a href="#cite_note-:9-38"><span class="cite-bracket">&#91;</span>38<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-:10_39-0" class="reference"><a href="#cite_note-:10-39"><span class="cite-bracket">&#91;</span>39<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/IAI_Searcher" title="IAI Searcher">IAI Searcher</a>
    </td>
    <td>Israel
    </td>
    <td>surveillance
    </td>
    <td>Mk. I / II
    </td>
    <td><sup id="cite_ref-janes-16sep15_40-0" class="reference"><a href="#cite_note-janes-16sep15-40"><span class="cite-bracket">&#91;</span>40<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td>ALS-50
    </td>
    <td>India
    </td>
    <td><a href="/wiki/Loitering_munition" title="Loitering munition">loitering munition</a>
    </td>
    <td>
    </td>
    <td>100<sup id="cite_ref-41" class="reference"><a href="#cite_note-41"><span class="cite-bracket">&#91;</span>41<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a rel="nofollow" class="external text" href="http://www.kadet-uav.com/">Kadet</a> Loitering Aerial Munition
    </td>
    <td>India
    </td>
    <td><a href="/wiki/Loitering_munition" title="Loitering munition">loitering munition</a>
    </td>
    <td>
    </td>
    <td>50+ on order
    </td>
    <td>Developed by <a href="/wiki/Defence_Research_and_Development_Organisation" title="Defence Research and Development Organisation">DRDO</a> and <a rel="nofollow" class="external text" href="http://www.kadet-uav.com/">KDS</a>
    <p>Multiple variants; Weight - 15 to 120 kg; Warhead - 2 to 40 kg; Max. Endurance - 12 hrs; Max. Range - 150 to 300 km; Canister launched and vertical take-off and landing (VTOL) variants<sup id="cite_ref-42" class="reference"><a href="#cite_note-42"><span class="cite-bracket">&#91;</span>42<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-43" class="reference"><a href="#cite_note-43"><span class="cite-bracket">&#91;</span>43<span class="cite-bracket">&#93;</span></a></sup>
    </p>
    </td></tr></tbody></table>
    <div class="mw-heading mw-heading2"><h2 id="Army_Aviation_Corps">Army Aviation Corps</h2></div>
    <link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1236090951"><div role="note" class="hatnote navigation-not-searchable">Further information: <a href="/wiki/Army_Aviation_Corps_(India)" title="Army Aviation Corps (India)">Army Aviation Corps (India)</a></div> 
    <figure class="mw-default-size mw-halign-right" typeof="mw:File/Thumb"><a href="/wiki/File:Rudra_Vayushakti_2024_(cropped).jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/1/1d/Rudra_Vayushakti_2024_%28cropped%29.jpg/220px-Rudra_Vayushakti_2024_%28cropped%29.jpg" decoding="async" width="220" height="124" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/1/1d/Rudra_Vayushakti_2024_%28cropped%29.jpg/330px-Rudra_Vayushakti_2024_%28cropped%29.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/1/1d/Rudra_Vayushakti_2024_%28cropped%29.jpg/440px-Rudra_Vayushakti_2024_%28cropped%29.jpg 2x" data-file-width="1024" data-file-height="576" /></a><figcaption><a href="/wiki/HAL_Rudra" title="HAL Rudra">HAL Rudra</a> attack helicopters during Rudra Shakti 2024 exercise</figcaption></figure>
    <table class="wikitable">
    <tbody><tr>
    <th style="text-align:center; background:#acc;">Aircraft
    </th>
    <th style="text-align: center; background:#acc;">Origin
    </th>
    <th style="text-align:l center; background:#acc;">Type
    </th>
    <th style="text-align:left; background:#acc;">Variant
    </th>
    <th style="text-align:center; background:#acc;">In service
    </th>
    <th style="text-align: center; background:#acc;">Notes
    </th></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Helicopters" class="mw-redirect" title="Helicopters">Helicopters</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Boeing_AH-64_Apache" title="Boeing AH-64 Apache">Boeing AH-64</a>
    </td>
    <td>United States
    </td>
    <td>attack
    </td>
    <td><a href="/wiki/Boeing_AH-64_Apache#AH-64E" title="Boeing AH-64 Apache">AH-64E(I)</a>
    </td>
    <td>
    </td>
    <td>6 on order<sup id="cite_ref-44" class="reference"><a href="#cite_note-44"><span class="cite-bracket">&#91;</span>44<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Prachand" title="HAL Prachand">HAL Prachand</a>
    </td>
    <td>India
    </td>
    <td><a href="/wiki/Attack_helicopter" title="Attack helicopter">attack</a>
    </td>
    <td>
    </td>
    <td>
    </td>
    <td>90 on order<sup id="cite_ref-:3_29-1" class="reference"><a href="#cite_note-:3-29"><span class="cite-bracket">&#91;</span>29<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Rudra" title="HAL Rudra">HAL Rudra</a>
    </td>
    <td><a href="/wiki/India" title="India">India</a>
    </td>
    <td>attack
    </td>
    <td>
    </td>
    <td>75<sup id="cite_ref-45" class="reference"><a href="#cite_note-45"><span class="cite-bracket">&#91;</span>45<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-:7_46-0" class="reference"><a href="#cite_note-:7-46"><span class="cite-bracket">&#91;</span>46<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Dhruv" title="HAL Dhruv">HAL Dhruv</a>
    </td>
    <td><a href="/wiki/India" title="India">India</a>
    </td>
    <td><a href="/wiki/Utility_helicopter" title="Utility helicopter">utility</a>
    </td>
    <td>
    </td>
    <td>76<sup id="cite_ref-:7_46-1" class="reference"><a href="#cite_note-:7-46"><span class="cite-bracket">&#91;</span>46<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-47" class="reference"><a href="#cite_note-47"><span class="cite-bracket">&#91;</span>47<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>19 more on order<sup id="cite_ref-:02_48-0" class="reference"><a href="#cite_note-:02-48"><span class="cite-bracket">&#91;</span>48<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-49" class="reference"><a href="#cite_note-49"><span class="cite-bracket">&#91;</span>49<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/A%C3%A9rospatiale_Alouette_III" title="Aérospatiale Alouette III">Alouette III</a>
    </td>
    <td>France/India
    </td>
    <td>liaison / utility
    </td>
    <td><a href="/wiki/HAL_Chetak" class="mw-redirect" title="HAL Chetak">Chetak</a>
    </td>
    <td rowspan="2">190<sup id="cite_ref-50" class="reference"><a href="#cite_note-50"><span class="cite-bracket">&#91;</span>50<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-51" class="reference"><a href="#cite_note-51"><span class="cite-bracket">&#91;</span>51<span class="cite-bracket">&#93;</span></a></sup> - 200<sup id="cite_ref-52" class="reference"><a href="#cite_note-52"><span class="cite-bracket">&#91;</span>52<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td rowspan="2">license-built by <a href="/wiki/Hindustan_Aeronautics_Limited" title="Hindustan Aeronautics Limited">HAL</a>
    </td></tr>
    <tr>
    <td><a href="/wiki/A%C3%A9rospatiale_SA_315B_Lama" title="Aérospatiale SA 315B Lama">SA 315B Lama</a>
    </td>
    <td>France/India
    </td>
    <td>liaison / utility
    </td>
    <td><a href="/wiki/A%C3%A9rospatiale_SA_315B_Lama#Variants" title="Aérospatiale SA 315B Lama">Cheetah</a>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Unmanned_aerial_vehicle" title="Unmanned aerial vehicle">UAV</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Drishti-10" title="Drishti-10">Drishti-10</a>
    </td>
    <td><a href="/wiki/Israel" title="Israel">Israel</a>/<a href="/wiki/India" title="India">India</a>
    </td>
    <td><a href="/wiki/Reconnaissance" title="Reconnaissance">Reconnaissance</a>
    </td>
    <td>
    </td>
    <td>
    </td>
    <td>2 on order<sup id="cite_ref-:4_53-0" class="reference"><a href="#cite_note-:4-53"><span class="cite-bracket">&#91;</span>53<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/IAI_Heron" title="IAI Heron">IAI Heron</a>
    </td>
    <td>Israel
    </td>
    <td><a href="/wiki/Surveillance_aircraft" title="Surveillance aircraft">Surveillance</a>
    </td>
    <td>Heron 1
    </td>
    <td>
    </td>
    <td><sup id="cite_ref-:04_54-0" class="reference"><a href="#cite_note-:04-54"><span class="cite-bracket">&#91;</span>54<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/IAI_Eitan" title="IAI Eitan">IAI Heron TP</a>
    </td>
    <td>Israel
    </td>
    <td><a href="/wiki/Surveillance_aircraft" title="Surveillance aircraft">Surveillance</a>
    </td>
    <td>
    </td>
    <td>4<sup id="cite_ref-55" class="reference"><a href="#cite_note-55"><span class="cite-bracket">&#91;</span>55<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>Deployed in <a href="/wiki/Ladakh" title="Ladakh">Ladakh</a> and <a href="/wiki/Northeast_India" title="Northeast India">Northeast</a>.
    </td></tr>
    <tr>
    <td><a href="/wiki/IAI_Heron" title="IAI Heron">IAI Heron</a> Mk 2
    </td>
    <td>Israel
    </td>
    <td><a href="/wiki/Surveillance_aircraft" title="Surveillance aircraft">Surveillance</a>
    </td>
    <td>Mk 2
    </td>
    <td>
    </td>
    <td>6 on order<sup id="cite_ref-56" class="reference"><a href="#cite_note-56"><span class="cite-bracket">&#91;</span>56<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/IAI_Searcher" title="IAI Searcher">IAI Searcher</a><sup id="cite_ref-janes-20feb13_57-0" class="reference"><a href="#cite_note-janes-20feb13-57"><span class="cite-bracket">&#91;</span>57<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td><a href="/wiki/Israel" title="Israel">Israel</a>
    </td>
    <td><a href="/wiki/Reconnaissance" title="Reconnaissance">Reconnaissance</a>
    </td>
    <td>Mk-II
    </td>
    <td>&lt;100<sup id="cite_ref-58" class="reference"><a href="#cite_note-58"><span class="cite-bracket">&#91;</span>58<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a rel="nofollow" class="external text" href="https://ideaforgetech.com/security-and-surveillance/switch-uav">Ideaforge Switch</a> <sup id="cite_ref-Business_Standard_India_59-0" class="reference"><a href="#cite_note-Business_Standard_India-59"><span class="cite-bracket">&#91;</span>59<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-60" class="reference"><a href="#cite_note-60"><span class="cite-bracket">&#91;</span>60<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td><a href="/wiki/India" title="India">India</a>
    </td>
    <td><a href="/wiki/Surveillance_aircraft" title="Surveillance aircraft">Surveillance</a>
    </td>
    <td>1.0
    </td>
    <td>
    </td>
    <td>undisclosed quantities on order<sup id="cite_ref-Business_Standard_India_59-1" class="reference"><a href="#cite_note-Business_Standard_India-59"><span class="cite-bracket">&#91;</span>59<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    
    <tr>
    <td>NewSpace NIMBUS
    </td>
    <td><a href="/wiki/India" title="India">India</a>
    </td>
    <td><a href="/wiki/Swarming_(military)" title="Swarming (military)">Swarm</a> drones
    </td>
    <td>Mk-III
    </td>
    <td>75
    </td>
    <td rowspan="2">Part of autonomous surveillance and armed drone swarm (A-SADS)<sup id="cite_ref-ns_61-0" class="reference"><a href="#cite_note-ns-61"><span class="cite-bracket">&#91;</span>61<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-62" class="reference"><a href="#cite_note-62"><span class="cite-bracket">&#91;</span>62<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td>NewSpace BELUGA
    </td>
    <td><a href="/wiki/India" title="India">India</a>
    </td>
    <td><a href="/wiki/Swarming_(military)" title="Swarming (military)">Swarm</a> drones
    </td>
    <td>
    </td>
    <td>25
    </td></tr>
    <tr>
    <td>Raphe MPhibr MR-20<sup id="cite_ref-rmp_63-0" class="reference"><a href="#cite_note-rmp-63"><span class="cite-bracket">&#91;</span>63<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td><a href="/wiki/India" title="India">India</a>
    </td>
    <td><a href="/wiki/Cargo" title="Cargo">Cargo </a>
    </td>
    <td>
    </td>
    <td>48<sup id="cite_ref-rmp_63-1" class="reference"><a href="#cite_note-rmp-63"><span class="cite-bracket">&#91;</span>63<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr></tbody></table>
    <div class="mw-heading mw-heading2"><h2 id="Naval_Air_Arm">Naval Air Arm</h2></div>
    <link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1236090951"><div role="note" class="hatnote navigation-not-searchable">Further information: <a href="/wiki/Indian_Naval_Air_Arm" title="Indian Naval Air Arm">Indian Naval Air Arm</a> and <a href="/wiki/List_of_Indian_naval_aircraft" class="mw-redirect" title="List of Indian naval aircraft">List of Indian naval aircraft</a></div>
    <figure class="mw-default-size mw-halign-right" typeof="mw:File/Thumb"><a href="/wiki/File:HAL_Dhruv_MKIII_Commandos_Heliborne_operation_3.jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/a/a6/HAL_Dhruv_MKIII_Commandos_Heliborne_operation_3.jpg/220px-HAL_Dhruv_MKIII_Commandos_Heliborne_operation_3.jpg" decoding="async" width="220" height="147" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/a/a6/HAL_Dhruv_MKIII_Commandos_Heliborne_operation_3.jpg/330px-HAL_Dhruv_MKIII_Commandos_Heliborne_operation_3.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/a/a6/HAL_Dhruv_MKIII_Commandos_Heliborne_operation_3.jpg/440px-HAL_Dhruv_MKIII_Commandos_Heliborne_operation_3.jpg 2x" data-file-width="1280" data-file-height="853" /></a><figcaption>Heliborne operation from <a href="/wiki/HAL_Dhruv" title="HAL Dhruv">HAL Dhruv MK-III</a></figcaption></figure>
    <figure class="mw-default-size mw-halign-right" typeof="mw:File/Thumb"><a href="/wiki/File:Boeing_P-8I_of_the_Indian_Navy_(modified).jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/c/cb/Boeing_P-8I_of_the_Indian_Navy_%28modified%29.jpg/220px-Boeing_P-8I_of_the_Indian_Navy_%28modified%29.jpg" decoding="async" width="220" height="142" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/c/cb/Boeing_P-8I_of_the_Indian_Navy_%28modified%29.jpg/330px-Boeing_P-8I_of_the_Indian_Navy_%28modified%29.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/c/cb/Boeing_P-8I_of_the_Indian_Navy_%28modified%29.jpg/440px-Boeing_P-8I_of_the_Indian_Navy_%28modified%29.jpg 2x" data-file-width="621" data-file-height="400" /></a><figcaption><a href="/wiki/Boeing_P-8_Poseidon#India" title="Boeing P-8 Poseidon">A Boeing P-8I Neptune of Indian Navy</a></figcaption></figure>
    <figure class="mw-default-size" typeof="mw:File/Thumb"><a href="/wiki/File:Sikorsky_MH-60R_Seahawk_helicopter_of_Indian_Navy.jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/6/6f/Sikorsky_MH-60R_Seahawk_helicopter_of_Indian_Navy.jpg/220px-Sikorsky_MH-60R_Seahawk_helicopter_of_Indian_Navy.jpg" decoding="async" width="220" height="147" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/6/6f/Sikorsky_MH-60R_Seahawk_helicopter_of_Indian_Navy.jpg/330px-Sikorsky_MH-60R_Seahawk_helicopter_of_Indian_Navy.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/6/6f/Sikorsky_MH-60R_Seahawk_helicopter_of_Indian_Navy.jpg/440px-Sikorsky_MH-60R_Seahawk_helicopter_of_Indian_Navy.jpg 2x" data-file-width="1920" data-file-height="1280" /></a><figcaption>MH-60R Seahawk helicopter of Indian Navy</figcaption></figure>
    <table class="wikitable">
    <tbody><tr>
    <th style="text-align:center; background:#acc;">Aircraft
    </th>
    <th style="text-align: center; background:#acc;">Origin
    </th>
    <th style="text-align:l center; background:#acc;">Type
    </th>
    <th style="text-align:left; background:#acc;">Variant
    </th>
    <th style="text-align:center; background:#acc;">In service
    </th>
    <th style="text-align: center; background:#acc;">Notes
    </th></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Military_aircraft#Combat_aircraft" title="Military aircraft">Combat Aircraft</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/MiG-29" class="mw-redirect" title="MiG-29">MiG-29</a>
    </td>
    <td><a href="/wiki/Russia" title="Russia">Russia</a>
    </td>
    <td><a href="/wiki/Multirole_combat_aircraft" title="Multirole combat aircraft">multirole</a>
    </td>
    <td><a href="/wiki/Mikoyan_MiG-29K" title="Mikoyan MiG-29K">MiG-29K</a>
    </td>
    <td>40<sup id="cite_ref-World_Air_Forces_2024_64-0" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-65" class="reference"><a href="#cite_note-65"><span class="cite-bracket">&#91;</span>65<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>7 <a href="/wiki/Mikoyan_MiG-29K#Variants" title="Mikoyan MiG-29K">KUB</a> variants provide <a href="/wiki/Trainer_(aircraft)#Operational_conversion" class="mw-redirect" title="Trainer (aircraft)">conversion training</a>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Maritime_patrol_aircraft" title="Maritime patrol aircraft">Maritime patrol</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Boeing_P-8_Poseidon" title="Boeing P-8 Poseidon">Boeing P-8</a>
    </td>
    <td>United States
    </td>
    <td><a href="/wiki/Anti-submarine_warfare" title="Anti-submarine warfare">ASW</a> / <a href="/wiki/Maritime_patrol_aircraft" title="Maritime patrol aircraft">patrol</a>
    </td>
    <td><a href="/wiki/Boeing_P-8_Poseidon#India" title="Boeing P-8 Poseidon"> P-8I</a>
    </td>
    <td>12<sup id="cite_ref-World_Air_Forces_2024_64-1" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Dornier_Do_228" class="mw-redirect" title="Dornier Do 228">Dornier Do 228</a>
    </td>
    <td>Germany
    </td>
    <td><a href="/wiki/Surveillance_aircraft" title="Surveillance aircraft"> surveillance</a>
    </td>
    <td>228-201<sup id="cite_ref-jawa-04_27-1" class="reference"><a href="#cite_note-jawa-04-27"><span class="cite-bracket">&#91;</span>27<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>25<sup id="cite_ref-66" class="reference"><a href="#cite_note-66"><span class="cite-bracket">&#91;</span>66<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>10 on order<sup id="cite_ref-World_Air_Forces_2024_64-2" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Britten-Norman_BN-2_Islander" title="Britten-Norman BN-2 Islander"> Britten-Norman BN-2</a>
    </td>
    <td>United Kingdom
    </td>
    <td>utility / <a href="/wiki/Maritime_patrol_aircraft" title="Maritime patrol aircraft">patrol</a>
    </td>
    <td><a href="/wiki/Britten-Norman_BN-2_Islander#Variants" title="Britten-Norman BN-2 Islander">BN-2B/2T</a><sup id="cite_ref-67" class="reference"><a href="#cite_note-67"><span class="cite-bracket">&#91;</span>67<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>4<sup id="cite_ref-World_Air_Forces_2024_64-3" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Helicopters" class="mw-redirect" title="Helicopters">Helicopters</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/HAL_Dhruv" title="HAL Dhruv">HAL Dhruv</a>
    </td>
    <td><a href="/wiki/India" title="India">India</a>
    </td>
    <td><a href="/wiki/Utility_helicopter" title="Utility helicopter">utility</a>
    </td>
    <td>
    </td>
    <td>24<sup id="cite_ref-World_Air_Forces_2024_64-4" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Kamov_Ka-31" title="Kamov Ka-31">Kamov Ka-31</a>
    </td>
    <td>Russia
    </td>
    <td><a href="/wiki/Airborne_early_warning_and_control" title="Airborne early warning and control">AEW</a>
    </td>
    <td>
    </td>
    <td>14<sup id="cite_ref-World_Air_Forces_2024_64-5" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>employs a <a href="/wiki/Planar_array_radar" class="mw-redirect" title="Planar array radar">Planar array radar</a>
    </td></tr>
    <tr>
    <td><a href="/wiki/Kamov_Ka-27" title="Kamov Ka-27">Kamov Ka-27</a>
    </td>
    <td><a href="/wiki/Russia" title="Russia">Russia</a>
    </td>
    <td><a href="/wiki/Anti-submarine_warfare" title="Anti-submarine warfare">ASW</a>
    </td>
    <td><a href="/wiki/Kamov_Ka-27#Variants" title="Kamov Ka-27">Ka-28</a>
    </td>
    <td>14<sup id="cite_ref-World_Air_Forces_2024_64-6" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Sikorsky_SH-60_Seahawk" title="Sikorsky SH-60 Seahawk">SH-60 Seahawk</a>
    </td>
    <td><a href="/wiki/United_States" title="United States">United States</a>
    </td>
    <td><a href="/wiki/Anti-surface_warfare" title="Anti-surface warfare">ASW</a> / <a href="/wiki/Search_and_rescue" title="Search and rescue">SAR</a>
    </td>
    <td><a href="/wiki/Sikorsky_SH-60_Seahawk#U.S._versions" title="Sikorsky SH-60 Seahawk">MH-60R</a>
    </td>
    <td>6<sup id="cite_ref-:5_68-0" class="reference"><a href="#cite_note-:5-68"><span class="cite-bracket">&#91;</span>68<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>24 on order<sup id="cite_ref-69" class="reference"><a href="#cite_note-69"><span class="cite-bracket">&#91;</span>69<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Westland_Sea_King" title="Westland Sea King">Westland Sea King</a>
    </td>
    <td>United Kingdom
    </td>
    <td><a href="/wiki/Search_and_rescue" title="Search and rescue">SAR</a> / utility
    </td>
    <td><a href="/wiki/Westland_Sea_King#Variants" title="Westland Sea King"> Mk.42B/C</a><sup id="cite_ref-hiranandani_70-0" class="reference"><a href="#cite_note-hiranandani-70"><span class="cite-bracket">&#91;</span>70<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>25<sup id="cite_ref-World_Air_Forces_2024_64-7" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>six are <a href="/wiki/Sikorsky_SH-3_Sea_King#Sikorsky_designations" title="Sikorsky SH-3 Sea King">UH-3H</a> variants
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Chetak" class="mw-redirect" title="HAL Chetak">HAL Chetak</a>
    </td>
    <td>France/India
    </td>
    <td>liaison / utility
    </td>
    <td>
    </td>
    <td>42<sup id="cite_ref-World_Air_Forces_2024_64-8" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Trainer_(aircraft)" class="mw-redirect" title="Trainer (aircraft)">Trainer Aircraft</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/BAE_Systems_Hawk" title="BAE Systems Hawk">BAE Hawk</a>
    </td>
    <td><a href="/wiki/United_Kingdom" title="United Kingdom">United Kingdom</a>
    </td>
    <td>Jet trainer
    </td>
    <td><a href="/wiki/BAE_Systems_Hawk#Hawk_132" title="BAE Systems Hawk">Hawk 132</a>
    </td>
    <td>17<sup id="cite_ref-World_Air_Forces_2024_64-9" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Kiran" class="mw-redirect" title="HAL Kiran">HAL Kiran</a>
    </td>
    <td><a href="/wiki/India" title="India">India</a>
    </td>
    <td>Jet trainer
    </td>
    <td>
    </td>
    <td>20<sup id="cite_ref-World_Air_Forces_2024_64-10" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Unmanned_aerial_vehicle" title="Unmanned aerial vehicle">UAV</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/IAI_Heron" title="IAI Heron">IAI Heron</a><sup id="cite_ref-bs-sipri_71-0" class="reference"><a href="#cite_note-bs-sipri-71"><span class="cite-bracket">&#91;</span>71<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>Israel
    </td>
    <td>surveillance
    </td>
    <td>Heron 1
    </td>
    <td>14<sup id="cite_ref-:03_72-0" class="reference"><a href="#cite_note-:03-72"><span class="cite-bracket">&#91;</span>72<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td><sup id="cite_ref-toi-inas_73-0" class="reference"><a href="#cite_note-toi-inas-73"><span class="cite-bracket">&#91;</span>73<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-74" class="reference"><a href="#cite_note-74"><span class="cite-bracket">&#91;</span>74<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/IAI_Searcher" title="IAI Searcher">IAI Searcher</a><sup id="cite_ref-janes-16sep15_40-1" class="reference"><a href="#cite_note-janes-16sep15-40"><span class="cite-bracket">&#91;</span>40<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td><a href="/wiki/Israel" title="Israel">Israel</a>
    </td>
    <td>surveillance
    </td>
    <td>Mk. II
    </td>
    <td>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/General_Atomics_MQ-9_Reaper" title="General Atomics MQ-9 Reaper">MQ-9 Reaper</a>
    </td>
    <td><a href="/wiki/United_States" title="United States">United States</a>
    </td>
    <td><a href="/wiki/Surveillance_drone" class="mw-redirect" title="Surveillance drone">surveillance</a>
    </td>
    <td><a href="/wiki/General_Atomics_MQ-9_Reaper#SeaGuardian" title="General Atomics MQ-9 Reaper">SeaGuardian</a>
    </td>
    <td>2<sup id="cite_ref-75" class="reference"><a href="#cite_note-75"><span class="cite-bracket">&#91;</span>75<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Drishti-10" title="Drishti-10">Drishti-10</a>
    </td>
    <td><a href="/wiki/Israel" title="Israel">Israel</a>/<a href="/wiki/India" title="India">India</a>
    </td>
    <td>surveillance
    </td>
    <td>
    </td>
    <td>2<sup id="cite_ref-:6_76-0" class="reference"><a href="#cite_note-:6-76"><span class="cite-bracket">&#91;</span>76<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-77" class="reference"><a href="#cite_note-77"><span class="cite-bracket">&#91;</span>77<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr></tbody></table>
    <div class="mw-heading mw-heading2"><h2 id="Coast_Guard">Coast Guard</h2></div>
    <figure class="mw-default-size" typeof="mw:File/Thumb"><a href="/wiki/File:Dornier_Do-228-101,_India_-_Coast_Guard_JP7712387.jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/2/29/Dornier_Do-228-101%2C_India_-_Coast_Guard_JP7712387.jpg/220px-Dornier_Do-228-101%2C_India_-_Coast_Guard_JP7712387.jpg" decoding="async" width="220" height="150" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/2/29/Dornier_Do-228-101%2C_India_-_Coast_Guard_JP7712387.jpg/330px-Dornier_Do-228-101%2C_India_-_Coast_Guard_JP7712387.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/2/29/Dornier_Do-228-101%2C_India_-_Coast_Guard_JP7712387.jpg/440px-Dornier_Do-228-101%2C_India_-_Coast_Guard_JP7712387.jpg 2x" data-file-width="976" data-file-height="664" /></a><figcaption>A Dornier Do-228-101</figcaption></figure>
    <link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1236090951"><div role="note" class="hatnote navigation-not-searchable">Further information: <a href="/wiki/Indian_Coast_Guard" title="Indian Coast Guard">Indian Coast Guard</a></div>
    <table class="wikitable sortable">
    <tbody><tr>
    <th style="text-align:center; background:#acc;">Aircraft
    </th>
    <th style="text-align:center; background:#acc;">Origin
    </th>
    <th style="text-align:center; background:#acc;">Type
    </th>
    <th style="text-align:center; background:#acc;">Variant
    </th>
    <th style="text-align:center; background:#acc;">In service
    </th>
    <th style="text-align:center; background:#acc;">Notes
    </th></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Maritime_patrol_aircraft" title="Maritime patrol aircraft">Maritime patrol</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Dornier_Do_228" class="mw-redirect" title="Dornier Do 228">Dornier Do 228</a>
    </td>
    <td><a href="/wiki/Germany" title="Germany">Germany</a>
    </td>
    <td><a href="/wiki/Reconnaissance_aircraft" title="Reconnaissance aircraft">reconnaissance</a>
    </td>
    <td>101/201<sup id="cite_ref-jawa-04_27-2" class="reference"><a href="#cite_note-jawa-04-27"><span class="cite-bracket">&#91;</span>27<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>36<sup id="cite_ref-thestatesman.com_78-0" class="reference"><a href="#cite_note-thestatesman.com-78"><span class="cite-bracket">&#91;</span>78<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>2 on order<sup id="cite_ref-79" class="reference"><a href="#cite_note-79"><span class="cite-bracket">&#91;</span>79<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Helicopters" class="mw-redirect" title="Helicopters">Helicopters</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/HAL_Dhruv" title="HAL Dhruv">HAL Dhruv</a>
    </td>
    <td>India
    </td>
    <td>utility
    </td>
    <td><a href="/wiki/HAL_Dhruv#Variants" title="HAL Dhruv">Mk. I</a> / Mk. III
    </td>
    <td>4 / 16<sup id="cite_ref-80" class="reference"><a href="#cite_note-80"><span class="cite-bracket">&#91;</span>80<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-81" class="reference"><a href="#cite_note-81"><span class="cite-bracket">&#91;</span>81<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-82" class="reference"><a href="#cite_note-82"><span class="cite-bracket">&#91;</span>82<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>9 Mk.III on order<sup id="cite_ref-:022_83-0" class="reference"><a href="#cite_note-:022-83"><span class="cite-bracket">&#91;</span>83<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-84" class="reference"><a href="#cite_note-84"><span class="cite-bracket">&#91;</span>84<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Chetak" class="mw-redirect" title="HAL Chetak">HAL Chetak</a>
    </td>
    <td>France/India
    </td>
    <td>utility
    </td>
    <td>
    </td>
    <td>17<sup id="cite_ref-:0_85-0" class="reference"><a href="#cite_note-:0-85"><span class="cite-bracket">&#91;</span>85<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr></tbody></table>
    <div class="mw-heading mw-heading2"><h2 id="See_also">See also</h2></div>
    <ul><li><a href="/wiki/List_of_historical_aircraft_of_the_Indian_Air_Force" title="List of historical aircraft of the Indian Air Force">List of historical aircraft of the Indian Air Force</a></li>
    <li><a href="/wiki/List_of_Indian_naval_aircraft" class="mw-redirect" title="List of Indian naval aircraft">List of Indian naval aircraft</a></li>
    <li><a href="/wiki/Currently_active_military_equipment_by_country" class="mw-redirect" title="Currently active military equipment by country">Currently active military equipment by country</a></li>
    <li><a href="/wiki/Military_of_India" class="mw-redirect" title="Military of India">Military of India</a></li>
    <li><a href="/wiki/Indian_Air_Force" title="Indian Air Force">Indian Air Force</a></li>
    <li><a href="/wiki/Indian_Naval_Air_Arm" title="Indian Naval Air Arm">Indian Naval Air Arm</a></li>
    <li><a href="/wiki/Future_of_the_Indian_Air_Force" title="Future of the Indian Air Force">Future of the Indian Air Force</a></li>
    <li><a href="/wiki/Border_Security_Force" title="Border Security Force">Border Security Force</a></li></ul>
    <div class="mw-heading mw-heading2"><h2 id="References">References</h2></div>
    <style data-mw-deduplicate="TemplateStyles:r1239543626">.mw-parser-output .reflist{margin-bottom:0.5em;list-style-type:decimal}@media screen{.mw-parser-output .reflist{font-size:90%}}.mw-parser-output .reflist .references{font-size:100%;margin-bottom:0;list-style-type:inherit}.mw-parser-output .reflist-columns-2{column-width:30em}.mw-parser-output .reflist-columns-3{column-width:25em}.mw-parser-output .reflist-columns{margin-top:0.3em}.mw-parser-output .reflist-columns ol{margin-top:0}.mw-parser-output .reflist-columns li{page-break-inside:avoid;break-inside:avoid-column}.mw-parser-output .reflist-upper-alpha{list-style-type:upper-alpha}.mw-parser-output .reflist-upper-roman{list-style-type:upper-roman}.mw-parser-output .reflist-lower-alpha{list-style-type:lower-alpha}.mw-parser-output .reflist-lower-greek{list-style-type:lower-greek}.mw-parser-output .reflist-lower-roman{list-style-type:lower-roman}</style><div class="reflist reflist-columns references-column-width" style="column-width: 30em;">
    <ol class="references">
    <li id="cite_note-:1-1"><span class="mw-cite-backlink">^ <a href="#cite_ref-:1_1-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-:1_1-1"><sup><i><b>b</b></i></sup></a> <a href="#cite_ref-:1_1-2"><sup><i><b>c</b></i></sup></a> <a href="#cite_ref-:1_1-3"><sup><i><b>d</b></i></sup></a> <a href="#cite_ref-:1_1-4"><sup><i><b>e</b></i></sup></a> <a href="#cite_ref-:1_1-5"><sup><i><b>f</b></i></sup></a> <a href="#cite_ref-:1_1-6"><sup><i><b>g</b></i></sup></a> <a href="#cite_ref-:1_1-7"><sup><i><b>h</b></i></sup></a> <a href="#cite_ref-:1_1-8"><sup><i><b>i</b></i></sup></a></span> <span class="reference-text"><style data-mw-deduplicate="TemplateStyles:r1238218222">.mw-parser-output cite.citation{font-style:inherit;word-wrap:break-word}.mw-parser-output .citation q{quotes:"\"""\"""'""'"}.mw-parser-output .citation:target{background-color:rgba(0,127,255,0.133)}.mw-parser-output .id-lock-free.id-lock-free a{background:url("//upload.wikimedia.org/wikipedia/commons/6/65/Lock-green.svg")right 0.1em center/9px no-repeat}.mw-parser-output .id-lock-limited.id-lock-limited a,.mw-parser-output .id-lock-registration.id-lock-registration a{background:url("//upload.wikimedia.org/wikipedia/commons/d/d6/Lock-gray-alt-2.svg")right 0.1em center/9px no-repeat}.mw-parser-output .id-lock-subscription.id-lock-subscription a{background:url("//upload.wikimedia.org/wikipedia/commons/a/aa/Lock-red-alt-2.svg")right 0.1em center/9px no-repeat}.mw-parser-output .cs1-ws-icon a{background:url("//upload.wikimedia.org/wikipedia/commons/4/4c/Wikisource-logo.svg")right 0.1em center/12px no-repeat}body:not(.skin-timeless):not(.skin-minerva) .mw-parser-output .id-lock-free a,body:not(.skin-timeless):not(.skin-minerva) .mw-parser-output .id-lock-limited a,body:not(.skin-timeless):not(.skin-minerva) .mw-parser-output .id-lock-registration a,body:not(.skin-timeless):not(.skin-minerva) .mw-parser-output .id-lock-subscription a,body:not(.skin-timeless):not(.skin-minerva) .mw-parser-output .cs1-ws-icon a{background-size:contain;padding:0 1em 0 0}.mw-parser-output .cs1-code{color:inherit;background:inherit;border:none;padding:inherit}.mw-parser-output .cs1-hidden-error{display:none;color:var(--color-error,#d33)}.mw-parser-output .cs1-visible-error{color:var(--color-error,#d33)}.mw-parser-output .cs1-maint{display:none;color:#085;margin-left:0.3em}.mw-parser-output .cs1-kern-left{padding-left:0.2em}.mw-parser-output .cs1-kern-right{padding-right:0.2em}.mw-parser-output .citation .mw-selflink{font-weight:inherit}@media screen{.mw-parser-output .cs1-format{font-size:95%}html.skin-theme-clientpref-night .mw-parser-output .cs1-maint{color:#18911f}}@media screen and (prefers-color-scheme:dark){html.skin-theme-clientpref-os .mw-parser-output .cs1-maint{color:#18911f}}</style><cite class="citation book cs1"><a rel="nofollow" class="external text" href="https://www.iiss.org/en/publications/the-military-balance/"><i>The Military Balance 2024</i></a>. The International Institute for Strategic Studies. pp.&#160;269–270. <a href="/wiki/ISBN_(identifier)" class="mw-redirect" title="ISBN (identifier)">ISBN</a>&#160;<a href="/wiki/Special:BookSources/9781032780047" title="Special:BookSources/9781032780047"><bdi>9781032780047</bdi></a>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=book&amp;rft.btitle=The+Military+Balance+2024&amp;rft.pages=269-270&amp;rft.pub=The+International+Institute+for+Strategic+Studies&amp;rft.isbn=9781032780047&amp;rft_id=https%3A%2F%2Fwww.iiss.org%2Fen%2Fpublications%2Fthe-military-balance%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-2"><span class="mw-cite-backlink"><b><a href="#cite_ref-2">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.business-standard.com/industry/news/delivery-of-single-seat-tejas-lca-mark-1-fighters-to-iaf-completed-123082300824_1.html">"Delivery of single-seat Tejas LCA Mark 1 fighters to IAF completed"</a>. <i>Business Standard</i>. 23 August 2023.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Business+Standard&amp;rft.atitle=Delivery+of+single-seat+Tejas+LCA+Mark+1+fighters+to+IAF+completed&amp;rft.date=2023-08-23&amp;rft_id=https%3A%2F%2Fwww.business-standard.com%2Findustry%2Fnews%2Fdelivery-of-single-seat-tejas-lca-mark-1-fighters-to-iaf-completed-123082300824_1.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-3"><span class="mw-cite-backlink"><b><a href="#cite_ref-3">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.ndtv.com/india-news/1st-crash-in-23-years-of-its-history-5-facts-about-tejas-fighter-jet-5224145">"1st Crash In 23 Years Of Its History, 5 Facts About Tejas Fighter Jet"</a>. <i>NDTV.com</i><span class="reference-accessdate">. Retrieved <span class="nowrap">12 March</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=NDTV.com&amp;rft.atitle=1st+Crash+In+23+Years+Of+Its+History%2C+5+Facts+About+Tejas+Fighter+Jet&amp;rft_id=https%3A%2F%2Fwww.ndtv.com%2Findia-news%2F1st-crash-in-23-years-of-its-history-5-facts-about-tejas-fighter-jet-5224145&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-4"><span class="mw-cite-backlink"><b><a href="#cite_ref-4">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://timesofindia.indiatimes.com/india/tejas-mk-1a-completes-maiden-flight-first-delivery-soon/articleshow/108846208.cms">"Tejas MK-1A completes maiden flight, first delivery soon"</a>. <i>The Times of India</i>. 28 March 2024. <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/0971-8257">0971-8257</a><span class="reference-accessdate">. Retrieved <span class="nowrap">9 May</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Times+of+India&amp;rft.atitle=Tejas+MK-1A+completes+maiden+flight%2C+first+delivery+soon&amp;rft.date=2024-03-28&amp;rft.issn=0971-8257&amp;rft_id=https%3A%2F%2Ftimesofindia.indiatimes.com%2Findia%2Ftejas-mk-1a-completes-maiden-flight-first-delivery-soon%2Farticleshow%2F108846208.cms&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-5"><span class="mw-cite-backlink"><b><a href="#cite_ref-5">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.indiatoday.in/india-today-insight/story/when-14-years-on-iaf-got-its-first-trainer-jet-for-lca-tejas-2446188-2023-10-08">"When, 14 years on, IAF got its first trainer jet for LCA Tejas"</a>. <i>India Today</i>. 8 October 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">9 May</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=India+Today&amp;rft.atitle=When%2C+14+years+on%2C+IAF+got+its+first+trainer+jet+for+LCA+Tejas&amp;rft.date=2023-10-08&amp;rft_id=https%3A%2F%2Fwww.indiatoday.in%2Findia-today-insight%2Fstory%2Fwhen-14-years-on-iaf-got-its-first-trainer-jet-for-lca-tejas-2446188-2023-10-08&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:11-6"><span class="mw-cite-backlink">^ <a href="#cite_ref-:11_6-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-:11_6-1"><sup><i><b>b</b></i></sup></a></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFPhilip2021" class="citation web cs1">Philip, Snehesh Alex (3 February 2021). <a rel="nofollow" class="external text" href="https://theprint.in/defence/contract-signed-for-83-lca-tejas-fighters-all-eyes-now-on-hal-delivery-schedule/597841/">"Contract signed for 83 LCA Tejas fighters, all eyes now on HAL delivery schedule"</a>. <i>ThePrint</i><span class="reference-accessdate">. Retrieved <span class="nowrap">9 May</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=ThePrint&amp;rft.atitle=Contract+signed+for+83+LCA+Tejas+fighters%2C+all+eyes+now+on+HAL+delivery+schedule&amp;rft.date=2021-02-03&amp;rft.aulast=Philip&amp;rft.aufirst=Snehesh+Alex&amp;rft_id=https%3A%2F%2Ftheprint.in%2Fdefence%2Fcontract-signed-for-83-lca-tejas-fighters-all-eyes-now-on-hal-delivery-schedule%2F597841%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-7"><span class="mw-cite-backlink"><b><a href="#cite_ref-7">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://www.moneycontrol.com/news/india/defence-ministry-approves-purchase-of-97-tejas-aircraft-and-156-prachanda-helicopters-sources-11833571.html">"Rs 2.23 lakh crore-deal: India approves purchase of 97 Tejas aircraft, 156 Prachanda helicopters, other defence equipment"</a>. <i>Money Control</i>. 30 November 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">30 November</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=Money+Control&amp;rft.atitle=Rs+2.23+lakh+crore-deal%3A+India+approves+purchase+of+97+Tejas+aircraft%2C+156+Prachanda+helicopters%2C+other+defence+equipment&amp;rft.date=2023-11-30&amp;rft_id=https%3A%2F%2Fwww.moneycontrol.com%2Fnews%2Findia%2Fdefence-ministry-approves-purchase-of-97-tejas-aircraft-and-156-prachanda-helicopters-sources-11833571.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-8"><span class="mw-cite-backlink"><b><a href="#cite_ref-8">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.aerotime.aero/articles/india-to-modernize-sukhoi-su-30mki-fighter-fleet-with-4-billion-program">"India moves closer to adding $4B upgrades to Su-30 jets - AeroTime"</a>. 26 January 2023. <a rel="nofollow" class="external text" href="https://web.archive.org/web/20230418094132/https://www.aerotime.aero/articles/india-to-modernize-sukhoi-su-30mki-fighter-fleet-with-4-billion-program">Archived</a> from the original on 18 April 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">18 April</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=India+moves+closer+to+adding+%244B+upgrades+to+Su-30+jets+-+AeroTime&amp;rft.date=2023-01-26&amp;rft_id=https%3A%2F%2Fwww.aerotime.aero%2Farticles%2Findia-to-modernize-sukhoi-su-30mki-fighter-fleet-with-4-billion-program&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-9"><span class="mw-cite-backlink"><b><a href="#cite_ref-9">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.hindustantimes.com/india-news/iafs-sukhoi-jet-crashes-in-maharashtras-nashik-pilot-ejects-safely-report-101717492196585.html">"Air Force's Sukhoi fighter jet crashes in Maharashtra's Nashik: Report"</a>. <i>Hindustan Times</i><span class="reference-accessdate">. Retrieved <span class="nowrap">4 June</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Hindustan+Times&amp;rft.atitle=Air+Force%27s+Sukhoi+fighter+jet+crashes+in+Maharashtra%27s+Nashik%3A+Report&amp;rft_id=https%3A%2F%2Fwww.hindustantimes.com%2Findia-news%2Fiafs-sukhoi-jet-crashes-in-maharashtras-nashik-pilot-ejects-safely-report-101717492196585.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-10"><span class="mw-cite-backlink"><b><a href="#cite_ref-10">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://timesofindia.indiatimes.com/india/mod-approves-12-more-sukhois-800-armoured-vehicles-others-for-rs-45000-crore/articleshow/103698530.cms?ssp=1&amp;darkschemeovr=1&amp;setlang=en-US">"Nod for Rs 45,000cr defence buys, 12 more Sukhois to fly in"</a>. <i>The Times of India</i>. 16 September 2023. <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/0971-8257">0971-8257</a><span class="reference-accessdate">. Retrieved <span class="nowrap">9 May</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Times+of+India&amp;rft.atitle=Nod+for+Rs+45%2C000cr+defence+buys%2C+12+more+Sukhois+to+fly+in&amp;rft.date=2023-09-16&amp;rft.issn=0971-8257&amp;rft_id=https%3A%2F%2Ftimesofindia.indiatimes.com%2Findia%2Fmod-approves-12-more-sukhois-800-armoured-vehicles-others-for-rs-45000-crore%2Farticleshow%2F103698530.cms%3Fssp%3D1%26darkschemeovr%3D1%26setlang%3Den-US&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-11"><span class="mw-cite-backlink"><b><a href="#cite_ref-11">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.ndtv.com/india-news/mig-29-fighter-jet-crashes-in-rajasthan-pilot-safe-6476114/amp/1">"MiG-29 Fighter Jet Crashes In Rajasthan, Pilot Safe"</a>. <i>NDTV.com</i><span class="reference-accessdate">. Retrieved <span class="nowrap">3 September</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=NDTV.com&amp;rft.atitle=MiG-29+Fighter+Jet+Crashes+In+Rajasthan%2C+Pilot+Safe&amp;rft_id=https%3A%2F%2Fwww.ndtv.com%2Findia-news%2Fmig-29-fighter-jet-crashes-in-rajasthan-pilot-safe-6476114%2Famp%2F1&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-12"><span class="mw-cite-backlink"><b><a href="#cite_ref-12">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://thewire.in/security/mig-21-squadron-retired-curtain-closing-iaf-most-abiding-fighter">"Another MiG-21 Squadron Retired: The Curtain Is Closing on IAF's Most Abiding Fighter"</a>. <i>The Wire</i><span class="reference-accessdate">. Retrieved <span class="nowrap">9 May</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=The+Wire&amp;rft.atitle=Another+MiG-21+Squadron+Retired%3A+The+Curtain+Is+Closing+on+IAF%E2%80%99s+Most+Abiding+Fighter&amp;rft_id=https%3A%2F%2Fthewire.in%2Fsecurity%2Fmig-21-squadron-retired-curtain-closing-iaf-most-abiding-fighter&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-13"><span class="mw-cite-backlink"><b><a href="#cite_ref-13">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFPeri2023" class="citation news cs1">Peri, Dinakar (8 November 2023). <a rel="nofollow" class="external text" href="https://www.thehindu.com/news/national/how-are-the-mig-21-fighter-jets-being-phased-out-explained/article67510157.ece">"How are the MiG-21 fighter jets being phased out? | Explained"</a>. <i>The Hindu</i>. <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/0971-751X">0971-751X</a><span class="reference-accessdate">. Retrieved <span class="nowrap">8 May</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Hindu&amp;rft.atitle=How+are+the+MiG-21+fighter+jets+being+phased+out%3F+%7C+Explained&amp;rft.date=2023-11-08&amp;rft.issn=0971-751X&amp;rft.aulast=Peri&amp;rft.aufirst=Dinakar&amp;rft_id=https%3A%2F%2Fwww.thehindu.com%2Fnews%2Fnational%2Fhow-are-the-mig-21-fighter-jets-being-phased-out-explained%2Farticle67510157.ece&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:12-14"><span class="mw-cite-backlink">^ <a href="#cite_ref-:12_14-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-:12_14-1"><sup><i><b>b</b></i></sup></a> <a href="#cite_ref-:12_14-2"><sup><i><b>c</b></i></sup></a> <a href="#cite_ref-:12_14-3"><sup><i><b>d</b></i></sup></a> <a href="#cite_ref-:12_14-4"><sup><i><b>e</b></i></sup></a> <a href="#cite_ref-:12_14-5"><sup><i><b>f</b></i></sup></a> <a href="#cite_ref-:12_14-6"><sup><i><b>g</b></i></sup></a> <a href="#cite_ref-:12_14-7"><sup><i><b>h</b></i></sup></a> <a href="#cite_ref-:12_14-8"><sup><i><b>i</b></i></sup></a> <a href="#cite_ref-:12_14-9"><sup><i><b>j</b></i></sup></a> <a href="#cite_ref-:12_14-10"><sup><i><b>k</b></i></sup></a> <a href="#cite_ref-:12_14-11"><sup><i><b>l</b></i></sup></a> <a href="#cite_ref-:12_14-12"><sup><i><b>m</b></i></sup></a> <a href="#cite_ref-:12_14-13"><sup><i><b>n</b></i></sup></a> <a href="#cite_ref-:12_14-14"><sup><i><b>o</b></i></sup></a> <a href="#cite_ref-:12_14-15"><sup><i><b>p</b></i></sup></a> <a href="#cite_ref-:12_14-16"><sup><i><b>q</b></i></sup></a> <a href="#cite_ref-:12_14-17"><sup><i><b>r</b></i></sup></a> <a href="#cite_ref-:12_14-18"><sup><i><b>s</b></i></sup></a> <a href="#cite_ref-:12_14-19"><sup><i><b>t</b></i></sup></a> <a href="#cite_ref-:12_14-20"><sup><i><b>u</b></i></sup></a> <a href="#cite_ref-:12_14-21"><sup><i><b>v</b></i></sup></a> <a href="#cite_ref-:12_14-22"><sup><i><b>w</b></i></sup></a> <a href="#cite_ref-:12_14-23"><sup><i><b>x</b></i></sup></a> <a href="#cite_ref-:12_14-24"><sup><i><b>y</b></i></sup></a></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.flightglobal.com/download?ac=98881">"World Air Forces 2024"</a>. 15 December 2023. <a rel="nofollow" class="external text" href="https://web.archive.org/web/20240105033828/https://www.flightglobal.com/download?ac=98881">Archived</a> from the original on 5 January 2024<span class="reference-accessdate">. Retrieved <span class="nowrap">13 April</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=World+Air+Forces+2024&amp;rft.date=2023-12-15&amp;rft_id=https%3A%2F%2Fwww.flightglobal.com%2Fdownload%3Fac%3D98881&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-15"><span class="mw-cite-backlink"><b><a href="#cite_ref-15">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.flightglobal.com/download?ac=98881">"2024 World Air Forces"</a>. <i>www.flightglobal.com</i>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=www.flightglobal.com&amp;rft.atitle=2024+World+Air+Forces&amp;rft_id=https%3A%2F%2Fwww.flightglobal.com%2Fdownload%3Fac%3D98881&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-16"><span class="mw-cite-backlink"><b><a href="#cite_ref-16">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://timesofindia.indiatimes.com/india/india-to-order-2-more-israeli-eyes-in-sky/articleshow/77774435.cms?from=mdr">"Ladakh face-off: India to order 2 more Israeli 'eyes in sky' for $1 billion"</a>. <i>The Times of India</i>. 27 August 2020. <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/0971-8257">0971-8257</a><span class="reference-accessdate">. Retrieved <span class="nowrap">7 February</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Times+of+India&amp;rft.atitle=Ladakh+face-off%3A+India+to+order+2+more+Israeli+%27eyes+in+sky%27+for+%241+billion&amp;rft.date=2020-08-27&amp;rft.issn=0971-8257&amp;rft_id=https%3A%2F%2Ftimesofindia.indiatimes.com%2Findia%2Findia-to-order-2-more-israeli-eyes-in-sky%2Farticleshow%2F77774435.cms%3Ffrom%3Dmdr&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-17"><span class="mw-cite-backlink"><b><a href="#cite_ref-17">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://forceindia.net/civilaviation/businessjets/more-than-special/">"Special Mission Aircraft are cheaper to operate than older intelligence gathering assets"</a><span class="reference-accessdate">. Retrieved <span class="nowrap">31 August</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=Special+Mission+Aircraft+are+cheaper+to+operate+than+older+intelligence+gathering+assets&amp;rft_id=https%3A%2F%2Fforceindia.net%2Fcivilaviation%2Fbusinessjets%2Fmore-than-special%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-18"><span class="mw-cite-backlink"><b><a href="#cite_ref-18">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFPhilip2020" class="citation web cs1">Philip, Snehesh Alex (14 May 2020). <a rel="nofollow" class="external text" href="https://theprint.in/defence/indias-oldest-flying-aircraft-in-spotlight-after-radar-website-shows-it-going-to-pakistan/421757/">"India's oldest flying aircraft in spotlight after radar website shows it going to Pakistan"</a>. <i>ThePrint</i><span class="reference-accessdate">. Retrieved <span class="nowrap">31 August</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=ThePrint&amp;rft.atitle=India%E2%80%99s+oldest+flying+aircraft+in+spotlight+after+radar+website+shows+it+going+to+Pakistan&amp;rft.date=2020-05-14&amp;rft.aulast=Philip&amp;rft.aufirst=Snehesh+Alex&amp;rft_id=https%3A%2F%2Ftheprint.in%2Fdefence%2Findias-oldest-flying-aircraft-in-spotlight-after-radar-website-shows-it-going-to-pakistan%2F421757%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-19"><span class="mw-cite-backlink"><b><a href="#cite_ref-19">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFMenon2013" class="citation web cs1">Menon, Jay (23 April 2013). <a rel="nofollow" class="external text" href="http://aviationweek.com/defense/rfp-coming-soon-indian-airborne-jamming-aircraft">"RFP Coming Soon For Indian Airborne Jamming Aircraft"</a>. <i>aviationweek.com</i>. AWIN First.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=aviationweek.com&amp;rft.atitle=RFP+Coming+Soon+For+Indian+Airborne+Jamming+Aircraft&amp;rft.date=2013-04-23&amp;rft.aulast=Menon&amp;rft.aufirst=Jay&amp;rft_id=http%3A%2F%2Faviationweek.com%2Fdefense%2Frfp-coming-soon-indian-airborne-jamming-aircraft&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-20"><span class="mw-cite-backlink"><b><a href="#cite_ref-20">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.hindustantimes.com/india-news/first-modified-boeing-777-aircraft-part-of-air-india-one-fleet-for-pm-to-arrive-in-delhi-today/story-V1eKOpfrXTGhXq34XNkjRL.html">"PM's new special aircraft, equipped with missile defence systems, lands in Delhi"</a>. <i>Hindustan Times</i>. 1 October 2020<span class="reference-accessdate">. Retrieved <span class="nowrap">1 October</span> 2020</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Hindustan+Times&amp;rft.atitle=PM%27s+new+special+aircraft%2C+equipped+with+missile+defence+systems%2C+lands+in+Delhi&amp;rft.date=2020-10-01&amp;rft_id=https%3A%2F%2Fwww.hindustantimes.com%2Findia-news%2Ffirst-modified-boeing-777-aircraft-part-of-air-india-one-fleet-for-pm-to-arrive-in-delhi-today%2Fstory-V1eKOpfrXTGhXq34XNkjRL.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-21"><span class="mw-cite-backlink"><b><a href="#cite_ref-21">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="http://www.dnaindia.com/india/report-india-s-air-force-one-takes-off-on-first-official-flight-1244364">"India's Air Force One takes off on first official flight"</a>. <i>dna</i>. PTI. 1 April 2009.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=dna&amp;rft.atitle=India%27s+Air+Force+One+takes+off+on+first+official+flight&amp;rft.date=2009-04-01&amp;rft_id=http%3A%2F%2Fwww.dnaindia.com%2Findia%2Freport-india-s-air-force-one-takes-off-on-first-official-flight-1244364&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-22"><span class="mw-cite-backlink"><b><a href="#cite_ref-22">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="http://www.thehindubusinessline.com/economy/logistics/india-gets-first-embraer-jet-with-indian-airborne-radar-tech/article3785186.ece">"India gets first Embraer jet with Indian airborne radar tech"</a>. <i>The Hindu Business Line</i>. PTI. 17 August 2012.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Hindu+Business+Line&amp;rft.atitle=India+gets+first+Embraer+jet+with+Indian+airborne+radar+tech&amp;rft.date=2012-08-17&amp;rft_id=http%3A%2F%2Fwww.thehindubusinessline.com%2Feconomy%2Flogistics%2Findia-gets-first-embraer-jet-with-indian-airborne-radar-tech%2Farticle3785186.ece&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-23"><span class="mw-cite-backlink"><b><a href="#cite_ref-23">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="http://pib.nic.in/newsite/erelease.aspx?relid=78432">"Purchase of Transport Aircraft"</a>. Press Information Bureau. 12 December 2011.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=Purchase+of+Transport+Aircraft&amp;rft.pub=Press+Information+Bureau&amp;rft.date=2011-12-12&amp;rft_id=http%3A%2F%2Fpib.nic.in%2Fnewsite%2Ferelease.aspx%3Frelid%3D78432&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-fg-27nov15-24"><span class="mw-cite-backlink"><b><a href="#cite_ref-fg-27nov15_24-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFChandra2015" class="citation news cs1">Chandra, Atul (27 November 2015). <a rel="nofollow" class="external text" href="https://www.flightglobal.com/news/articles/india-receives-last-batch-of-ukraine-upgraded-an-32s-419513/">"India receives last batch of Ukraine-upgraded An-32s"</a>. <i>Flightglobal.com</i>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=Flightglobal.com&amp;rft.atitle=India+receives+last+batch+of+Ukraine-upgraded+An-32s&amp;rft.date=2015-11-27&amp;rft.aulast=Chandra&amp;rft.aufirst=Atul&amp;rft_id=https%3A%2F%2Fwww.flightglobal.com%2Fnews%2Farticles%2Findia-receives-last-batch-of-ukraine-upgraded-an-32s-419513%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-25"><span class="mw-cite-backlink"><b><a href="#cite_ref-25">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFgargi.chaudhry" class="citation web cs1">gargi.chaudhry. <a rel="nofollow" class="external text" href="https://newsable.asianetnews.com/india-defence/airbus-to-deliver-another-two-c295-aircraft-to-indian-air-force-sg6skn">"Airbus to deliver another two C295 aircraft to Indian Air Force"</a>. <i>Asianet News Network Pvt Ltd</i><span class="reference-accessdate">. Retrieved <span class="nowrap">6 July</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Asianet+News+Network+Pvt+Ltd&amp;rft.atitle=Airbus+to+deliver+another+two+C295+aircraft+to+Indian+Air+Force&amp;rft.au=gargi.chaudhry&amp;rft_id=https%3A%2F%2Fnewsable.asianetnews.com%2Findia-defence%2Fairbus-to-deliver-another-two-c295-aircraft-to-indian-air-force-sg6skn&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-26"><span class="mw-cite-backlink"><b><a href="#cite_ref-26">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.news18.com/news/india/govt-likely-to-seal-deal-on-purchase-of-56-c-295-military-transport-planes-in-next-few-days-4239749.html">"Govt Seals Mega Deal with Airbus for Purchase of 56 C-295 Military Transport Aircraft"</a>. <i>News18</i>. 24 September 2021<span class="reference-accessdate">. Retrieved <span class="nowrap">24 September</span> 2021</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=News18&amp;rft.atitle=Govt+Seals+Mega+Deal+with+Airbus+for+Purchase+of+56+C-295+Military+Transport+Aircraft&amp;rft.date=2021-09-24&amp;rft_id=https%3A%2F%2Fwww.news18.com%2Fnews%2Findia%2Fgovt-likely-to-seal-deal-on-purchase-of-56-c-295-military-transport-planes-in-next-few-days-4239749.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-jawa-04-27"><span class="mw-cite-backlink">^ <a href="#cite_ref-jawa-04_27-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-jawa-04_27-1"><sup><i><b>b</b></i></sup></a> <a href="#cite_ref-jawa-04_27-2"><sup><i><b>c</b></i></sup></a></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFJacksonMunsonPeacock2004" class="citation book cs1">Jackson, Paul; Munson, Kenneth; Peacock, Lindsay, eds. (2004). "HAL (Dornier) 228". <i>Jane's All the World's Aircraft</i> (95th year of issue 2004-2005.&#160;ed.). Coulsdon: Janes Information Group. p.&#160;206. <a href="/wiki/ISBN_(identifier)" class="mw-redirect" title="ISBN (identifier)">ISBN</a>&#160;<a href="/wiki/Special:BookSources/0710626142" title="Special:BookSources/0710626142"><bdi>0710626142</bdi></a>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=bookitem&amp;rft.atitle=HAL+%28Dornier%29+228&amp;rft.btitle=Jane%27s+All+the+World%27s+Aircraft&amp;rft.place=Coulsdon&amp;rft.pages=206&amp;rft.edition=95th+year+of+issue+2004-2005.&amp;rft.pub=Janes+Information+Group&amp;rft.date=2004&amp;rft.isbn=0710626142&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:2-28"><span class="mw-cite-backlink"><b><a href="#cite_ref-:2_28-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.pib.gov.in/www.pib.gov.in/Pressreleaseshare.aspx?PRID=1811565">"CCS Approves Procurement of 15 Light Combat Helicopters (LCH) Limited Series Production (LSP) from HAL for IAF (10) &amp; IA(05)"</a>. <i>www.pib.gov.in</i><span class="reference-accessdate">. Retrieved <span class="nowrap">15 December</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=www.pib.gov.in&amp;rft.atitle=CCS+Approves+Procurement+of+15+Light+Combat+Helicopters+%28LCH%29+Limited+Series+Production+%28LSP%29+from+HAL+for+IAF+%2810%29+%26+IA%2805%29&amp;rft_id=https%3A%2F%2Fwww.pib.gov.in%2Fwww.pib.gov.in%2FPressreleaseshare.aspx%3FPRID%3D1811565&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:3-29"><span class="mw-cite-backlink">^ <a href="#cite_ref-:3_29-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-:3_29-1"><sup><i><b>b</b></i></sup></a></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-iafs-strengthened-arsenal-acquisition-of-97-tejas-mk1a-jets-marks-a-milestone-3321952/">"IAF's Strengthened Arsenal: Acquisition of 97 Tejas Mk1A Jets Marks a Milestone"</a>. <i>Financialexpress</i>. 30 November 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">15 December</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Financialexpress&amp;rft.atitle=IAF%27s+Strengthened+Arsenal%3A+Acquisition+of+97+Tejas+Mk1A+Jets+Marks+a+Milestone&amp;rft.date=2023-11-30&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-iafs-strengthened-arsenal-acquisition-of-97-tejas-mk1a-jets-marks-a-milestone-3321952%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-30"><span class="mw-cite-backlink"><b><a href="#cite_ref-30">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://defenceaviationpost.com/about-50-rudra-attack-helicopters-to-be-acquired-by-the-indian-air-force/">"About 50 Rudra Attack Helicopters To Be Acquired By The Indian Air Force"</a>. 16 April 2022<span class="reference-accessdate">. Retrieved <span class="nowrap">16 April</span> 2022</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=About+50+Rudra+Attack+Helicopters+To+Be+Acquired+By+The+Indian+Air+Force&amp;rft.date=2022-04-16&amp;rft_id=https%3A%2F%2Fdefenceaviationpost.com%2Fabout-50-rudra-attack-helicopters-to-be-acquired-by-the-indian-air-force%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-31"><span class="mw-cite-backlink"><b><a href="#cite_ref-31">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFPubby" class="citation news cs1">Pubby, Manu. <a rel="nofollow" class="external text" href="https://economictimes.indiatimes.com/news/defence/indigenous-light-choppers-get-go-ahead-delivery-in-22/articleshow/81638498.cms">"Indigenous light choppers get go-ahead, delivery in 2022"</a>. <i>The Economic Times</i>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Economic+Times&amp;rft.atitle=Indigenous+light+choppers+get+go-ahead%2C+delivery+in+2022&amp;rft.aulast=Pubby&amp;rft.aufirst=Manu&amp;rft_id=https%3A%2F%2Feconomictimes.indiatimes.com%2Fnews%2Fdefence%2Findigenous-light-choppers-get-go-ahead-delivery-in-22%2Farticleshow%2F81638498.cms&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-32"><span class="mw-cite-backlink"><b><a href="#cite_ref-32">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-indigenous-luh-set-to-replace-aging-cheetah-and-chetak-fleet-3285693/">"Indigenous LUH Set to Replace Aging Cheetah and Chetak Fleet"</a>. <i>Financialexpress</i>. 25 October 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">23 September</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Financialexpress&amp;rft.atitle=Indigenous+LUH+Set+to+Replace+Aging+Cheetah+and+Chetak+Fleet&amp;rft.date=2023-10-25&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-indigenous-luh-set-to-replace-aging-cheetah-and-chetak-fleet-3285693%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-33"><span class="mw-cite-backlink"><b><a href="#cite_ref-33">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-indigenous-luh-set-to-replace-aging-cheetah-and-chetak-fleet-3285693/">"Indigenous LUH Set to Replace Aging Cheetah and Chetak Fleet"</a>. <i>Financialexpress</i>. 25 October 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">23 September</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Financialexpress&amp;rft.atitle=Indigenous+LUH+Set+to+Replace+Aging+Cheetah+and+Chetak+Fleet&amp;rft.date=2023-10-25&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-indigenous-luh-set-to-replace-aging-cheetah-and-chetak-fleet-3285693%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:8-34"><span class="mw-cite-backlink"><b><a href="#cite_ref-:8_34-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://www.hindustantimes.com/india-news/iafs-hawk-aircraft-crashes-at-kalaikunda-airbase-in-bengal-pilots-eject-safely-101707827270284.html">"IAF's Hawk aircraft crashes at Kalaikunda airbase in Bengal; pilots eject safely"</a>. <i><a href="/wiki/Hindustan_Times" title="Hindustan Times">Hindustan Times</a></i>. 13 February 2024<span class="reference-accessdate">. Retrieved <span class="nowrap">14 February</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=Hindustan+Times&amp;rft.atitle=IAF%27s+Hawk+aircraft+crashes+at+Kalaikunda+airbase+in+Bengal%3B+pilots+eject+safely&amp;rft.date=2024-02-13&amp;rft_id=https%3A%2F%2Fwww.hindustantimes.com%2Findia-news%2Fiafs-hawk-aircraft-crashes-at-kalaikunda-airbase-in-bengal-pilots-eject-safely-101707827270284.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-35"><span class="mw-cite-backlink"><b><a href="#cite_ref-35">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://archive.today/20200429143302/https://www.janes.com/article/92112/pipistrel-completes-deliveries-of-garud-trainers-to-india">"Pipistrel completes deliveries of Garud trainers to India | Jane's 360"</a>. <i>archive.ph</i>. 29 April 2020. Archived from <a rel="nofollow" class="external text" href="https://www.janes.com/article/92112/pipistrel-completes-deliveries-of-garud-trainers-to-india">the original</a> on 29 April 2020<span class="reference-accessdate">. Retrieved <span class="nowrap">1 December</span> 2021</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=archive.ph&amp;rft.atitle=Pipistrel+completes+deliveries+of+Garud+trainers+to+India+%7C+Jane%27s+360&amp;rft.date=2020-04-29&amp;rft_id=https%3A%2F%2Fwww.janes.com%2Farticle%2F92112%2Fpipistrel-completes-deliveries-of-garud-trainers-to-india&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-36"><span class="mw-cite-backlink"><b><a href="#cite_ref-36">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="http://www.strategypage.com/militaryforums/512-20022.aspx">"Defence Industry Daily: Israel sells heron UAVs to India and Australia"</a>. Strategypage.com. 11 November 2005. <a rel="nofollow" class="external text" href="https://web.archive.org/web/20130929011438/http://www.strategypage.com/militaryforums/512-20022.aspx">Archived</a> from the original on 29 September 2013<span class="reference-accessdate">. Retrieved <span class="nowrap">18 November</span> 2012</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=Defence+Industry+Daily%3A+Israel+sells+heron+UAVs+to+India+and+Australia&amp;rft.pub=Strategypage.com&amp;rft.date=2005-11-11&amp;rft_id=http%3A%2F%2Fwww.strategypage.com%2Fmilitaryforums%2F512-20022.aspx&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:06-37"><span class="mw-cite-backlink"><b><a href="#cite_ref-:06_37-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-iafs-heron-rpa-crashes-in-jaisalmer-court-of-inquiry-initiated-3468130/">"IAF's 'Heron' RPA crashes in Jaisalmer; Court of Inquiry initiated"</a>. <i>Financialexpress</i>. 25 April 2024<span class="reference-accessdate">. Retrieved <span class="nowrap">26 April</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Financialexpress&amp;rft.atitle=IAF%E2%80%99s+%E2%80%98Heron%E2%80%99+RPA+crashes+in+Jaisalmer%3B+Court+of+Inquiry+initiated&amp;rft.date=2024-04-25&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-iafs-heron-rpa-crashes-in-jaisalmer-court-of-inquiry-initiated-3468130%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:9-38"><span class="mw-cite-backlink"><b><a href="#cite_ref-:9_38-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.hindustantimes.com/india-news/india-inducts-new-strike-capable-heron-mark-2-drones-in-northern-sector-details-101691892126424.html">"India inducts new drones at forward air base in Northern sector: Report"</a>. <i>Hindustan Times</i>. 13 August 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">21 March</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Hindustan+Times&amp;rft.atitle=India+inducts+new+drones+at+forward+air+base+in+Northern+sector%3A+Report&amp;rft.date=2023-08-13&amp;rft_id=https%3A%2F%2Fwww.hindustantimes.com%2Findia-news%2Findia-inducts-new-strike-capable-heron-mark-2-drones-in-northern-sector-details-101691892126424.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:10-39"><span class="mw-cite-backlink"><b><a href="#cite_ref-:10_39-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.janes.com/defence-news/news-detail/indian-air-force-inducts-heron-mk-ii">"Indian Air Force inducts Heron Mk II"</a>. <i>Janes.com</i><span class="reference-accessdate">. Retrieved <span class="nowrap">21 March</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Janes.com&amp;rft.atitle=Indian+Air+Force+inducts+Heron+Mk+II&amp;rft_id=https%3A%2F%2Fwww.janes.com%2Fdefence-news%2Fnews-detail%2Findian-air-force-inducts-heron-mk-ii&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-janes-16sep15-40"><span class="mw-cite-backlink">^ <a href="#cite_ref-janes-16sep15_40-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-janes-16sep15_40-1"><sup><i><b>b</b></i></sup></a></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFBedi2015" class="citation journal cs1">Bedi, Rahul (16 September 2015). "India to buy Heron TP UAVs". <i>IHS Jane's Defence Weekly</i>. <b>52</b> (44). <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/2048-3430">2048-3430</a>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=IHS+Jane%27s+Defence+Weekly&amp;rft.atitle=India+to+buy+Heron+TP+UAVs&amp;rft.volume=52&amp;rft.issue=44&amp;rft.date=2015-09-16&amp;rft.issn=2048-3430&amp;rft.aulast=Bedi&amp;rft.aufirst=Rahul&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-41"><span class="mw-cite-backlink"><b><a href="#cite_ref-41">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.janes.com/defence-news/news-detail/aero-india-2023-iaf-to-receive-100-loitering-munitions-from-tasl">"Aero India 2023: IAF to receive 100 loitering munitions from TASL"</a>. <i>Janes.com</i><span class="reference-accessdate">. Retrieved <span class="nowrap">17 February</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Janes.com&amp;rft.atitle=Aero+India+2023%3A+IAF+to+receive+100+loitering+munitions+from+TASL&amp;rft_id=https%3A%2F%2Fwww.janes.com%2Fdefence-news%2Fnews-detail%2Faero-india-2023-iaf-to-receive-100-loitering-munitions-from-tasl&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-42"><span class="mw-cite-backlink"><b><a href="#cite_ref-42">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.theweek.in/news/india/2024/05/08/indias-first-kamikaze-drone-developed-5000-units-can-be-made-in-2-3-yrs.html">"India's first kamikaze drone developed; 5,000 units can be made in 2-3 yrs"</a>. <i>The Week</i><span class="reference-accessdate">. Retrieved <span class="nowrap">9 May</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=The+Week&amp;rft.atitle=India%E2%80%99s+first+kamikaze+drone+developed%3B+5%2C000+units+can+be+made+in+2-3+yrs&amp;rft_id=https%3A%2F%2Fwww.theweek.in%2Fnews%2Findia%2F2024%2F05%2F08%2Findias-first-kamikaze-drone-developed-5000-units-can-be-made-in-2-3-yrs.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-43"><span class="mw-cite-backlink"><b><a href="#cite_ref-43">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-kadet-defence-systems-introduces-indias-pioneering-loitering-aerial-munitions-lam-for-the-armed-forces-3481405/">"Kadet Defence systems introduces India's pioneering Loitering Aerial Munitions (LAM) for the armed forces"</a>. <i>Financialexpress</i>. 8 May 2024<span class="reference-accessdate">. Retrieved <span class="nowrap">9 May</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Financialexpress&amp;rft.atitle=Kadet+Defence+systems+introduces+India%E2%80%99s+pioneering+Loitering+Aerial+Munitions+%28LAM%29+for+the+armed+forces&amp;rft.date=2024-05-08&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-kadet-defence-systems-introduces-indias-pioneering-loitering-aerial-munitions-lam-for-the-armed-forces-3481405%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-44"><span class="mw-cite-backlink"><b><a href="#cite_ref-44">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.hindustantimes.com/india-news/boeing-begins-production-of-apache-attack-helicopters-for-indian-army-in-arizona-delivery-scheduled-for-2024-101692197822841.html">"Boeing begins production of army's Apache helicopters; deliveries next year"</a>. <i>Hindustan Times</i>. 16 August 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">15 December</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Hindustan+Times&amp;rft.atitle=Boeing+begins+production+of+army%27s+Apache+helicopters%3B+deliveries+next+year&amp;rft.date=2023-08-16&amp;rft_id=https%3A%2F%2Fwww.hindustantimes.com%2Findia-news%2Fboeing-begins-production-of-apache-attack-helicopters-for-indian-army-in-arizona-delivery-scheduled-for-2024-101692197822841.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-45"><span class="mw-cite-backlink"><b><a href="#cite_ref-45">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://economictimes.indiatimes.com/news/new-updates/watch-iafs-apache-like-made-in-india-light-combat-helicopter/articleshow/94481515.cms?from=mdr">"Watch: IAF's Apache-like Made in India Light Combat Helicopter"</a>. <i>The Economic Times</i>. 27 September 2022. <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/0013-0389">0013-0389</a><span class="reference-accessdate">. Retrieved <span class="nowrap">13 August</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Economic+Times&amp;rft.atitle=Watch%3A+IAF%27s+Apache-like+Made+in+India+Light+Combat+Helicopter&amp;rft.date=2022-09-27&amp;rft.issn=0013-0389&amp;rft_id=https%3A%2F%2Feconomictimes.indiatimes.com%2Fnews%2Fnew-updates%2Fwatch-iafs-apache-like-made-in-india-light-combat-helicopter%2Farticleshow%2F94481515.cms%3Ffrom%3Dmdr&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:7-46"><span class="mw-cite-backlink">^ <a href="#cite_ref-:7_46-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-:7_46-1"><sup><i><b>b</b></i></sup></a></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-army-chief-says-lch-good-for-high-altitude-army-to-procure-95-of-them-2982095/">"Army Chief says LCH good for high altitude; Army to procure 95 of them"</a>. <i>Financialexpress</i>. 15 February 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">16 February</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Financialexpress&amp;rft.atitle=Army+Chief+says+LCH+good+for+high+altitude%3B+Army+to+procure+95+of+them&amp;rft.date=2023-02-15&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-army-chief-says-lch-good-for-high-altitude-army-to-procure-95-of-them-2982095%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-47"><span class="mw-cite-backlink"><b><a href="#cite_ref-47">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFTeam2024" class="citation web cs1">Team, IADN Editorial (25 May 2024). <a rel="nofollow" class="external text" href="https://iadnews.in/hal-delivers-dhruv-helicopters-to-army-within-2-weeks-of-contract-signing/">"HAL delivers Dhruv helicopters to Army within 2 weeks of contract signing - IADN"</a>. <i>- IADN</i><span class="reference-accessdate">. Retrieved <span class="nowrap">26 May</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=-+IADN&amp;rft.atitle=HAL+delivers+Dhruv+helicopters+to+Army+within+2+weeks+of+contract+signing+-+IADN&amp;rft.date=2024-05-25&amp;rft.aulast=Team&amp;rft.aufirst=IADN+Editorial&amp;rft_id=https%3A%2F%2Fiadnews.in%2Fhal-delivers-dhruv-helicopters-to-army-within-2-weeks-of-contract-signing%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:02-48"><span class="mw-cite-backlink"><b><a href="#cite_ref-:02_48-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.reuters.com/business/aerospace-defense/indias-defence-ministry-signs-deals-worth-975-mln-indigenous-helicopters-2024-03-13/">"India's defence ministry signs deals worth $975 mln for indigenous helicopters"</a>. <i><a href="/wiki/Reuters" title="Reuters">Reuters</a></i>. 13 March 2024.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Reuters&amp;rft.atitle=India%27s+defence+ministry+signs+deals+worth+%24975+mln+for+indigenous+helicopters&amp;rft.date=2024-03-13&amp;rft_id=https%3A%2F%2Fwww.reuters.com%2Fbusiness%2Faerospace-defense%2Findias-defence-ministry-signs-deals-worth-975-mln-indigenous-helicopters-2024-03-13%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-49"><span class="mw-cite-backlink"><b><a href="#cite_ref-49">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.indiatoday.in/india/story/centre-approves-34-new-dhruv-choppers-for-army-coast-guard-2512013-2024-03-07">"Centre approves 34 new Dhruv choppers for Army, Coast Guard"</a>. <i>India Today</i><span class="reference-accessdate">. Retrieved <span class="nowrap">8 March</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=India+Today&amp;rft.atitle=Centre+approves+34+new+Dhruv+choppers+for+Army%2C+Coast+Guard&amp;rft_id=https%3A%2F%2Fwww.indiatoday.in%2Findia%2Fstory%2Fcentre-approves-34-new-dhruv-choppers-for-army-coast-guard-2512013-2024-03-07&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-50"><span class="mw-cite-backlink"><b><a href="#cite_ref-50">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-indigenous-luh-set-to-replace-aging-cheetah-and-chetak-fleet-3285693/">"Indigenous LUH Set to Replace Aging Cheetah and Chetak Fleet"</a>. <i>Financialexpress</i>. 25 October 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">23 September</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Financialexpress&amp;rft.atitle=Indigenous+LUH+Set+to+Replace+Aging+Cheetah+and+Chetak+Fleet&amp;rft.date=2023-10-25&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-indigenous-luh-set-to-replace-aging-cheetah-and-chetak-fleet-3285693%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-51"><span class="mw-cite-backlink"><b><a href="#cite_ref-51">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://www.thehindu.com/news/national/army-aviation-augments-combat-power-while-ageing-cheetah-chetaks-await-replacement/article65623822.ece">"Army Aviation augments combat power while ageing Cheetah, Chetaks await replacement"</a>. <i>The Hindu</i>. 10 July 2022. <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/0971-751X">0971-751X</a><span class="reference-accessdate">. Retrieved <span class="nowrap">30 July</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Hindu&amp;rft.atitle=Army+Aviation+augments+combat+power+while+ageing+Cheetah%2C+Chetaks+await+replacement&amp;rft.date=2022-07-10&amp;rft.issn=0971-751X&amp;rft_id=https%3A%2F%2Fwww.thehindu.com%2Fnews%2Fnational%2Farmy-aviation-augments-combat-power-while-ageing-cheetah-chetaks-await-replacement%2Farticle65623822.ece&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-52"><span class="mw-cite-backlink"><b><a href="#cite_ref-52">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://indianexpress.com/article/india/cheetah-helicopter-army-crash-arunachal-pradesh-search-ops-underway-8501053/">"Two pilots killed after Army's Cheetah helicopter crashes near Arunachal's Bomdila; probe ordered"</a>. <i>The Indian Express</i>. 16 March 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">30 July</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=The+Indian+Express&amp;rft.atitle=Two+pilots+killed+after+Army%27s+Cheetah+helicopter+crashes+near+Arunachal%27s+Bomdila%3B+probe+ordered&amp;rft.date=2023-03-16&amp;rft_id=https%3A%2F%2Findianexpress.com%2Farticle%2Findia%2Fcheetah-helicopter-army-crash-arunachal-pradesh-search-ops-underway-8501053%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:4-53"><span class="mw-cite-backlink"><b><a href="#cite_ref-:4_53-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.janes.com/defence-news/news-detail/india-orders-hermes-900-for-army-navy">"India orders Hermes 900 for army, navy"</a>. <i>Janes.com</i><span class="reference-accessdate">. Retrieved <span class="nowrap">15 December</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Janes.com&amp;rft.atitle=India+orders+Hermes+900+for+army%2C+navy&amp;rft_id=https%3A%2F%2Fwww.janes.com%2Fdefence-news%2Fnews-detail%2Findia-orders-hermes-900-for-army-navy&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:04-54"><span class="mw-cite-backlink"><b><a href="#cite_ref-:04_54-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-iafs-heron-rpa-crashes-in-jaisalmer-court-of-inquiry-initiated-3468130/">"IAF's 'Heron' RPA crashes in Jaisalmer; Court of Inquiry initiated"</a>. <i>Financialexpress</i>. 25 April 2024<span class="reference-accessdate">. Retrieved <span class="nowrap">26 April</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Financialexpress&amp;rft.atitle=IAF%E2%80%99s+%E2%80%98Heron%E2%80%99+RPA+crashes+in+Jaisalmer%3B+Court+of+Inquiry+initiated&amp;rft.date=2024-04-25&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-iafs-heron-rpa-crashes-in-jaisalmer-court-of-inquiry-initiated-3468130%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-55"><span class="mw-cite-backlink"><b><a href="#cite_ref-55">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.news18.com/news/india/army-gets-deliveries-of-2-israeli-heron-tp-drones-bought-in-2020-deploys-them-along-lac-in-ladakh-6162541.html">"Army Gets Deliveries of 2 Israeli Heron TP Drones Bought in 2020, Deploys Them Along LAC in Ladakh"</a>. <i>News18</i>. 14 October 2022<span class="reference-accessdate">. Retrieved <span class="nowrap">28 June</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=News18&amp;rft.atitle=Army+Gets+Deliveries+of+2+Israeli+Heron+TP+Drones+Bought+in+2020%2C+Deploys+Them+Along+LAC+in+Ladakh&amp;rft.date=2022-10-14&amp;rft_id=https%3A%2F%2Fwww.news18.com%2Fnews%2Findia%2Farmy-gets-deliveries-of-2-israeli-heron-tp-drones-bought-in-2020-deploys-them-along-lac-in-ladakh-6162541.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-56"><span class="mw-cite-backlink"><b><a href="#cite_ref-56">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFThakur2022" class="citation web cs1">Thakur, Vijainder K. (24 October 2022). <a rel="nofollow" class="external text" href="https://www.eurasiantimes.com/india-is-negotiating-with-israel-aerospace-to-locally-heron-mk2-drones/">"Decisive Edge For IAF? India Negotiating With Israel To Locally Manufacture 'Weaponizable' Heron Mk2 Drones"</a>. <i>Latest Asian, Middle-East, EurAsian, Indian News</i><span class="reference-accessdate">. Retrieved <span class="nowrap">27 April</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Latest+Asian%2C+Middle-East%2C+EurAsian%2C+Indian+News&amp;rft.atitle=Decisive+Edge+For+IAF%3F+India+Negotiating+With+Israel+To+Locally+Manufacture+%27Weaponizable%27+Heron+Mk2+Drones&amp;rft.date=2022-10-24&amp;rft.aulast=Thakur&amp;rft.aufirst=Vijainder+K.&amp;rft_id=https%3A%2F%2Fwww.eurasiantimes.com%2Findia-is-negotiating-with-israel-aerospace-to-locally-heron-mk2-drones%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-janes-20feb13-57"><span class="mw-cite-backlink"><b><a href="#cite_ref-janes-20feb13_57-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFBedi2013" class="citation journal cs1">Bedi, Rahul (20 February 2013). "India signs up for more Heron UAVs". <i>IHS Jane's Defence Weekly</i>. <b>50</b> (12). <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/2048-3430">2048-3430</a>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=IHS+Jane%27s+Defence+Weekly&amp;rft.atitle=India+signs+up+for+more+Heron+UAVs&amp;rft.volume=50&amp;rft.issue=12&amp;rft.date=2013-02-20&amp;rft.issn=2048-3430&amp;rft.aulast=Bedi&amp;rft.aufirst=Rahul&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-58"><span class="mw-cite-backlink"><b><a href="#cite_ref-58">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="http://www.milpower.org/showclass.asp?class=Searcher">"Show aircraft class: IAI Searcher"</a>. <i>milpower</i>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=milpower&amp;rft.atitle=Show+aircraft+class%3A+IAI+Searcher&amp;rft_id=http%3A%2F%2Fwww.milpower.org%2Fshowclass.asp%3Fclass%3DSearcher&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-Business_Standard_India-59"><span class="mw-cite-backlink">^ <a href="#cite_ref-Business_Standard_India_59-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-Business_Standard_India_59-1"><sup><i><b>b</b></i></sup></a></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://www.business-standard.com/article/current-affairs/indian-army-signs-20-mn-contract-with-ideaforge-to-procure-switch-drones-121011401192_1.html">"Indian Army signs $20 mn contract with ideaForge to procure SWITCH drones"</a>. <i>Business Standard India</i>. Press Trust of India. 14 January 2021<span class="reference-accessdate">. Retrieved <span class="nowrap">19 April</span> 2022</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=Business+Standard+India&amp;rft.atitle=Indian+Army+signs+%2420+mn+contract+with+ideaForge+to+procure+SWITCH+drones&amp;rft.date=2021-01-14&amp;rft_id=https%3A%2F%2Fwww.business-standard.com%2Farticle%2Fcurrent-affairs%2Findian-army-signs-20-mn-contract-with-ideaforge-to-procure-switch-drones-121011401192_1.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-60"><span class="mw-cite-backlink"><b><a href="#cite_ref-60">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.ideaforge.co.in/wp-content/uploads/2021/01/SWITCH-Prime-Brochure-web.pdf">"Switch Prime"</a> <span class="cs1-format">(PDF)</span>. ideaForge<span class="reference-accessdate">. Retrieved <span class="nowrap">27 December</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=Switch+Prime&amp;rft.pub=ideaForge&amp;rft_id=https%3A%2F%2Fwww.ideaforge.co.in%2Fwp-content%2Fuploads%2F2021%2F01%2FSWITCH-Prime-Brochure-web.pdf&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-ns-61"><span class="mw-cite-backlink"><b><a href="#cite_ref-ns_61-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://theigmp.org/indian-army-receives-its-first-swarm-drones-from-newspace/">"Indian army receives its first swarm drones from newspace"</a>. The IGMP (9 march 2023).</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.atitle=Indian+army+receives+its+first+swarm+drones+from+newspace&amp;rft_id=https%3A%2F%2Ftheigmp.org%2Findian-army-receives-its-first-swarm-drones-from-newspace%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-62"><span class="mw-cite-backlink"><b><a href="#cite_ref-62">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.janes.com/defence-news/news-detail/indian-army-receives-swarming-uavs">"Indian Army receives 'swarming&#39; UAVs"</a>. <i>Janes.com</i><span class="reference-accessdate">. Retrieved <span class="nowrap">27 April</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Janes.com&amp;rft.atitle=Indian+Army+receives+%E2%80%98swarming%26%2339%3B+UAVs&amp;rft_id=https%3A%2F%2Fwww.janes.com%2Fdefence-news%2Fnews-detail%2Findian-army-receives-swarming-uavs&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-rmp-63"><span class="mw-cite-backlink">^ <a href="#cite_ref-rmp_63-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-rmp_63-1"><sup><i><b>b</b></i></sup></a></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://www.livefistdefence.com/first-look-at-indian-armys-new-cargo-drones-for-ladakh/">"First Look At Indian Army's New Cargo Drones For Ladakh"</a>. livefistdefence<span class="reference-accessdate">. Retrieved <span class="nowrap">8 September</span> 2021</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.atitle=First+Look+At+Indian+Army%27s+New+Cargo+Drones+For+Ladakh&amp;rft_id=https%3A%2F%2Fwww.livefistdefence.com%2Ffirst-look-at-indian-armys-new-cargo-drones-for-ladakh%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-World_Air_Forces_2024-64"><span class="mw-cite-backlink">^ <a href="#cite_ref-World_Air_Forces_2024_64-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-World_Air_Forces_2024_64-1"><sup><i><b>b</b></i></sup></a> <a href="#cite_ref-World_Air_Forces_2024_64-2"><sup><i><b>c</b></i></sup></a> <a href="#cite_ref-World_Air_Forces_2024_64-3"><sup><i><b>d</b></i></sup></a> <a href="#cite_ref-World_Air_Forces_2024_64-4"><sup><i><b>e</b></i></sup></a> <a href="#cite_ref-World_Air_Forces_2024_64-5"><sup><i><b>f</b></i></sup></a> <a href="#cite_ref-World_Air_Forces_2024_64-6"><sup><i><b>g</b></i></sup></a> <a href="#cite_ref-World_Air_Forces_2024_64-7"><sup><i><b>h</b></i></sup></a> <a href="#cite_ref-World_Air_Forces_2024_64-8"><sup><i><b>i</b></i></sup></a> <a href="#cite_ref-World_Air_Forces_2024_64-9"><sup><i><b>j</b></i></sup></a> <a href="#cite_ref-World_Air_Forces_2024_64-10"><sup><i><b>k</b></i></sup></a></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFHoyle2023" class="citation web cs1">Hoyle, Craig (2023). <a rel="nofollow" class="external text" href="https://www.flightglobal.com/download?ac=98881">"World Air Forces 2024"</a>. <a href="/wiki/FlightGlobal" title="FlightGlobal">FlightGlobal</a><span class="reference-accessdate">. Retrieved <span class="nowrap">27 December</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=World+Air+Forces+2024&amp;rft.pub=FlightGlobal&amp;rft.date=2023&amp;rft.aulast=Hoyle&amp;rft.aufirst=Craig&amp;rft_id=https%3A%2F%2Fwww.flightglobal.com%2Fdownload%3Fac%3D98881&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-65"><span class="mw-cite-backlink"><b><a href="#cite_ref-65">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.janes.com/defence-news/news-detail/indian-navy-reports-crash-of-fifth-mig-29k-in-four-years">"Indian Navy reports crash of fifth MiG-29K in four years"</a>. 13 October 2022<span class="reference-accessdate">. Retrieved <span class="nowrap">21 March</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=Indian+Navy+reports+crash+of+fifth+MiG-29K+in+four+years&amp;rft.date=2022-10-13&amp;rft_id=https%3A%2F%2Fwww.janes.com%2Fdefence-news%2Fnews-detail%2Findian-navy-reports-crash-of-fifth-mig-29k-in-four-years&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-66"><span class="mw-cite-backlink"><b><a href="#cite_ref-66">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://pib.gov.in/PressReleasePage.aspx?PRID=2015025">"MoD signs contract worth over Rs. 2,890 cr with HAL for Mid Life Upgrade of 25 Dornier Aircraft of Indian Navy"</a>. <i>pib.gov.in</i><span class="reference-accessdate">. Retrieved <span class="nowrap">15 March</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=pib.gov.in&amp;rft.atitle=MoD+signs+contract+worth+over+Rs.+2%2C890+cr+with+HAL+for+Mid+Life+Upgrade+of+25+Dornier+Aircraft+of+Indian+Navy&amp;rft_id=https%3A%2F%2Fpib.gov.in%2FPressReleasePage.aspx%3FPRID%3D2015025&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-67"><span class="mw-cite-backlink"><b><a href="#cite_ref-67">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.indiannavy.nic.in/content/dorniers-1">"Dorniers | INAS 550 – The Flying Fish"</a>. <i>www.indiannavy.nic.in</i>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=www.indiannavy.nic.in&amp;rft.atitle=Dorniers+%7C+INAS+550+%E2%80%93+The+Flying+Fish&amp;rft_id=https%3A%2F%2Fwww.indiannavy.nic.in%2Fcontent%2Fdorniers-1&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:5-68"><span class="mw-cite-backlink"><b><a href="#cite_ref-:5_68-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFSentinels" class="citation web cs1">Sentinels, India. <a rel="nofollow" class="external text" href="https://www.indiasentinels.com/navy/lockheed-martin-delivers-6th-mh-60r-romeo-helicopter-to-indian-navy-6070">"Lockheed Martin delivers 6th MH-60R 'Romeo' helicopter to Indian Navy"</a>. <i>www.indiasentinels.com</i><span class="reference-accessdate">. Retrieved <span class="nowrap">15 December</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=www.indiasentinels.com&amp;rft.atitle=Lockheed+Martin+delivers+6th+MH-60R+%27Romeo%27+helicopter+to+Indian+Navy&amp;rft.aulast=Sentinels&amp;rft.aufirst=India&amp;rft_id=https%3A%2F%2Fwww.indiasentinels.com%2Fnavy%2Flockheed-martin-delivers-6th-mh-60r-romeo-helicopter-to-indian-navy-6070&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-69"><span class="mw-cite-backlink"><b><a href="#cite_ref-69">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-romeos-are-coming-to-india-long-wait-for-mh-60r-multi-mission-helicopter-for-indian-navy-is-over-2609515/">"Romeos are coming to India! Long wait for MH-60R multi-mission helicopter for Indian Navy is over"</a>. <i>Financialexpress</i>. 28 July 2022<span class="reference-accessdate">. Retrieved <span class="nowrap">15 December</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Financialexpress&amp;rft.atitle=Romeos+are+coming+to+India%21+Long+wait+for+MH-60R+multi-mission+helicopter+for+Indian+Navy+is+over&amp;rft.date=2022-07-28&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-romeos-are-coming-to-india-long-wait-for-mh-60r-multi-mission-helicopter-for-indian-navy-is-over-2609515%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-hiranandani-70"><span class="mw-cite-backlink"><b><a href="#cite_ref-hiranandani_70-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFHiranandani2005" class="citation book cs1">Hiranandani, G. M. (2005). <a rel="nofollow" class="external text" href="https://books.google.com/books?id=1WxI9TlAxIQC"><i>Transition to Eminence: The Indian Navy 1976-1990</i></a>. Lancer Publishers. p.&#160;99. <a href="/wiki/ISBN_(identifier)" class="mw-redirect" title="ISBN (identifier)">ISBN</a>&#160;<a href="/wiki/Special:BookSources/9788170622666" title="Special:BookSources/9788170622666"><bdi>9788170622666</bdi></a>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=book&amp;rft.btitle=Transition+to+Eminence%3A+The+Indian+Navy+1976-1990&amp;rft.pages=99&amp;rft.pub=Lancer+Publishers&amp;rft.date=2005&amp;rft.isbn=9788170622666&amp;rft.aulast=Hiranandani&amp;rft.aufirst=G.+M.&amp;rft_id=https%3A%2F%2Fbooks.google.com%2Fbooks%3Fid%3D1WxI9TlAxIQC&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-bs-sipri-71"><span class="mw-cite-backlink"><b><a href="#cite_ref-bs-sipri_71-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFMallapur2015" class="citation news cs1">Mallapur, Chaitanya (4 May 2015). <a rel="nofollow" class="external text" href="http://www.business-standard.com/article/specials/india-tops-list-of-drone-importing-nations-115050400136_1.html">"India tops list of drone-importing nations"</a>. <i>IndiaSpend</i>. Business Standard.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=IndiaSpend&amp;rft.atitle=India+tops+list+of+drone-importing+nations&amp;rft.date=2015-05-04&amp;rft.aulast=Mallapur&amp;rft.aufirst=Chaitanya&amp;rft_id=http%3A%2F%2Fwww.business-standard.com%2Farticle%2Fspecials%2Findia-tops-list-of-drone-importing-nations-115050400136_1.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:03-72"><span class="mw-cite-backlink"><b><a href="#cite_ref-:03_72-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-iafs-heron-rpa-crashes-in-jaisalmer-court-of-inquiry-initiated-3468130/">"IAF's 'Heron' RPA crashes in Jaisalmer; Court of Inquiry initiated"</a>. <i>Financialexpress</i>. 25 April 2024<span class="reference-accessdate">. Retrieved <span class="nowrap">26 April</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Financialexpress&amp;rft.atitle=IAF%E2%80%99s+%E2%80%98Heron%E2%80%99+RPA+crashes+in+Jaisalmer%3B+Court+of+Inquiry+initiated&amp;rft.date=2024-04-25&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-iafs-heron-rpa-crashes-in-jaisalmer-court-of-inquiry-initiated-3468130%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-toi-inas-73"><span class="mw-cite-backlink"><b><a href="#cite_ref-toi-inas_73-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://web.archive.org/web/20121104115844/http://articles.timesofindia.indiatimes.com/2011-01-18/ahmedabad/28352057_1_uav-squadron-unmanned-aerial-vehicle-squadron-western-coast">"Eye in the sky to guard Gujarat coast"</a>. <i><a href="/wiki/The_Times_of_India" title="The Times of India">The Times of India</a></i>. 18 January 2011. Archived from <a rel="nofollow" class="external text" href="http://articles.timesofindia.indiatimes.com/2011-01-18/ahmedabad/28352057_1_uav-squadron-unmanned-aerial-vehicle-squadron-western-coast">the original</a> on 4 November 2012<span class="reference-accessdate">. Retrieved <span class="nowrap">3 July</span> 2013</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Times+of+India&amp;rft.atitle=Eye+in+the+sky+to+guard+Gujarat+coast&amp;rft.date=2011-01-18&amp;rft_id=http%3A%2F%2Farticles.timesofindia.indiatimes.com%2F2011-01-18%2Fahmedabad%2F28352057_1_uav-squadron-unmanned-aerial-vehicle-squadron-western-coast&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-74"><span class="mw-cite-backlink"><b><a href="#cite_ref-74">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="http://us.rediff.com/news/2006/jan/06uav.htm?q=np&amp;file=.htm">"Indian Navy commissions first UAV squadron"</a>. Us.rediff.com<span class="reference-accessdate">. Retrieved <span class="nowrap">18 November</span> 2012</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=Indian+Navy+commissions+first+UAV+squadron&amp;rft.pub=Us.rediff.com&amp;rft_id=http%3A%2F%2Fus.rediff.com%2Fnews%2F2006%2Fjan%2F06uav.htm%3Fq%3Dnp%26file%3D.htm&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-75"><span class="mw-cite-backlink"><b><a href="#cite_ref-75">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFPeri2020" class="citation news cs1">Peri, Dinakar (25 November 2020). <a rel="nofollow" class="external text" href="https://www.thehindu.com/news/national/navy-inducts-two-sea-guardian-drones-on-lease-from-us/article33178519.ece">"Navy inducts two Sea Guardian drones on lease from U.S."</a> <i>The Hindu</i>. <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/0971-751X">0971-751X</a><span class="reference-accessdate">. Retrieved <span class="nowrap">30 November</span> 2020</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Hindu&amp;rft.atitle=Navy+inducts+two+Sea+Guardian+drones+on+lease+from+U.S.&amp;rft.date=2020-11-25&amp;rft.issn=0971-751X&amp;rft.aulast=Peri&amp;rft.aufirst=Dinakar&amp;rft_id=https%3A%2F%2Fwww.thehindu.com%2Fnews%2Fnational%2Fnavy-inducts-two-sea-guardian-drones-on-lease-from-us%2Farticle33178519.ece&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:6-76"><span class="mw-cite-backlink"><b><a href="#cite_ref-:6_76-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.hindustantimes.com/india-news/india-first-indigenously-manufactured-uav-drishti-10-starliner-flagged-off-101704866050985.html">"India's first indigenously manufactured UAV 'Drishti 10 Starliner' flagged off"</a>. <i>Hindustan Times</i>. 10 January 2024<span class="reference-accessdate">. Retrieved <span class="nowrap">10 January</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Hindustan+Times&amp;rft.atitle=India%27s+first+indigenously+manufactured+UAV+%27Drishti+10+Starliner%27+flagged+off&amp;rft.date=2024-01-10&amp;rft_id=https%3A%2F%2Fwww.hindustantimes.com%2Findia-news%2Findia-first-indigenously-manufactured-uav-drishti-10-starliner-flagged-off-101704866050985.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-77"><span class="mw-cite-backlink"><b><a href="#cite_ref-77">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.indiatoday.in/india/story/navy-gets-first-india-made-long-endurance-starliner-drone-2486731-2024-01-10">"Navy gets first India-made long endurance Drishti 10 Starliner drone"</a>. <i>India Today</i><span class="reference-accessdate">. Retrieved <span class="nowrap">10 January</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=India+Today&amp;rft.atitle=Navy+gets+first+India-made+long+endurance+Drishti+10+Starliner+drone&amp;rft_id=https%3A%2F%2Fwww.indiatoday.in%2Findia%2Fstory%2Fnavy-gets-first-india-made-long-endurance-starliner-drone-2486731-2024-01-10&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-thestatesman.com-78"><span class="mw-cite-backlink"><b><a href="#cite_ref-thestatesman.com_78-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://www.thestatesman.com/northeast/indian-coast-guard-to-induct-16-advanced-light-helicopters-2-of-them-for-north-east-1502742438.html">"Indian Coast Guard to induct 16 Advanced Light Helicopters in July, 2 of them for North-East"</a>. <i><a href="/wiki/The_Statesman_(India)" title="The Statesman (India)">The Statesman</a></i>. 2 April 2019.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Statesman&amp;rft.atitle=Indian+Coast+Guard+to+induct+16+Advanced+Light+Helicopters+in+July%2C+2+of+them+for+North-East&amp;rft.date=2019-04-02&amp;rft_id=https%3A%2F%2Fwww.thestatesman.com%2Fnortheast%2Findian-coast-guard-to-induct-16-advanced-light-helicopters-2-of-them-for-north-east-1502742438.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-79"><span class="mw-cite-backlink"><b><a href="#cite_ref-79">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-indian-coast-guard-to-get-dornier-aircraft-from-hal-3160424/">"Indian Coast Guard to get Dornier aircraft from HAL"</a>. 7 July 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">8 July</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.atitle=Indian+Coast+Guard+to+get+Dornier+aircraft+from+HAL&amp;rft.date=2023-07-07&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-indian-coast-guard-to-get-dornier-aircraft-from-hal-3160424%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-80"><span class="mw-cite-backlink"><b><a href="#cite_ref-80">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.ndtv.com/india-news/army-clears-grounded-dhruv-chopper-fleet-for-flight-but-conditions-apply-4080889">"Army Clears Grounded 'Dhruv' Chopper Fleet For Flight, But Conditions Apply"</a>. <i>NDTV.com</i><span class="reference-accessdate">. Retrieved <span class="nowrap">13 August</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=NDTV.com&amp;rft.atitle=Army+Clears+Grounded+%27Dhruv%27+Chopper+Fleet+For+Flight%2C+But+Conditions+Apply&amp;rft_id=https%3A%2F%2Fwww.ndtv.com%2Findia-news%2Farmy-clears-grounded-dhruv-chopper-fleet-for-flight-but-conditions-apply-4080889&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-81"><span class="mw-cite-backlink"><b><a href="#cite_ref-81">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.pib.gov.in/PressReleasePage.aspx?PRID=1880134">"Indian Coast Guard Advanced Light Helicopter Mk-III squadron, 840 Sqn (CG), commissioned in Chennai"</a>. <i>www.pib.gov.in</i><span class="reference-accessdate">. Retrieved <span class="nowrap">13 August</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=www.pib.gov.in&amp;rft.atitle=Indian+Coast+Guard+Advanced+Light+Helicopter+Mk-III+squadron%2C+840+Sqn+%28CG%29%2C+commissioned+in+Chennai&amp;rft_id=https%3A%2F%2Fwww.pib.gov.in%2FPressReleasePage.aspx%3FPRID%3D1880134&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-82"><span class="mw-cite-backlink"><b><a href="#cite_ref-82">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://www.thehindu.com/news/national/indian-coast-guard-looks-for-new-helicopters-rotary-unmanned-aerial-vehicles/article66187739.ece">"Indian Coast Guard looks for new helicopters, rotary Unmanned Aerial Vehicles"</a>. <i>The Hindu</i>. 26 November 2022. <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/0971-751X">0971-751X</a><span class="reference-accessdate">. Retrieved <span class="nowrap">13 August</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Hindu&amp;rft.atitle=Indian+Coast+Guard+looks+for+new+helicopters%2C+rotary+Unmanned+Aerial+Vehicles&amp;rft.date=2022-11-26&amp;rft.issn=0971-751X&amp;rft_id=https%3A%2F%2Fwww.thehindu.com%2Fnews%2Fnational%2Findian-coast-guard-looks-for-new-helicopters-rotary-unmanned-aerial-vehicles%2Farticle66187739.ece&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:022-83"><span class="mw-cite-backlink"><b><a href="#cite_ref-:022_83-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.reuters.com/business/aerospace-defense/indias-defence-ministry-signs-deals-worth-975-mln-indigenous-helicopters-2024-03-13/">"India's defence ministry signs deals worth $975 mln for indigenous helicopters"</a>. <i><a href="/wiki/Reuters" title="Reuters">Reuters</a></i>. 13 March 2024.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Reuters&amp;rft.atitle=India%27s+defence+ministry+signs+deals+worth+%24975+mln+for+indigenous+helicopters&amp;rft.date=2024-03-13&amp;rft_id=https%3A%2F%2Fwww.reuters.com%2Fbusiness%2Faerospace-defense%2Findias-defence-ministry-signs-deals-worth-975-mln-indigenous-helicopters-2024-03-13%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-84"><span class="mw-cite-backlink"><b><a href="#cite_ref-84">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://economictimes.indiatimes.com/news/defence/cabinet-committee-on-security-clears-34-new-dhruv-choppers-for-indian-coast-guard-army/articleshow/108306276.cms?from=mdr">"Cabinet Committee on Security clears 34 new Dhruv choppers for Indian Coast Guard, Army"</a>. <i>The Economic Times</i>. 7 March 2024. <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/0013-0389">0013-0389</a><span class="reference-accessdate">. Retrieved <span class="nowrap">8 March</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Economic+Times&amp;rft.atitle=Cabinet+Committee+on+Security+clears+34+new+Dhruv+choppers+for+Indian+Coast+Guard%2C+Army&amp;rft.date=2024-03-07&amp;rft.issn=0013-0389&amp;rft_id=https%3A%2F%2Feconomictimes.indiatimes.com%2Fnews%2Fdefence%2Fcabinet-committee-on-security-clears-34-new-dhruv-choppers-for-indian-coast-guard-army%2Farticleshow%2F108306276.cms%3Ffrom%3Dmdr&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:0-85"><span class="mw-cite-backlink"><b><a href="#cite_ref-:0_85-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.iiss.org/publications/the-military-balance/">"The Military Balance 2023"</a>. <a href="/wiki/International_Institute_for_Strategic_Studies" title="International Institute for Strategic Studies">International Institute for Strategic Studies</a>. p.&#160;252<span class="reference-accessdate">. Retrieved <span class="nowrap">27 December</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=The+Military+Balance+2023&amp;rft.pages=252&amp;rft.pub=International+Institute+for+Strategic+Studies&amp;rft_id=https%3A%2F%2Fwww.iiss.org%2Fpublications%2Fthe-military-balance%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    </ol></div>
    <div class="mw-heading mw-heading2"><h2 id="External_links">External links</h2></div>
    <ul><li><a rel="nofollow" class="external text" href="http://indianairforce.nic.in/show_unit_page.php?pg_id=23&amp;cat=F">The Official Home Page of Indian Air Force.</a></li></ul>
    <div class="navbox-styles"><style data-mw-deduplicate="TemplateStyles:r1129693374">.mw-parser-output .hlist dl,.mw-parser-output .hlist ol,.mw-parser-output .hlist ul{margin:0;padding:0}.mw-parser-output .hlist dd,.mw-parser-output .hlist dt,.mw-parser-output .hlist li{margin:0;display:inline}.mw-parser-output .hlist.inline,.mw-parser-output .hlist.inline dl,.mw-parser-output .hlist.inline ol,.mw-parser-output .hlist.inline ul,.mw-parser-output .hlist dl dl,.mw-parser-output .hlist dl ol,.mw-parser-output .hlist dl ul,.mw-parser-output .hlist ol dl,.mw-parser-output .hlist ol ol,.mw-parser-output .hlist ol ul,.mw-parser-output .hlist ul dl,.mw-parser-output .hlist ul ol,.mw-parser-output .hlist ul ul{display:inline}.mw-parser-output .hlist .mw-empty-li{display:none}.mw-parser-output .hlist dt::after{content:": "}.mw-parser-output .hlist dd::after,.mw-parser-output .hlist li::after{content:" · ";font-weight:bold}.mw-parser-output .hlist dd:last-child::after,.mw-parser-output .hlist dt:last-child::after,.mw-parser-output .hlist li:last-child::after{content:none}.mw-parser-output .hlist dd dd:first-child::before,.mw-parser-output .hlist dd dt:first-child::before,.mw-parser-output .hlist dd li:first-child::before,.mw-parser-output .hlist dt dd:first-child::before,.mw-parser-output .hlist dt dt:first-child::before,.mw-parser-output .hlist dt li:first-child::before,.mw-parser-output .hlist li dd:first-child::before,.mw-parser-output .hlist li dt:first-child::before,.mw-parser-output .hlist li li:first-child::before{content:" (";font-weight:normal}.mw-parser-output .hlist dd dd:last-child::after,.mw-parser-output .hlist dd dt:last-child::after,.mw-parser-output .hlist dd li:last-child::after,.mw-parser-output .hlist dt dd:last-child::after,.mw-parser-output .hlist dt dt:last-child::after,.mw-parser-output .hlist dt li:last-child::after,.mw-parser-output .hlist li dd:last-child::after,.mw-parser-output .hlist li dt:last-child::after,.mw-parser-output .hlist li li:last-child::after{content:")";font-weight:normal}.mw-parser-output .hlist ol{counter-reset:listitem}.mw-parser-output .hlist ol>li{counter-increment:listitem}.mw-parser-output .hlist ol>li::before{content:" "counter(listitem)"\a0 "}.mw-parser-output .hlist dd ol>li:first-child::before,.mw-parser-output .hlist dt ol>li:first-child::before,.mw-parser-output .hlist li ol>li:first-child::before{content:" ("counter(listitem)"\a0 "}</style><style data-mw-deduplicate="TemplateStyles:r1236075235">.mw-parser-output .navbox{box-sizing:border-box;border:1px solid #a2a9b1;width:100%;clear:both;font-size:88%;text-align:center;padding:1px;margin:1em auto 0}.mw-parser-output .navbox .navbox{margin-top:0}.mw-parser-output .navbox+.navbox,.mw-parser-output .navbox+.navbox-styles+.navbox{margin-top:-1px}.mw-parser-output .navbox-inner,.mw-parser-output .navbox-subgroup{width:100%}.mw-parser-output .navbox-group,.mw-parser-output .navbox-title,.mw-parser-output .navbox-abovebelow{padding:0.25em 1em;line-height:1.5em;text-align:center}.mw-parser-output .navbox-group{white-space:nowrap;text-align:right}.mw-parser-output .navbox,.mw-parser-output .navbox-subgroup{background-color:#fdfdfd}.mw-parser-output .navbox-list{line-height:1.5em;border-color:#fdfdfd}.mw-parser-output .navbox-list-with-group{text-align:left;border-left-width:2px;border-left-style:solid}.mw-parser-output tr+tr>.navbox-abovebelow,.mw-parser-output tr+tr>.navbox-group,.mw-parser-output tr+tr>.navbox-image,.mw-parser-output tr+tr>.navbox-list{border-top:2px solid #fdfdfd}.mw-parser-output .navbox-title{background-color:#ccf}.mw-parser-output .navbox-abovebelow,.mw-parser-output .navbox-group,.mw-parser-output .navbox-subgroup .navbox-title{background-color:#ddf}.mw-parser-output .navbox-subgroup .navbox-group,.mw-parser-output .navbox-subgroup .navbox-abovebelow{background-color:#e6e6ff}.mw-parser-output .navbox-even{background-color:#f7f7f7}.mw-parser-output .navbox-odd{background-color:transparent}.mw-parser-output .navbox .hlist td dl,.mw-parser-output .navbox .hlist td ol,.mw-parser-output .navbox .hlist td ul,.mw-parser-output .navbox td.hlist dl,.mw-parser-output .navbox td.hlist ol,.mw-parser-output .navbox td.hlist ul{padding:0.125em 0}.mw-parser-output .navbox .navbar{display:block;font-size:100%}.mw-parser-output .navbox-title .navbar{float:left;text-align:left;margin-right:0.5em}body.skin--responsive .mw-parser-output .navbox-image img{max-width:none!important}@media print{body.ns-0 .mw-parser-output .navbox{display:none!important}}</style></div><div role="navigation" class="navbox" aria-labelledby="18px_Indian_Armed_Forces" style=";wide;padding:3px"><table class="nowraplinks hlist mw-collapsible mw-collapsed navbox-inner" style="border-spacing:0;background:transparent;color:inherit"><tbody><tr><th scope="col" class="navbox-title" colspan="2" style="background-color:#C3D6EF;color:inherit;"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1129693374"><style data-mw-deduplicate="TemplateStyles:r1239400231">.mw-parser-output .navbar{display:inline;font-size:88%;font-weight:normal}.mw-parser-output .navbar-collapse{float:left;text-align:left}.mw-parser-output .navbar-boxtext{word-spacing:0}.mw-parser-output .navbar ul{display:inline-block;white-space:nowrap;line-height:inherit}.mw-parser-output .navbar-brackets::before{margin-right:-0.125em;content:"[ "}.mw-parser-output .navbar-brackets::after{margin-left:-0.125em;content:" ]"}.mw-parser-output .navbar li{word-spacing:-0.125em}.mw-parser-output .navbar a>span,.mw-parser-output .navbar a>abbr{text-decoration:inherit}.mw-parser-output .navbar-mini abbr{font-variant:small-caps;border-bottom:none;text-decoration:none;cursor:inherit}.mw-parser-output .navbar-ct-full{font-size:114%;margin:0 7em}.mw-parser-output .navbar-ct-mini{font-size:114%;margin:0 4em}html.skin-theme-clientpref-night .mw-parser-output .navbar li a abbr{color:var(--color-base)!important}@media(prefers-color-scheme:dark){html.skin-theme-clientpref-os .mw-parser-output .navbar li a abbr{color:var(--color-base)!important}}@media print{.mw-parser-output .navbar{display:none!important}}</style><div class="navbar plainlinks hlist navbar-mini"><ul><li class="nv-view"><a href="/wiki/Template:Military_of_India" title="Template:Military of India"><abbr title="View this template" style="color:inherit">v</abbr></a></li><li class="nv-talk"><a href="/wiki/Template_talk:Military_of_India" title="Template talk:Military of India"><abbr title="Discuss this template" style="color:inherit">t</abbr></a></li><li class="nv-edit"><a href="/wiki/Special:EditPage/Template:Military_of_India" title="Special:EditPage/Template:Military of India"><abbr title="Edit this template" style="color:inherit">e</abbr></a></li></ul></div><div id="18px_Indian_Armed_Forces" style="font-size:114%;margin:0 4em"><span typeof="mw:File"><a href="/wiki/File:Indian_Armed_Forces.svg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/4/4a/Indian_Armed_Forces.svg/18px-Indian_Armed_Forces.svg.png" decoding="async" width="18" height="12" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/4/4a/Indian_Armed_Forces.svg/27px-Indian_Armed_Forces.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/4/4a/Indian_Armed_Forces.svg/36px-Indian_Armed_Forces.svg.png 2x" data-file-width="900" data-file-height="600" /></a></span> <a href="/wiki/Indian_Armed_Forces" title="Indian Armed Forces">Indian Armed Forces</a></div></th></tr><tr><td class="navbox-abovebelow" colspan="2" style="background-color:#DCDCDC;color:inherit;"><div>
    <ul><li><span class="flagicon"><span class="mw-image-border" typeof="mw:File"><span><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/e/ea/Flag_of_Indian_Army.svg/23px-Flag_of_Indian_Army.svg.png" decoding="async" width="23" height="12" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/e/ea/Flag_of_Indian_Army.svg/35px-Flag_of_Indian_Army.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/e/ea/Flag_of_Indian_Army.svg/46px-Flag_of_Indian_Army.svg.png 2x" data-file-width="900" data-file-height="450" /></span></span>&#160;</span><a href="/wiki/Indian_Army" title="Indian Army">Indian Army</a></li>
    <li><span class="flagicon"><span class="mw-image-border" typeof="mw:File"><span><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/3/35/Naval_Ensign_of_India.svg/23px-Naval_Ensign_of_India.svg.png" decoding="async" width="23" height="12" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/3/35/Naval_Ensign_of_India.svg/35px-Naval_Ensign_of_India.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/3/35/Naval_Ensign_of_India.svg/46px-Naval_Ensign_of_India.svg.png 2x" data-file-width="1200" data-file-height="600" /></span></span>&#160;</span><a href="/wiki/Indian_Navy" title="Indian Navy">Indian Navy</a></li>
    <li><span class="flagicon"><span class="mw-image-border" typeof="mw:File"><span><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/8/8e/Air_Force_Ensign_of_India.svg/23px-Air_Force_Ensign_of_India.svg.png" decoding="async" width="23" height="12" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/8/8e/Air_Force_Ensign_of_India.svg/35px-Air_Force_Ensign_of_India.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/8/8e/Air_Force_Ensign_of_India.svg/46px-Air_Force_Ensign_of_India.svg.png 2x" data-file-width="1200" data-file-height="600" /></span></span>&#160;</span><a href="/wiki/Indian_Air_Force" title="Indian Air Force">Indian Air Force</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Leadership</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/President_of_India" title="President of India">President</a></li>
    <li><a href="/wiki/Prime_Minister_of_India" title="Prime Minister of India">Prime Minister</a></li>
    <li><a href="/wiki/Minister_of_Defence_(India)" title="Minister of Defence (India)">Minister of Defence</a></li>
    <li><a href="/wiki/Defence_Secretary_(India)" title="Defence Secretary (India)">Defence Secretary</a></li>
    <li><a href="/wiki/National_Security_Advisor_(India)" title="National Security Advisor (India)">National Security Advisor</a></li>
    <li><a href="/wiki/Chief_of_Defence_Staff_(India)" title="Chief of Defence Staff (India)">Chief of Defence Staff</a> (<a href="/wiki/Chairman_Chiefs_of_Staff_Committee" class="mw-redirect" title="Chairman Chiefs of Staff Committee">Chairman Chiefs of Staff Committee</a>)</li>
    <li><a href="/wiki/Chief_of_the_Army_Staff_(India)" title="Chief of the Army Staff (India)">Chief of the Army Staff</a></li>
    <li><a href="/wiki/Chief_of_the_Naval_Staff_(India)" title="Chief of the Naval Staff (India)">Chief of the Naval Staff</a></li>
    <li><a href="/wiki/Chief_of_the_Air_Staff_(India)" title="Chief of the Air Staff (India)">Chief of the Air Staff</a></li>
    <li><a href="/wiki/Chief_of_Integrated_Defence_Staff" title="Chief of Integrated Defence Staff">Vice Chief of Defence Staff</a></li>
    <li><a href="/wiki/Director_General_Armed_Forces_Medical_Services_(India)" title="Director General Armed Forces Medical Services (India)">Director General Armed Forces Medical Services</a></li>
    <li><a href="/wiki/List_of_serving_generals_of_the_Indian_Army" title="List of serving generals of the Indian Army">Serving generals</a></li>
    <li><a href="/wiki/List_of_serving_admirals_of_the_Indian_Navy" title="List of serving admirals of the Indian Navy">Serving admirals</a></li>
    <li><a href="/wiki/List_of_serving_marshals_of_the_Indian_Air_Force" title="List of serving marshals of the Indian Air Force">Serving marshals</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Organisation</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks navbox-subgroup" style="border-spacing:0;;wide"><tbody><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Ministry and<br />committees/councils</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Ministry_of_Defence_(India)" title="Ministry of Defence (India)">Ministry of Defence</a>
    <ul><li><a href="/wiki/Department_of_Military_Affairs" title="Department of Military Affairs">Department of Military Affairs</a></li>
    <li><a href="/wiki/Defence_Research_and_Development_Organisation" title="Defence Research and Development Organisation">Department of Defence Research and Development</a></li>
    <li><a href="/wiki/Department_of_Ex-servicemen_Welfare" title="Department of Ex-servicemen Welfare">Department of Ex-servicemen Welfare</a></li></ul></li>
    <li><a href="/wiki/National_Security_Council_(India)" title="National Security Council (India)">National Security Council</a></li>
    <li><a href="/wiki/Cabinet_Committee_on_Security" title="Cabinet Committee on Security">Cabinet Committee on Security</a></li>
    <li><a href="/wiki/Standing_Committee_on_Defence_(India)" title="Standing Committee on Defence (India)">Standing Committee on Defence</a></li>
    <li><a href="/wiki/Defence_Planning_Committee" title="Defence Planning Committee">Defence Planning Committee</a></li>
    <li><a href="/wiki/Nuclear_Command_Authority_(India)" title="Nuclear Command Authority (India)">Nuclear Command Authority</a></li>
    <li><a href="/wiki/Integrated_Defence_Staff" title="Integrated Defence Staff">Integrated Defence Staff</a></li>
    <li><a href="/wiki/Defence_Intelligence_Agency_(India)" title="Defence Intelligence Agency (India)">Defence Intelligence Agency</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Commands</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks navbox-subgroup" style="border-spacing:0;;wide"><tbody><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;"><a href="/wiki/Joint_warfare" title="Joint warfare">Joint</a></th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Indian_Armed_Forces_Tri-Service_Commands" class="mw-redirect" title="Indian Armed Forces Tri-Service Commands">Integrated Theatre Commands</a></li>
    <li><a href="/wiki/Andaman_and_Nicobar_Command" title="Andaman and Nicobar Command">Andaman and Nicobar Command</a>
    <ul><li><a href="/wiki/Commander-in-Chief,_Andaman_and_Nicobar_Command" title="Commander-in-Chief, Andaman and Nicobar Command">Commander-in-Chief</a></li></ul></li>
    <li><a href="/wiki/Strategic_Forces_Command" title="Strategic Forces Command">Strategic Forces Command</a>
    <ul><li><a href="/wiki/Commander-in-Chief,_Strategic_Forces_Command" title="Commander-in-Chief, Strategic Forces Command">Commander-in-Chief</a></li></ul></li>
    <li><a href="/wiki/Northern_Theatre_Command_(India)" title="Northern Theatre Command (India)">Northern Theatre Command (India)</a></li>
    <li><a href="/wiki/Western_Theatre_Command_(India)" title="Western Theatre Command (India)">Western Theatre Command (India)</a></li>
    <li><a href="/wiki/Maritime_Theatre_Command" title="Maritime Theatre Command">Maritime Theatre Command</a></li>
    <li><a href="/wiki/Defence_Cyber_Agency" title="Defence Cyber Agency">Defence Cyber Agency</a></li>
    <li><a href="/wiki/Defence_Space_Agency" title="Defence Space Agency">Defence Space Agency</a></li>
    <li><a href="/wiki/Armed_Forces_Special_Operations_Division" title="Armed Forces Special Operations Division">Armed Forces Special Operations Division</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;"><a href="/wiki/Indian_Army" title="Indian Army">Army</a></th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Central_Command_(India)" title="Central Command (India)">Central Command</a></li>
    <li><a href="/wiki/Eastern_Command_(India)" title="Eastern Command (India)">Eastern Command</a></li>
    <li><a href="/wiki/Northern_Command_(India)" title="Northern Command (India)">Northern Command</a></li>
    <li><a href="/wiki/Southern_Command_(India)" title="Southern Command (India)">Southern Command</a></li>
    <li><a href="/wiki/South_Western_Command_(India)" title="South Western Command (India)">South Western Command</a></li>
    <li><a href="/wiki/Western_Command_(India)" title="Western Command (India)">Western Command</a></li>
    <li><a href="/wiki/Army_Training_Command" title="Army Training Command">Army Training Command</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;"><a href="/wiki/Indian_Navy" title="Indian Navy">Navy</a></th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Western_Naval_Command" title="Western Naval Command">Western Naval Command</a></li>
    <li><a href="/wiki/Eastern_Naval_Command" title="Eastern Naval Command">Eastern Naval Command</a></li>
    <li><a href="/wiki/Southern_Naval_Command" title="Southern Naval Command">Southern Naval Command</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;"><a href="/wiki/Indian_Air_Force" title="Indian Air Force">Air Force</a></th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Central_Air_Command_(India)" title="Central Air Command (India)">Central Air Command</a></li>
    <li><a href="/wiki/Eastern_Air_Command_(India)" title="Eastern Air Command (India)">Eastern Air Command</a></li>
    <li><a href="/wiki/Southern_Air_Command_(India)" title="Southern Air Command (India)">Southern Air Command</a></li>
    <li><a href="/wiki/South_Western_Air_Command" title="South Western Air Command">South Western Air Command</a></li>
    <li><a href="/wiki/Western_Air_Command_(India)" title="Western Air Command (India)">Western Air Command</a></li>
    <li><a href="/wiki/Training_Command_(India)" title="Training Command (India)">Training Command</a></li>
    <li><a href="/wiki/Maintenance_Command" title="Maintenance Command">Maintenance Command</a></li></ul>
    </div></td></tr></tbody></table><div></div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Other components</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Indian_Coast_Guard" title="Indian Coast Guard">Indian Coast Guard</a></li>
    <li><a href="/wiki/National_Cadet_Corps_(India)" title="National Cadet Corps (India)">National Cadet Corps</a></li>
    <li><a href="/wiki/Paramilitary_forces_of_India" title="Paramilitary forces of India">Paramilitary forces</a></li>
    <li><a href="/wiki/Special_forces_of_India" title="Special forces of India">Special forces</a></li>
    <li><a href="/wiki/Territorial_Army_(India)" title="Territorial Army (India)">Territorial Army</a></li>
    <li><a href="/wiki/Border_Roads_Organisation" title="Border Roads Organisation">Border Roads Organisation</a></li></ul>
    </div></td></tr></tbody></table><div></div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Personnel</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Military_academies_in_India" title="Military academies in India">Military Academies</a></li>
    <li>Ranks and insignia
    <ul><li><a href="/wiki/Army_ranks_and_insignia_of_India" class="mw-redirect" title="Army ranks and insignia of India">Army</a></li>
    <li><a href="/wiki/Naval_ranks_and_insignia_of_India" class="mw-redirect" title="Naval ranks and insignia of India">Navy</a></li>
    <li><a href="/wiki/Air_Force_ranks_and_insignia_of_India" class="mw-redirect" title="Air Force ranks and insignia of India">Air Force</a></li>
    <li><a href="/wiki/Indian_Coast_Guard#Rank_insignia" title="Indian Coast Guard">Coast Guard</a></li>
    <li><a href="/wiki/Border_Roads_Organisation#Ranks" title="Border Roads Organisation">Border Roads Organisation</a></li>
    <li><a href="/wiki/Paramilitary_forces_of_India#Ranks_and_insignia" title="Paramilitary forces of India">Paramilitary forces</a></li></ul></li>
    <li><a href="/wiki/Awards_and_decorations_of_the_Indian_Armed_Forces" title="Awards and decorations of the Indian Armed Forces">Awards and Decorations</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;"><a href="/wiki/List_of_military_operations_of_India" title="List of military operations of India">Operations</a></th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks navbox-subgroup" style="border-spacing:0;;wide"><tbody><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Wars</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Indo-Pakistani_wars_and_conflicts" title="Indo-Pakistani wars and conflicts">Indo-Pakistani wars</a>
    <ul><li><a href="/wiki/Indo-Pakistani_War_of_1947%E2%80%931948" class="mw-redirect" title="Indo-Pakistani War of 1947–1948">1947–1948</a></li>
    <li><a href="/wiki/Indo-Pakistani_War_of_1965" class="mw-redirect" title="Indo-Pakistani War of 1965">1965</a>
    <ul><li><a href="/wiki/Battle_of_Asal_Uttar" title="Battle of Asal Uttar">Battle of Asal Uttar</a></li>
    <li><a href="/wiki/Battle_of_Chawinda" title="Battle of Chawinda">Battle of Chawinda</a></li></ul></li>
    <li><a href="/wiki/Indo-Pakistani_War_of_1971" class="mw-redirect" title="Indo-Pakistani War of 1971">1971</a>
    <ul><li><a href="/wiki/Indo-Pakistani_Naval_War_of_1971" title="Indo-Pakistani Naval War of 1971">Naval War</a></li>
    <li><a href="/wiki/East_Pakistan_Air_Operations_(1971)" title="East Pakistan Air Operations (1971)">Air War</a></li>
    <li><a href="/wiki/Battle_of_Chamb" class="mw-redirect" title="Battle of Chamb">Battle of Chamb</a></li>
    <li><a href="/wiki/Operation_Trident_(1971)" title="Operation Trident (1971)">Operation <i>Trident</i></a></li>
    <li><a href="/wiki/Operation_Cactus-Lilly" class="mw-redirect" title="Operation Cactus-Lilly">Operation <i>Cactus-Lilly</i></a></li>
    <li><a href="/wiki/Battle_of_Longewala" title="Battle of Longewala">Battle of Longewala</a></li></ul></li>
    <li><a href="/wiki/Kargil_War" title="Kargil War">Kargil War</a></li></ul></li>
    <li><a href="/wiki/Sino-Indian_War" title="Sino-Indian War">Sino-Indian War</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">External <br />conflicts</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Kashmir_conflict" title="Kashmir conflict">Kashmir conflict</a></li>
    <li><a href="/wiki/Korean_War" title="Korean War">Korean War</a></li>
    <li><a href="/wiki/Siachen_conflict" title="Siachen conflict">Siachen conflict</a></li>
    <li><a href="/wiki/Line_of_Control" title="Line of Control">Indo-Pakistani border skirmishes</a>
    <ul><li><a href="/wiki/2001%E2%80%932002_India%E2%80%93Pakistan_standoff" title="2001–2002 India–Pakistan standoff">Operation <i>Parakram</i></a></li>
    <li><a href="/wiki/2011_India%E2%80%93Pakistan_border_skirmish" title="2011 India–Pakistan border skirmish">2011</a></li>
    <li><a href="/wiki/2013_India%E2%80%93Pakistan_border_skirmishes" title="2013 India–Pakistan border skirmishes">2013</a></li>
    <li><a href="/wiki/2014%E2%80%932015_India%E2%80%93Pakistan_border_skirmishes" title="2014–2015 India–Pakistan border skirmishes">2014–2015</a></li>
    <li><a href="/wiki/2016%E2%80%932018_India%E2%80%93Pakistan_border_skirmishes" title="2016–2018 India–Pakistan border skirmishes">2016–2018</a></li>
    <li><a href="/wiki/2019_India%E2%80%93Pakistan_border_skirmishes" title="2019 India–Pakistan border skirmishes">2019</a>
    <ul><li><a href="/wiki/2019_Balakot_airstrike" title="2019 Balakot airstrike">Balakot airstrike</a></li></ul></li></ul></li>
    <li><a href="/wiki/Congo_Crisis" title="Congo Crisis">Congo Crisis</a></li>
    <li><a href="/wiki/Line_of_Actual_Control" title="Line of Actual Control">Sino-Indian border skirmish</a>
    <ul><li><a href="/wiki/Sumdorong_Chu_standoff" title="Sumdorong Chu standoff">1987</a></li>
    <li><a href="/wiki/Nathu_La_and_Cho_La_clashes" title="Nathu La and Cho La clashes">Nathu La and Cho La clashes</a></li>
    <li><a href="/wiki/2017_China%E2%80%93India_border_standoff" title="2017 China–India border standoff">Doklam standoff</a></li>
    <li><a href="/wiki/2020%E2%80%932021_China%E2%80%93India_skirmishes" title="2020–2021 China–India skirmishes">2020</a></li></ul></li>
    <li><a href="/wiki/Indian_intervention_in_the_Sri_Lankan_Civil_War" title="Indian intervention in the Sri Lankan Civil War">Indian intervention in the Sri Lankan Civil War</a></li>
    <li><a href="/wiki/1988_Maldives_coup_d%27%C3%A9tat_attempt" class="mw-redirect" title="1988 Maldives coup d&#39;état attempt">Operation <i>Cactus</i></a></li>
    <li><a href="/wiki/1990_airlift_of_Indians_from_Kuwait" title="1990 airlift of Indians from Kuwait">Evacuation of Indian civilians from Kuwait</a></li>
    <li><a href="/wiki/Piracy_off_the_coast_of_Somalia" title="Piracy off the coast of Somalia">Piracy off the coast of Somalia</a></li>
    <li><a href="/wiki/Operation_Raahat" title="Operation Raahat">Operation <i>Raahat</i></a></li>
    <li><a href="/wiki/Operation_Devi_Shakti" title="Operation Devi Shakti">Operation <i>Devi Shakti</i></a></li>
    <li><a href="/wiki/2015_Indian_counter-insurgency_operation_in_Myanmar" title="2015 Indian counter-insurgency operation in Myanmar">Indo-Myanmar border strike</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Annexations</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Annexation_of_Hyderabad" title="Annexation of Hyderabad">Operation <i>Polo</i> (Hyderabad)</a></li>
    <li><a href="/wiki/Annexation_of_Goa" title="Annexation of Goa">Operation <i>Vijay</i> (Portuguese India -  Goa, Damaon, Silvassa &amp; Diu)</a></li>
    <li><a href="/wiki/Annexation_of_Junagadh" title="Annexation of Junagadh">Junagadh</a></li>
    <li><a href="/wiki/Annexation_of_Dadra_and_Nagar_Haveli" title="Annexation of Dadra and Nagar Haveli">Dadra and Nagar Haveli</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Insurgencies</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Insurgency_in_Northeast_India" title="Insurgency in Northeast India">Northeast India</a></li>
    <li><a href="/wiki/Insurgency_in_Punjab" class="mw-redirect" title="Insurgency in Punjab">Punjab</a>
    <ul><li><a href="/wiki/Operation_Blue_Star" title="Operation Blue Star">Operation <i>Blue Star</i></a></li>
    <li><a href="/wiki/Operation_Woodrose" title="Operation Woodrose">Operation <i>Woodrose</i></a></li></ul></li>
    <li><a href="/wiki/Insurgency_in_Jammu_and_Kashmir" title="Insurgency in Jammu and Kashmir">Kashmir</a>
    <ul><li><a href="/wiki/Indian_Army_operations_in_Jammu_and_Kashmir" title="Indian Army operations in Jammu and Kashmir">Counter-insurgency operations</a></li>
    <li><a href="/wiki/2016_Indian_Line_of_Control_strike" title="2016 Indian Line of Control strike">LOC surgical strike</a></li></ul></li></ul>
    </div></td></tr></tbody></table><div></div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Equipment</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Defence_Research_and_Development_Organisation" title="Defence Research and Development Organisation">Defence Research and Development Organisation</a></li>
    <li><a href="/wiki/Ordnance_Factory_Board" class="mw-redirect" title="Ordnance Factory Board">Ordnance Factory Board</a></li>
    <li><a href="/wiki/List_of_Indian_military_missiles" title="List of Indian military missiles">Ballistic missiles</a></li>
    <li><a href="/wiki/India_and_weapons_of_mass_destruction" title="India and weapons of mass destruction">Weapons of mass destruction</a></li></ul>
    </div><table class="nowraplinks navbox-subgroup" style="border-spacing:0;;wide"><tbody><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Army</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_equipment_of_the_Indian_Army" title="List of equipment of the Indian Army">List of equipment of the Indian Army</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Navy</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_active_Indian_Navy_ships" title="List of active Indian Navy ships">Active Ships</a></li>
    <li><a href="/wiki/List_of_ships_of_the_Indian_Navy" title="List of ships of the Indian Navy">Historical Ships</a></li>
    <li><a href="/wiki/Weapon_systems_of_the_Indian_Navy" title="Weapon systems of the Indian Navy">Weapon Systems</a></li>
    <li><a href="/wiki/Future_of_the_Indian_Navy" title="Future of the Indian Navy">Future</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Air Force</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a class="mw-selflink selflink">Active Aircraft</a></li>
    <li><a href="/wiki/List_of_historical_aircraft_of_the_Indian_Air_Force" title="List of historical aircraft of the Indian Air Force">Historical Aircraft</a></li>
    <li><a href="/wiki/List_of_active_Indian_Air_Force_aircraft_squadrons" title="List of active Indian Air Force aircraft squadrons">Aircraft Squadrons</a></li>
    <li><a href="/wiki/Future_of_the_Indian_Air_Force" title="Future of the Indian Air Force">Future</a></li></ul>
    </div></td></tr></tbody></table><div>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Documents</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Ensuring_Secure_Seas:_Indian_Maritime_Security_Strategy" title="Ensuring Secure Seas: Indian Maritime Security Strategy">Indian Maritime Security Strategy</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Other topics</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/President%27s_fleet_review" title="President&#39;s fleet review">President's fleet review</a></li>
    <li><a href="/wiki/Military_history_of_India" title="Military history of India">History</a></li>
    <li><a href="/wiki/President%27s_Colour_Award" title="President&#39;s Colour Award">President's Colour Award</a></li>
    <li><a href="/wiki/Women_in_the_Indian_Armed_Forces" title="Women in the Indian Armed Forces">Women in the Indian Armed Forces</a></li>
    <li><a href="/wiki/Armed_Forces_Flag_Day" title="Armed Forces Flag Day">Armed Forces Flag Day</a></li>
    <li><a href="/wiki/Armed_Forces_Tribunal" title="Armed Forces Tribunal">Armed Forces Tribunal</a></li>
    <li><a href="/wiki/Indian_Armed_Forces_rank_flags" title="Indian Armed Forces rank flags">Indian Armed Forces rank flags</a></li>
    <li><a href="/wiki/Indian_military_bands" title="Indian military bands">Indian military bands</a></li>
    <li><a href="/wiki/National_War_Memorial_(India)" title="National War Memorial (India)">National War Memorial</a></li>
    <li><a href="/wiki/Amar_Jawan_Jyoti" title="Amar Jawan Jyoti">Amar Jawan Jyoti</a></li></ul>
    </div></td></tr><tr><td class="navbox-abovebelow" colspan="2" style="background-color:#DCDCDC;color:inherit;"><div>
    <ul><li><span class="noviewer" typeof="mw:File"><span title="Category"><img alt="" src="//upload.wikimedia.org/wikipedia/en/thumb/9/96/Symbol_category_class.svg/16px-Symbol_category_class.svg.png" decoding="async" width="16" height="16" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/en/thumb/9/96/Symbol_category_class.svg/23px-Symbol_category_class.svg.png 1.5x, //upload.wikimedia.org/wikipedia/en/thumb/9/96/Symbol_category_class.svg/31px-Symbol_category_class.svg.png 2x" data-file-width="180" data-file-height="185" /></span></span> <a href="/wiki/Category:Military_of_India" title="Category:Military of India">Category</a>
    <ul><li><a href="/wiki/Category:Indian_Army" title="Category:Indian Army">Army</a></li>
    <li><a href="/wiki/Category:Indian_Navy" title="Category:Indian Navy">Navy</a></li>
    <li><a href="/wiki/Category:Indian_Air_Force" title="Category:Indian Air Force">Air Force</a></li></ul></li></ul>
    </div></td></tr></tbody></table></div>
    <div class="navbox-styles"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1129693374"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1236075235"></div><div role="navigation" class="navbox" aria-labelledby="Lists_of_aircraft" style="padding:3px"><table class="nowraplinks mw-collapsible mw-collapsed navbox-inner" style="border-spacing:0;background:transparent;color:inherit"><tbody><tr><th scope="col" class="navbox-title" colspan="2"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1129693374"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1239400231"><div class="navbar plainlinks hlist navbar-mini"><ul><li class="nv-view"><a href="/wiki/Template:Lists_of_aircraft" title="Template:Lists of aircraft"><abbr title="View this template">v</abbr></a></li><li class="nv-talk"><a href="/wiki/Template_talk:Lists_of_aircraft" title="Template talk:Lists of aircraft"><abbr title="Discuss this template">t</abbr></a></li><li class="nv-edit"><a href="/wiki/Special:EditPage/Template:Lists_of_aircraft" title="Special:EditPage/Template:Lists of aircraft"><abbr title="Edit this template">e</abbr></a></li></ul></div><div id="Lists_of_aircraft" style="font-size:114%;margin:0 4em"><a href="/wiki/List_of_aircraft" title="List of aircraft">Lists of aircraft</a></div></th></tr><tr><td colspan="2" class="navbox-list navbox-odd hlist" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks mw-collapsible expanded navbox-subgroup" style="border-spacing:0"><tbody><tr><th scope="col" class="navbox-title" colspan="2"><div id="By_name" style="font-size:114%;margin:0 4em">By name</div></th></tr><tr><td colspan="2" class="navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_aircraft_(pre-1914)" title="List of aircraft (pre-1914)">pre-1914</a></li>
    <li><a href="/wiki/List_of_aircraft_(0-A)" class="mw-redirect" title="List of aircraft (0-A)">0-Ah</a></li>
    <li><a href="/wiki/List_of_aircraft_(Ai-Am)" class="mw-redirect" title="List of aircraft (Ai-Am)">Ai-Am</a></li>
    <li><a href="/wiki/List_of_aircraft_(An-Az)" class="mw-redirect" title="List of aircraft (An-Az)">An-Az</a></li>
    <li><a href="/wiki/List_of_aircraft_(B-Be)" class="mw-redirect" title="List of aircraft (B-Be)">B-Be</a></li>
    <li><a href="/wiki/List_of_aircraft_(Bf-Bo)" class="mw-redirect" title="List of aircraft (Bf-Bo)">Bf-Bo</a></li>
    <li><a href="/wiki/List_of_aircraft_(Br-Bz)" class="mw-redirect" title="List of aircraft (Br-Bz)">Br-Bz</a></li>
    <li><a href="/wiki/List_of_aircraft_(C-Ca)" class="mw-redirect" title="List of aircraft (C-Ca)">C-Ca</a></li>
    <li><a href="/wiki/List_of_aircraft_(Cd-Cn)" class="mw-redirect" title="List of aircraft (Cd-Cn)">Cd-Cn</a></li>
    <li><a href="/wiki/List_of_aircraft_(Co-Cz)" class="mw-redirect" title="List of aircraft (Co-Cz)">Co-Cz</a></li>
    <li><a href="/wiki/List_of_aircraft_(D)" class="mw-redirect" title="List of aircraft (D)">D</a></li>
    <li><a href="/wiki/List_of_aircraft_(E)" title="List of aircraft (E)">E</a></li>
    <li><a href="/wiki/List_of_aircraft_(F)" title="List of aircraft (F)">F</a></li>
    <li><a href="/wiki/List_of_aircraft_(G-Gn)" title="List of aircraft (G-Gn)">G-Gn</a></li>
    <li><a href="/wiki/List_of_aircraft_(Go-Gz)" title="List of aircraft (Go-Gz)">Go-Gz</a></li>
    <li><a href="/wiki/List_of_aircraft_(H)" class="mw-redirect" title="List of aircraft (H)">H</a></li>
    <li><a href="/wiki/List_of_aircraft_(I)" title="List of aircraft (I)">I</a></li>
    <li><a href="/wiki/List_of_aircraft_(J)" title="List of aircraft (J)">J</a></li>
    <li><a href="/wiki/List_of_aircraft_(K)" title="List of aircraft (K)">K</a></li>
    <li><a href="/wiki/List_of_aircraft_(La-Lh)" class="mw-redirect" title="List of aircraft (La-Lh)">La-Lh</a></li>
    <li><a href="/wiki/List_of_aircraft_(Li-Lz)" class="mw-redirect" title="List of aircraft (Li-Lz)">Li-Lz</a></li>
    <li><a href="/wiki/List_of_aircraft_(M)" class="mw-redirect" title="List of aircraft (M)">M</a></li>
    <li><a href="/wiki/List_of_aircraft_(N)" title="List of aircraft (N)">N</a></li>
    <li><a href="/wiki/List_of_aircraft_(O)" title="List of aircraft (O)">O</a></li>
    <li><a href="/wiki/List_of_aircraft_(P)" class="mw-redirect" title="List of aircraft (P)">P</a></li>
    <li><a href="/wiki/List_of_aircraft_(Q)" title="List of aircraft (Q)">Q</a></li>
    <li><a href="/wiki/List_of_aircraft_(R)" title="List of aircraft (R)">R</a></li>
    <li><a href="/wiki/List_of_aircraft_(S)" title="List of aircraft (S)">S</a></li>
    <li><a href="/wiki/List_of_aircraft_(T)" title="List of aircraft (T)">T</a></li>
    <li><a href="/wiki/List_of_aircraft_(U)" title="List of aircraft (U)">U</a></li>
    <li><a href="/wiki/List_of_aircraft_(V)" title="List of aircraft (V)">V</a></li>
    <li><a href="/wiki/List_of_aircraft_(W)" title="List of aircraft (W)">W</a></li>
    <li><a href="/wiki/List_of_aircraft_(X)" title="List of aircraft (X)">X</a></li>
    <li><a href="/wiki/List_of_aircraft_(Y)" title="List of aircraft (Y)">Y</a></li>
    <li><a href="/wiki/List_of_aircraft_(Z)" title="List of aircraft (Z)">Z</a></li>
    <li><a href="/wiki/List_of_gliders" title="List of gliders">Gliders</a></li>
    <li><a href="/wiki/List_of_human-powered_aircraft" title="List of human-powered aircraft">List</a> of <a href="/wiki/Human-powered_aircraft" title="Human-powered aircraft">human-powered aircraft</a></li>
    <li><a href="/wiki/List_of_unmanned_aerial_vehicles" title="List of unmanned aerial vehicles">List</a> of <a href="/wiki/Unmanned_aerial_vehicle" title="Unmanned aerial vehicle">unmanned aerial vehicle</a></li></ul>
    </div></td></tr></tbody></table><div></div></td></tr><tr><td colspan="2" class="navbox-list navbox-odd hlist" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks mw-collapsible mw-collapsed navbox-subgroup" style="border-spacing:0"><tbody><tr><th scope="col" class="navbox-title" colspan="2"><div id="Civil_aircraft" style="font-size:114%;margin:0 4em"><a href="/wiki/List_of_civil_aircraft" title="List of civil aircraft">Civil aircraft</a></div></th></tr><tr><td colspan="2" class="navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks navbox-subgroup" style="border-spacing:0"><tbody><tr><td colspan="2" class="navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks mw-collapsible mw-collapsed navbox-subgroup" style="border-spacing:0"><tbody><tr><th scope="col" class="navbox-title" colspan="2" style="font-size:95%;"><div id="By_characteristic" style="font-size:114%;margin:0 4em">By characteristic</div></th></tr><tr><td colspan="2" class="navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks navbox-subgroup" style="border-spacing:0"><tbody><tr><th scope="row" class="navbox-group" style="width:1%">Type</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_aerobatic_aircraft" title="List of aerobatic aircraft">Aerobatic</a></li>
    <li><a href="/wiki/Bush_plane" title="Bush plane">Bush planes</a></li>
    <li><a href="/wiki/List_of_electric_aircraft" title="List of electric aircraft">Electric aircraft</a></li>
    <li><a href="/wiki/List_of_flying_wings" title="List of flying wings">Flying wings</a></li>
    <li><a href="/wiki/List_of_gliders" title="List of gliders">Gliders</a></li>
    <li><a href="/wiki/List_of_human-powered_aircraft" title="List of human-powered aircraft">Human-powered</a></li>
    <li><a href="/wiki/Prone_pilot#List_of_prone-pilot_aircraft" title="Prone pilot">Prone-pilot</a></li>
    <li><a href="/wiki/List_of_rocket_aircraft" class="mw-redirect" title="List of rocket aircraft">Rocket-powered</a></li>
    <li><a href="/wiki/List_of_flying_boats_and_floatplanes" title="List of flying boats and floatplanes">Flying boats and floatplanes</a></li>
    <li><a href="/wiki/List_of_STOL_aircraft" title="List of STOL aircraft">STOL</a></li>
    <li><a href="/wiki/List_of_supersonic_aircraft" title="List of supersonic aircraft">Supersonic</a></li>
    <li><a href="/wiki/Trimotor" title="Trimotor">Trimotors</a></li>
    <li><a href="/wiki/List_of_triplanes" title="List of triplanes">Triplanes</a></li>
    <li><a href="/wiki/List_of_unmanned_aerial_vehicles" title="List of unmanned aerial vehicles">Unmanned</a></li>
    <li><a href="/wiki/List_of_VTOL_aircraft" title="List of VTOL aircraft">VTOL</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%">Fuselage</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Double-deck_aircraft" title="Double-deck aircraft">Double-deck</a></li>
    <li><a href="/wiki/Narrow-body_aircraft" title="Narrow-body aircraft">Narrow-body</a></li>
    <li><a href="/wiki/Wide-body_aircraft" title="Wide-body aircraft">Wide-body</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%"><div class="hlist"><ul><li>Weight</li><li>Size</li></ul></div></th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_airliners_by_maximum_takeoff_weight" title="List of airliners by maximum takeoff weight">Maximum takeoff weight</a></li>
    <li><a href="/wiki/List_of_current_production_certified_light_aircraft" title="List of current production certified light aircraft">Light aircraft</a>
    <ul><li><a href="/wiki/List_of_very_light_jets" class="mw-redirect" title="List of very light jets">very light jets</a></li></ul></li>
    <li><a href="/wiki/List_of_large_aircraft" title="List of large aircraft">Large aircraft</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%">Manufacturer</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><span class="noviewer" typeof="mw:File"><span title="Template"><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/16px-Symbol_template_class_pink.svg.png" decoding="async" width="16" height="16" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/23px-Symbol_template_class_pink.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/31px-Symbol_template_class_pink.svg.png 2x" data-file-width="180" data-file-height="185" /></span></span>&#160;<a href="/wiki/Template:Airbus_Group_aircraft" class="mw-redirect" title="Template:Airbus Group aircraft">Airbus</a></li>
    <li><span class="noviewer" typeof="mw:File"><span title="Template"><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/16px-Symbol_template_class_pink.svg.png" decoding="async" width="16" height="16" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/23px-Symbol_template_class_pink.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/31px-Symbol_template_class_pink.svg.png 2x" data-file-width="180" data-file-height="185" /></span></span>&#160;<a href="/wiki/Template:Antonov_aircraft" title="Template:Antonov aircraft">Antonov</a></li>
    <li><span class="noviewer" typeof="mw:File"><span title="Template"><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/16px-Symbol_template_class_pink.svg.png" decoding="async" width="16" height="16" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/23px-Symbol_template_class_pink.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/31px-Symbol_template_class_pink.svg.png 2x" data-file-width="180" data-file-height="185" /></span></span>&#160;<a href="/wiki/Template:Boeing_airliners" title="Template:Boeing airliners">Boeing</a></li>
    <li><span class="noviewer" typeof="mw:File"><span title="Template"><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/16px-Symbol_template_class_pink.svg.png" decoding="async" width="16" height="16" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/23px-Symbol_template_class_pink.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/31px-Symbol_template_class_pink.svg.png 2x" data-file-width="180" data-file-height="185" /></span></span>&#160;<a href="/wiki/Template:Bombardier_aircraft" title="Template:Bombardier aircraft">Bombardier</a></li>
    <li><span class="noviewer" typeof="mw:File"><span title="Template"><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/16px-Symbol_template_class_pink.svg.png" decoding="async" width="16" height="16" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/23px-Symbol_template_class_pink.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/31px-Symbol_template_class_pink.svg.png 2x" data-file-width="180" data-file-height="185" /></span></span>&#160;<a href="/wiki/Template:Douglas_airliners" title="Template:Douglas airliners">Douglas&#160;/&#32;McDonnell Douglas</a></li>
    <li><span class="noviewer" typeof="mw:File"><span title="Template"><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/16px-Symbol_template_class_pink.svg.png" decoding="async" width="16" height="16" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/23px-Symbol_template_class_pink.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/31px-Symbol_template_class_pink.svg.png 2x" data-file-width="180" data-file-height="185" /></span></span>&#160;<a href="/wiki/Template:Embraer_aircraft" title="Template:Embraer aircraft">Embraer</a></li>
    <li><span class="noviewer" typeof="mw:File"><span title="Template"><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/16px-Symbol_template_class_pink.svg.png" decoding="async" width="16" height="16" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/23px-Symbol_template_class_pink.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/31px-Symbol_template_class_pink.svg.png 2x" data-file-width="180" data-file-height="185" /></span></span>&#160;<a href="/wiki/Template:Ilyushin_aircraft" title="Template:Ilyushin aircraft">Ilyushin</a></li>
    <li><span class="noviewer" typeof="mw:File"><span title="Template"><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/16px-Symbol_template_class_pink.svg.png" decoding="async" width="16" height="16" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/23px-Symbol_template_class_pink.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/31px-Symbol_template_class_pink.svg.png 2x" data-file-width="180" data-file-height="185" /></span></span>&#160;<a href="/wiki/Template:Tupolev_aircraft" title="Template:Tupolev aircraft">Tupolev</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%">Engine number</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Twinjet" title="Twinjet">Twinjets</a></li>
    <li><a href="/wiki/Trijet" title="Trijet">Trijets</a></li>
    <li><a href="/wiki/Trimotor" title="Trimotor">Trimotors</a></li>
    <li><a href="/wiki/Four-engined_jet_aircraft" title="Four-engined jet aircraft">Four-engined jet aircraft</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%">Range</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_jet_airliners" class="mw-redirect" title="List of jet airliners">Jet airliners</a></li>
    <li><a href="/wiki/List_of_regional_airliners" title="List of regional airliners">Regional airliners</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%">Use</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_racing_aircraft" title="List of racing aircraft">Racers</a></li>
    <li><a href="/wiki/Regional_airliner" title="Regional airliner">Regional airliner</a>
    <ul><li><a href="/wiki/Regional_jet" title="Regional jet">regional jet</a></li></ul></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%">Research</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Early_flying_machines" title="Early flying machines">Early flying machines</a></li>
    <li><a href="/wiki/List_of_experimental_aircraft" title="List of experimental aircraft">Experimental</a></li>
    <li><a href="/wiki/List_of_X-planes" title="List of X-planes">X-planes</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%">Rotor-powered</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_rotorcraft" title="List of rotorcraft">Rotorcraft</a>
    <ul><li><a href="/wiki/List_of_utility_helicopters" class="mw-redirect" title="List of utility helicopters">utility</a></li></ul></li>
    <li><a href="/wiki/Tiltrotor#List_of_tiltrotor_aircraft" title="Tiltrotor">Tiltrotors</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%"><div class="hlist"><ul><li>Executive</li><li>Private</li></ul></div></th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Business_jet" title="Business jet">Business jets</a></li>
    <li><a href="/wiki/Light-sport_aircraft" title="Light-sport aircraft">Light-sport aircraft</a></li>
    <li><a href="/wiki/Flying_car" title="Flying car">Flying car</a></li></ul>
    </div></td></tr></tbody></table><div></div></td></tr></tbody></table><div></div></td></tr><tr><td colspan="2" class="navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks mw-collapsible expanded navbox-subgroup" style="border-spacing:0"><tbody><tr><th scope="col" class="navbox-title" colspan="2" style="font-size:95%;"><div id="Other_lists" style="font-size:114%;margin:0 4em">Other lists</div></th></tr><tr><td colspan="2" class="navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_aircraft_by_date_and_usage_category" title="List of aircraft by date and usage category">By date and usage</a></li>
    <li><a href="/wiki/List_of_aircraft_by_tail_number" title="List of aircraft by tail number">By tail number</a></li>
    <li><a href="/wiki/List_of_most-produced_aircraft" title="List of most-produced aircraft">Most-produced</a></li></ul>
    </div></td></tr></tbody></table><div></div></td></tr></tbody></table><div></div></td></tr></tbody></table><div></div></td></tr><tr><td colspan="2" class="navbox-list navbox-odd hlist" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks mw-collapsible uncollapsed navbox-subgroup" style="border-spacing:0"><tbody><tr><th scope="col" class="navbox-title" colspan="2"><div id="Military_aircraft" style="font-size:114%;margin:0 4em"><a href="/wiki/Military_aircraft" title="Military aircraft">Military aircraft</a></div></th></tr><tr><td colspan="2" class="navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks navbox-subgroup" style="border-spacing:0"><tbody><tr><th scope="row" class="navbox-group" style="width:1%">Role</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_airborne_early_warning_aircraft" title="List of airborne early warning aircraft">AEW</a></li>
    <li><a href="/wiki/List_of_attack_aircraft" title="List of attack aircraft">Attack</a></li>
    <li><a href="/wiki/List_of_bomber_aircraft" title="List of bomber aircraft">Bomber</a>
    <ul><li><a href="/wiki/List_of_torpedo_bombers" title="List of torpedo bombers">Torpedo</a></li></ul></li>
    <li><a href="/wiki/List_of_carrier-based_aircraft" title="List of carrier-based aircraft">Carrier-based</a></li>
    <li><a href="/wiki/List_of_fighter_aircraft" title="List of fighter aircraft">Fighter</a></li>
    <li><a href="/wiki/List_of_maritime_patrol_aircraft" title="List of maritime patrol aircraft">Maritime patrol</a></li>
    <li><a href="/wiki/List_of_submarine-borne_aircraft" title="List of submarine-borne aircraft">Submarine-borne</a></li>
    <li><a href="/wiki/List_of_tanker_aircraft" title="List of tanker aircraft">Tanker</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%"><a href="/wiki/Lists_of_military_aircraft_by_nation" title="Lists of military aircraft by nation">Nation</a></th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks navbox-subgroup" style="border-spacing:0"><tbody><tr><td colspan="2" class="navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_Afghan_Air_Force_aircraft" title="List of Afghan Air Force aircraft">Afghanistan</a></li>
    <li><a href="/wiki/List_of_Albanian_Air_Force_aircraft" title="List of Albanian Air Force aircraft">Albania</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Argentine_Air_Force" title="List of aircraft of the Argentine Air Force">Argentina</a></li>
    <li><a href="/wiki/List_of_current_Royal_Australian_Air_Force_aircraft" title="List of current Royal Australian Air Force aircraft">Australia</a></li>
    <li><a href="/wiki/List_of_active_Bangladesh_military_aircraft" title="List of active Bangladesh military aircraft">Bangladesh</a></li>
    <li><a href="/wiki/List_of_Belize_Defence_Force_Air_Wing_aircraft" class="mw-redirect" title="List of Belize Defence Force Air Wing aircraft">Belize</a></li>
    <li><a href="/wiki/List_of_active_Brazilian_military_aircraft" title="List of active Brazilian military aircraft">Brazil</a></li>
    <li><a href="/wiki/List_of_active_Bulgarian_military_aircraft" class="mw-redirect" title="List of active Bulgarian military aircraft">Bulgaria</a></li>
    <li><a href="/wiki/List_of_aircraft_of_Canada%27s_air_forces" title="List of aircraft of Canada&#39;s air forces">Canada</a></li>
    <li><a href="/wiki/List_of_active_Chile_military_aircraft" title="List of active Chile military aircraft">Chile</a></li>
    <li><a href="/wiki/List_of_active_People%27s_Liberation_Army_aircraft" title="List of active People&#39;s Liberation Army aircraft">China</a></li>
    <li><a href="/wiki/List_of_military_aircraft_of_the_Czech_Republic" title="List of military aircraft of the Czech Republic">Czech Republic</a></li>
    <li><a href="/wiki/List_of_military_aircraft_of_Denmark" title="List of military aircraft of Denmark">Denmark</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Egyptian_Air_Force" title="List of aircraft of the Egyptian Air Force">Egypt</a></li>
    <li><a href="/wiki/List_of_military_aircraft_of_Finland" title="List of military aircraft of Finland">Finland</a></li>
    <li><a href="/wiki/List_of_military_aircraft_of_France" title="List of military aircraft of France">France</a></li>
    <li><a href="/wiki/List_of_military_aircraft_of_Germany" title="List of military aircraft of Germany">Germany</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Hellenic_Air_Force" class="mw-redirect" title="List of aircraft of the Hellenic Air Force">Greece</a></li>
    <li><a class="mw-selflink selflink">India</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Indonesian_National_Armed_Forces" title="List of aircraft of the Indonesian National Armed Forces">Indonesia</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Iranian_Air_Force" title="List of aircraft of the Iranian Air Force">Iran</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Irish_Air_Corps" title="List of aircraft of the Irish Air Corps">Ireland</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Israeli_Air_Force" title="List of aircraft of the Israeli Air Force">Israel</a></li>
    <li><a href="/wiki/List_of_active_Italian_military_aircraft" title="List of active Italian military aircraft">Italy</a></li>
    <li><a href="/wiki/List_of_military_aircraft_of_Japan" title="List of military aircraft of Japan">Japan</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Malaysian_Armed_Forces" title="List of aircraft of the Malaysian Armed Forces">Malaysia</a></li>
    <li><a href="/wiki/List_of_active_Moroccan_military_aircraft" class="mw-redirect" title="List of active Moroccan military aircraft">Morocco</a></li>
    <li><a href="/wiki/List_of_active_New_Zealand_military_aircraft" class="mw-redirect" title="List of active New Zealand military aircraft">New Zealand</a></li>
    <li><a href="/wiki/List_of_military_aircraft_of_Norway" title="List of military aircraft of Norway">Norway</a></li>
    <li><a href="/wiki/List_of_active_Pakistan_military_aircraft" title="List of active Pakistan military aircraft">Pakistan</a></li>
    <li><a href="/wiki/List_of_active_military_aircraft_of_the_Philippines" title="List of active military aircraft of the Philippines">Philippines</a></li>
    <li><a href="/wiki/List_of_retired_Polish_Air_Force_aircraft" title="List of retired Polish Air Force aircraft">Poland</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Portuguese_Air_Force" class="mw-redirect" title="List of aircraft of the Portuguese Air Force">Portugal</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Romanian_Air_Force" title="List of aircraft of the Romanian Air Force">Romania</a></li>
    <li><a href="/wiki/List_of_currently_active_Russian_military_aircraft" class="mw-redirect" title="List of currently active Russian military aircraft">Russia</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_South_African_Air_Force" title="List of aircraft of the South African Air Force">South Africa</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Spanish_Air_and_Space_Force" class="mw-redirect" title="List of aircraft of the Spanish Air and Space Force">Spain</a></li>
    <li><a href="/wiki/List_of_military_aircraft_of_Sri_Lanka" title="List of military aircraft of Sri Lanka">Sri Lanka</a></li>
    <li><a href="/wiki/List_of_military_aircraft_of_Sweden" title="List of military aircraft of Sweden">Sweden</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Swiss_Air_Force" title="List of aircraft of the Swiss Air Force">Switzerland</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Royal_Thai_Air_Force" title="List of aircraft of the Royal Thai Air Force">Thailand</a></li>
    <li><a href="/wiki/List_of_active_Turkish_Air_Force_aircraft" title="List of active Turkish Air Force aircraft">Turkey</a></li>
    <li><a href="/wiki/List_of_active_United_Kingdom_military_aircraft" title="List of active United Kingdom military aircraft">United Kingdom</a></li>
    <li><a href="/wiki/List_of_active_United_States_military_aircraft" title="List of active United States military aircraft">United States</a></li></ul>
    </div></td></tr></tbody></table><div></div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%">Era</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_World_War_I_Entente_aircraft" title="List of World War I Entente aircraft">WWI Entente</a></li>
    <li><a href="/wiki/List_of_World_War_I_Central_Powers_aircraft" title="List of World War I Central Powers aircraft">WWI Central Powers</a></li>
    <li><a href="/wiki/List_of_interwar_military_aircraft" title="List of interwar military aircraft">Interwar</a></li>
    <li><a href="/wiki/List_of_aircraft_of_World_War_II" title="List of aircraft of World War II">World War II</a></li>
    <li><a href="/wiki/List_of_jet_aircraft_of_World_War_II" title="List of jet aircraft of World War II">World War II jets</a></li></ul>
    </div></td></tr></tbody></table><div></div></td></tr></tbody></table><div></div></td></tr></tbody></table></div>
    <!-- 
    NewPP limit report
    Parsed by mw‐web.codfw.main‐6dfc4fc9cc‐cvgc2
    Cached time: 20241010160229
    Cache expiry: 2592000
    Reduced expiry: false
    Complications: [vary‐revision‐sha1, show‐toc]
    CPU time usage: 0.864 seconds
    Real time usage: 1.113 seconds
    Preprocessor visited node count: 4903/1000000
    Post‐expand include size: 283991/2097152 bytes
    Template argument size: 894/2097152 bytes
    Highest expansion depth: 12/100
    Expensive parser function count: 10/500
    Unstrip recursion depth: 1/20
    Unstrip post‐expand size: 324093/5000000 bytes
    Lua time usage: 0.503/10.000 seconds
    Lua memory usage: 5999431/52428800 bytes
    Number of Wikibase entities loaded: 0/400
    -->
    <!--
    Transclusion expansion time report (%,ms,calls,template)
    100.00%  888.096      1 -total
     50.41%  447.732      1 Template:Reflist
     21.35%  189.599     58 Template:Cite_web
     13.80%  122.599      3 Template:Cite_book
     13.37%  118.754      1 Template:Military_of_India
     12.52%  111.209      1 Template:Pp
      7.82%   69.470     22 Template:Cite_news
      6.78%   60.230      1 Template:Short_description
      6.36%   56.483      2 Template:Navbox_with_collapsible_groups
      4.55%   40.412      1 Template:Lists_of_aircraft
    -->
    
    <!-- Saved in parser cache with key enwiki:pcache:idhash:2192619-0!canonical and timestamp 20241010160229 and revision id 1250455700. Rendering was triggered because: page-view
     -->
    </div><!--esi <esi:include src="/esitest-fa8a495983347898/content" /> --><noscript><img src="https://login.wikimedia.org/wiki/Special:CentralAutoLogin/start?type=1x1" alt="" width="1" height="1" style="border: none; position: absolute;"></noscript>
    <div class="printfooter" data-nosnippet="">Retrieved from "<a dir="ltr" href="https://en.wikipedia.org/w/index.php?title=List_of_active_Indian_military_aircraft&amp;oldid=1250455700">https://en.wikipedia.org/w/index.php?title=List_of_active_Indian_military_aircraft&amp;oldid=1250455700</a>"</div></div>
    					<div id="catlinks" class="catlinks" data-mw="interface"><div id="mw-normal-catlinks" class="mw-normal-catlinks"><a href="/wiki/Help:Category" title="Help:Category">Categories</a>: <ul><li><a href="/wiki/Category:Indian_Air_Force" title="Category:Indian Air Force">Indian Air Force</a></li><li><a href="/wiki/Category:Indian_military_aircraft" title="Category:Indian military aircraft">Indian military aircraft</a></li><li><a href="/wiki/Category:Lists_of_military_aircraft" title="Category:Lists of military aircraft">Lists of military aircraft</a></li><li><a href="/wiki/Category:Indian_military-related_lists" title="Category:Indian military-related lists">Indian military-related lists</a></li><li><a href="/wiki/Category:India_aviation-related_lists" title="Category:India aviation-related lists">India aviation-related lists</a></li></ul></div><div id="mw-hidden-catlinks" class="mw-hidden-catlinks mw-hidden-cats-hidden">Hidden categories: <ul><li><a href="/wiki/Category:Wikipedia_semi-protected_pages" title="Category:Wikipedia semi-protected pages">Wikipedia semi-protected pages</a></li><li><a href="/wiki/Category:Articles_with_short_description" title="Category:Articles with short description">Articles with short description</a></li><li><a href="/wiki/Category:Short_description_is_different_from_Wikidata" title="Category:Short description is different from Wikidata">Short description is different from Wikidata</a></li><li><a href="/wiki/Category:Use_dmy_dates_from_October_2019" title="Category:Use dmy dates from October 2019">Use dmy dates from October 2019</a></li></ul></div></div>
    				</div>
    			</main>
    			
    		</div>
    		<div class="mw-footer-container">
    			
    <footer id="footer" class="mw-footer" >
    	<ul id="footer-info">
    	<li id="footer-info-lastmod"> This page was last edited on 10 October 2024, at 14:30<span class="anonymous-show">&#160;(UTC)</span>.</li>
    	<li id="footer-info-copyright">Text is available under the <a rel="license" href="//en.wikipedia.org/wiki/Wikipedia:Text_of_the_Creative_Commons_Attribution-ShareAlike_4.0_International_License">Creative Commons Attribution-ShareAlike License 4.0</a><a rel="license" href="//en.wikipedia.org/wiki/Wikipedia:Text_of_the_Creative_Commons_Attribution-ShareAlike_4.0_International_License" style="display:none;"></a>;
    additional terms may apply. By using this site, you agree to the <a href="//foundation.wikimedia.org/wiki/Special:MyLanguage/Policy:Terms_of_Use">Terms of Use</a> and <a href="//foundation.wikimedia.org/wiki/Special:MyLanguage/Policy:Privacy_policy">Privacy Policy</a>. Wikipedia® is a registered trademark of the <a href="//wikimediafoundation.org/">Wikimedia Foundation, Inc.</a>, a non-profit organization.</li>
    </ul>
    
    	<ul id="footer-places">
    	<li id="footer-places-privacy"><a href="https://foundation.wikimedia.org/wiki/Special:MyLanguage/Policy:Privacy_policy">Privacy policy</a></li>
    	<li id="footer-places-about"><a href="/wiki/Wikipedia:About">About Wikipedia</a></li>
    	<li id="footer-places-disclaimers"><a href="/wiki/Wikipedia:General_disclaimer">Disclaimers</a></li>
    	<li id="footer-places-contact"><a href="//en.wikipedia.org/wiki/Wikipedia:Contact_us">Contact Wikipedia</a></li>
    	<li id="footer-places-wm-codeofconduct"><a href="https://foundation.wikimedia.org/wiki/Special:MyLanguage/Policy:Universal_Code_of_Conduct">Code of Conduct</a></li>
    	<li id="footer-places-developers"><a href="https://developer.wikimedia.org">Developers</a></li>
    	<li id="footer-places-statslink"><a href="https://stats.wikimedia.org/#/en.wikipedia.org">Statistics</a></li>
    	<li id="footer-places-cookiestatement"><a href="https://foundation.wikimedia.org/wiki/Special:MyLanguage/Policy:Cookie_statement">Cookie statement</a></li>
    	<li id="footer-places-mobileview"><a href="//en.m.wikipedia.org/w/index.php?title=List_of_active_Indian_military_aircraft&amp;mobileaction=toggle_view_mobile" class="noprint stopMobileRedirectToggle">Mobile view</a></li>
    </ul>
    
    	<ul id="footer-icons" class="noprint">
    	<li id="footer-copyrightico"><a href="https://wikimediafoundation.org/" class="cdx-button cdx-button--fake-button cdx-button--size-large cdx-button--fake-button--enabled"><img src="/static/images/footer/wikimedia-button.svg" width="84" height="29" alt="Wikimedia Foundation" loading="lazy"></a></li>
    	<li id="footer-poweredbyico"><a href="https://www.mediawiki.org/" class="cdx-button cdx-button--fake-button cdx-button--size-large cdx-button--fake-button--enabled"><img src="/w/resources/assets/poweredby_mediawiki.svg" alt="Powered by MediaWiki" width="88" height="31" loading="lazy"></a></li>
    </ul>
    
    </footer>
    
    		</div>
    	</div> 
    </div> 
    <div class="vector-settings" id="p-dock-bottom">
    	<ul></ul>
    </div><script>(RLQ=window.RLQ||[]).push(function(){mw.config.set({"wgHostname":"mw-web.codfw.main-6dfc4fc9cc-cvgc2","wgBackendResponseTime":1256,"wgPageParseReport":{"limitreport":{"cputime":"0.864","walltime":"1.113","ppvisitednodes":{"value":4903,"limit":1000000},"postexpandincludesize":{"value":283991,"limit":2097152},"templateargumentsize":{"value":894,"limit":2097152},"expansiondepth":{"value":12,"limit":100},"expensivefunctioncount":{"value":10,"limit":500},"unstrip-depth":{"value":1,"limit":20},"unstrip-size":{"value":324093,"limit":5000000},"entityaccesscount":{"value":0,"limit":400},"timingprofile":["100.00%  888.096      1 -total"," 50.41%  447.732      1 Template:Reflist"," 21.35%  189.599     58 Template:Cite_web"," 13.80%  122.599      3 Template:Cite_book"," 13.37%  118.754      1 Template:Military_of_India"," 12.52%  111.209      1 Template:Pp","  7.82%   69.470     22 Template:Cite_news","  6.78%   60.230      1 Template:Short_description","  6.36%   56.483      2 Template:Navbox_with_collapsible_groups","  4.55%   40.412      1 Template:Lists_of_aircraft"]},"scribunto":{"limitreport-timeusage":{"value":"0.503","limit":"10.000"},"limitreport-memusage":{"value":5999431,"limit":52428800}},"cachereport":{"origin":"mw-web.codfw.main-6dfc4fc9cc-cvgc2","timestamp":"20241010160229","ttl":2592000,"transientcontent":false}}});});</script>
    <script type="application/ld+json">{"@context":"https:\/\/schema.org","@type":"Article","name":"List of active Indian military aircraft","url":"https:\/\/en.wikipedia.org\/wiki\/List_of_active_Indian_military_aircraft","sameAs":"http:\/\/www.wikidata.org\/entity\/Q6604953","mainEntity":"http:\/\/www.wikidata.org\/entity\/Q6604953","author":{"@type":"Organization","name":"Contributors to Wikimedia projects"},"publisher":{"@type":"Organization","name":"Wikimedia Foundation, Inc.","logo":{"@type":"ImageObject","url":"https:\/\/www.wikimedia.org\/static\/images\/wmf-hor-googpub.png"}},"datePublished":"2005-07-08T09:02:01Z","dateModified":"2024-10-10T14:30:41Z","headline":"Wikimedia list article"}</script>
    </body>
    </html>
    


```python
soup= beautifulsoup(url.text,"html.parser")
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    Cell In[19], line 1
    ----> 1 soup= beautifulsoup(url.text,"html.parser")
    

    NameError: name 'beautifulsoup' is not defined



```python
from BS4 import beautifulsoup
```


    ---------------------------------------------------------------------------

    ModuleNotFoundError                       Traceback (most recent call last)

    Cell In[21], line 1
    ----> 1 from BS4 import beautifulsoup
    

    ModuleNotFoundError: No module named 'BS4'



```python
! pip install beautifulsoup4
```

    Requirement already satisfied: beautifulsoup4 in d:\users\lib\site-packages (4.12.3)
    Requirement already satisfied: soupsieve>1.2 in d:\users\lib\site-packages (from beautifulsoup4) (2.5)
    


```python
from beautifulsoup4 import beautifulsoup
```


    ---------------------------------------------------------------------------

    ModuleNotFoundError                       Traceback (most recent call last)

    Cell In[25], line 1
    ----> 1 from beautifulsoup4 import beautifulsoup
    

    ModuleNotFoundError: No module named 'beautifulsoup4'



```python
from bs4 import beautifulsoup
```


    ---------------------------------------------------------------------------

    ImportError                               Traceback (most recent call last)

    Cell In[27], line 1
    ----> 1 from bs4 import beautifulsoup
    

    ImportError: cannot import name 'beautifulsoup' from 'bs4' (D:\Users\Lib\site-packages\bs4\__init__.py)



```python
python -m pip install --upgrade pip

```


      Cell In[29], line 1
        python -m pip install --upgrade pip
                  ^
    SyntaxError: invalid syntax
    



```python
pip install --upgrade pip

```

    Requirement already satisfied: pip in d:\users\lib\site-packages (24.0)
    Collecting pip
      Downloading pip-24.2-py3-none-any.whl.metadata (3.6 kB)
    Downloading pip-24.2-py3-none-any.whl (1.8 MB)
       ---------------------------------------- 0.0/1.8 MB ? eta -:--:--
       ---------------------------------------- 0.0/1.8 MB ? eta -:--:--
       - -------------------------------------- 0.1/1.8 MB 991.0 kB/s eta 0:00:02
       -------- ------------------------------- 0.4/1.8 MB 3.3 MB/s eta 0:00:01
       ------------ --------------------------- 0.6/1.8 MB 4.1 MB/s eta 0:00:01
       ------------------- -------------------- 0.9/1.8 MB 4.3 MB/s eta 0:00:01
       --------------------------- ------------ 1.3/1.8 MB 5.0 MB/s eta 0:00:01
       ----------------------------------- ---- 1.6/1.8 MB 5.4 MB/s eta 0:00:01
       ---------------------------------------- 1.8/1.8 MB 5.5 MB/s eta 0:00:00
    Installing collected packages: pip
      Attempting uninstall: pip
        Found existing installation: pip 24.0
        Uninstalling pip-24.0:
          Successfully uninstalled pip-24.0
    Successfully installed pip-24.2
    Note: you may need to restart the kernel to use updated packages.
    


```python
pip cache purge

```

    Files removed: 679
    Note: you may need to restart the kernel to use updated packages.
    


```python
pip install beautifulsoup4==4.12.3

```

    Requirement already satisfied: beautifulsoup4==4.12.3 in d:\users\lib\site-packages (4.12.3)
    Requirement already satisfied: soupsieve>1.2 in d:\users\lib\site-packages (from beautifulsoup4==4.12.3) (2.5)
    Note: you may need to restart the kernel to use updated packages.
    


```python
soup= beautifulsoup(url.text,"html.parser")
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    Cell In[1], line 1
    ----> 1 soup= beautifulsoup(url.text,"html.parser")
    

    NameError: name 'beautifulsoup' is not defined



```python
from bs4 import BeautifulSoup
soup = BeautifulSoup(url.text, "html.parser")

```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    Cell In[3], line 2
          1 from bs4 import BeautifulSoup
    ----> 2 soup = BeautifulSoup(url.text, "html.parser")
    

    NameError: name 'url' is not defined



```python
url=requests.get("https://en.wikipedia.org/wiki/List_of_active_Indian_military_aircraft",headers={"user-agent":"Mozilla/5.0"})
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    Cell In[5], line 1
    ----> 1 url=requests.get("https://en.wikipedia.org/wiki/List_of_active_Indian_military_aircraft",headers={"user-agent":"Mozilla/5.0"})
    

    NameError: name 'requests' is not defined



```python
import requests
url=requests.get("https://en.wikipedia.org/wiki/List_of_active_Indian_military_aircraft",headers={"user-agent":"Mozilla/5.0"})
```


```python
print(url)
```

    <Response [200]>
    


```python
print(url.text)
```

    <!DOCTYPE html>
    <html class="client-nojs vector-feature-language-in-header-enabled vector-feature-language-in-main-page-header-disabled vector-feature-sticky-header-disabled vector-feature-page-tools-pinned-disabled vector-feature-toc-pinned-clientpref-1 vector-feature-main-menu-pinned-disabled vector-feature-limited-width-clientpref-1 vector-feature-limited-width-content-enabled vector-feature-custom-font-size-clientpref-1 vector-feature-appearance-pinned-clientpref-1 vector-feature-night-mode-enabled skin-theme-clientpref-day vector-toc-available" lang="en" dir="ltr">
    <head>
    <meta charset="UTF-8">
    <title>List of active Indian military aircraft - Wikipedia</title>
    <script>(function(){var className="client-js vector-feature-language-in-header-enabled vector-feature-language-in-main-page-header-disabled vector-feature-sticky-header-disabled vector-feature-page-tools-pinned-disabled vector-feature-toc-pinned-clientpref-1 vector-feature-main-menu-pinned-disabled vector-feature-limited-width-clientpref-1 vector-feature-limited-width-content-enabled vector-feature-custom-font-size-clientpref-1 vector-feature-appearance-pinned-clientpref-1 vector-feature-night-mode-enabled skin-theme-clientpref-day vector-toc-available";var cookie=document.cookie.match(/(?:^|; )enwikimwclientpreferences=([^;]+)/);if(cookie){cookie[1].split('%2C').forEach(function(pref){className=className.replace(new RegExp('(^| )'+pref.replace(/-clientpref-\w+$|[^\w-]+/g,'')+'-clientpref-\\w+( |$)'),'$1'+pref+'$2');});}document.documentElement.className=className;}());RLCONF={"wgBreakFrames":false,"wgSeparatorTransformTable":["",""],"wgDigitTransformTable":["",""],"wgDefaultDateFormat":"dmy",
    "wgMonthNames":["","January","February","March","April","May","June","July","August","September","October","November","December"],"wgRequestId":"8ef1d1bb-a151-4240-8cd8-f88596b73970","wgCanonicalNamespace":"","wgCanonicalSpecialPageName":false,"wgNamespaceNumber":0,"wgPageName":"List_of_active_Indian_military_aircraft","wgTitle":"List of active Indian military aircraft","wgCurRevisionId":1250455700,"wgRevisionId":1250455700,"wgArticleId":2192619,"wgIsArticle":true,"wgIsRedirect":false,"wgAction":"view","wgUserName":null,"wgUserGroups":["*"],"wgCategories":["Wikipedia semi-protected pages","Articles with short description","Short description is different from Wikidata","Use dmy dates from October 2019","Indian Air Force","Indian military aircraft","Lists of military aircraft","Indian military-related lists","India aviation-related lists"],"wgPageViewLanguage":"en","wgPageContentLanguage":"en","wgPageContentModel":"wikitext","wgRelevantPageName":"List_of_active_Indian_military_aircraft",
    "wgRelevantArticleId":2192619,"wgIsProbablyEditable":false,"wgRelevantPageIsProbablyEditable":false,"wgRestrictionEdit":["autoconfirmed"],"wgRestrictionMove":[],"wgNoticeProject":"wikipedia","wgCiteReferencePreviewsActive":false,"wgFlaggedRevsParams":{"tags":{"status":{"levels":1}}},"wgMediaViewerOnClick":true,"wgMediaViewerEnabledByDefault":true,"wgPopupsFlags":0,"wgVisualEditor":{"pageLanguageCode":"en","pageLanguageDir":"ltr","pageVariantFallbacks":"en"},"wgMFDisplayWikibaseDescriptions":{"search":true,"watchlist":true,"tagline":false,"nearby":true},"wgWMESchemaEditAttemptStepOversample":false,"wgWMEPageLength":40000,"wgULSCurrentAutonym":"English","wgRelatedArticlesCompat":[],"wgCentralAuthMobileDomain":false,"wgEditSubmitButtonLabelPublish":true,"wgULSPosition":"interlanguage","wgULSisCompactLinksEnabled":false,"wgVector2022LanguageInHeader":true,"wgULSisLanguageSelectorEmpty":false,"wgWikibaseItemId":"Q6604953","wgCheckUserClientHintsHeadersJsApi":["architecture","bitness",
    "brands","fullVersionList","mobile","model","platform","platformVersion"],"GEHomepageSuggestedEditsEnableTopics":true,"wgGETopicsMatchModeEnabled":false,"wgGEStructuredTaskRejectionReasonTextInputEnabled":false,"wgGELevelingUpEnabledForUser":false};RLSTATE={"ext.globalCssJs.user.styles":"ready","site.styles":"ready","user.styles":"ready","ext.globalCssJs.user":"ready","user":"ready","user.options":"loading","ext.cite.styles":"ready","skins.vector.search.codex.styles":"ready","skins.vector.styles":"ready","skins.vector.icons":"ready","jquery.tablesorter.styles":"ready","jquery.makeCollapsible.styles":"ready","ext.wikimediamessages.styles":"ready","ext.visualEditor.desktopArticleTarget.noscript":"ready","ext.uls.interlanguage":"ready","wikibase.client.init":"ready","ext.wikimediaBadges":"ready"};RLPAGEMODULES=["ext.cite.ux-enhancements","mediawiki.page.media","site","mediawiki.page.ready","jquery.tablesorter","jquery.makeCollapsible","mediawiki.toc","skins.vector.js",
    "ext.centralNotice.geoIP","ext.centralNotice.startUp","ext.gadget.ReferenceTooltips","ext.gadget.switcher","ext.urlShortener.toolbar","ext.centralauth.centralautologin","mmv.head","mmv.bootstrap.autostart","ext.popups","ext.visualEditor.desktopArticleTarget.init","ext.visualEditor.targetLoader","ext.echo.centralauth","ext.eventLogging","ext.wikimediaEvents","ext.navigationTiming","ext.uls.interface","ext.cx.eventlogging.campaigns","ext.cx.uls.quick.actions","wikibase.client.vector-2022","ext.checkUser.clientHints","ext.quicksurveys.init","ext.growthExperiments.SuggestedEditSession","wikibase.sidebar.tracking"];</script>
    <script>(RLQ=window.RLQ||[]).push(function(){mw.loader.impl(function(){return["user.options@12s5i",function($,jQuery,require,module){mw.user.tokens.set({"patrolToken":"+\\","watchToken":"+\\","csrfToken":"+\\"});
    }];});});</script>
    <link rel="stylesheet" href="/w/load.php?lang=en&amp;modules=ext.cite.styles%7Cext.uls.interlanguage%7Cext.visualEditor.desktopArticleTarget.noscript%7Cext.wikimediaBadges%7Cext.wikimediamessages.styles%7Cjquery.makeCollapsible.styles%7Cjquery.tablesorter.styles%7Cskins.vector.icons%2Cstyles%7Cskins.vector.search.codex.styles%7Cwikibase.client.init&amp;only=styles&amp;skin=vector-2022">
    <script async="" src="/w/load.php?lang=en&amp;modules=startup&amp;only=scripts&amp;raw=1&amp;skin=vector-2022"></script>
    <meta name="ResourceLoaderDynamicStyles" content="">
    <link rel="stylesheet" href="/w/load.php?lang=en&amp;modules=site.styles&amp;only=styles&amp;skin=vector-2022">
    <meta name="generator" content="MediaWiki 1.43.0-wmf.26">
    <meta name="referrer" content="origin">
    <meta name="referrer" content="origin-when-cross-origin">
    <meta name="robots" content="max-image-preview:standard">
    <meta name="format-detection" content="telephone=no">
    <meta name="viewport" content="width=1120">
    <meta property="og:title" content="List of active Indian military aircraft - Wikipedia">
    <meta property="og:type" content="website">
    <link rel="preconnect" href="//upload.wikimedia.org">
    <link rel="alternate" media="only screen and (max-width: 640px)" href="//en.m.wikipedia.org/wiki/List_of_active_Indian_military_aircraft">
    <link rel="apple-touch-icon" href="/static/apple-touch/wikipedia.png">
    <link rel="icon" href="/static/favicon/wikipedia.ico">
    <link rel="search" type="application/opensearchdescription+xml" href="/w/rest.php/v1/search" title="Wikipedia (en)">
    <link rel="EditURI" type="application/rsd+xml" href="//en.wikipedia.org/w/api.php?action=rsd">
    <link rel="canonical" href="https://en.wikipedia.org/wiki/List_of_active_Indian_military_aircraft">
    <link rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/deed.en">
    <link rel="alternate" type="application/atom+xml" title="Wikipedia Atom feed" href="/w/index.php?title=Special:RecentChanges&amp;feed=atom">
    <link rel="dns-prefetch" href="//meta.wikimedia.org" />
    <link rel="dns-prefetch" href="//login.wikimedia.org">
    </head>
    <body class="skin--responsive skin-vector skin-vector-search-vue mediawiki ltr sitedir-ltr mw-hide-empty-elt ns-0 ns-subject page-List_of_active_Indian_military_aircraft rootpage-List_of_active_Indian_military_aircraft skin-vector-2022 action-view"><a class="mw-jump-link" href="#bodyContent">Jump to content</a>
    <div class="vector-header-container">
    	<header class="vector-header mw-header">
    		<div class="vector-header-start">
    			<nav class="vector-main-menu-landmark" aria-label="Site">
    				
    <div id="vector-main-menu-dropdown" class="vector-dropdown vector-main-menu-dropdown vector-button-flush-left vector-button-flush-right"  >
    	<input type="checkbox" id="vector-main-menu-dropdown-checkbox" role="button" aria-haspopup="true" data-event-name="ui.dropdown-vector-main-menu-dropdown" class="vector-dropdown-checkbox "  aria-label="Main menu"  >
    	<label id="vector-main-menu-dropdown-label" for="vector-main-menu-dropdown-checkbox" class="vector-dropdown-label cdx-button cdx-button--fake-button cdx-button--fake-button--enabled cdx-button--weight-quiet cdx-button--icon-only " aria-hidden="true"  ><span class="vector-icon mw-ui-icon-menu mw-ui-icon-wikimedia-menu"></span>
    
    <span class="vector-dropdown-label-text">Main menu</span>
    	</label>
    	<div class="vector-dropdown-content">
    
    
    				<div id="vector-main-menu-unpinned-container" class="vector-unpinned-container">
    		
    <div id="vector-main-menu" class="vector-main-menu vector-pinnable-element">
    	<div
    	class="vector-pinnable-header vector-main-menu-pinnable-header vector-pinnable-header-unpinned"
    	data-feature-name="main-menu-pinned"
    	data-pinnable-element-id="vector-main-menu"
    	data-pinned-container-id="vector-main-menu-pinned-container"
    	data-unpinned-container-id="vector-main-menu-unpinned-container"
    >
    	<div class="vector-pinnable-header-label">Main menu</div>
    	<button class="vector-pinnable-header-toggle-button vector-pinnable-header-pin-button" data-event-name="pinnable-header.vector-main-menu.pin">move to sidebar</button>
    	<button class="vector-pinnable-header-toggle-button vector-pinnable-header-unpin-button" data-event-name="pinnable-header.vector-main-menu.unpin">hide</button>
    </div>
    
    	
    <div id="p-navigation" class="vector-menu mw-portlet mw-portlet-navigation"  >
    	<div class="vector-menu-heading">
    		Navigation
    	</div>
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			<li id="n-mainpage-description" class="mw-list-item"><a href="/wiki/Main_Page" title="Visit the main page [z]" accesskey="z"><span>Main page</span></a></li><li id="n-contents" class="mw-list-item"><a href="/wiki/Wikipedia:Contents" title="Guides to browsing Wikipedia"><span>Contents</span></a></li><li id="n-currentevents" class="mw-list-item"><a href="/wiki/Portal:Current_events" title="Articles related to current events"><span>Current events</span></a></li><li id="n-randompage" class="mw-list-item"><a href="/wiki/Special:Random" title="Visit a randomly selected article [x]" accesskey="x"><span>Random article</span></a></li><li id="n-aboutsite" class="mw-list-item"><a href="/wiki/Wikipedia:About" title="Learn about Wikipedia and how it works"><span>About Wikipedia</span></a></li><li id="n-contactpage" class="mw-list-item"><a href="//en.wikipedia.org/wiki/Wikipedia:Contact_us" title="How to contact Wikipedia"><span>Contact us</span></a></li>
    		</ul>
    		
    	</div>
    </div>
    
    	
    	
    <div id="p-interaction" class="vector-menu mw-portlet mw-portlet-interaction"  >
    	<div class="vector-menu-heading">
    		Contribute
    	</div>
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			<li id="n-help" class="mw-list-item"><a href="/wiki/Help:Contents" title="Guidance on how to use and edit Wikipedia"><span>Help</span></a></li><li id="n-introduction" class="mw-list-item"><a href="/wiki/Help:Introduction" title="Learn how to edit Wikipedia"><span>Learn to edit</span></a></li><li id="n-portal" class="mw-list-item"><a href="/wiki/Wikipedia:Community_portal" title="The hub for editors"><span>Community portal</span></a></li><li id="n-recentchanges" class="mw-list-item"><a href="/wiki/Special:RecentChanges" title="A list of recent changes to Wikipedia [r]" accesskey="r"><span>Recent changes</span></a></li><li id="n-upload" class="mw-list-item"><a href="/wiki/Wikipedia:File_upload_wizard" title="Add images or other media for use on Wikipedia"><span>Upload file</span></a></li>
    		</ul>
    		
    	</div>
    </div>
    
    </div>
    
    				</div>
    
    	</div>
    </div>
    
    		</nav>
    			
    <a href="/wiki/Main_Page" class="mw-logo">
    	<img class="mw-logo-icon" src="/static/images/icons/wikipedia.png" alt="" aria-hidden="true" height="50" width="50">
    	<span class="mw-logo-container skin-invert">
    		<img class="mw-logo-wordmark" alt="Wikipedia" src="/static/images/mobile/copyright/wikipedia-wordmark-en.svg" style="width: 7.5em; height: 1.125em;">
    		<img class="mw-logo-tagline" alt="The Free Encyclopedia" src="/static/images/mobile/copyright/wikipedia-tagline-en.svg" width="117" height="13" style="width: 7.3125em; height: 0.8125em;">
    	</span>
    </a>
    
    		</div>
    		<div class="vector-header-end">
    			
    <div id="p-search" role="search" class="vector-search-box-vue  vector-search-box-collapses vector-search-box-show-thumbnail vector-search-box-auto-expand-width vector-search-box">
    	<a href="/wiki/Special:Search" class="cdx-button cdx-button--fake-button cdx-button--fake-button--enabled cdx-button--weight-quiet cdx-button--icon-only search-toggle" title="Search Wikipedia [f]" accesskey="f"><span class="vector-icon mw-ui-icon-search mw-ui-icon-wikimedia-search"></span>
    
    <span>Search</span>
    	</a>
    	<div class="vector-typeahead-search-container">
    		<div class="cdx-typeahead-search cdx-typeahead-search--show-thumbnail cdx-typeahead-search--auto-expand-width">
    			<form action="/w/index.php" id="searchform" class="cdx-search-input cdx-search-input--has-end-button">
    				<div id="simpleSearch" class="cdx-search-input__input-wrapper"  data-search-loc="header-moved">
    					<div class="cdx-text-input cdx-text-input--has-start-icon">
    						<input
    							class="cdx-text-input__input"
    							 type="search" name="search" placeholder="Search Wikipedia" aria-label="Search Wikipedia" autocapitalize="sentences" title="Search Wikipedia [f]" accesskey="f" id="searchInput"
    							>
    						<span class="cdx-text-input__icon cdx-text-input__start-icon"></span>
    					</div>
    					<input type="hidden" name="title" value="Special:Search">
    				</div>
    				<button class="cdx-button cdx-search-input__end-button">Search</button>
    			</form>
    		</div>
    	</div>
    </div>
    
    			<nav class="vector-user-links vector-user-links-wide" aria-label="Personal tools">
    	<div class="vector-user-links-main">
    	
    <div id="p-vector-user-menu-preferences" class="vector-menu mw-portlet emptyPortlet"  >
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			
    		</ul>
    		
    	</div>
    </div>
    
    	
    <div id="p-vector-user-menu-userpage" class="vector-menu mw-portlet"  >
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			<li id="ca-sitesupport" class="mw-list-item user-links-collapsible-item"><a data-mw="interface" href="https://donate.wikimedia.org/wiki/Special:FundraiserRedirector?utm_source=donate&amp;utm_medium=sidebar&amp;utm_campaign=C13_en.wikipedia.org&amp;uselang=en" title="Support us by donating to the Wikimedia Foundation" class=""><span>Donate</span></a>
    </li>
    
    			
    		</ul>
    		
    	</div>
    </div>
    
    	<nav class="vector-appearance-landmark" aria-label="Appearance">
    		
    <div id="vector-appearance-dropdown" class="vector-dropdown "  title="Change the appearance of the page&#039;s font size, width, and color" >
    	<input type="checkbox" id="vector-appearance-dropdown-checkbox" role="button" aria-haspopup="true" data-event-name="ui.dropdown-vector-appearance-dropdown" class="vector-dropdown-checkbox "  aria-label="Appearance"  >
    	<label id="vector-appearance-dropdown-label" for="vector-appearance-dropdown-checkbox" class="vector-dropdown-label cdx-button cdx-button--fake-button cdx-button--fake-button--enabled cdx-button--weight-quiet cdx-button--icon-only " aria-hidden="true"  ><span class="vector-icon mw-ui-icon-appearance mw-ui-icon-wikimedia-appearance"></span>
    
    <span class="vector-dropdown-label-text">Appearance</span>
    	</label>
    	<div class="vector-dropdown-content">
    
    
    			<div id="vector-appearance-unpinned-container" class="vector-unpinned-container">
    				
    			</div>
    		
    	</div>
    </div>
    
    	</nav>
    	
    <div id="p-vector-user-menu-notifications" class="vector-menu mw-portlet emptyPortlet"  >
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			
    		</ul>
    		
    	</div>
    </div>
    
    	
    <div id="p-vector-user-menu-overflow" class="vector-menu mw-portlet"  >
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			<li id="pt-createaccount-2" class="user-links-collapsible-item mw-list-item user-links-collapsible-item"><a data-mw="interface" href="/w/index.php?title=Special:CreateAccount&amp;returnto=List+of+active+Indian+military+aircraft" title="You are encouraged to create an account and log in; however, it is not mandatory" class=""><span>Create account</span></a>
    </li>
    <li id="pt-login-2" class="user-links-collapsible-item mw-list-item user-links-collapsible-item"><a data-mw="interface" href="/w/index.php?title=Special:UserLogin&amp;returnto=List+of+active+Indian+military+aircraft" title="You&#039;re encouraged to log in; however, it&#039;s not mandatory. [o]" accesskey="o" class=""><span>Log in</span></a>
    </li>
    
    			
    		</ul>
    		
    	</div>
    </div>
    
    	</div>
    	
    <div id="vector-user-links-dropdown" class="vector-dropdown vector-user-menu vector-button-flush-right vector-user-menu-logged-out"  title="Log in and more options" >
    	<input type="checkbox" id="vector-user-links-dropdown-checkbox" role="button" aria-haspopup="true" data-event-name="ui.dropdown-vector-user-links-dropdown" class="vector-dropdown-checkbox "  aria-label="Personal tools"  >
    	<label id="vector-user-links-dropdown-label" for="vector-user-links-dropdown-checkbox" class="vector-dropdown-label cdx-button cdx-button--fake-button cdx-button--fake-button--enabled cdx-button--weight-quiet cdx-button--icon-only " aria-hidden="true"  ><span class="vector-icon mw-ui-icon-ellipsis mw-ui-icon-wikimedia-ellipsis"></span>
    
    <span class="vector-dropdown-label-text">Personal tools</span>
    	</label>
    	<div class="vector-dropdown-content">
    
    
    		
    <div id="p-personal" class="vector-menu mw-portlet mw-portlet-personal user-links-collapsible-item"  title="User menu" >
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			<li id="pt-createaccount" class="user-links-collapsible-item mw-list-item"><a href="/w/index.php?title=Special:CreateAccount&amp;returnto=List+of+active+Indian+military+aircraft" title="You are encouraged to create an account and log in; however, it is not mandatory"><span class="vector-icon mw-ui-icon-userAdd mw-ui-icon-wikimedia-userAdd"></span> <span>Create account</span></a></li><li id="pt-login" class="user-links-collapsible-item mw-list-item"><a href="/w/index.php?title=Special:UserLogin&amp;returnto=List+of+active+Indian+military+aircraft" title="You&#039;re encouraged to log in; however, it&#039;s not mandatory. [o]" accesskey="o"><span class="vector-icon mw-ui-icon-logIn mw-ui-icon-wikimedia-logIn"></span> <span>Log in</span></a></li>
    		</ul>
    		
    	</div>
    </div>
    
    <div id="p-user-menu-anon-editor" class="vector-menu mw-portlet mw-portlet-user-menu-anon-editor"  >
    	<div class="vector-menu-heading">
    		Pages for logged out editors <a href="/wiki/Help:Introduction" aria-label="Learn more about editing"><span>learn more</span></a>
    	</div>
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			<li id="pt-anoncontribs" class="mw-list-item"><a href="/wiki/Special:MyContributions" title="A list of edits made from this IP address [y]" accesskey="y"><span>Contributions</span></a></li><li id="pt-anontalk" class="mw-list-item"><a href="/wiki/Special:MyTalk" title="Discussion about edits from this IP address [n]" accesskey="n"><span>Talk</span></a></li>
    		</ul>
    		
    	</div>
    </div>
    
    	
    	</div>
    </div>
    
    </nav>
    
    		</div>
    	</header>
    </div>
    <div class="mw-page-container">
    	<div class="mw-page-container-inner">
    		<div class="vector-sitenotice-container">
    			<div id="siteNotice"><!-- CentralNotice --></div>
    		</div>
    		<div class="vector-column-start">
    			<div class="vector-main-menu-container">
    		<div id="mw-navigation">
    			<nav id="mw-panel" class="vector-main-menu-landmark" aria-label="Site">
    				<div id="vector-main-menu-pinned-container" class="vector-pinned-container">
    				
    				</div>
    		</nav>
    		</div>
    	</div>
    	<div class="vector-sticky-pinned-container">
    				<nav id="mw-panel-toc" aria-label="Contents" data-event-name="ui.sidebar-toc" class="mw-table-of-contents-container vector-toc-landmark">
    					<div id="vector-toc-pinned-container" class="vector-pinned-container">
    					<div id="vector-toc" class="vector-toc vector-pinnable-element">
    	<div
    	class="vector-pinnable-header vector-toc-pinnable-header vector-pinnable-header-pinned"
    	data-feature-name="toc-pinned"
    	data-pinnable-element-id="vector-toc"
    	
    	
    >
    	<h2 class="vector-pinnable-header-label">Contents</h2>
    	<button class="vector-pinnable-header-toggle-button vector-pinnable-header-pin-button" data-event-name="pinnable-header.vector-toc.pin">move to sidebar</button>
    	<button class="vector-pinnable-header-toggle-button vector-pinnable-header-unpin-button" data-event-name="pinnable-header.vector-toc.unpin">hide</button>
    </div>
    
    
    	<ul class="vector-toc-contents" id="mw-panel-toc-list">
    		<li id="toc-mw-content-text"
    			class="vector-toc-list-item vector-toc-level-1">
    			<a href="#" class="vector-toc-link">
    				<div class="vector-toc-text">(Top)</div>
    			</a>
    		</li>
    		<li id="toc-Air_Force"
    		class="vector-toc-list-item vector-toc-level-1 vector-toc-list-item-expanded">
    		<a class="vector-toc-link" href="#Air_Force">
    			<div class="vector-toc-text">
    				<span class="vector-toc-numb">1</span>
    				<span>Air Force</span>
    			</div>
    		</a>
    		
    		<ul id="toc-Air_Force-sublist" class="vector-toc-list">
    		</ul>
    	</li>
    	<li id="toc-Army_Aviation_Corps"
    		class="vector-toc-list-item vector-toc-level-1 vector-toc-list-item-expanded">
    		<a class="vector-toc-link" href="#Army_Aviation_Corps">
    			<div class="vector-toc-text">
    				<span class="vector-toc-numb">2</span>
    				<span>Army Aviation Corps</span>
    			</div>
    		</a>
    		
    		<ul id="toc-Army_Aviation_Corps-sublist" class="vector-toc-list">
    		</ul>
    	</li>
    	<li id="toc-Naval_Air_Arm"
    		class="vector-toc-list-item vector-toc-level-1 vector-toc-list-item-expanded">
    		<a class="vector-toc-link" href="#Naval_Air_Arm">
    			<div class="vector-toc-text">
    				<span class="vector-toc-numb">3</span>
    				<span>Naval Air Arm</span>
    			</div>
    		</a>
    		
    		<ul id="toc-Naval_Air_Arm-sublist" class="vector-toc-list">
    		</ul>
    	</li>
    	<li id="toc-Coast_Guard"
    		class="vector-toc-list-item vector-toc-level-1 vector-toc-list-item-expanded">
    		<a class="vector-toc-link" href="#Coast_Guard">
    			<div class="vector-toc-text">
    				<span class="vector-toc-numb">4</span>
    				<span>Coast Guard</span>
    			</div>
    		</a>
    		
    		<ul id="toc-Coast_Guard-sublist" class="vector-toc-list">
    		</ul>
    	</li>
    	<li id="toc-See_also"
    		class="vector-toc-list-item vector-toc-level-1 vector-toc-list-item-expanded">
    		<a class="vector-toc-link" href="#See_also">
    			<div class="vector-toc-text">
    				<span class="vector-toc-numb">5</span>
    				<span>See also</span>
    			</div>
    		</a>
    		
    		<ul id="toc-See_also-sublist" class="vector-toc-list">
    		</ul>
    	</li>
    	<li id="toc-References"
    		class="vector-toc-list-item vector-toc-level-1 vector-toc-list-item-expanded">
    		<a class="vector-toc-link" href="#References">
    			<div class="vector-toc-text">
    				<span class="vector-toc-numb">6</span>
    				<span>References</span>
    			</div>
    		</a>
    		
    		<ul id="toc-References-sublist" class="vector-toc-list">
    		</ul>
    	</li>
    	<li id="toc-External_links"
    		class="vector-toc-list-item vector-toc-level-1 vector-toc-list-item-expanded">
    		<a class="vector-toc-link" href="#External_links">
    			<div class="vector-toc-text">
    				<span class="vector-toc-numb">7</span>
    				<span>External links</span>
    			</div>
    		</a>
    		
    		<ul id="toc-External_links-sublist" class="vector-toc-list">
    		</ul>
    	</li>
    </ul>
    </div>
    
    					</div>
    		</nav>
    			</div>
    		</div>
    		<div class="mw-content-container">
    			<main id="content" class="mw-body">
    				<header class="mw-body-header vector-page-titlebar">
    					<nav aria-label="Contents" class="vector-toc-landmark">
    						
    <div id="vector-page-titlebar-toc" class="vector-dropdown vector-page-titlebar-toc vector-button-flush-left"  >
    	<input type="checkbox" id="vector-page-titlebar-toc-checkbox" role="button" aria-haspopup="true" data-event-name="ui.dropdown-vector-page-titlebar-toc" class="vector-dropdown-checkbox "  aria-label="Toggle the table of contents"  >
    	<label id="vector-page-titlebar-toc-label" for="vector-page-titlebar-toc-checkbox" class="vector-dropdown-label cdx-button cdx-button--fake-button cdx-button--fake-button--enabled cdx-button--weight-quiet cdx-button--icon-only " aria-hidden="true"  ><span class="vector-icon mw-ui-icon-listBullet mw-ui-icon-wikimedia-listBullet"></span>
    
    <span class="vector-dropdown-label-text">Toggle the table of contents</span>
    	</label>
    	<div class="vector-dropdown-content">
    
    
    							<div id="vector-page-titlebar-toc-unpinned-container" class="vector-unpinned-container">
    			</div>
    		
    	</div>
    </div>
    
    					</nav>
    					<h1 id="firstHeading" class="firstHeading mw-first-heading"><span class="mw-page-title-main">List of active Indian military aircraft</span></h1>
    							
    <div id="p-lang-btn" class="vector-dropdown mw-portlet mw-portlet-lang"  >
    	<input type="checkbox" id="p-lang-btn-checkbox" role="button" aria-haspopup="true" data-event-name="ui.dropdown-p-lang-btn" class="vector-dropdown-checkbox mw-interlanguage-selector" aria-label="Go to an article in another language. Available in 2 languages"   >
    	<label id="p-lang-btn-label" for="p-lang-btn-checkbox" class="vector-dropdown-label cdx-button cdx-button--fake-button cdx-button--fake-button--enabled cdx-button--weight-quiet cdx-button--action-progressive mw-portlet-lang-heading-2" aria-hidden="true"  ><span class="vector-icon mw-ui-icon-language-progressive mw-ui-icon-wikimedia-language-progressive"></span>
    
    <span class="vector-dropdown-label-text">2 languages</span>
    	</label>
    	<div class="vector-dropdown-content">
    
    		<div class="vector-menu-content">
    			
    			<ul class="vector-menu-content-list">
    				
    				<li class="interlanguage-link interwiki-ml mw-list-item"><a href="https://ml.wikipedia.org/wiki/%E0%B4%AD%E0%B4%BE%E0%B4%B0%E0%B4%A4%E0%B5%80%E0%B4%AF_%E0%B4%B5%E0%B4%BE%E0%B4%AF%E0%B5%81%E0%B4%B8%E0%B5%87%E0%B4%A8_%E0%B4%89%E0%B4%AA%E0%B4%AF%E0%B5%8B%E0%B4%97%E0%B4%BF%E0%B4%95%E0%B5%8D%E0%B4%95%E0%B5%81%E0%B4%A8%E0%B5%8D%E0%B4%A8_%E0%B4%B5%E0%B4%BF%E0%B4%AE%E0%B4%BE%E0%B4%A8%E0%B4%99%E0%B5%8D%E0%B4%99%E0%B5%BE" title="ഭാരതീയ വായുസേന ഉപയോഗിക്കുന്ന വിമാനങ്ങൾ – Malayalam" lang="ml" hreflang="ml" data-title="ഭാരതീയ വായുസേന ഉപയോഗിക്കുന്ന വിമാനങ്ങൾ" data-language-autonym="മലയാളം" data-language-local-name="Malayalam" class="interlanguage-link-target"><span>മലയാളം</span></a></li><li class="interlanguage-link interwiki-ta mw-list-item"><a href="https://ta.wikipedia.org/wiki/%E0%AE%87%E0%AE%A8%E0%AF%8D%E0%AE%A4%E0%AE%BF%E0%AE%AF_%E0%AE%87%E0%AE%B0%E0%AE%BE%E0%AE%A3%E0%AF%81%E0%AE%B5%E0%AE%A4%E0%AF%8D%E0%AE%A4%E0%AE%BF%E0%AE%B2%E0%AF%8D_%E0%AE%9A%E0%AF%86%E0%AE%AF%E0%AE%B2%E0%AF%8D%E0%AE%AA%E0%AE%BE%E0%AE%9F%E0%AF%8D%E0%AE%9F%E0%AE%BF%E0%AE%B2%E0%AF%8D_%E0%AE%89%E0%AE%B3%E0%AF%8D%E0%AE%B3_%E0%AE%B5%E0%AE%BE%E0%AE%A9%E0%AF%82%E0%AE%B0%E0%AF%8D%E0%AE%A4%E0%AE%BF%E0%AE%95%E0%AE%B3%E0%AE%BF%E0%AE%A9%E0%AF%8D_%E0%AE%AA%E0%AE%9F%E0%AF%8D%E0%AE%9F%E0%AE%BF%E0%AE%AF%E0%AE%B2%E0%AF%8D" title="இந்திய இராணுவத்தில் செயல்பாட்டில் உள்ள வானூர்திகளின் பட்டியல் – Tamil" lang="ta" hreflang="ta" data-title="இந்திய இராணுவத்தில் செயல்பாட்டில் உள்ள வானூர்திகளின் பட்டியல்" data-language-autonym="தமிழ்" data-language-local-name="Tamil" class="interlanguage-link-target"><span>தமிழ்</span></a></li>
    			</ul>
    			<div class="after-portlet after-portlet-lang"><span class="wb-langlinks-edit wb-langlinks-link"><a href="https://www.wikidata.org/wiki/Special:EntityPage/Q6604953#sitelinks-wikipedia" title="Edit interlanguage links" class="wbc-editpage">Edit links</a></span></div>
    		</div>
    
    	</div>
    </div>
    </header>
    				<div class="vector-page-toolbar">
    					<div class="vector-page-toolbar-container">
    						<div id="left-navigation">
    							<nav aria-label="Namespaces">
    								
    <div id="p-associated-pages" class="vector-menu vector-menu-tabs mw-portlet mw-portlet-associated-pages"  >
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			<li id="ca-nstab-main" class="selected vector-tab-noicon mw-list-item"><a href="/wiki/List_of_active_Indian_military_aircraft" title="View the content page [c]" accesskey="c"><span>Article</span></a></li><li id="ca-talk" class="vector-tab-noicon mw-list-item"><a href="/wiki/Talk:List_of_active_Indian_military_aircraft" rel="discussion" title="Discuss improvements to the content page [t]" accesskey="t"><span>Talk</span></a></li>
    		</ul>
    		
    	</div>
    </div>
    
    								
    <div id="vector-variants-dropdown" class="vector-dropdown emptyPortlet"  >
    	<input type="checkbox" id="vector-variants-dropdown-checkbox" role="button" aria-haspopup="true" data-event-name="ui.dropdown-vector-variants-dropdown" class="vector-dropdown-checkbox " aria-label="Change language variant"   >
    	<label id="vector-variants-dropdown-label" for="vector-variants-dropdown-checkbox" class="vector-dropdown-label cdx-button cdx-button--fake-button cdx-button--fake-button--enabled cdx-button--weight-quiet" aria-hidden="true"  ><span class="vector-dropdown-label-text">English</span>
    	</label>
    	<div class="vector-dropdown-content">
    
    
    					
    <div id="p-variants" class="vector-menu mw-portlet mw-portlet-variants emptyPortlet"  >
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			
    		</ul>
    		
    	</div>
    </div>
    
    				
    	</div>
    </div>
    
    							</nav>
    						</div>
    						<div id="right-navigation" class="vector-collapsible">
    							<nav aria-label="Views">
    								
    <div id="p-views" class="vector-menu vector-menu-tabs mw-portlet mw-portlet-views"  >
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			<li id="ca-view" class="selected vector-tab-noicon mw-list-item"><a href="/wiki/List_of_active_Indian_military_aircraft"><span>Read</span></a></li><li id="ca-viewsource" class="vector-tab-noicon mw-list-item"><a href="/w/index.php?title=List_of_active_Indian_military_aircraft&amp;action=edit" title="This page is protected.&#10;You can view its source [e]" accesskey="e"><span>View source</span></a></li><li id="ca-history" class="vector-tab-noicon mw-list-item"><a href="/w/index.php?title=List_of_active_Indian_military_aircraft&amp;action=history" title="Past revisions of this page [h]" accesskey="h"><span>View history</span></a></li>
    		</ul>
    		
    	</div>
    </div>
    
    							</nav>
    				
    							<nav class="vector-page-tools-landmark" aria-label="Page tools">
    								
    <div id="vector-page-tools-dropdown" class="vector-dropdown vector-page-tools-dropdown"  >
    	<input type="checkbox" id="vector-page-tools-dropdown-checkbox" role="button" aria-haspopup="true" data-event-name="ui.dropdown-vector-page-tools-dropdown" class="vector-dropdown-checkbox "  aria-label="Tools"  >
    	<label id="vector-page-tools-dropdown-label" for="vector-page-tools-dropdown-checkbox" class="vector-dropdown-label cdx-button cdx-button--fake-button cdx-button--fake-button--enabled cdx-button--weight-quiet" aria-hidden="true"  ><span class="vector-dropdown-label-text">Tools</span>
    	</label>
    	<div class="vector-dropdown-content">
    
    
    									<div id="vector-page-tools-unpinned-container" class="vector-unpinned-container">
    						
    <div id="vector-page-tools" class="vector-page-tools vector-pinnable-element">
    	<div
    	class="vector-pinnable-header vector-page-tools-pinnable-header vector-pinnable-header-unpinned"
    	data-feature-name="page-tools-pinned"
    	data-pinnable-element-id="vector-page-tools"
    	data-pinned-container-id="vector-page-tools-pinned-container"
    	data-unpinned-container-id="vector-page-tools-unpinned-container"
    >
    	<div class="vector-pinnable-header-label">Tools</div>
    	<button class="vector-pinnable-header-toggle-button vector-pinnable-header-pin-button" data-event-name="pinnable-header.vector-page-tools.pin">move to sidebar</button>
    	<button class="vector-pinnable-header-toggle-button vector-pinnable-header-unpin-button" data-event-name="pinnable-header.vector-page-tools.unpin">hide</button>
    </div>
    
    	
    <div id="p-cactions" class="vector-menu mw-portlet mw-portlet-cactions emptyPortlet vector-has-collapsible-items"  title="More options" >
    	<div class="vector-menu-heading">
    		Actions
    	</div>
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			<li id="ca-more-view" class="selected vector-more-collapsible-item mw-list-item"><a href="/wiki/List_of_active_Indian_military_aircraft"><span>Read</span></a></li><li id="ca-more-viewsource" class="vector-more-collapsible-item mw-list-item"><a href="/w/index.php?title=List_of_active_Indian_military_aircraft&amp;action=edit"><span>View source</span></a></li><li id="ca-more-history" class="vector-more-collapsible-item mw-list-item"><a href="/w/index.php?title=List_of_active_Indian_military_aircraft&amp;action=history"><span>View history</span></a></li>
    		</ul>
    		
    	</div>
    </div>
    
    <div id="p-tb" class="vector-menu mw-portlet mw-portlet-tb"  >
    	<div class="vector-menu-heading">
    		General
    	</div>
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			<li id="t-whatlinkshere" class="mw-list-item"><a href="/wiki/Special:WhatLinksHere/List_of_active_Indian_military_aircraft" title="List of all English Wikipedia pages containing links to this page [j]" accesskey="j"><span>What links here</span></a></li><li id="t-recentchangeslinked" class="mw-list-item"><a href="/wiki/Special:RecentChangesLinked/List_of_active_Indian_military_aircraft" rel="nofollow" title="Recent changes in pages linked from this page [k]" accesskey="k"><span>Related changes</span></a></li><li id="t-upload" class="mw-list-item"><a href="/wiki/Wikipedia:File_Upload_Wizard" title="Upload files [u]" accesskey="u"><span>Upload file</span></a></li><li id="t-specialpages" class="mw-list-item"><a href="/wiki/Special:SpecialPages" title="A list of all special pages [q]" accesskey="q"><span>Special pages</span></a></li><li id="t-permalink" class="mw-list-item"><a href="/w/index.php?title=List_of_active_Indian_military_aircraft&amp;oldid=1250455700" title="Permanent link to this revision of this page"><span>Permanent link</span></a></li><li id="t-info" class="mw-list-item"><a href="/w/index.php?title=List_of_active_Indian_military_aircraft&amp;action=info" title="More information about this page"><span>Page information</span></a></li><li id="t-cite" class="mw-list-item"><a href="/w/index.php?title=Special:CiteThisPage&amp;page=List_of_active_Indian_military_aircraft&amp;id=1250455700&amp;wpFormIdentifier=titleform" title="Information on how to cite this page"><span>Cite this page</span></a></li><li id="t-urlshortener" class="mw-list-item"><a href="/w/index.php?title=Special:UrlShortener&amp;url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FList_of_active_Indian_military_aircraft"><span>Get shortened URL</span></a></li><li id="t-urlshortener-qrcode" class="mw-list-item"><a href="/w/index.php?title=Special:QrCode&amp;url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FList_of_active_Indian_military_aircraft"><span>Download QR code</span></a></li><li id="t-wikibase" class="mw-list-item"><a href="https://www.wikidata.org/wiki/Special:EntityPage/Q6604953" title="Structured data on this page hosted by Wikidata [g]" accesskey="g"><span>Wikidata item</span></a></li>
    		</ul>
    		
    	</div>
    </div>
    
    <div id="p-coll-print_export" class="vector-menu mw-portlet mw-portlet-coll-print_export"  >
    	<div class="vector-menu-heading">
    		Print/export
    	</div>
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			<li id="coll-download-as-rl" class="mw-list-item"><a href="/w/index.php?title=Special:DownloadAsPdf&amp;page=List_of_active_Indian_military_aircraft&amp;action=show-download-screen" title="Download this page as a PDF file"><span>Download as PDF</span></a></li><li id="t-print" class="mw-list-item"><a href="/w/index.php?title=List_of_active_Indian_military_aircraft&amp;printable=yes" title="Printable version of this page [p]" accesskey="p"><span>Printable version</span></a></li>
    		</ul>
    		
    	</div>
    </div>
    
    <div id="p-wikibase-otherprojects" class="vector-menu mw-portlet mw-portlet-wikibase-otherprojects emptyPortlet"  >
    	<div class="vector-menu-heading">
    		In other projects
    	</div>
    	<div class="vector-menu-content">
    		
    		<ul class="vector-menu-content-list">
    			
    			
    		</ul>
    		
    	</div>
    </div>
    
    </div>
    
    									</div>
    				
    	</div>
    </div>
    
    							</nav>
    						</div>
    					</div>
    				</div>
    				<div class="vector-column-end">
    					<div class="vector-sticky-pinned-container">
    						<nav class="vector-page-tools-landmark" aria-label="Page tools">
    							<div id="vector-page-tools-pinned-container" class="vector-pinned-container">
    				
    							</div>
    		</nav>
    						<nav class="vector-appearance-landmark" aria-label="Appearance">
    							<div id="vector-appearance-pinned-container" class="vector-pinned-container">
    				<div id="vector-appearance" class="vector-appearance vector-pinnable-element">
    	<div
    	class="vector-pinnable-header vector-appearance-pinnable-header vector-pinnable-header-pinned"
    	data-feature-name="appearance-pinned"
    	data-pinnable-element-id="vector-appearance"
    	data-pinned-container-id="vector-appearance-pinned-container"
    	data-unpinned-container-id="vector-appearance-unpinned-container"
    >
    	<div class="vector-pinnable-header-label">Appearance</div>
    	<button class="vector-pinnable-header-toggle-button vector-pinnable-header-pin-button" data-event-name="pinnable-header.vector-appearance.pin">move to sidebar</button>
    	<button class="vector-pinnable-header-toggle-button vector-pinnable-header-unpin-button" data-event-name="pinnable-header.vector-appearance.unpin">hide</button>
    </div>
    
    
    </div>
    
    							</div>
    		</nav>
    					</div>
    				</div>
    				<div id="bodyContent" class="vector-body" aria-labelledby="firstHeading" data-mw-ve-target-container>
    					<div class="vector-body-before-content">
    							<div class="mw-indicators">
    		<div id="mw-indicator-pp-default" class="mw-indicator"><div class="mw-parser-output"><span typeof="mw:File"><a href="/wiki/Wikipedia:Protection_policy#semi" title="This article is semi-protected until January 16, 2026 at 09:19 UTC."><img alt="Page semi-protected" src="//upload.wikimedia.org/wikipedia/en/thumb/1/1b/Semi-protection-shackle.svg/20px-Semi-protection-shackle.svg.png" decoding="async" width="20" height="20" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/en/thumb/1/1b/Semi-protection-shackle.svg/30px-Semi-protection-shackle.svg.png 1.5x, //upload.wikimedia.org/wikipedia/en/thumb/1/1b/Semi-protection-shackle.svg/40px-Semi-protection-shackle.svg.png 2x" data-file-width="512" data-file-height="512" /></a></span></div></div>
    		</div>
    
    						<div id="siteSub" class="noprint">From Wikipedia, the free encyclopedia</div>
    					</div>
    					<div id="contentSub"><div id="mw-content-subtitle"></div></div>
    					
    					
    					<div id="mw-content-text" class="mw-body-content"><div class="mw-content-ltr mw-parser-output" lang="en" dir="ltr"><p class="mw-empty-elt">
    </p>
    <div class="shortdescription nomobile noexcerpt noprint searchaux" style="display:none">Current aircraft of the Indian Armed Forces</div>
    <p>
    This article provides a <b>list of active Indian military aircraft</b> currently in service with the <a href="/wiki/Indian_Armed_Forces" title="Indian Armed Forces">Indian Armed Forces</a>, as well as aircraft on order. For a list of historical <a href="/wiki/Military_aircraft" title="Military aircraft">military aircraft</a> used by the Indian military, see <a href="/wiki/List_of_historical_aircraft_of_the_Indian_Air_Force" title="List of historical aircraft of the Indian Air Force">list of historical aircraft of the Indian Air Force</a>.
    </p>
    <meta property="mw:PageProp/toc" />
    <div class="mw-heading mw-heading2"><h2 id="Air_Force">Air Force</h2></div>
    <style data-mw-deduplicate="TemplateStyles:r1236090951">.mw-parser-output .hatnote{font-style:italic}.mw-parser-output div.hatnote{padding-left:1.6em;margin-bottom:0.5em}.mw-parser-output .hatnote i{font-style:normal}.mw-parser-output .hatnote+link+.hatnote{margin-top:-0.5em}@media print{body.ns-0 .mw-parser-output .hatnote{display:none!important}}</style><div role="note" class="hatnote navigation-not-searchable">Further information: <a href="/wiki/Indian_Air_Force" title="Indian Air Force">Indian Air Force</a> and <a href="/wiki/Future_of_the_Indian_Air_Force" title="Future of the Indian Air Force">Future of the Indian Air Force</a></div>
    <figure class="mw-default-size" typeof="mw:File/Thumb"><a href="/wiki/File:Tejas_MK1_TarangShakti24.jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/d/d2/Tejas_MK1_TarangShakti24.jpg/220px-Tejas_MK1_TarangShakti24.jpg" decoding="async" width="220" height="147" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/d/d2/Tejas_MK1_TarangShakti24.jpg/330px-Tejas_MK1_TarangShakti24.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/d/d2/Tejas_MK1_TarangShakti24.jpg/440px-Tejas_MK1_TarangShakti24.jpg 2x" data-file-width="1280" data-file-height="853" /></a><figcaption><a href="/wiki/HAL_Tejas" title="HAL Tejas">HAL Tejas</a> at TarangShakti 2024</figcaption></figure>
    <figure class="mw-default-size" typeof="mw:File/Thumb"><a href="/wiki/File:RB005_-_Dassault_Rafale_-_Indian_Air_Force_-_50976863128.jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/0/08/RB005_-_Dassault_Rafale_-_Indian_Air_Force_-_50976863128.jpg/220px-RB005_-_Dassault_Rafale_-_Indian_Air_Force_-_50976863128.jpg" decoding="async" width="220" height="140" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/0/08/RB005_-_Dassault_Rafale_-_Indian_Air_Force_-_50976863128.jpg/330px-RB005_-_Dassault_Rafale_-_Indian_Air_Force_-_50976863128.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/0/08/RB005_-_Dassault_Rafale_-_Indian_Air_Force_-_50976863128.jpg/440px-RB005_-_Dassault_Rafale_-_Indian_Air_Force_-_50976863128.jpg 2x" data-file-width="3780" data-file-height="2411" /></a><figcaption>IAF <a href="/wiki/Rafale" class="mw-redirect" title="Rafale">Rafale</a> take off from <a href="/wiki/Dassault_Aviation" title="Dassault Aviation">Dassault Aviation</a> Facility, <a href="/wiki/Bordeaux%E2%80%93M%C3%A9rignac_Airport" title="Bordeaux–Mérignac Airport">Merignac</a>, France.</figcaption></figure>
    <figure class="mw-default-size" typeof="mw:File/Thumb"><a href="/wiki/File:Su-30_MKI_firing_Brahmos-ER.jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/5/52/Su-30_MKI_firing_Brahmos-ER.jpg/220px-Su-30_MKI_firing_Brahmos-ER.jpg" decoding="async" width="220" height="147" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/5/52/Su-30_MKI_firing_Brahmos-ER.jpg/330px-Su-30_MKI_firing_Brahmos-ER.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/5/52/Su-30_MKI_firing_Brahmos-ER.jpg/440px-Su-30_MKI_firing_Brahmos-ER.jpg 2x" data-file-width="660" data-file-height="440" /></a><figcaption>A Su-30MKI firing Brahmos ER</figcaption></figure>
    <figure class="mw-default-size mw-halign-right" typeof="mw:File/Thumb"><a href="/wiki/File:DRDO_AEW%26C_Embraer_ERJ_145.JPG" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/f/fa/DRDO_AEW%26C_Embraer_ERJ_145.JPG/220px-DRDO_AEW%26C_Embraer_ERJ_145.JPG" decoding="async" width="220" height="144" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/f/fa/DRDO_AEW%26C_Embraer_ERJ_145.JPG/330px-DRDO_AEW%26C_Embraer_ERJ_145.JPG 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/f/fa/DRDO_AEW%26C_Embraer_ERJ_145.JPG/440px-DRDO_AEW%26C_Embraer_ERJ_145.JPG 2x" data-file-width="1334" data-file-height="876" /></a><figcaption>Netra AEW&amp;C on Embraer ERJ 145 platform</figcaption></figure>
    <figure class="mw-default-size mw-halign-right" typeof="mw:File/Thumb"><a href="/wiki/File:IAF-C-17.jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/3/30/IAF-C-17.jpg/220px-IAF-C-17.jpg" decoding="async" width="220" height="157" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/3/30/IAF-C-17.jpg/330px-IAF-C-17.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/3/30/IAF-C-17.jpg/440px-IAF-C-17.jpg 2x" data-file-width="2100" data-file-height="1500" /></a><figcaption><a href="/wiki/Boeing_C-17_Globemaster_III" title="Boeing C-17 Globemaster III">C-17 Globemaster III</a> in service</figcaption></figure>
    <figure class="mw-default-size" typeof="mw:File/Thumb"><a href="/wiki/File:C-295_Indian_Air_Force.jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/9/95/C-295_Indian_Air_Force.jpg/220px-C-295_Indian_Air_Force.jpg" decoding="async" width="220" height="124" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/9/95/C-295_Indian_Air_Force.jpg/330px-C-295_Indian_Air_Force.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/9/95/C-295_Indian_Air_Force.jpg/440px-C-295_Indian_Air_Force.jpg 2x" data-file-width="1024" data-file-height="576" /></a><figcaption><a href="/wiki/EADS_CASA_C-295" title="EADS CASA C-295">C-295</a> is replacing HS-748</figcaption></figure>
    <figure class="mw-default-size" typeof="mw:File/Thumb"><a href="/wiki/File:HAL_Prachand_(cropped).jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/c/c9/HAL_Prachand_%28cropped%29.jpg/220px-HAL_Prachand_%28cropped%29.jpg" decoding="async" width="220" height="146" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/c/c9/HAL_Prachand_%28cropped%29.jpg/330px-HAL_Prachand_%28cropped%29.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/c/c9/HAL_Prachand_%28cropped%29.jpg/440px-HAL_Prachand_%28cropped%29.jpg 2x" data-file-width="3815" data-file-height="2526" /></a><figcaption><a href="/wiki/HAL_Prachand" title="HAL Prachand">HAL Prachand</a></figcaption></figure>
    <table class="wikitable">
    <tbody><tr>
    <th style="text-align:center; background:#acc;">Aircraft
    </th>
    <th style="text-align: center; background:#acc;">Origin
    </th>
    <th style="text-align: center; background:#acc;">Type
    </th>
    <th style="text-align:left; background:#acc;">Variant
    </th>
    <th style="text-align:center; background:#acc;">In service
    </th>
    <th style="text-align: center; background:#acc;">Notes
    </th></tr>
    <tr>
    <th style="align: center; background: lavender;" colspan="6"><a href="/wiki/Military_aircraft#Combat_aircraft" title="Military aircraft">Combat Aircraft</a>
    </th></tr>
    <tr>
    <td rowspan="2"><a href="/wiki/Dassault_Rafale" title="Dassault Rafale">Dassault Rafale</a>
    </td>
    <td rowspan="2"><a href="/wiki/France" title="France">France</a>
    </td>
    <td rowspan="2"><a href="/wiki/Multirole_combat_aircraft" title="Multirole combat aircraft">Multirole</a>
    </td>
    <td><a href="/wiki/Dassault_Rafale#Variants" title="Dassault Rafale">DH</a>
    </td>
    <td>8<sup id="cite_ref-:1_1-0" class="reference"><a href="#cite_note-:1-1"><span class="cite-bracket">&#91;</span>1<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Dassault_Rafale#Variants" title="Dassault Rafale">EH</a>
    </td>
    <td>28<sup id="cite_ref-:1_1-1" class="reference"><a href="#cite_note-:1-1"><span class="cite-bracket">&#91;</span>1<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td rowspan="3"><a href="/wiki/HAL_Tejas" title="HAL Tejas">HAL Tejas</a>
    </td>
    <td rowspan="3"><a href="/wiki/India" title="India">India</a>
    </td>
    <td><a href="/wiki/Multirole_combat_aircraft" title="Multirole combat aircraft">Multirole</a>
    </td>
    <td><a href="/wiki/HAL_Tejas#Variants" title="HAL Tejas">Mk.1</a>
    </td>
    <td>31<sup id="cite_ref-2" class="reference"><a href="#cite_note-2"><span class="cite-bracket">&#91;</span>2<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-3" class="reference"><a href="#cite_note-3"><span class="cite-bracket">&#91;</span>3<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Trainer_aircraft#Operational_conversion" title="Trainer aircraft">Conversion trainer</a>
    </td>
    <td><a href="/wiki/HAL_Tejas#Variants" title="HAL Tejas">Mk.1 Trainer</a>
    </td>
    <td>2<sup id="cite_ref-4" class="reference"><a href="#cite_note-4"><span class="cite-bracket">&#91;</span>4<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-5" class="reference"><a href="#cite_note-5"><span class="cite-bracket">&#91;</span>5<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>Used for training; 16 more on order<sup id="cite_ref-:11_6-0" class="reference"><a href="#cite_note-:11-6"><span class="cite-bracket">&#91;</span>6<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Multirole_combat_aircraft" title="Multirole combat aircraft">Multirole</a>
    </td>
    <td><a href="/wiki/HAL_Tejas#Variants" title="HAL Tejas">Mk.1A</a>
    </td>
    <td>
    </td>
    <td>73 on order, 97 more approved<sup id="cite_ref-:11_6-1" class="reference"><a href="#cite_note-:11-6"><span class="cite-bracket">&#91;</span>6<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-7" class="reference"><a href="#cite_note-7"><span class="cite-bracket">&#91;</span>7<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Sukhoi_Su-30MKI" title="Sukhoi Su-30MKI">Sukhoi Su-30MKI</a>
    </td>
    <td><a href="/wiki/Russia" title="Russia">Russia</a>
    </td>
    <td><a href="/wiki/Multirole_combat_aircraft" title="Multirole combat aircraft">Multirole</a>
    </td>
    <td><a href="/wiki/Sukhoi_Su-30#Su-30MKI_and_derivatives" title="Sukhoi Su-30">Su-30MKI Flanker H</a>
    </td>
    <td>259<sup id="cite_ref-8" class="reference"><a href="#cite_note-8"><span class="cite-bracket">&#91;</span>8<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-9" class="reference"><a href="#cite_note-9"><span class="cite-bracket">&#91;</span>9<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>12 more cleared.<sup id="cite_ref-10" class="reference"><a href="#cite_note-10"><span class="cite-bracket">&#91;</span>10<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td rowspan="2"><a href="/wiki/Mikoyan_MiG-29" title="Mikoyan MiG-29">Mikoyan MiG-29</a>
    </td>
    <td rowspan="2"><a href="/wiki/Soviet_Union" title="Soviet Union">Soviet Union</a>
    </td>
    <td rowspan="2"><a href="/wiki/Multirole_combat_aircraft" title="Multirole combat aircraft">Multirole</a>
    </td>
    <td><a href="/wiki/Mikoyan_MiG-29#Variants" title="Mikoyan MiG-29">Fulcrum</a>
    </td>
    <td>53<sup id="cite_ref-:1_1-2" class="reference"><a href="#cite_note-:1-1"><span class="cite-bracket">&#91;</span>1<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-11" class="reference"><a href="#cite_note-11"><span class="cite-bracket">&#91;</span>11<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>Including 12 <a href="/wiki/Mikoyan_MiG-29#Variants" title="Mikoyan MiG-29">MiG-29UPG</a>.
    </td></tr>
    <tr>
    <td><a href="/wiki/Mikoyan_MiG-29#Variants" title="Mikoyan MiG-29">Fulcrum B</a>
    </td>
    <td>7<sup id="cite_ref-:1_1-3" class="reference"><a href="#cite_note-:1-1"><span class="cite-bracket">&#91;</span>1<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td rowspan="2"><a href="/wiki/Dassault_Mirage_2000" title="Dassault Mirage 2000">Dassault Mirage 2000</a>
    </td>
    <td rowspan="2"><a href="/wiki/France" title="France">France</a>
    </td>
    <td rowspan="2"><a href="/wiki/Multirole_combat_aircraft" title="Multirole combat aircraft">Multirole</a>
    </td>
    <td><a href="/wiki/Dassault_Mirage_2000#Variants" title="Dassault Mirage 2000">-2000H</a>
    </td>
    <td>37<sup id="cite_ref-:1_1-4" class="reference"><a href="#cite_note-:1-1"><span class="cite-bracket">&#91;</span>1<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Dassault_Mirage_2000#Variants" title="Dassault Mirage 2000">-2000TH</a>
    </td>
    <td>10<sup id="cite_ref-:1_1-5" class="reference"><a href="#cite_note-:1-1"><span class="cite-bracket">&#91;</span>1<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>Used for training.
    </td></tr>
    <tr>
    <td rowspan="3"><a href="/wiki/SEPECAT_Jaguar" title="SEPECAT Jaguar">SEPECAT Jaguar</a>
    </td>
    <td rowspan="3"><a href="/wiki/United_Kingdom" title="United Kingdom">United Kingdom</a>
    </td>
    <td rowspan="3"><a href="/wiki/Attack_aircraft" title="Attack aircraft">Attack</a>
    </td>
    <td><a href="/wiki/SEPECAT_Jaguar#Variants" title="SEPECAT Jaguar">IB</a>
    </td>
    <td>28<sup id="cite_ref-:1_1-6" class="reference"><a href="#cite_note-:1-1"><span class="cite-bracket">&#91;</span>1<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>Used for training.
    </td></tr>
    <tr>
    <td><a href="/wiki/SEPECAT_Jaguar#Variants" title="SEPECAT Jaguar">IS</a>
    </td>
    <td>79<sup id="cite_ref-:1_1-7" class="reference"><a href="#cite_note-:1-1"><span class="cite-bracket">&#91;</span>1<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/SEPECAT_Jaguar#Variants" title="SEPECAT Jaguar">IM</a>
    </td>
    <td>8<sup id="cite_ref-:1_1-8" class="reference"><a href="#cite_note-:1-1"><span class="cite-bracket">&#91;</span>1<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>Maritime strike aircraft carrying <a href="/wiki/Sea_Eagle_(missile)" title="Sea Eagle (missile)">Sea Eagle</a> missile.
    </td></tr>
    <tr>
    <td><a href="/wiki/Mikoyan-Gurevich_MiG-21" title="Mikoyan-Gurevich MiG-21">Mikoyan-Gurevich MiG-21</a>
    </td>
    <td><a href="/wiki/Soviet_Union" title="Soviet Union">Soviet Union</a>
    </td>
    <td><a href="/wiki/Interceptor_aircraft" title="Interceptor aircraft">Interceptor</a>
    </td>
    <td><a href="/wiki/List_of_Mikoyan-Gurevich_MiG-21_variants" title="List of Mikoyan-Gurevich MiG-21 variants">MiG-21 <i>Bison</i></a>
    </td>
    <td>40<sup id="cite_ref-12" class="reference"><a href="#cite_note-12"><span class="cite-bracket">&#91;</span>12<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>Being phased out.<sup id="cite_ref-13" class="reference"><a href="#cite_note-13"><span class="cite-bracket">&#91;</span>13<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Airborne_early_warning_and_control" title="Airborne early warning and control">AEW&amp;CS</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Embraer_R-99" title="Embraer R-99">Embraer R-99</a>
    </td>
    <td><a href="/wiki/Brazil" title="Brazil">Brazil</a>
    </td>
    <td><a href="/wiki/Airborne_early_warning_and_control" title="Airborne early warning and control">AEW&amp;C</a>
    </td>
    <td><a href="/wiki/DRDO_AEW%26CS#Platforms" title="DRDO AEW&amp;CS">Netra Mk1</a>
    </td>
    <td>3<sup id="cite_ref-:12_14-0" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>equipped with a <a href="/wiki/DRDO_AEW%26CS" title="DRDO AEW&amp;CS"> Netra AEW&amp;CS</a>.
    </td></tr>
    <tr>
    <td><a href="/wiki/Beriev_A-50" title="Beriev A-50">Beriev A-50</a>
    </td>
    <td>Soviet Union
    </td>
    <td>AEW&amp;C
    </td>
    <td><a href="/wiki/Beriev_A-50#Variants" title="Beriev A-50">A-50EI</a>
    </td>
    <td>3<sup id="cite_ref-:12_14-1" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>equipped with the <a href="/wiki/EL/W-2090" title="EL/W-2090">EL/W-2090</a> radar. 2 more planned.<sup id="cite_ref-15" class="reference"><a href="#cite_note-15"><span class="cite-bracket">&#91;</span>15<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-16" class="reference"><a href="#cite_note-16"><span class="cite-bracket">&#91;</span>16<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Reconnaissance_aircraft" title="Reconnaissance aircraft">Reconnaissance</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Boeing_707" title="Boeing 707">Boeing 707</a>
    </td>
    <td><a href="/wiki/United_States" title="United States">United States</a>
    </td>
    <td><a href="/wiki/Signals_intelligence" title="Signals intelligence">SIGINT</a> / <a href="/wiki/ELINT" class="mw-redirect" title="ELINT">ELINT</a>
    </td>
    <td>707-337C Phalcon
    </td>
    <td>1<sup id="cite_ref-:12_14-2" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td rowspan="4">Operated by <a href="/wiki/Aviation_Research_Centre" title="Aviation Research Centre">Aviation Research Centre</a> (ARC) of <a href="/wiki/Research_and_Analysis_Wing" title="Research and Analysis Wing">R&amp;AW</a>.<sup id="cite_ref-17" class="reference"><a href="#cite_note-17"><span class="cite-bracket">&#91;</span>17<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-18" class="reference"><a href="#cite_note-18"><span class="cite-bracket">&#91;</span>18<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Bombardier_Global_Express" title="Bombardier Global Express">Global 5000</a>
    </td>
    <td>United States
    </td>
    <td><a href="/wiki/Signals_intelligence" title="Signals intelligence">SIGINT</a> / <a href="/wiki/ELINT" class="mw-redirect" title="ELINT">ELINT</a>
    </td>
    <td>
    </td>
    <td>2<sup id="cite_ref-:12_14-3" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Gulfstream_III" title="Gulfstream III">Gulfstream III</a>
    </td>
    <td>United States
    </td>
    <td><a href="/wiki/Signals_intelligence#Electronic_signals_intelligence" title="Signals intelligence">ELINT</a>
    </td>
    <td><a href="/wiki/Gulfstream_III#Variants" title="Gulfstream III">SRA</a><sup id="cite_ref-19" class="reference"><a href="#cite_note-19"><span class="cite-bracket">&#91;</span>19<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>3<sup id="cite_ref-:12_14-4" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Gulfstream_G100" title="Gulfstream G100">Gulfstream G100</a>
    </td>
    <td><a href="/wiki/Israel" title="Israel">Israel</a>
    </td>
    <td><a href="/wiki/Surveillance_aircraft" title="Surveillance aircraft">surveillance</a>
    </td>
    <td><a href="/wiki/Gulfstream_G100#Variants" title="Gulfstream G100">1125 Astra</a>
    </td>
    <td>2<sup id="cite_ref-:12_14-5" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Aerial_refueling" title="Aerial refueling">Tanker</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Ilyushin_Il-78" title="Ilyushin Il-78">Ilyushin Il-78</a>
    </td>
    <td>Soviet Union
    </td>
    <td>aerial refuelling
    </td>
    <td><a href="/wiki/Ilyushin_Il-78#Variants" title="Ilyushin Il-78">Il-78MKI</a>
    </td>
    <td>6<sup id="cite_ref-:12_14-6" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Military_transport_aircraft" title="Military transport aircraft">Transport</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Boeing_777" title="Boeing 777">Boeing 777</a>
    </td>
    <td>United States
    </td>
    <td>VIP transport
    </td>
    <td><a href="/wiki/777-300ER" class="mw-redirect" title="777-300ER">777-300ER</a>
    </td>
    <td>2<sup id="cite_ref-20" class="reference"><a href="#cite_note-20"><span class="cite-bracket">&#91;</span>20<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>Used as <a href="/wiki/Air_India_One" title="Air India One">Air India One</a> for presidential flight
    </td></tr>
    <tr>
    <td><a href="/wiki/Boeing_737" title="Boeing 737">Boeing 737</a>
    </td>
    <td>United States
    </td>
    <td><a href="/wiki/Air_transports_of_heads_of_state_and_government" title="Air transports of heads of state and government">VIP transport</a>
    </td>
    <td><a href="/wiki/Boeing_737#Boeing_Business_Jet_(BBJ)" title="Boeing 737">737-700</a>
    </td>
    <td>3<sup id="cite_ref-21" class="reference"><a href="#cite_note-21"><span class="cite-bracket">&#91;</span>21<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Embraer_Legacy_600" title="Embraer Legacy 600">Embraer Legacy 600</a>
    </td>
    <td>Brazil
    </td>
    <td><a href="/wiki/Air_transports_of_heads_of_state_and_government" title="Air transports of heads of state and government">VIP transport</a>
    </td>
    <td>
    </td>
    <td>4<sup id="cite_ref-22" class="reference"><a href="#cite_note-22"><span class="cite-bracket">&#91;</span>22<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Boeing_C-17_Globemaster_III" title="Boeing C-17 Globemaster III">Boeing C-17</a>
    </td>
    <td>United States
    </td>
    <td><a href="/wiki/Strategic_airlifter" class="mw-redirect" title="Strategic airlifter">strategic airlifter</a>
    </td>
    <td>
    </td>
    <td>11<sup id="cite_ref-:12_14-7" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Ilyushin_Il-76" title="Ilyushin Il-76">Ilyushin Il-76</a>
    </td>
    <td>Soviet Union
    </td>
    <td>strategic airlifter
    </td>
    <td><a href="/wiki/Ilyushin_Il-76#Military_variants" title="Ilyushin Il-76">Il-76MD</a>
    </td>
    <td>17<sup id="cite_ref-:12_14-8" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Lockheed_Martin_C-130J_Super_Hercules" title="Lockheed Martin C-130J Super Hercules">C-130J Super Hercules</a>
    </td>
    <td>United States
    </td>
    <td><a href="/wiki/Airlift#Tactical_airlift" title="Airlift">tactical airlifter</a>
    </td>
    <td><a href="/wiki/C-130J#Variants" class="mw-redirect" title="C-130J">C-130J-30</a><sup id="cite_ref-23" class="reference"><a href="#cite_note-23"><span class="cite-bracket">&#91;</span>23<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>12<sup id="cite_ref-:12_14-9" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Airbus_A321" title="Airbus A321">Airbus A321</a>
    </td>
    <td><a href="/wiki/Europe" title="Europe">Europe</a>
    </td>
    <td>transport
    </td>
    <td><a href="/wiki/A321-200" class="mw-redirect" title="A321-200">A321-200</a>
    </td>
    <td>4<sup id="cite_ref-:12_14-10" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Antonov_An-32" title="Antonov An-32">Antonov An-32</a>
    </td>
    <td>Soviet Union
    </td>
    <td><a href="/wiki/Airlift#Tactical_airlift" title="Airlift">tactical airlifter</a>
    </td>
    <td>
    </td>
    <td>103<sup id="cite_ref-:12_14-11" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>53 are the <a href="/wiki/Antonov_An-32#Variants" title="Antonov An-32">32RE</a> variant<sup id="cite_ref-fg-27nov15_24-0" class="reference"><a href="#cite_note-fg-27nov15-24"><span class="cite-bracket">&#91;</span>24<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/EADS_CASA_C-295" title="EADS CASA C-295">EADS CASA C-295</a>
    </td>
    <td><a href="/wiki/Spain" title="Spain">Spain</a>
    </td>
    <td><a href="/wiki/Airlift#Tactical_airlift" title="Airlift">tactical airlifter</a>
    </td>
    <td><a href="/wiki/EADS_CASA_C-295#Variants" title="EADS CASA C-295">C-295MW</a>
    </td>
    <td>5<sup id="cite_ref-25" class="reference"><a href="#cite_note-25"><span class="cite-bracket">&#91;</span>25<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>51 more on order - <a href="/wiki/Hawker_Siddeley_HS_748" title="Hawker Siddeley HS 748">HS 748</a> replacement<sup id="cite_ref-26" class="reference"><a href="#cite_note-26"><span class="cite-bracket">&#91;</span>26<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Hawker_Siddeley_HS_748" title="Hawker Siddeley HS 748">Hawker Siddeley HS 748</a>
    </td>
    <td>United Kingdom
    </td>
    <td><a href="/wiki/Airlift#Tactical_airlift" title="Airlift">tactical airlifter</a>
    </td>
    <td>
    </td>
    <td>57<sup id="cite_ref-:12_14-12" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>To be replaced by <a href="/wiki/EADS_CASA_C-295" title="EADS CASA C-295">EADS CASA C-295</a>
    </td></tr>
    <tr>
    <td><a href="/wiki/Dornier_228" title="Dornier 228">Dornier Do 228</a>
    </td>
    <td><a href="/wiki/Germany" title="Germany">Germany</a>
    </td>
    <td><a href="/wiki/Airlift#Tactical_airlift" title="Airlift">tactical airlifter</a>
    </td>
    <td>228-201
    </td>
    <td>58<sup id="cite_ref-:12_14-13" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>license built by <a href="/wiki/Hindustan_Aeronautics_Limited" title="Hindustan Aeronautics Limited">HAL</a><sup id="cite_ref-jawa-04_27-0" class="reference"><a href="#cite_note-jawa-04-27"><span class="cite-bracket">&#91;</span>27<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Helicopters" class="mw-redirect" title="Helicopters">Helicopters</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Boeing_AH-64_Apache" title="Boeing AH-64 Apache">Boeing AH-64</a>
    </td>
    <td><a href="/wiki/United_States" title="United States">United States</a>
    </td>
    <td>attack
    </td>
    <td><a href="/wiki/Boeing_AH-64_Apache#AH-64E" title="Boeing AH-64 Apache">AH-64E</a>
    </td>
    <td>22<sup id="cite_ref-:12_14-14" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Mil_Mi-24" title="Mil Mi-24">Mil Mi-24</a>
    </td>
    <td>Russia
    </td>
    <td><a href="/wiki/Attack_helicopter" title="Attack helicopter">attack</a>
    </td>
    <td><a href="/wiki/List_of_Mil_Mi-24_variants" title="List of Mil Mi-24 variants">Mi-24/25/35</a>
    </td>
    <td>15<sup id="cite_ref-:12_14-15" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Light_Combat_Helicopter" class="mw-redirect" title="HAL Light Combat Helicopter">HAL Prachand</a>
    </td>
    <td>India
    </td>
    <td>attack
    </td>
    <td>
    </td>
    <td>10<sup id="cite_ref-:2_28-0" class="reference"><a href="#cite_note-:2-28"><span class="cite-bracket">&#91;</span>28<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>66 on order<sup id="cite_ref-:3_29-0" class="reference"><a href="#cite_note-:3-29"><span class="cite-bracket">&#91;</span>29<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Rudra" title="HAL Rudra">HAL Rudra</a>
    </td>
    <td>India
    </td>
    <td>attack
    </td>
    <td>
    </td>
    <td>16
    </td>
    <td>50 on order.<sup id="cite_ref-30" class="reference"><a href="#cite_note-30"><span class="cite-bracket">&#91;</span>30<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Boeing_CH-47_Chinook" title="Boeing CH-47 Chinook">CH-47 Chinook</a>
    </td>
    <td>United States
    </td>
    <td>transport
    </td>
    <td><a href="/wiki/Boeing_CH-47_Chinook#CH-47F" title="Boeing CH-47 Chinook">CH-47F</a>
    </td>
    <td>15<sup id="cite_ref-:12_14-16" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Mil_Mi-17" title="Mil Mi-17">Mil Mi-17</a>
    </td>
    <td>Russia
    </td>
    <td>utility
    </td>
    <td><a href="/wiki/Mil_Mi-17#Variants" title="Mil Mi-17">Mi-17V-5</a>
    </td>
    <td>222<sup id="cite_ref-:12_14-17" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Dhruv" title="HAL Dhruv">HAL Dhruv</a>
    </td>
    <td>India
    </td>
    <td><a href="/wiki/Utility_helicopter" title="Utility helicopter">utility</a>
    </td>
    <td>
    </td>
    <td>95<sup id="cite_ref-:12_14-18" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Light_Utility_Helicopter" title="HAL Light Utility Helicopter">HAL LUH</a>
    </td>
    <td>India
    </td>
    <td>utility
    </td>
    <td>
    </td>
    <td>
    </td>
    <td>6 on order<sup id="cite_ref-31" class="reference"><a href="#cite_note-31"><span class="cite-bracket">&#91;</span>31<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td rowspan="2"><a href="/wiki/A%C3%A9rospatiale_Alouette_III" title="Aérospatiale Alouette III">Alouette III</a>
    </td>
    <td rowspan="2">France/India
    </td>
    <td rowspan="2">liaison
    </td>
    <td><a href="/wiki/HAL_Chetak" class="mw-redirect" title="HAL Chetak">Chetak</a>
    </td>
    <td>77<sup id="cite_ref-:12_14-19" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td rowspan="3">license-built by <a href="/wiki/Hindustan_Aeronautics_Limited" title="Hindustan Aeronautics Limited">HAL</a>. A fleet of around 120 aircraft.<sup id="cite_ref-32" class="reference"><a href="#cite_note-32"><span class="cite-bracket">&#91;</span>32<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Cheetal" class="mw-redirect" title="HAL Cheetal">Cheetal</a>
    </td>
    <td>18<sup id="cite_ref-33" class="reference"><a href="#cite_note-33"><span class="cite-bracket">&#91;</span>33<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/A%C3%A9rospatiale_SA_315B_Lama" title="Aérospatiale SA 315B Lama">SA 315B Lama</a>
    </td>
    <td>France/India
    </td>
    <td>utility
    </td>
    <td><a href="/wiki/A%C3%A9rospatiale_SA_315B_Lama#Variants" title="Aérospatiale SA 315B Lama">Cheetah</a>
    </td>
    <td>18<sup id="cite_ref-:12_14-20" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Trainer_(aircraft)" class="mw-redirect" title="Trainer (aircraft)">Trainer Aircraft</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/BAE_Systems_Hawk" title="BAE Systems Hawk">BAE Hawk</a>
    </td>
    <td>United Kingdom
    </td>
    <td><a href="/wiki/Trainer_aircraft#Advanced_training" title="Trainer aircraft">Advanced trainer</a>
    </td>
    <td><a href="/wiki/BAE_Systems_Hawk#Hawk_132" title="BAE Systems Hawk">Hawk 132</a>
    </td>
    <td>101
    <p><sup id="cite_ref-:12_14-21" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-:8_34-0" class="reference"><a href="#cite_note-:8-34"><span class="cite-bracket">&#91;</span>34<span class="cite-bracket">&#93;</span></a></sup>
    </p>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Kiran" class="mw-redirect" title="HAL Kiran">HAL Kiran</a>
    </td>
    <td>India
    </td>
    <td><a href="/wiki/Trainer_aircraft" title="Trainer aircraft">Intermediate trainer</a>
    </td>
    <td>
    </td>
    <td>77<sup id="cite_ref-:12_14-22" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_HTT-40" title="HAL HTT-40">HAL HTT-40</a>
    </td>
    <td><a href="/wiki/India" title="India">India</a>
    </td>
    <td><a href="/wiki/Trainer_aircraft#Basic_training" title="Trainer aircraft">Basic trainer</a>
    </td>
    <td>
    </td>
    <td>
    </td>
    <td>70 on order <sup id="cite_ref-:12_14-23" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Pilatus_PC-7" title="Pilatus PC-7">Pilatus PC-7</a>
    </td>
    <td><a href="/wiki/Switzerland" title="Switzerland">Switzerland</a>
    </td>
    <td><a href="/wiki/Trainer_aircraft#Basic_training" title="Trainer aircraft">Basic trainer</a>
    </td>
    <td><a href="/wiki/Pilatus_PC-7#Variants" title="Pilatus PC-7">Mk II</a>
    </td>
    <td>75<sup id="cite_ref-:12_14-24" class="reference"><a href="#cite_note-:12-14"><span class="cite-bracket">&#91;</span>14<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Pipistrel_Virus" title="Pipistrel Virus">Pipistrel Virus</a>
    </td>
    <td><a href="/wiki/Slovenia" title="Slovenia">Slovenia</a>
    </td>
    <td><a href="/wiki/Ab-initio_trainer" class="mw-redirect" title="Ab-initio trainer">Ab initio trainer</a>
    </td>
    <td>
    </td>
    <td>72<sup id="cite_ref-35" class="reference"><a href="#cite_note-35"><span class="cite-bracket">&#91;</span>35<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Unmanned_aerial_vehicle" title="Unmanned aerial vehicle">UAV</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/IAI_Heron" title="IAI Heron">IAI Heron</a>
    </td>
    <td>Israel
    </td>
    <td><a href="/wiki/Surveillance_drones" class="mw-redirect" title="Surveillance drones">surveillance</a>
    </td>
    <td>Heron 1
    </td>
    <td>47<sup id="cite_ref-36" class="reference"><a href="#cite_note-36"><span class="cite-bracket">&#91;</span>36<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td><sup id="cite_ref-:06_37-0" class="reference"><a href="#cite_note-:06-37"><span class="cite-bracket">&#91;</span>37<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/IAI_Heron" title="IAI Heron">IAI Heron</a> Mk 2
    </td>
    <td>Israel
    </td>
    <td><a href="/wiki/Surveillance_drones" class="mw-redirect" title="Surveillance drones">surveillance</a>
    </td>
    <td>Mk 2
    </td>
    <td>4<sup id="cite_ref-:9_38-0" class="reference"><a href="#cite_note-:9-38"><span class="cite-bracket">&#91;</span>38<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-:10_39-0" class="reference"><a href="#cite_note-:10-39"><span class="cite-bracket">&#91;</span>39<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/IAI_Searcher" title="IAI Searcher">IAI Searcher</a>
    </td>
    <td>Israel
    </td>
    <td>surveillance
    </td>
    <td>Mk. I / II
    </td>
    <td><sup id="cite_ref-janes-16sep15_40-0" class="reference"><a href="#cite_note-janes-16sep15-40"><span class="cite-bracket">&#91;</span>40<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td>ALS-50
    </td>
    <td>India
    </td>
    <td><a href="/wiki/Loitering_munition" title="Loitering munition">loitering munition</a>
    </td>
    <td>
    </td>
    <td>100<sup id="cite_ref-41" class="reference"><a href="#cite_note-41"><span class="cite-bracket">&#91;</span>41<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a rel="nofollow" class="external text" href="http://www.kadet-uav.com/">Kadet</a> Loitering Aerial Munition
    </td>
    <td>India
    </td>
    <td><a href="/wiki/Loitering_munition" title="Loitering munition">loitering munition</a>
    </td>
    <td>
    </td>
    <td>50+ on order
    </td>
    <td>Developed by <a href="/wiki/Defence_Research_and_Development_Organisation" title="Defence Research and Development Organisation">DRDO</a> and <a rel="nofollow" class="external text" href="http://www.kadet-uav.com/">KDS</a>
    <p>Multiple variants; Weight - 15 to 120 kg; Warhead - 2 to 40 kg; Max. Endurance - 12 hrs; Max. Range - 150 to 300 km; Canister launched and vertical take-off and landing (VTOL) variants<sup id="cite_ref-42" class="reference"><a href="#cite_note-42"><span class="cite-bracket">&#91;</span>42<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-43" class="reference"><a href="#cite_note-43"><span class="cite-bracket">&#91;</span>43<span class="cite-bracket">&#93;</span></a></sup>
    </p>
    </td></tr></tbody></table>
    <div class="mw-heading mw-heading2"><h2 id="Army_Aviation_Corps">Army Aviation Corps</h2></div>
    <link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1236090951"><div role="note" class="hatnote navigation-not-searchable">Further information: <a href="/wiki/Army_Aviation_Corps_(India)" title="Army Aviation Corps (India)">Army Aviation Corps (India)</a></div> 
    <figure class="mw-default-size mw-halign-right" typeof="mw:File/Thumb"><a href="/wiki/File:Rudra_Vayushakti_2024_(cropped).jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/1/1d/Rudra_Vayushakti_2024_%28cropped%29.jpg/220px-Rudra_Vayushakti_2024_%28cropped%29.jpg" decoding="async" width="220" height="124" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/1/1d/Rudra_Vayushakti_2024_%28cropped%29.jpg/330px-Rudra_Vayushakti_2024_%28cropped%29.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/1/1d/Rudra_Vayushakti_2024_%28cropped%29.jpg/440px-Rudra_Vayushakti_2024_%28cropped%29.jpg 2x" data-file-width="1024" data-file-height="576" /></a><figcaption><a href="/wiki/HAL_Rudra" title="HAL Rudra">HAL Rudra</a> attack helicopters during Rudra Shakti 2024 exercise</figcaption></figure>
    <table class="wikitable">
    <tbody><tr>
    <th style="text-align:center; background:#acc;">Aircraft
    </th>
    <th style="text-align: center; background:#acc;">Origin
    </th>
    <th style="text-align:l center; background:#acc;">Type
    </th>
    <th style="text-align:left; background:#acc;">Variant
    </th>
    <th style="text-align:center; background:#acc;">In service
    </th>
    <th style="text-align: center; background:#acc;">Notes
    </th></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Helicopters" class="mw-redirect" title="Helicopters">Helicopters</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Boeing_AH-64_Apache" title="Boeing AH-64 Apache">Boeing AH-64</a>
    </td>
    <td>United States
    </td>
    <td>attack
    </td>
    <td><a href="/wiki/Boeing_AH-64_Apache#AH-64E" title="Boeing AH-64 Apache">AH-64E(I)</a>
    </td>
    <td>
    </td>
    <td>6 on order<sup id="cite_ref-44" class="reference"><a href="#cite_note-44"><span class="cite-bracket">&#91;</span>44<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Prachand" title="HAL Prachand">HAL Prachand</a>
    </td>
    <td>India
    </td>
    <td><a href="/wiki/Attack_helicopter" title="Attack helicopter">attack</a>
    </td>
    <td>
    </td>
    <td>
    </td>
    <td>90 on order<sup id="cite_ref-:3_29-1" class="reference"><a href="#cite_note-:3-29"><span class="cite-bracket">&#91;</span>29<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Rudra" title="HAL Rudra">HAL Rudra</a>
    </td>
    <td><a href="/wiki/India" title="India">India</a>
    </td>
    <td>attack
    </td>
    <td>
    </td>
    <td>75<sup id="cite_ref-45" class="reference"><a href="#cite_note-45"><span class="cite-bracket">&#91;</span>45<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-:7_46-0" class="reference"><a href="#cite_note-:7-46"><span class="cite-bracket">&#91;</span>46<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Dhruv" title="HAL Dhruv">HAL Dhruv</a>
    </td>
    <td><a href="/wiki/India" title="India">India</a>
    </td>
    <td><a href="/wiki/Utility_helicopter" title="Utility helicopter">utility</a>
    </td>
    <td>
    </td>
    <td>76<sup id="cite_ref-:7_46-1" class="reference"><a href="#cite_note-:7-46"><span class="cite-bracket">&#91;</span>46<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-47" class="reference"><a href="#cite_note-47"><span class="cite-bracket">&#91;</span>47<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>19 more on order<sup id="cite_ref-:02_48-0" class="reference"><a href="#cite_note-:02-48"><span class="cite-bracket">&#91;</span>48<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-49" class="reference"><a href="#cite_note-49"><span class="cite-bracket">&#91;</span>49<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/A%C3%A9rospatiale_Alouette_III" title="Aérospatiale Alouette III">Alouette III</a>
    </td>
    <td>France/India
    </td>
    <td>liaison / utility
    </td>
    <td><a href="/wiki/HAL_Chetak" class="mw-redirect" title="HAL Chetak">Chetak</a>
    </td>
    <td rowspan="2">190<sup id="cite_ref-50" class="reference"><a href="#cite_note-50"><span class="cite-bracket">&#91;</span>50<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-51" class="reference"><a href="#cite_note-51"><span class="cite-bracket">&#91;</span>51<span class="cite-bracket">&#93;</span></a></sup> - 200<sup id="cite_ref-52" class="reference"><a href="#cite_note-52"><span class="cite-bracket">&#91;</span>52<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td rowspan="2">license-built by <a href="/wiki/Hindustan_Aeronautics_Limited" title="Hindustan Aeronautics Limited">HAL</a>
    </td></tr>
    <tr>
    <td><a href="/wiki/A%C3%A9rospatiale_SA_315B_Lama" title="Aérospatiale SA 315B Lama">SA 315B Lama</a>
    </td>
    <td>France/India
    </td>
    <td>liaison / utility
    </td>
    <td><a href="/wiki/A%C3%A9rospatiale_SA_315B_Lama#Variants" title="Aérospatiale SA 315B Lama">Cheetah</a>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Unmanned_aerial_vehicle" title="Unmanned aerial vehicle">UAV</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Drishti-10" title="Drishti-10">Drishti-10</a>
    </td>
    <td><a href="/wiki/Israel" title="Israel">Israel</a>/<a href="/wiki/India" title="India">India</a>
    </td>
    <td><a href="/wiki/Reconnaissance" title="Reconnaissance">Reconnaissance</a>
    </td>
    <td>
    </td>
    <td>
    </td>
    <td>2 on order<sup id="cite_ref-:4_53-0" class="reference"><a href="#cite_note-:4-53"><span class="cite-bracket">&#91;</span>53<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/IAI_Heron" title="IAI Heron">IAI Heron</a>
    </td>
    <td>Israel
    </td>
    <td><a href="/wiki/Surveillance_aircraft" title="Surveillance aircraft">Surveillance</a>
    </td>
    <td>Heron 1
    </td>
    <td>
    </td>
    <td><sup id="cite_ref-:04_54-0" class="reference"><a href="#cite_note-:04-54"><span class="cite-bracket">&#91;</span>54<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/IAI_Eitan" title="IAI Eitan">IAI Heron TP</a>
    </td>
    <td>Israel
    </td>
    <td><a href="/wiki/Surveillance_aircraft" title="Surveillance aircraft">Surveillance</a>
    </td>
    <td>
    </td>
    <td>4<sup id="cite_ref-55" class="reference"><a href="#cite_note-55"><span class="cite-bracket">&#91;</span>55<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>Deployed in <a href="/wiki/Ladakh" title="Ladakh">Ladakh</a> and <a href="/wiki/Northeast_India" title="Northeast India">Northeast</a>.
    </td></tr>
    <tr>
    <td><a href="/wiki/IAI_Heron" title="IAI Heron">IAI Heron</a> Mk 2
    </td>
    <td>Israel
    </td>
    <td><a href="/wiki/Surveillance_aircraft" title="Surveillance aircraft">Surveillance</a>
    </td>
    <td>Mk 2
    </td>
    <td>
    </td>
    <td>6 on order<sup id="cite_ref-56" class="reference"><a href="#cite_note-56"><span class="cite-bracket">&#91;</span>56<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/IAI_Searcher" title="IAI Searcher">IAI Searcher</a><sup id="cite_ref-janes-20feb13_57-0" class="reference"><a href="#cite_note-janes-20feb13-57"><span class="cite-bracket">&#91;</span>57<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td><a href="/wiki/Israel" title="Israel">Israel</a>
    </td>
    <td><a href="/wiki/Reconnaissance" title="Reconnaissance">Reconnaissance</a>
    </td>
    <td>Mk-II
    </td>
    <td>&lt;100<sup id="cite_ref-58" class="reference"><a href="#cite_note-58"><span class="cite-bracket">&#91;</span>58<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a rel="nofollow" class="external text" href="https://ideaforgetech.com/security-and-surveillance/switch-uav">Ideaforge Switch</a> <sup id="cite_ref-Business_Standard_India_59-0" class="reference"><a href="#cite_note-Business_Standard_India-59"><span class="cite-bracket">&#91;</span>59<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-60" class="reference"><a href="#cite_note-60"><span class="cite-bracket">&#91;</span>60<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td><a href="/wiki/India" title="India">India</a>
    </td>
    <td><a href="/wiki/Surveillance_aircraft" title="Surveillance aircraft">Surveillance</a>
    </td>
    <td>1.0
    </td>
    <td>
    </td>
    <td>undisclosed quantities on order<sup id="cite_ref-Business_Standard_India_59-1" class="reference"><a href="#cite_note-Business_Standard_India-59"><span class="cite-bracket">&#91;</span>59<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    
    <tr>
    <td>NewSpace NIMBUS
    </td>
    <td><a href="/wiki/India" title="India">India</a>
    </td>
    <td><a href="/wiki/Swarming_(military)" title="Swarming (military)">Swarm</a> drones
    </td>
    <td>Mk-III
    </td>
    <td>75
    </td>
    <td rowspan="2">Part of autonomous surveillance and armed drone swarm (A-SADS)<sup id="cite_ref-ns_61-0" class="reference"><a href="#cite_note-ns-61"><span class="cite-bracket">&#91;</span>61<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-62" class="reference"><a href="#cite_note-62"><span class="cite-bracket">&#91;</span>62<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td>NewSpace BELUGA
    </td>
    <td><a href="/wiki/India" title="India">India</a>
    </td>
    <td><a href="/wiki/Swarming_(military)" title="Swarming (military)">Swarm</a> drones
    </td>
    <td>
    </td>
    <td>25
    </td></tr>
    <tr>
    <td>Raphe MPhibr MR-20<sup id="cite_ref-rmp_63-0" class="reference"><a href="#cite_note-rmp-63"><span class="cite-bracket">&#91;</span>63<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td><a href="/wiki/India" title="India">India</a>
    </td>
    <td><a href="/wiki/Cargo" title="Cargo">Cargo </a>
    </td>
    <td>
    </td>
    <td>48<sup id="cite_ref-rmp_63-1" class="reference"><a href="#cite_note-rmp-63"><span class="cite-bracket">&#91;</span>63<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr></tbody></table>
    <div class="mw-heading mw-heading2"><h2 id="Naval_Air_Arm">Naval Air Arm</h2></div>
    <link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1236090951"><div role="note" class="hatnote navigation-not-searchable">Further information: <a href="/wiki/Indian_Naval_Air_Arm" title="Indian Naval Air Arm">Indian Naval Air Arm</a> and <a href="/wiki/List_of_Indian_naval_aircraft" class="mw-redirect" title="List of Indian naval aircraft">List of Indian naval aircraft</a></div>
    <figure class="mw-default-size mw-halign-right" typeof="mw:File/Thumb"><a href="/wiki/File:HAL_Dhruv_MKIII_Commandos_Heliborne_operation_3.jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/a/a6/HAL_Dhruv_MKIII_Commandos_Heliborne_operation_3.jpg/220px-HAL_Dhruv_MKIII_Commandos_Heliborne_operation_3.jpg" decoding="async" width="220" height="147" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/a/a6/HAL_Dhruv_MKIII_Commandos_Heliborne_operation_3.jpg/330px-HAL_Dhruv_MKIII_Commandos_Heliborne_operation_3.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/a/a6/HAL_Dhruv_MKIII_Commandos_Heliborne_operation_3.jpg/440px-HAL_Dhruv_MKIII_Commandos_Heliborne_operation_3.jpg 2x" data-file-width="1280" data-file-height="853" /></a><figcaption>Heliborne operation from <a href="/wiki/HAL_Dhruv" title="HAL Dhruv">HAL Dhruv MK-III</a></figcaption></figure>
    <figure class="mw-default-size mw-halign-right" typeof="mw:File/Thumb"><a href="/wiki/File:Boeing_P-8I_of_the_Indian_Navy_(modified).jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/c/cb/Boeing_P-8I_of_the_Indian_Navy_%28modified%29.jpg/220px-Boeing_P-8I_of_the_Indian_Navy_%28modified%29.jpg" decoding="async" width="220" height="142" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/c/cb/Boeing_P-8I_of_the_Indian_Navy_%28modified%29.jpg/330px-Boeing_P-8I_of_the_Indian_Navy_%28modified%29.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/c/cb/Boeing_P-8I_of_the_Indian_Navy_%28modified%29.jpg/440px-Boeing_P-8I_of_the_Indian_Navy_%28modified%29.jpg 2x" data-file-width="621" data-file-height="400" /></a><figcaption><a href="/wiki/Boeing_P-8_Poseidon#India" title="Boeing P-8 Poseidon">A Boeing P-8I Neptune of Indian Navy</a></figcaption></figure>
    <figure class="mw-default-size" typeof="mw:File/Thumb"><a href="/wiki/File:Sikorsky_MH-60R_Seahawk_helicopter_of_Indian_Navy.jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/6/6f/Sikorsky_MH-60R_Seahawk_helicopter_of_Indian_Navy.jpg/220px-Sikorsky_MH-60R_Seahawk_helicopter_of_Indian_Navy.jpg" decoding="async" width="220" height="147" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/6/6f/Sikorsky_MH-60R_Seahawk_helicopter_of_Indian_Navy.jpg/330px-Sikorsky_MH-60R_Seahawk_helicopter_of_Indian_Navy.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/6/6f/Sikorsky_MH-60R_Seahawk_helicopter_of_Indian_Navy.jpg/440px-Sikorsky_MH-60R_Seahawk_helicopter_of_Indian_Navy.jpg 2x" data-file-width="1920" data-file-height="1280" /></a><figcaption>MH-60R Seahawk helicopter of Indian Navy</figcaption></figure>
    <table class="wikitable">
    <tbody><tr>
    <th style="text-align:center; background:#acc;">Aircraft
    </th>
    <th style="text-align: center; background:#acc;">Origin
    </th>
    <th style="text-align:l center; background:#acc;">Type
    </th>
    <th style="text-align:left; background:#acc;">Variant
    </th>
    <th style="text-align:center; background:#acc;">In service
    </th>
    <th style="text-align: center; background:#acc;">Notes
    </th></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Military_aircraft#Combat_aircraft" title="Military aircraft">Combat Aircraft</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/MiG-29" class="mw-redirect" title="MiG-29">MiG-29</a>
    </td>
    <td><a href="/wiki/Russia" title="Russia">Russia</a>
    </td>
    <td><a href="/wiki/Multirole_combat_aircraft" title="Multirole combat aircraft">multirole</a>
    </td>
    <td><a href="/wiki/Mikoyan_MiG-29K" title="Mikoyan MiG-29K">MiG-29K</a>
    </td>
    <td>40<sup id="cite_ref-World_Air_Forces_2024_64-0" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-65" class="reference"><a href="#cite_note-65"><span class="cite-bracket">&#91;</span>65<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>7 <a href="/wiki/Mikoyan_MiG-29K#Variants" title="Mikoyan MiG-29K">KUB</a> variants provide <a href="/wiki/Trainer_(aircraft)#Operational_conversion" class="mw-redirect" title="Trainer (aircraft)">conversion training</a>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Maritime_patrol_aircraft" title="Maritime patrol aircraft">Maritime patrol</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Boeing_P-8_Poseidon" title="Boeing P-8 Poseidon">Boeing P-8</a>
    </td>
    <td>United States
    </td>
    <td><a href="/wiki/Anti-submarine_warfare" title="Anti-submarine warfare">ASW</a> / <a href="/wiki/Maritime_patrol_aircraft" title="Maritime patrol aircraft">patrol</a>
    </td>
    <td><a href="/wiki/Boeing_P-8_Poseidon#India" title="Boeing P-8 Poseidon"> P-8I</a>
    </td>
    <td>12<sup id="cite_ref-World_Air_Forces_2024_64-1" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Dornier_Do_228" class="mw-redirect" title="Dornier Do 228">Dornier Do 228</a>
    </td>
    <td>Germany
    </td>
    <td><a href="/wiki/Surveillance_aircraft" title="Surveillance aircraft"> surveillance</a>
    </td>
    <td>228-201<sup id="cite_ref-jawa-04_27-1" class="reference"><a href="#cite_note-jawa-04-27"><span class="cite-bracket">&#91;</span>27<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>25<sup id="cite_ref-66" class="reference"><a href="#cite_note-66"><span class="cite-bracket">&#91;</span>66<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>10 on order<sup id="cite_ref-World_Air_Forces_2024_64-2" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Britten-Norman_BN-2_Islander" title="Britten-Norman BN-2 Islander"> Britten-Norman BN-2</a>
    </td>
    <td>United Kingdom
    </td>
    <td>utility / <a href="/wiki/Maritime_patrol_aircraft" title="Maritime patrol aircraft">patrol</a>
    </td>
    <td><a href="/wiki/Britten-Norman_BN-2_Islander#Variants" title="Britten-Norman BN-2 Islander">BN-2B/2T</a><sup id="cite_ref-67" class="reference"><a href="#cite_note-67"><span class="cite-bracket">&#91;</span>67<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>4<sup id="cite_ref-World_Air_Forces_2024_64-3" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Helicopters" class="mw-redirect" title="Helicopters">Helicopters</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/HAL_Dhruv" title="HAL Dhruv">HAL Dhruv</a>
    </td>
    <td><a href="/wiki/India" title="India">India</a>
    </td>
    <td><a href="/wiki/Utility_helicopter" title="Utility helicopter">utility</a>
    </td>
    <td>
    </td>
    <td>24<sup id="cite_ref-World_Air_Forces_2024_64-4" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Kamov_Ka-31" title="Kamov Ka-31">Kamov Ka-31</a>
    </td>
    <td>Russia
    </td>
    <td><a href="/wiki/Airborne_early_warning_and_control" title="Airborne early warning and control">AEW</a>
    </td>
    <td>
    </td>
    <td>14<sup id="cite_ref-World_Air_Forces_2024_64-5" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>employs a <a href="/wiki/Planar_array_radar" class="mw-redirect" title="Planar array radar">Planar array radar</a>
    </td></tr>
    <tr>
    <td><a href="/wiki/Kamov_Ka-27" title="Kamov Ka-27">Kamov Ka-27</a>
    </td>
    <td><a href="/wiki/Russia" title="Russia">Russia</a>
    </td>
    <td><a href="/wiki/Anti-submarine_warfare" title="Anti-submarine warfare">ASW</a>
    </td>
    <td><a href="/wiki/Kamov_Ka-27#Variants" title="Kamov Ka-27">Ka-28</a>
    </td>
    <td>14<sup id="cite_ref-World_Air_Forces_2024_64-6" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Sikorsky_SH-60_Seahawk" title="Sikorsky SH-60 Seahawk">SH-60 Seahawk</a>
    </td>
    <td><a href="/wiki/United_States" title="United States">United States</a>
    </td>
    <td><a href="/wiki/Anti-surface_warfare" title="Anti-surface warfare">ASW</a> / <a href="/wiki/Search_and_rescue" title="Search and rescue">SAR</a>
    </td>
    <td><a href="/wiki/Sikorsky_SH-60_Seahawk#U.S._versions" title="Sikorsky SH-60 Seahawk">MH-60R</a>
    </td>
    <td>6<sup id="cite_ref-:5_68-0" class="reference"><a href="#cite_note-:5-68"><span class="cite-bracket">&#91;</span>68<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>24 on order<sup id="cite_ref-69" class="reference"><a href="#cite_note-69"><span class="cite-bracket">&#91;</span>69<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Westland_Sea_King" title="Westland Sea King">Westland Sea King</a>
    </td>
    <td>United Kingdom
    </td>
    <td><a href="/wiki/Search_and_rescue" title="Search and rescue">SAR</a> / utility
    </td>
    <td><a href="/wiki/Westland_Sea_King#Variants" title="Westland Sea King"> Mk.42B/C</a><sup id="cite_ref-hiranandani_70-0" class="reference"><a href="#cite_note-hiranandani-70"><span class="cite-bracket">&#91;</span>70<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>25<sup id="cite_ref-World_Air_Forces_2024_64-7" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>six are <a href="/wiki/Sikorsky_SH-3_Sea_King#Sikorsky_designations" title="Sikorsky SH-3 Sea King">UH-3H</a> variants
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Chetak" class="mw-redirect" title="HAL Chetak">HAL Chetak</a>
    </td>
    <td>France/India
    </td>
    <td>liaison / utility
    </td>
    <td>
    </td>
    <td>42<sup id="cite_ref-World_Air_Forces_2024_64-8" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Trainer_(aircraft)" class="mw-redirect" title="Trainer (aircraft)">Trainer Aircraft</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/BAE_Systems_Hawk" title="BAE Systems Hawk">BAE Hawk</a>
    </td>
    <td><a href="/wiki/United_Kingdom" title="United Kingdom">United Kingdom</a>
    </td>
    <td>Jet trainer
    </td>
    <td><a href="/wiki/BAE_Systems_Hawk#Hawk_132" title="BAE Systems Hawk">Hawk 132</a>
    </td>
    <td>17<sup id="cite_ref-World_Air_Forces_2024_64-9" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Kiran" class="mw-redirect" title="HAL Kiran">HAL Kiran</a>
    </td>
    <td><a href="/wiki/India" title="India">India</a>
    </td>
    <td>Jet trainer
    </td>
    <td>
    </td>
    <td>20<sup id="cite_ref-World_Air_Forces_2024_64-10" class="reference"><a href="#cite_note-World_Air_Forces_2024-64"><span class="cite-bracket">&#91;</span>64<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Unmanned_aerial_vehicle" title="Unmanned aerial vehicle">UAV</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/IAI_Heron" title="IAI Heron">IAI Heron</a><sup id="cite_ref-bs-sipri_71-0" class="reference"><a href="#cite_note-bs-sipri-71"><span class="cite-bracket">&#91;</span>71<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>Israel
    </td>
    <td>surveillance
    </td>
    <td>Heron 1
    </td>
    <td>14<sup id="cite_ref-:03_72-0" class="reference"><a href="#cite_note-:03-72"><span class="cite-bracket">&#91;</span>72<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td><sup id="cite_ref-toi-inas_73-0" class="reference"><a href="#cite_note-toi-inas-73"><span class="cite-bracket">&#91;</span>73<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-74" class="reference"><a href="#cite_note-74"><span class="cite-bracket">&#91;</span>74<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/IAI_Searcher" title="IAI Searcher">IAI Searcher</a><sup id="cite_ref-janes-16sep15_40-1" class="reference"><a href="#cite_note-janes-16sep15-40"><span class="cite-bracket">&#91;</span>40<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td><a href="/wiki/Israel" title="Israel">Israel</a>
    </td>
    <td>surveillance
    </td>
    <td>Mk. II
    </td>
    <td>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/General_Atomics_MQ-9_Reaper" title="General Atomics MQ-9 Reaper">MQ-9 Reaper</a>
    </td>
    <td><a href="/wiki/United_States" title="United States">United States</a>
    </td>
    <td><a href="/wiki/Surveillance_drone" class="mw-redirect" title="Surveillance drone">surveillance</a>
    </td>
    <td><a href="/wiki/General_Atomics_MQ-9_Reaper#SeaGuardian" title="General Atomics MQ-9 Reaper">SeaGuardian</a>
    </td>
    <td>2<sup id="cite_ref-75" class="reference"><a href="#cite_note-75"><span class="cite-bracket">&#91;</span>75<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Drishti-10" title="Drishti-10">Drishti-10</a>
    </td>
    <td><a href="/wiki/Israel" title="Israel">Israel</a>/<a href="/wiki/India" title="India">India</a>
    </td>
    <td>surveillance
    </td>
    <td>
    </td>
    <td>2<sup id="cite_ref-:6_76-0" class="reference"><a href="#cite_note-:6-76"><span class="cite-bracket">&#91;</span>76<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-77" class="reference"><a href="#cite_note-77"><span class="cite-bracket">&#91;</span>77<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr></tbody></table>
    <div class="mw-heading mw-heading2"><h2 id="Coast_Guard">Coast Guard</h2></div>
    <figure class="mw-default-size" typeof="mw:File/Thumb"><a href="/wiki/File:Dornier_Do-228-101,_India_-_Coast_Guard_JP7712387.jpg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/2/29/Dornier_Do-228-101%2C_India_-_Coast_Guard_JP7712387.jpg/220px-Dornier_Do-228-101%2C_India_-_Coast_Guard_JP7712387.jpg" decoding="async" width="220" height="150" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/2/29/Dornier_Do-228-101%2C_India_-_Coast_Guard_JP7712387.jpg/330px-Dornier_Do-228-101%2C_India_-_Coast_Guard_JP7712387.jpg 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/2/29/Dornier_Do-228-101%2C_India_-_Coast_Guard_JP7712387.jpg/440px-Dornier_Do-228-101%2C_India_-_Coast_Guard_JP7712387.jpg 2x" data-file-width="976" data-file-height="664" /></a><figcaption>A Dornier Do-228-101</figcaption></figure>
    <link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1236090951"><div role="note" class="hatnote navigation-not-searchable">Further information: <a href="/wiki/Indian_Coast_Guard" title="Indian Coast Guard">Indian Coast Guard</a></div>
    <table class="wikitable sortable">
    <tbody><tr>
    <th style="text-align:center; background:#acc;">Aircraft
    </th>
    <th style="text-align:center; background:#acc;">Origin
    </th>
    <th style="text-align:center; background:#acc;">Type
    </th>
    <th style="text-align:center; background:#acc;">Variant
    </th>
    <th style="text-align:center; background:#acc;">In service
    </th>
    <th style="text-align:center; background:#acc;">Notes
    </th></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Maritime_patrol_aircraft" title="Maritime patrol aircraft">Maritime patrol</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Dornier_Do_228" class="mw-redirect" title="Dornier Do 228">Dornier Do 228</a>
    </td>
    <td><a href="/wiki/Germany" title="Germany">Germany</a>
    </td>
    <td><a href="/wiki/Reconnaissance_aircraft" title="Reconnaissance aircraft">reconnaissance</a>
    </td>
    <td>101/201<sup id="cite_ref-jawa-04_27-2" class="reference"><a href="#cite_note-jawa-04-27"><span class="cite-bracket">&#91;</span>27<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>36<sup id="cite_ref-thestatesman.com_78-0" class="reference"><a href="#cite_note-thestatesman.com-78"><span class="cite-bracket">&#91;</span>78<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>2 on order<sup id="cite_ref-79" class="reference"><a href="#cite_note-79"><span class="cite-bracket">&#91;</span>79<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Helicopters" class="mw-redirect" title="Helicopters">Helicopters</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/HAL_Dhruv" title="HAL Dhruv">HAL Dhruv</a>
    </td>
    <td>India
    </td>
    <td>utility
    </td>
    <td><a href="/wiki/HAL_Dhruv#Variants" title="HAL Dhruv">Mk. I</a> / Mk. III
    </td>
    <td>4 / 16<sup id="cite_ref-80" class="reference"><a href="#cite_note-80"><span class="cite-bracket">&#91;</span>80<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-81" class="reference"><a href="#cite_note-81"><span class="cite-bracket">&#91;</span>81<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-82" class="reference"><a href="#cite_note-82"><span class="cite-bracket">&#91;</span>82<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>9 Mk.III on order<sup id="cite_ref-:022_83-0" class="reference"><a href="#cite_note-:022-83"><span class="cite-bracket">&#91;</span>83<span class="cite-bracket">&#93;</span></a></sup><sup id="cite_ref-84" class="reference"><a href="#cite_note-84"><span class="cite-bracket">&#91;</span>84<span class="cite-bracket">&#93;</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Chetak" class="mw-redirect" title="HAL Chetak">HAL Chetak</a>
    </td>
    <td>France/India
    </td>
    <td>utility
    </td>
    <td>
    </td>
    <td>17<sup id="cite_ref-:0_85-0" class="reference"><a href="#cite_note-:0-85"><span class="cite-bracket">&#91;</span>85<span class="cite-bracket">&#93;</span></a></sup>
    </td>
    <td>
    </td></tr></tbody></table>
    <div class="mw-heading mw-heading2"><h2 id="See_also">See also</h2></div>
    <ul><li><a href="/wiki/List_of_historical_aircraft_of_the_Indian_Air_Force" title="List of historical aircraft of the Indian Air Force">List of historical aircraft of the Indian Air Force</a></li>
    <li><a href="/wiki/List_of_Indian_naval_aircraft" class="mw-redirect" title="List of Indian naval aircraft">List of Indian naval aircraft</a></li>
    <li><a href="/wiki/Currently_active_military_equipment_by_country" class="mw-redirect" title="Currently active military equipment by country">Currently active military equipment by country</a></li>
    <li><a href="/wiki/Military_of_India" class="mw-redirect" title="Military of India">Military of India</a></li>
    <li><a href="/wiki/Indian_Air_Force" title="Indian Air Force">Indian Air Force</a></li>
    <li><a href="/wiki/Indian_Naval_Air_Arm" title="Indian Naval Air Arm">Indian Naval Air Arm</a></li>
    <li><a href="/wiki/Future_of_the_Indian_Air_Force" title="Future of the Indian Air Force">Future of the Indian Air Force</a></li>
    <li><a href="/wiki/Border_Security_Force" title="Border Security Force">Border Security Force</a></li></ul>
    <div class="mw-heading mw-heading2"><h2 id="References">References</h2></div>
    <style data-mw-deduplicate="TemplateStyles:r1239543626">.mw-parser-output .reflist{margin-bottom:0.5em;list-style-type:decimal}@media screen{.mw-parser-output .reflist{font-size:90%}}.mw-parser-output .reflist .references{font-size:100%;margin-bottom:0;list-style-type:inherit}.mw-parser-output .reflist-columns-2{column-width:30em}.mw-parser-output .reflist-columns-3{column-width:25em}.mw-parser-output .reflist-columns{margin-top:0.3em}.mw-parser-output .reflist-columns ol{margin-top:0}.mw-parser-output .reflist-columns li{page-break-inside:avoid;break-inside:avoid-column}.mw-parser-output .reflist-upper-alpha{list-style-type:upper-alpha}.mw-parser-output .reflist-upper-roman{list-style-type:upper-roman}.mw-parser-output .reflist-lower-alpha{list-style-type:lower-alpha}.mw-parser-output .reflist-lower-greek{list-style-type:lower-greek}.mw-parser-output .reflist-lower-roman{list-style-type:lower-roman}</style><div class="reflist reflist-columns references-column-width" style="column-width: 30em;">
    <ol class="references">
    <li id="cite_note-:1-1"><span class="mw-cite-backlink">^ <a href="#cite_ref-:1_1-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-:1_1-1"><sup><i><b>b</b></i></sup></a> <a href="#cite_ref-:1_1-2"><sup><i><b>c</b></i></sup></a> <a href="#cite_ref-:1_1-3"><sup><i><b>d</b></i></sup></a> <a href="#cite_ref-:1_1-4"><sup><i><b>e</b></i></sup></a> <a href="#cite_ref-:1_1-5"><sup><i><b>f</b></i></sup></a> <a href="#cite_ref-:1_1-6"><sup><i><b>g</b></i></sup></a> <a href="#cite_ref-:1_1-7"><sup><i><b>h</b></i></sup></a> <a href="#cite_ref-:1_1-8"><sup><i><b>i</b></i></sup></a></span> <span class="reference-text"><style data-mw-deduplicate="TemplateStyles:r1238218222">.mw-parser-output cite.citation{font-style:inherit;word-wrap:break-word}.mw-parser-output .citation q{quotes:"\"""\"""'""'"}.mw-parser-output .citation:target{background-color:rgba(0,127,255,0.133)}.mw-parser-output .id-lock-free.id-lock-free a{background:url("//upload.wikimedia.org/wikipedia/commons/6/65/Lock-green.svg")right 0.1em center/9px no-repeat}.mw-parser-output .id-lock-limited.id-lock-limited a,.mw-parser-output .id-lock-registration.id-lock-registration a{background:url("//upload.wikimedia.org/wikipedia/commons/d/d6/Lock-gray-alt-2.svg")right 0.1em center/9px no-repeat}.mw-parser-output .id-lock-subscription.id-lock-subscription a{background:url("//upload.wikimedia.org/wikipedia/commons/a/aa/Lock-red-alt-2.svg")right 0.1em center/9px no-repeat}.mw-parser-output .cs1-ws-icon a{background:url("//upload.wikimedia.org/wikipedia/commons/4/4c/Wikisource-logo.svg")right 0.1em center/12px no-repeat}body:not(.skin-timeless):not(.skin-minerva) .mw-parser-output .id-lock-free a,body:not(.skin-timeless):not(.skin-minerva) .mw-parser-output .id-lock-limited a,body:not(.skin-timeless):not(.skin-minerva) .mw-parser-output .id-lock-registration a,body:not(.skin-timeless):not(.skin-minerva) .mw-parser-output .id-lock-subscription a,body:not(.skin-timeless):not(.skin-minerva) .mw-parser-output .cs1-ws-icon a{background-size:contain;padding:0 1em 0 0}.mw-parser-output .cs1-code{color:inherit;background:inherit;border:none;padding:inherit}.mw-parser-output .cs1-hidden-error{display:none;color:var(--color-error,#d33)}.mw-parser-output .cs1-visible-error{color:var(--color-error,#d33)}.mw-parser-output .cs1-maint{display:none;color:#085;margin-left:0.3em}.mw-parser-output .cs1-kern-left{padding-left:0.2em}.mw-parser-output .cs1-kern-right{padding-right:0.2em}.mw-parser-output .citation .mw-selflink{font-weight:inherit}@media screen{.mw-parser-output .cs1-format{font-size:95%}html.skin-theme-clientpref-night .mw-parser-output .cs1-maint{color:#18911f}}@media screen and (prefers-color-scheme:dark){html.skin-theme-clientpref-os .mw-parser-output .cs1-maint{color:#18911f}}</style><cite class="citation book cs1"><a rel="nofollow" class="external text" href="https://www.iiss.org/en/publications/the-military-balance/"><i>The Military Balance 2024</i></a>. The International Institute for Strategic Studies. pp.&#160;269–270. <a href="/wiki/ISBN_(identifier)" class="mw-redirect" title="ISBN (identifier)">ISBN</a>&#160;<a href="/wiki/Special:BookSources/9781032780047" title="Special:BookSources/9781032780047"><bdi>9781032780047</bdi></a>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=book&amp;rft.btitle=The+Military+Balance+2024&amp;rft.pages=269-270&amp;rft.pub=The+International+Institute+for+Strategic+Studies&amp;rft.isbn=9781032780047&amp;rft_id=https%3A%2F%2Fwww.iiss.org%2Fen%2Fpublications%2Fthe-military-balance%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-2"><span class="mw-cite-backlink"><b><a href="#cite_ref-2">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.business-standard.com/industry/news/delivery-of-single-seat-tejas-lca-mark-1-fighters-to-iaf-completed-123082300824_1.html">"Delivery of single-seat Tejas LCA Mark 1 fighters to IAF completed"</a>. <i>Business Standard</i>. 23 August 2023.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Business+Standard&amp;rft.atitle=Delivery+of+single-seat+Tejas+LCA+Mark+1+fighters+to+IAF+completed&amp;rft.date=2023-08-23&amp;rft_id=https%3A%2F%2Fwww.business-standard.com%2Findustry%2Fnews%2Fdelivery-of-single-seat-tejas-lca-mark-1-fighters-to-iaf-completed-123082300824_1.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-3"><span class="mw-cite-backlink"><b><a href="#cite_ref-3">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.ndtv.com/india-news/1st-crash-in-23-years-of-its-history-5-facts-about-tejas-fighter-jet-5224145">"1st Crash In 23 Years Of Its History, 5 Facts About Tejas Fighter Jet"</a>. <i>NDTV.com</i><span class="reference-accessdate">. Retrieved <span class="nowrap">12 March</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=NDTV.com&amp;rft.atitle=1st+Crash+In+23+Years+Of+Its+History%2C+5+Facts+About+Tejas+Fighter+Jet&amp;rft_id=https%3A%2F%2Fwww.ndtv.com%2Findia-news%2F1st-crash-in-23-years-of-its-history-5-facts-about-tejas-fighter-jet-5224145&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-4"><span class="mw-cite-backlink"><b><a href="#cite_ref-4">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://timesofindia.indiatimes.com/india/tejas-mk-1a-completes-maiden-flight-first-delivery-soon/articleshow/108846208.cms">"Tejas MK-1A completes maiden flight, first delivery soon"</a>. <i>The Times of India</i>. 28 March 2024. <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/0971-8257">0971-8257</a><span class="reference-accessdate">. Retrieved <span class="nowrap">9 May</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Times+of+India&amp;rft.atitle=Tejas+MK-1A+completes+maiden+flight%2C+first+delivery+soon&amp;rft.date=2024-03-28&amp;rft.issn=0971-8257&amp;rft_id=https%3A%2F%2Ftimesofindia.indiatimes.com%2Findia%2Ftejas-mk-1a-completes-maiden-flight-first-delivery-soon%2Farticleshow%2F108846208.cms&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-5"><span class="mw-cite-backlink"><b><a href="#cite_ref-5">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.indiatoday.in/india-today-insight/story/when-14-years-on-iaf-got-its-first-trainer-jet-for-lca-tejas-2446188-2023-10-08">"When, 14 years on, IAF got its first trainer jet for LCA Tejas"</a>. <i>India Today</i>. 8 October 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">9 May</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=India+Today&amp;rft.atitle=When%2C+14+years+on%2C+IAF+got+its+first+trainer+jet+for+LCA+Tejas&amp;rft.date=2023-10-08&amp;rft_id=https%3A%2F%2Fwww.indiatoday.in%2Findia-today-insight%2Fstory%2Fwhen-14-years-on-iaf-got-its-first-trainer-jet-for-lca-tejas-2446188-2023-10-08&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:11-6"><span class="mw-cite-backlink">^ <a href="#cite_ref-:11_6-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-:11_6-1"><sup><i><b>b</b></i></sup></a></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFPhilip2021" class="citation web cs1">Philip, Snehesh Alex (3 February 2021). <a rel="nofollow" class="external text" href="https://theprint.in/defence/contract-signed-for-83-lca-tejas-fighters-all-eyes-now-on-hal-delivery-schedule/597841/">"Contract signed for 83 LCA Tejas fighters, all eyes now on HAL delivery schedule"</a>. <i>ThePrint</i><span class="reference-accessdate">. Retrieved <span class="nowrap">9 May</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=ThePrint&amp;rft.atitle=Contract+signed+for+83+LCA+Tejas+fighters%2C+all+eyes+now+on+HAL+delivery+schedule&amp;rft.date=2021-02-03&amp;rft.aulast=Philip&amp;rft.aufirst=Snehesh+Alex&amp;rft_id=https%3A%2F%2Ftheprint.in%2Fdefence%2Fcontract-signed-for-83-lca-tejas-fighters-all-eyes-now-on-hal-delivery-schedule%2F597841%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-7"><span class="mw-cite-backlink"><b><a href="#cite_ref-7">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://www.moneycontrol.com/news/india/defence-ministry-approves-purchase-of-97-tejas-aircraft-and-156-prachanda-helicopters-sources-11833571.html">"Rs 2.23 lakh crore-deal: India approves purchase of 97 Tejas aircraft, 156 Prachanda helicopters, other defence equipment"</a>. <i>Money Control</i>. 30 November 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">30 November</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=Money+Control&amp;rft.atitle=Rs+2.23+lakh+crore-deal%3A+India+approves+purchase+of+97+Tejas+aircraft%2C+156+Prachanda+helicopters%2C+other+defence+equipment&amp;rft.date=2023-11-30&amp;rft_id=https%3A%2F%2Fwww.moneycontrol.com%2Fnews%2Findia%2Fdefence-ministry-approves-purchase-of-97-tejas-aircraft-and-156-prachanda-helicopters-sources-11833571.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-8"><span class="mw-cite-backlink"><b><a href="#cite_ref-8">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.aerotime.aero/articles/india-to-modernize-sukhoi-su-30mki-fighter-fleet-with-4-billion-program">"India moves closer to adding $4B upgrades to Su-30 jets - AeroTime"</a>. 26 January 2023. <a rel="nofollow" class="external text" href="https://web.archive.org/web/20230418094132/https://www.aerotime.aero/articles/india-to-modernize-sukhoi-su-30mki-fighter-fleet-with-4-billion-program">Archived</a> from the original on 18 April 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">18 April</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=India+moves+closer+to+adding+%244B+upgrades+to+Su-30+jets+-+AeroTime&amp;rft.date=2023-01-26&amp;rft_id=https%3A%2F%2Fwww.aerotime.aero%2Farticles%2Findia-to-modernize-sukhoi-su-30mki-fighter-fleet-with-4-billion-program&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-9"><span class="mw-cite-backlink"><b><a href="#cite_ref-9">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.hindustantimes.com/india-news/iafs-sukhoi-jet-crashes-in-maharashtras-nashik-pilot-ejects-safely-report-101717492196585.html">"Air Force's Sukhoi fighter jet crashes in Maharashtra's Nashik: Report"</a>. <i>Hindustan Times</i><span class="reference-accessdate">. Retrieved <span class="nowrap">4 June</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Hindustan+Times&amp;rft.atitle=Air+Force%27s+Sukhoi+fighter+jet+crashes+in+Maharashtra%27s+Nashik%3A+Report&amp;rft_id=https%3A%2F%2Fwww.hindustantimes.com%2Findia-news%2Fiafs-sukhoi-jet-crashes-in-maharashtras-nashik-pilot-ejects-safely-report-101717492196585.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-10"><span class="mw-cite-backlink"><b><a href="#cite_ref-10">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://timesofindia.indiatimes.com/india/mod-approves-12-more-sukhois-800-armoured-vehicles-others-for-rs-45000-crore/articleshow/103698530.cms?ssp=1&amp;darkschemeovr=1&amp;setlang=en-US">"Nod for Rs 45,000cr defence buys, 12 more Sukhois to fly in"</a>. <i>The Times of India</i>. 16 September 2023. <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/0971-8257">0971-8257</a><span class="reference-accessdate">. Retrieved <span class="nowrap">9 May</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Times+of+India&amp;rft.atitle=Nod+for+Rs+45%2C000cr+defence+buys%2C+12+more+Sukhois+to+fly+in&amp;rft.date=2023-09-16&amp;rft.issn=0971-8257&amp;rft_id=https%3A%2F%2Ftimesofindia.indiatimes.com%2Findia%2Fmod-approves-12-more-sukhois-800-armoured-vehicles-others-for-rs-45000-crore%2Farticleshow%2F103698530.cms%3Fssp%3D1%26darkschemeovr%3D1%26setlang%3Den-US&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-11"><span class="mw-cite-backlink"><b><a href="#cite_ref-11">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.ndtv.com/india-news/mig-29-fighter-jet-crashes-in-rajasthan-pilot-safe-6476114/amp/1">"MiG-29 Fighter Jet Crashes In Rajasthan, Pilot Safe"</a>. <i>NDTV.com</i><span class="reference-accessdate">. Retrieved <span class="nowrap">3 September</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=NDTV.com&amp;rft.atitle=MiG-29+Fighter+Jet+Crashes+In+Rajasthan%2C+Pilot+Safe&amp;rft_id=https%3A%2F%2Fwww.ndtv.com%2Findia-news%2Fmig-29-fighter-jet-crashes-in-rajasthan-pilot-safe-6476114%2Famp%2F1&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-12"><span class="mw-cite-backlink"><b><a href="#cite_ref-12">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://thewire.in/security/mig-21-squadron-retired-curtain-closing-iaf-most-abiding-fighter">"Another MiG-21 Squadron Retired: The Curtain Is Closing on IAF's Most Abiding Fighter"</a>. <i>The Wire</i><span class="reference-accessdate">. Retrieved <span class="nowrap">9 May</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=The+Wire&amp;rft.atitle=Another+MiG-21+Squadron+Retired%3A+The+Curtain+Is+Closing+on+IAF%E2%80%99s+Most+Abiding+Fighter&amp;rft_id=https%3A%2F%2Fthewire.in%2Fsecurity%2Fmig-21-squadron-retired-curtain-closing-iaf-most-abiding-fighter&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-13"><span class="mw-cite-backlink"><b><a href="#cite_ref-13">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFPeri2023" class="citation news cs1">Peri, Dinakar (8 November 2023). <a rel="nofollow" class="external text" href="https://www.thehindu.com/news/national/how-are-the-mig-21-fighter-jets-being-phased-out-explained/article67510157.ece">"How are the MiG-21 fighter jets being phased out? | Explained"</a>. <i>The Hindu</i>. <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/0971-751X">0971-751X</a><span class="reference-accessdate">. Retrieved <span class="nowrap">8 May</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Hindu&amp;rft.atitle=How+are+the+MiG-21+fighter+jets+being+phased+out%3F+%7C+Explained&amp;rft.date=2023-11-08&amp;rft.issn=0971-751X&amp;rft.aulast=Peri&amp;rft.aufirst=Dinakar&amp;rft_id=https%3A%2F%2Fwww.thehindu.com%2Fnews%2Fnational%2Fhow-are-the-mig-21-fighter-jets-being-phased-out-explained%2Farticle67510157.ece&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:12-14"><span class="mw-cite-backlink">^ <a href="#cite_ref-:12_14-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-:12_14-1"><sup><i><b>b</b></i></sup></a> <a href="#cite_ref-:12_14-2"><sup><i><b>c</b></i></sup></a> <a href="#cite_ref-:12_14-3"><sup><i><b>d</b></i></sup></a> <a href="#cite_ref-:12_14-4"><sup><i><b>e</b></i></sup></a> <a href="#cite_ref-:12_14-5"><sup><i><b>f</b></i></sup></a> <a href="#cite_ref-:12_14-6"><sup><i><b>g</b></i></sup></a> <a href="#cite_ref-:12_14-7"><sup><i><b>h</b></i></sup></a> <a href="#cite_ref-:12_14-8"><sup><i><b>i</b></i></sup></a> <a href="#cite_ref-:12_14-9"><sup><i><b>j</b></i></sup></a> <a href="#cite_ref-:12_14-10"><sup><i><b>k</b></i></sup></a> <a href="#cite_ref-:12_14-11"><sup><i><b>l</b></i></sup></a> <a href="#cite_ref-:12_14-12"><sup><i><b>m</b></i></sup></a> <a href="#cite_ref-:12_14-13"><sup><i><b>n</b></i></sup></a> <a href="#cite_ref-:12_14-14"><sup><i><b>o</b></i></sup></a> <a href="#cite_ref-:12_14-15"><sup><i><b>p</b></i></sup></a> <a href="#cite_ref-:12_14-16"><sup><i><b>q</b></i></sup></a> <a href="#cite_ref-:12_14-17"><sup><i><b>r</b></i></sup></a> <a href="#cite_ref-:12_14-18"><sup><i><b>s</b></i></sup></a> <a href="#cite_ref-:12_14-19"><sup><i><b>t</b></i></sup></a> <a href="#cite_ref-:12_14-20"><sup><i><b>u</b></i></sup></a> <a href="#cite_ref-:12_14-21"><sup><i><b>v</b></i></sup></a> <a href="#cite_ref-:12_14-22"><sup><i><b>w</b></i></sup></a> <a href="#cite_ref-:12_14-23"><sup><i><b>x</b></i></sup></a> <a href="#cite_ref-:12_14-24"><sup><i><b>y</b></i></sup></a></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.flightglobal.com/download?ac=98881">"World Air Forces 2024"</a>. 15 December 2023. <a rel="nofollow" class="external text" href="https://web.archive.org/web/20240105033828/https://www.flightglobal.com/download?ac=98881">Archived</a> from the original on 5 January 2024<span class="reference-accessdate">. Retrieved <span class="nowrap">13 April</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=World+Air+Forces+2024&amp;rft.date=2023-12-15&amp;rft_id=https%3A%2F%2Fwww.flightglobal.com%2Fdownload%3Fac%3D98881&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-15"><span class="mw-cite-backlink"><b><a href="#cite_ref-15">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.flightglobal.com/download?ac=98881">"2024 World Air Forces"</a>. <i>www.flightglobal.com</i>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=www.flightglobal.com&amp;rft.atitle=2024+World+Air+Forces&amp;rft_id=https%3A%2F%2Fwww.flightglobal.com%2Fdownload%3Fac%3D98881&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-16"><span class="mw-cite-backlink"><b><a href="#cite_ref-16">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://timesofindia.indiatimes.com/india/india-to-order-2-more-israeli-eyes-in-sky/articleshow/77774435.cms?from=mdr">"Ladakh face-off: India to order 2 more Israeli 'eyes in sky' for $1 billion"</a>. <i>The Times of India</i>. 27 August 2020. <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/0971-8257">0971-8257</a><span class="reference-accessdate">. Retrieved <span class="nowrap">7 February</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Times+of+India&amp;rft.atitle=Ladakh+face-off%3A+India+to+order+2+more+Israeli+%27eyes+in+sky%27+for+%241+billion&amp;rft.date=2020-08-27&amp;rft.issn=0971-8257&amp;rft_id=https%3A%2F%2Ftimesofindia.indiatimes.com%2Findia%2Findia-to-order-2-more-israeli-eyes-in-sky%2Farticleshow%2F77774435.cms%3Ffrom%3Dmdr&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-17"><span class="mw-cite-backlink"><b><a href="#cite_ref-17">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://forceindia.net/civilaviation/businessjets/more-than-special/">"Special Mission Aircraft are cheaper to operate than older intelligence gathering assets"</a><span class="reference-accessdate">. Retrieved <span class="nowrap">31 August</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=Special+Mission+Aircraft+are+cheaper+to+operate+than+older+intelligence+gathering+assets&amp;rft_id=https%3A%2F%2Fforceindia.net%2Fcivilaviation%2Fbusinessjets%2Fmore-than-special%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-18"><span class="mw-cite-backlink"><b><a href="#cite_ref-18">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFPhilip2020" class="citation web cs1">Philip, Snehesh Alex (14 May 2020). <a rel="nofollow" class="external text" href="https://theprint.in/defence/indias-oldest-flying-aircraft-in-spotlight-after-radar-website-shows-it-going-to-pakistan/421757/">"India's oldest flying aircraft in spotlight after radar website shows it going to Pakistan"</a>. <i>ThePrint</i><span class="reference-accessdate">. Retrieved <span class="nowrap">31 August</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=ThePrint&amp;rft.atitle=India%E2%80%99s+oldest+flying+aircraft+in+spotlight+after+radar+website+shows+it+going+to+Pakistan&amp;rft.date=2020-05-14&amp;rft.aulast=Philip&amp;rft.aufirst=Snehesh+Alex&amp;rft_id=https%3A%2F%2Ftheprint.in%2Fdefence%2Findias-oldest-flying-aircraft-in-spotlight-after-radar-website-shows-it-going-to-pakistan%2F421757%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-19"><span class="mw-cite-backlink"><b><a href="#cite_ref-19">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFMenon2013" class="citation web cs1">Menon, Jay (23 April 2013). <a rel="nofollow" class="external text" href="http://aviationweek.com/defense/rfp-coming-soon-indian-airborne-jamming-aircraft">"RFP Coming Soon For Indian Airborne Jamming Aircraft"</a>. <i>aviationweek.com</i>. AWIN First.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=aviationweek.com&amp;rft.atitle=RFP+Coming+Soon+For+Indian+Airborne+Jamming+Aircraft&amp;rft.date=2013-04-23&amp;rft.aulast=Menon&amp;rft.aufirst=Jay&amp;rft_id=http%3A%2F%2Faviationweek.com%2Fdefense%2Frfp-coming-soon-indian-airborne-jamming-aircraft&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-20"><span class="mw-cite-backlink"><b><a href="#cite_ref-20">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.hindustantimes.com/india-news/first-modified-boeing-777-aircraft-part-of-air-india-one-fleet-for-pm-to-arrive-in-delhi-today/story-V1eKOpfrXTGhXq34XNkjRL.html">"PM's new special aircraft, equipped with missile defence systems, lands in Delhi"</a>. <i>Hindustan Times</i>. 1 October 2020<span class="reference-accessdate">. Retrieved <span class="nowrap">1 October</span> 2020</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Hindustan+Times&amp;rft.atitle=PM%27s+new+special+aircraft%2C+equipped+with+missile+defence+systems%2C+lands+in+Delhi&amp;rft.date=2020-10-01&amp;rft_id=https%3A%2F%2Fwww.hindustantimes.com%2Findia-news%2Ffirst-modified-boeing-777-aircraft-part-of-air-india-one-fleet-for-pm-to-arrive-in-delhi-today%2Fstory-V1eKOpfrXTGhXq34XNkjRL.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-21"><span class="mw-cite-backlink"><b><a href="#cite_ref-21">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="http://www.dnaindia.com/india/report-india-s-air-force-one-takes-off-on-first-official-flight-1244364">"India's Air Force One takes off on first official flight"</a>. <i>dna</i>. PTI. 1 April 2009.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=dna&amp;rft.atitle=India%27s+Air+Force+One+takes+off+on+first+official+flight&amp;rft.date=2009-04-01&amp;rft_id=http%3A%2F%2Fwww.dnaindia.com%2Findia%2Freport-india-s-air-force-one-takes-off-on-first-official-flight-1244364&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-22"><span class="mw-cite-backlink"><b><a href="#cite_ref-22">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="http://www.thehindubusinessline.com/economy/logistics/india-gets-first-embraer-jet-with-indian-airborne-radar-tech/article3785186.ece">"India gets first Embraer jet with Indian airborne radar tech"</a>. <i>The Hindu Business Line</i>. PTI. 17 August 2012.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Hindu+Business+Line&amp;rft.atitle=India+gets+first+Embraer+jet+with+Indian+airborne+radar+tech&amp;rft.date=2012-08-17&amp;rft_id=http%3A%2F%2Fwww.thehindubusinessline.com%2Feconomy%2Flogistics%2Findia-gets-first-embraer-jet-with-indian-airborne-radar-tech%2Farticle3785186.ece&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-23"><span class="mw-cite-backlink"><b><a href="#cite_ref-23">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="http://pib.nic.in/newsite/erelease.aspx?relid=78432">"Purchase of Transport Aircraft"</a>. Press Information Bureau. 12 December 2011.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=Purchase+of+Transport+Aircraft&amp;rft.pub=Press+Information+Bureau&amp;rft.date=2011-12-12&amp;rft_id=http%3A%2F%2Fpib.nic.in%2Fnewsite%2Ferelease.aspx%3Frelid%3D78432&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-fg-27nov15-24"><span class="mw-cite-backlink"><b><a href="#cite_ref-fg-27nov15_24-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFChandra2015" class="citation news cs1">Chandra, Atul (27 November 2015). <a rel="nofollow" class="external text" href="https://www.flightglobal.com/news/articles/india-receives-last-batch-of-ukraine-upgraded-an-32s-419513/">"India receives last batch of Ukraine-upgraded An-32s"</a>. <i>Flightglobal.com</i>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=Flightglobal.com&amp;rft.atitle=India+receives+last+batch+of+Ukraine-upgraded+An-32s&amp;rft.date=2015-11-27&amp;rft.aulast=Chandra&amp;rft.aufirst=Atul&amp;rft_id=https%3A%2F%2Fwww.flightglobal.com%2Fnews%2Farticles%2Findia-receives-last-batch-of-ukraine-upgraded-an-32s-419513%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-25"><span class="mw-cite-backlink"><b><a href="#cite_ref-25">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFgargi.chaudhry" class="citation web cs1">gargi.chaudhry. <a rel="nofollow" class="external text" href="https://newsable.asianetnews.com/india-defence/airbus-to-deliver-another-two-c295-aircraft-to-indian-air-force-sg6skn">"Airbus to deliver another two C295 aircraft to Indian Air Force"</a>. <i>Asianet News Network Pvt Ltd</i><span class="reference-accessdate">. Retrieved <span class="nowrap">6 July</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Asianet+News+Network+Pvt+Ltd&amp;rft.atitle=Airbus+to+deliver+another+two+C295+aircraft+to+Indian+Air+Force&amp;rft.au=gargi.chaudhry&amp;rft_id=https%3A%2F%2Fnewsable.asianetnews.com%2Findia-defence%2Fairbus-to-deliver-another-two-c295-aircraft-to-indian-air-force-sg6skn&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-26"><span class="mw-cite-backlink"><b><a href="#cite_ref-26">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.news18.com/news/india/govt-likely-to-seal-deal-on-purchase-of-56-c-295-military-transport-planes-in-next-few-days-4239749.html">"Govt Seals Mega Deal with Airbus for Purchase of 56 C-295 Military Transport Aircraft"</a>. <i>News18</i>. 24 September 2021<span class="reference-accessdate">. Retrieved <span class="nowrap">24 September</span> 2021</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=News18&amp;rft.atitle=Govt+Seals+Mega+Deal+with+Airbus+for+Purchase+of+56+C-295+Military+Transport+Aircraft&amp;rft.date=2021-09-24&amp;rft_id=https%3A%2F%2Fwww.news18.com%2Fnews%2Findia%2Fgovt-likely-to-seal-deal-on-purchase-of-56-c-295-military-transport-planes-in-next-few-days-4239749.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-jawa-04-27"><span class="mw-cite-backlink">^ <a href="#cite_ref-jawa-04_27-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-jawa-04_27-1"><sup><i><b>b</b></i></sup></a> <a href="#cite_ref-jawa-04_27-2"><sup><i><b>c</b></i></sup></a></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFJacksonMunsonPeacock2004" class="citation book cs1">Jackson, Paul; Munson, Kenneth; Peacock, Lindsay, eds. (2004). "HAL (Dornier) 228". <i>Jane's All the World's Aircraft</i> (95th year of issue 2004-2005.&#160;ed.). Coulsdon: Janes Information Group. p.&#160;206. <a href="/wiki/ISBN_(identifier)" class="mw-redirect" title="ISBN (identifier)">ISBN</a>&#160;<a href="/wiki/Special:BookSources/0710626142" title="Special:BookSources/0710626142"><bdi>0710626142</bdi></a>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=bookitem&amp;rft.atitle=HAL+%28Dornier%29+228&amp;rft.btitle=Jane%27s+All+the+World%27s+Aircraft&amp;rft.place=Coulsdon&amp;rft.pages=206&amp;rft.edition=95th+year+of+issue+2004-2005.&amp;rft.pub=Janes+Information+Group&amp;rft.date=2004&amp;rft.isbn=0710626142&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:2-28"><span class="mw-cite-backlink"><b><a href="#cite_ref-:2_28-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.pib.gov.in/www.pib.gov.in/Pressreleaseshare.aspx?PRID=1811565">"CCS Approves Procurement of 15 Light Combat Helicopters (LCH) Limited Series Production (LSP) from HAL for IAF (10) &amp; IA(05)"</a>. <i>www.pib.gov.in</i><span class="reference-accessdate">. Retrieved <span class="nowrap">15 December</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=www.pib.gov.in&amp;rft.atitle=CCS+Approves+Procurement+of+15+Light+Combat+Helicopters+%28LCH%29+Limited+Series+Production+%28LSP%29+from+HAL+for+IAF+%2810%29+%26+IA%2805%29&amp;rft_id=https%3A%2F%2Fwww.pib.gov.in%2Fwww.pib.gov.in%2FPressreleaseshare.aspx%3FPRID%3D1811565&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:3-29"><span class="mw-cite-backlink">^ <a href="#cite_ref-:3_29-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-:3_29-1"><sup><i><b>b</b></i></sup></a></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-iafs-strengthened-arsenal-acquisition-of-97-tejas-mk1a-jets-marks-a-milestone-3321952/">"IAF's Strengthened Arsenal: Acquisition of 97 Tejas Mk1A Jets Marks a Milestone"</a>. <i>Financialexpress</i>. 30 November 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">15 December</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Financialexpress&amp;rft.atitle=IAF%27s+Strengthened+Arsenal%3A+Acquisition+of+97+Tejas+Mk1A+Jets+Marks+a+Milestone&amp;rft.date=2023-11-30&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-iafs-strengthened-arsenal-acquisition-of-97-tejas-mk1a-jets-marks-a-milestone-3321952%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-30"><span class="mw-cite-backlink"><b><a href="#cite_ref-30">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://defenceaviationpost.com/about-50-rudra-attack-helicopters-to-be-acquired-by-the-indian-air-force/">"About 50 Rudra Attack Helicopters To Be Acquired By The Indian Air Force"</a>. 16 April 2022<span class="reference-accessdate">. Retrieved <span class="nowrap">16 April</span> 2022</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=About+50+Rudra+Attack+Helicopters+To+Be+Acquired+By+The+Indian+Air+Force&amp;rft.date=2022-04-16&amp;rft_id=https%3A%2F%2Fdefenceaviationpost.com%2Fabout-50-rudra-attack-helicopters-to-be-acquired-by-the-indian-air-force%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-31"><span class="mw-cite-backlink"><b><a href="#cite_ref-31">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFPubby" class="citation news cs1">Pubby, Manu. <a rel="nofollow" class="external text" href="https://economictimes.indiatimes.com/news/defence/indigenous-light-choppers-get-go-ahead-delivery-in-22/articleshow/81638498.cms">"Indigenous light choppers get go-ahead, delivery in 2022"</a>. <i>The Economic Times</i>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Economic+Times&amp;rft.atitle=Indigenous+light+choppers+get+go-ahead%2C+delivery+in+2022&amp;rft.aulast=Pubby&amp;rft.aufirst=Manu&amp;rft_id=https%3A%2F%2Feconomictimes.indiatimes.com%2Fnews%2Fdefence%2Findigenous-light-choppers-get-go-ahead-delivery-in-22%2Farticleshow%2F81638498.cms&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-32"><span class="mw-cite-backlink"><b><a href="#cite_ref-32">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-indigenous-luh-set-to-replace-aging-cheetah-and-chetak-fleet-3285693/">"Indigenous LUH Set to Replace Aging Cheetah and Chetak Fleet"</a>. <i>Financialexpress</i>. 25 October 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">23 September</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Financialexpress&amp;rft.atitle=Indigenous+LUH+Set+to+Replace+Aging+Cheetah+and+Chetak+Fleet&amp;rft.date=2023-10-25&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-indigenous-luh-set-to-replace-aging-cheetah-and-chetak-fleet-3285693%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-33"><span class="mw-cite-backlink"><b><a href="#cite_ref-33">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-indigenous-luh-set-to-replace-aging-cheetah-and-chetak-fleet-3285693/">"Indigenous LUH Set to Replace Aging Cheetah and Chetak Fleet"</a>. <i>Financialexpress</i>. 25 October 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">23 September</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Financialexpress&amp;rft.atitle=Indigenous+LUH+Set+to+Replace+Aging+Cheetah+and+Chetak+Fleet&amp;rft.date=2023-10-25&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-indigenous-luh-set-to-replace-aging-cheetah-and-chetak-fleet-3285693%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:8-34"><span class="mw-cite-backlink"><b><a href="#cite_ref-:8_34-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://www.hindustantimes.com/india-news/iafs-hawk-aircraft-crashes-at-kalaikunda-airbase-in-bengal-pilots-eject-safely-101707827270284.html">"IAF's Hawk aircraft crashes at Kalaikunda airbase in Bengal; pilots eject safely"</a>. <i><a href="/wiki/Hindustan_Times" title="Hindustan Times">Hindustan Times</a></i>. 13 February 2024<span class="reference-accessdate">. Retrieved <span class="nowrap">14 February</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=Hindustan+Times&amp;rft.atitle=IAF%27s+Hawk+aircraft+crashes+at+Kalaikunda+airbase+in+Bengal%3B+pilots+eject+safely&amp;rft.date=2024-02-13&amp;rft_id=https%3A%2F%2Fwww.hindustantimes.com%2Findia-news%2Fiafs-hawk-aircraft-crashes-at-kalaikunda-airbase-in-bengal-pilots-eject-safely-101707827270284.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-35"><span class="mw-cite-backlink"><b><a href="#cite_ref-35">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://archive.today/20200429143302/https://www.janes.com/article/92112/pipistrel-completes-deliveries-of-garud-trainers-to-india">"Pipistrel completes deliveries of Garud trainers to India | Jane's 360"</a>. <i>archive.ph</i>. 29 April 2020. Archived from <a rel="nofollow" class="external text" href="https://www.janes.com/article/92112/pipistrel-completes-deliveries-of-garud-trainers-to-india">the original</a> on 29 April 2020<span class="reference-accessdate">. Retrieved <span class="nowrap">1 December</span> 2021</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=archive.ph&amp;rft.atitle=Pipistrel+completes+deliveries+of+Garud+trainers+to+India+%7C+Jane%27s+360&amp;rft.date=2020-04-29&amp;rft_id=https%3A%2F%2Fwww.janes.com%2Farticle%2F92112%2Fpipistrel-completes-deliveries-of-garud-trainers-to-india&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-36"><span class="mw-cite-backlink"><b><a href="#cite_ref-36">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="http://www.strategypage.com/militaryforums/512-20022.aspx">"Defence Industry Daily: Israel sells heron UAVs to India and Australia"</a>. Strategypage.com. 11 November 2005. <a rel="nofollow" class="external text" href="https://web.archive.org/web/20130929011438/http://www.strategypage.com/militaryforums/512-20022.aspx">Archived</a> from the original on 29 September 2013<span class="reference-accessdate">. Retrieved <span class="nowrap">18 November</span> 2012</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=Defence+Industry+Daily%3A+Israel+sells+heron+UAVs+to+India+and+Australia&amp;rft.pub=Strategypage.com&amp;rft.date=2005-11-11&amp;rft_id=http%3A%2F%2Fwww.strategypage.com%2Fmilitaryforums%2F512-20022.aspx&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:06-37"><span class="mw-cite-backlink"><b><a href="#cite_ref-:06_37-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-iafs-heron-rpa-crashes-in-jaisalmer-court-of-inquiry-initiated-3468130/">"IAF's 'Heron' RPA crashes in Jaisalmer; Court of Inquiry initiated"</a>. <i>Financialexpress</i>. 25 April 2024<span class="reference-accessdate">. Retrieved <span class="nowrap">26 April</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Financialexpress&amp;rft.atitle=IAF%E2%80%99s+%E2%80%98Heron%E2%80%99+RPA+crashes+in+Jaisalmer%3B+Court+of+Inquiry+initiated&amp;rft.date=2024-04-25&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-iafs-heron-rpa-crashes-in-jaisalmer-court-of-inquiry-initiated-3468130%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:9-38"><span class="mw-cite-backlink"><b><a href="#cite_ref-:9_38-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.hindustantimes.com/india-news/india-inducts-new-strike-capable-heron-mark-2-drones-in-northern-sector-details-101691892126424.html">"India inducts new drones at forward air base in Northern sector: Report"</a>. <i>Hindustan Times</i>. 13 August 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">21 March</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Hindustan+Times&amp;rft.atitle=India+inducts+new+drones+at+forward+air+base+in+Northern+sector%3A+Report&amp;rft.date=2023-08-13&amp;rft_id=https%3A%2F%2Fwww.hindustantimes.com%2Findia-news%2Findia-inducts-new-strike-capable-heron-mark-2-drones-in-northern-sector-details-101691892126424.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:10-39"><span class="mw-cite-backlink"><b><a href="#cite_ref-:10_39-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.janes.com/defence-news/news-detail/indian-air-force-inducts-heron-mk-ii">"Indian Air Force inducts Heron Mk II"</a>. <i>Janes.com</i><span class="reference-accessdate">. Retrieved <span class="nowrap">21 March</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Janes.com&amp;rft.atitle=Indian+Air+Force+inducts+Heron+Mk+II&amp;rft_id=https%3A%2F%2Fwww.janes.com%2Fdefence-news%2Fnews-detail%2Findian-air-force-inducts-heron-mk-ii&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-janes-16sep15-40"><span class="mw-cite-backlink">^ <a href="#cite_ref-janes-16sep15_40-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-janes-16sep15_40-1"><sup><i><b>b</b></i></sup></a></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFBedi2015" class="citation journal cs1">Bedi, Rahul (16 September 2015). "India to buy Heron TP UAVs". <i>IHS Jane's Defence Weekly</i>. <b>52</b> (44). <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/2048-3430">2048-3430</a>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=IHS+Jane%27s+Defence+Weekly&amp;rft.atitle=India+to+buy+Heron+TP+UAVs&amp;rft.volume=52&amp;rft.issue=44&amp;rft.date=2015-09-16&amp;rft.issn=2048-3430&amp;rft.aulast=Bedi&amp;rft.aufirst=Rahul&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-41"><span class="mw-cite-backlink"><b><a href="#cite_ref-41">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.janes.com/defence-news/news-detail/aero-india-2023-iaf-to-receive-100-loitering-munitions-from-tasl">"Aero India 2023: IAF to receive 100 loitering munitions from TASL"</a>. <i>Janes.com</i><span class="reference-accessdate">. Retrieved <span class="nowrap">17 February</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Janes.com&amp;rft.atitle=Aero+India+2023%3A+IAF+to+receive+100+loitering+munitions+from+TASL&amp;rft_id=https%3A%2F%2Fwww.janes.com%2Fdefence-news%2Fnews-detail%2Faero-india-2023-iaf-to-receive-100-loitering-munitions-from-tasl&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-42"><span class="mw-cite-backlink"><b><a href="#cite_ref-42">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.theweek.in/news/india/2024/05/08/indias-first-kamikaze-drone-developed-5000-units-can-be-made-in-2-3-yrs.html">"India's first kamikaze drone developed; 5,000 units can be made in 2-3 yrs"</a>. <i>The Week</i><span class="reference-accessdate">. Retrieved <span class="nowrap">9 May</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=The+Week&amp;rft.atitle=India%E2%80%99s+first+kamikaze+drone+developed%3B+5%2C000+units+can+be+made+in+2-3+yrs&amp;rft_id=https%3A%2F%2Fwww.theweek.in%2Fnews%2Findia%2F2024%2F05%2F08%2Findias-first-kamikaze-drone-developed-5000-units-can-be-made-in-2-3-yrs.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-43"><span class="mw-cite-backlink"><b><a href="#cite_ref-43">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-kadet-defence-systems-introduces-indias-pioneering-loitering-aerial-munitions-lam-for-the-armed-forces-3481405/">"Kadet Defence systems introduces India's pioneering Loitering Aerial Munitions (LAM) for the armed forces"</a>. <i>Financialexpress</i>. 8 May 2024<span class="reference-accessdate">. Retrieved <span class="nowrap">9 May</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Financialexpress&amp;rft.atitle=Kadet+Defence+systems+introduces+India%E2%80%99s+pioneering+Loitering+Aerial+Munitions+%28LAM%29+for+the+armed+forces&amp;rft.date=2024-05-08&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-kadet-defence-systems-introduces-indias-pioneering-loitering-aerial-munitions-lam-for-the-armed-forces-3481405%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-44"><span class="mw-cite-backlink"><b><a href="#cite_ref-44">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.hindustantimes.com/india-news/boeing-begins-production-of-apache-attack-helicopters-for-indian-army-in-arizona-delivery-scheduled-for-2024-101692197822841.html">"Boeing begins production of army's Apache helicopters; deliveries next year"</a>. <i>Hindustan Times</i>. 16 August 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">15 December</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Hindustan+Times&amp;rft.atitle=Boeing+begins+production+of+army%27s+Apache+helicopters%3B+deliveries+next+year&amp;rft.date=2023-08-16&amp;rft_id=https%3A%2F%2Fwww.hindustantimes.com%2Findia-news%2Fboeing-begins-production-of-apache-attack-helicopters-for-indian-army-in-arizona-delivery-scheduled-for-2024-101692197822841.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-45"><span class="mw-cite-backlink"><b><a href="#cite_ref-45">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://economictimes.indiatimes.com/news/new-updates/watch-iafs-apache-like-made-in-india-light-combat-helicopter/articleshow/94481515.cms?from=mdr">"Watch: IAF's Apache-like Made in India Light Combat Helicopter"</a>. <i>The Economic Times</i>. 27 September 2022. <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/0013-0389">0013-0389</a><span class="reference-accessdate">. Retrieved <span class="nowrap">13 August</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Economic+Times&amp;rft.atitle=Watch%3A+IAF%27s+Apache-like+Made+in+India+Light+Combat+Helicopter&amp;rft.date=2022-09-27&amp;rft.issn=0013-0389&amp;rft_id=https%3A%2F%2Feconomictimes.indiatimes.com%2Fnews%2Fnew-updates%2Fwatch-iafs-apache-like-made-in-india-light-combat-helicopter%2Farticleshow%2F94481515.cms%3Ffrom%3Dmdr&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:7-46"><span class="mw-cite-backlink">^ <a href="#cite_ref-:7_46-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-:7_46-1"><sup><i><b>b</b></i></sup></a></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-army-chief-says-lch-good-for-high-altitude-army-to-procure-95-of-them-2982095/">"Army Chief says LCH good for high altitude; Army to procure 95 of them"</a>. <i>Financialexpress</i>. 15 February 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">16 February</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Financialexpress&amp;rft.atitle=Army+Chief+says+LCH+good+for+high+altitude%3B+Army+to+procure+95+of+them&amp;rft.date=2023-02-15&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-army-chief-says-lch-good-for-high-altitude-army-to-procure-95-of-them-2982095%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-47"><span class="mw-cite-backlink"><b><a href="#cite_ref-47">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFTeam2024" class="citation web cs1">Team, IADN Editorial (25 May 2024). <a rel="nofollow" class="external text" href="https://iadnews.in/hal-delivers-dhruv-helicopters-to-army-within-2-weeks-of-contract-signing/">"HAL delivers Dhruv helicopters to Army within 2 weeks of contract signing - IADN"</a>. <i>- IADN</i><span class="reference-accessdate">. Retrieved <span class="nowrap">26 May</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=-+IADN&amp;rft.atitle=HAL+delivers+Dhruv+helicopters+to+Army+within+2+weeks+of+contract+signing+-+IADN&amp;rft.date=2024-05-25&amp;rft.aulast=Team&amp;rft.aufirst=IADN+Editorial&amp;rft_id=https%3A%2F%2Fiadnews.in%2Fhal-delivers-dhruv-helicopters-to-army-within-2-weeks-of-contract-signing%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:02-48"><span class="mw-cite-backlink"><b><a href="#cite_ref-:02_48-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.reuters.com/business/aerospace-defense/indias-defence-ministry-signs-deals-worth-975-mln-indigenous-helicopters-2024-03-13/">"India's defence ministry signs deals worth $975 mln for indigenous helicopters"</a>. <i><a href="/wiki/Reuters" title="Reuters">Reuters</a></i>. 13 March 2024.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Reuters&amp;rft.atitle=India%27s+defence+ministry+signs+deals+worth+%24975+mln+for+indigenous+helicopters&amp;rft.date=2024-03-13&amp;rft_id=https%3A%2F%2Fwww.reuters.com%2Fbusiness%2Faerospace-defense%2Findias-defence-ministry-signs-deals-worth-975-mln-indigenous-helicopters-2024-03-13%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-49"><span class="mw-cite-backlink"><b><a href="#cite_ref-49">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.indiatoday.in/india/story/centre-approves-34-new-dhruv-choppers-for-army-coast-guard-2512013-2024-03-07">"Centre approves 34 new Dhruv choppers for Army, Coast Guard"</a>. <i>India Today</i><span class="reference-accessdate">. Retrieved <span class="nowrap">8 March</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=India+Today&amp;rft.atitle=Centre+approves+34+new+Dhruv+choppers+for+Army%2C+Coast+Guard&amp;rft_id=https%3A%2F%2Fwww.indiatoday.in%2Findia%2Fstory%2Fcentre-approves-34-new-dhruv-choppers-for-army-coast-guard-2512013-2024-03-07&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-50"><span class="mw-cite-backlink"><b><a href="#cite_ref-50">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-indigenous-luh-set-to-replace-aging-cheetah-and-chetak-fleet-3285693/">"Indigenous LUH Set to Replace Aging Cheetah and Chetak Fleet"</a>. <i>Financialexpress</i>. 25 October 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">23 September</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Financialexpress&amp;rft.atitle=Indigenous+LUH+Set+to+Replace+Aging+Cheetah+and+Chetak+Fleet&amp;rft.date=2023-10-25&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-indigenous-luh-set-to-replace-aging-cheetah-and-chetak-fleet-3285693%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-51"><span class="mw-cite-backlink"><b><a href="#cite_ref-51">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://www.thehindu.com/news/national/army-aviation-augments-combat-power-while-ageing-cheetah-chetaks-await-replacement/article65623822.ece">"Army Aviation augments combat power while ageing Cheetah, Chetaks await replacement"</a>. <i>The Hindu</i>. 10 July 2022. <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/0971-751X">0971-751X</a><span class="reference-accessdate">. Retrieved <span class="nowrap">30 July</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Hindu&amp;rft.atitle=Army+Aviation+augments+combat+power+while+ageing+Cheetah%2C+Chetaks+await+replacement&amp;rft.date=2022-07-10&amp;rft.issn=0971-751X&amp;rft_id=https%3A%2F%2Fwww.thehindu.com%2Fnews%2Fnational%2Farmy-aviation-augments-combat-power-while-ageing-cheetah-chetaks-await-replacement%2Farticle65623822.ece&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-52"><span class="mw-cite-backlink"><b><a href="#cite_ref-52">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://indianexpress.com/article/india/cheetah-helicopter-army-crash-arunachal-pradesh-search-ops-underway-8501053/">"Two pilots killed after Army's Cheetah helicopter crashes near Arunachal's Bomdila; probe ordered"</a>. <i>The Indian Express</i>. 16 March 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">30 July</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=The+Indian+Express&amp;rft.atitle=Two+pilots+killed+after+Army%27s+Cheetah+helicopter+crashes+near+Arunachal%27s+Bomdila%3B+probe+ordered&amp;rft.date=2023-03-16&amp;rft_id=https%3A%2F%2Findianexpress.com%2Farticle%2Findia%2Fcheetah-helicopter-army-crash-arunachal-pradesh-search-ops-underway-8501053%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:4-53"><span class="mw-cite-backlink"><b><a href="#cite_ref-:4_53-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.janes.com/defence-news/news-detail/india-orders-hermes-900-for-army-navy">"India orders Hermes 900 for army, navy"</a>. <i>Janes.com</i><span class="reference-accessdate">. Retrieved <span class="nowrap">15 December</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Janes.com&amp;rft.atitle=India+orders+Hermes+900+for+army%2C+navy&amp;rft_id=https%3A%2F%2Fwww.janes.com%2Fdefence-news%2Fnews-detail%2Findia-orders-hermes-900-for-army-navy&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:04-54"><span class="mw-cite-backlink"><b><a href="#cite_ref-:04_54-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-iafs-heron-rpa-crashes-in-jaisalmer-court-of-inquiry-initiated-3468130/">"IAF's 'Heron' RPA crashes in Jaisalmer; Court of Inquiry initiated"</a>. <i>Financialexpress</i>. 25 April 2024<span class="reference-accessdate">. Retrieved <span class="nowrap">26 April</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Financialexpress&amp;rft.atitle=IAF%E2%80%99s+%E2%80%98Heron%E2%80%99+RPA+crashes+in+Jaisalmer%3B+Court+of+Inquiry+initiated&amp;rft.date=2024-04-25&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-iafs-heron-rpa-crashes-in-jaisalmer-court-of-inquiry-initiated-3468130%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-55"><span class="mw-cite-backlink"><b><a href="#cite_ref-55">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.news18.com/news/india/army-gets-deliveries-of-2-israeli-heron-tp-drones-bought-in-2020-deploys-them-along-lac-in-ladakh-6162541.html">"Army Gets Deliveries of 2 Israeli Heron TP Drones Bought in 2020, Deploys Them Along LAC in Ladakh"</a>. <i>News18</i>. 14 October 2022<span class="reference-accessdate">. Retrieved <span class="nowrap">28 June</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=News18&amp;rft.atitle=Army+Gets+Deliveries+of+2+Israeli+Heron+TP+Drones+Bought+in+2020%2C+Deploys+Them+Along+LAC+in+Ladakh&amp;rft.date=2022-10-14&amp;rft_id=https%3A%2F%2Fwww.news18.com%2Fnews%2Findia%2Farmy-gets-deliveries-of-2-israeli-heron-tp-drones-bought-in-2020-deploys-them-along-lac-in-ladakh-6162541.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-56"><span class="mw-cite-backlink"><b><a href="#cite_ref-56">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFThakur2022" class="citation web cs1">Thakur, Vijainder K. (24 October 2022). <a rel="nofollow" class="external text" href="https://www.eurasiantimes.com/india-is-negotiating-with-israel-aerospace-to-locally-heron-mk2-drones/">"Decisive Edge For IAF? India Negotiating With Israel To Locally Manufacture 'Weaponizable' Heron Mk2 Drones"</a>. <i>Latest Asian, Middle-East, EurAsian, Indian News</i><span class="reference-accessdate">. Retrieved <span class="nowrap">27 April</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Latest+Asian%2C+Middle-East%2C+EurAsian%2C+Indian+News&amp;rft.atitle=Decisive+Edge+For+IAF%3F+India+Negotiating+With+Israel+To+Locally+Manufacture+%27Weaponizable%27+Heron+Mk2+Drones&amp;rft.date=2022-10-24&amp;rft.aulast=Thakur&amp;rft.aufirst=Vijainder+K.&amp;rft_id=https%3A%2F%2Fwww.eurasiantimes.com%2Findia-is-negotiating-with-israel-aerospace-to-locally-heron-mk2-drones%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-janes-20feb13-57"><span class="mw-cite-backlink"><b><a href="#cite_ref-janes-20feb13_57-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFBedi2013" class="citation journal cs1">Bedi, Rahul (20 February 2013). "India signs up for more Heron UAVs". <i>IHS Jane's Defence Weekly</i>. <b>50</b> (12). <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/2048-3430">2048-3430</a>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=IHS+Jane%27s+Defence+Weekly&amp;rft.atitle=India+signs+up+for+more+Heron+UAVs&amp;rft.volume=50&amp;rft.issue=12&amp;rft.date=2013-02-20&amp;rft.issn=2048-3430&amp;rft.aulast=Bedi&amp;rft.aufirst=Rahul&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-58"><span class="mw-cite-backlink"><b><a href="#cite_ref-58">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="http://www.milpower.org/showclass.asp?class=Searcher">"Show aircraft class: IAI Searcher"</a>. <i>milpower</i>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=milpower&amp;rft.atitle=Show+aircraft+class%3A+IAI+Searcher&amp;rft_id=http%3A%2F%2Fwww.milpower.org%2Fshowclass.asp%3Fclass%3DSearcher&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-Business_Standard_India-59"><span class="mw-cite-backlink">^ <a href="#cite_ref-Business_Standard_India_59-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-Business_Standard_India_59-1"><sup><i><b>b</b></i></sup></a></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://www.business-standard.com/article/current-affairs/indian-army-signs-20-mn-contract-with-ideaforge-to-procure-switch-drones-121011401192_1.html">"Indian Army signs $20 mn contract with ideaForge to procure SWITCH drones"</a>. <i>Business Standard India</i>. Press Trust of India. 14 January 2021<span class="reference-accessdate">. Retrieved <span class="nowrap">19 April</span> 2022</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=Business+Standard+India&amp;rft.atitle=Indian+Army+signs+%2420+mn+contract+with+ideaForge+to+procure+SWITCH+drones&amp;rft.date=2021-01-14&amp;rft_id=https%3A%2F%2Fwww.business-standard.com%2Farticle%2Fcurrent-affairs%2Findian-army-signs-20-mn-contract-with-ideaforge-to-procure-switch-drones-121011401192_1.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-60"><span class="mw-cite-backlink"><b><a href="#cite_ref-60">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.ideaforge.co.in/wp-content/uploads/2021/01/SWITCH-Prime-Brochure-web.pdf">"Switch Prime"</a> <span class="cs1-format">(PDF)</span>. ideaForge<span class="reference-accessdate">. Retrieved <span class="nowrap">27 December</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=Switch+Prime&amp;rft.pub=ideaForge&amp;rft_id=https%3A%2F%2Fwww.ideaforge.co.in%2Fwp-content%2Fuploads%2F2021%2F01%2FSWITCH-Prime-Brochure-web.pdf&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-ns-61"><span class="mw-cite-backlink"><b><a href="#cite_ref-ns_61-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://theigmp.org/indian-army-receives-its-first-swarm-drones-from-newspace/">"Indian army receives its first swarm drones from newspace"</a>. The IGMP (9 march 2023).</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.atitle=Indian+army+receives+its+first+swarm+drones+from+newspace&amp;rft_id=https%3A%2F%2Ftheigmp.org%2Findian-army-receives-its-first-swarm-drones-from-newspace%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-62"><span class="mw-cite-backlink"><b><a href="#cite_ref-62">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.janes.com/defence-news/news-detail/indian-army-receives-swarming-uavs">"Indian Army receives 'swarming&#39; UAVs"</a>. <i>Janes.com</i><span class="reference-accessdate">. Retrieved <span class="nowrap">27 April</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Janes.com&amp;rft.atitle=Indian+Army+receives+%E2%80%98swarming%26%2339%3B+UAVs&amp;rft_id=https%3A%2F%2Fwww.janes.com%2Fdefence-news%2Fnews-detail%2Findian-army-receives-swarming-uavs&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-rmp-63"><span class="mw-cite-backlink">^ <a href="#cite_ref-rmp_63-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-rmp_63-1"><sup><i><b>b</b></i></sup></a></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://www.livefistdefence.com/first-look-at-indian-armys-new-cargo-drones-for-ladakh/">"First Look At Indian Army's New Cargo Drones For Ladakh"</a>. livefistdefence<span class="reference-accessdate">. Retrieved <span class="nowrap">8 September</span> 2021</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.atitle=First+Look+At+Indian+Army%27s+New+Cargo+Drones+For+Ladakh&amp;rft_id=https%3A%2F%2Fwww.livefistdefence.com%2Ffirst-look-at-indian-armys-new-cargo-drones-for-ladakh%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-World_Air_Forces_2024-64"><span class="mw-cite-backlink">^ <a href="#cite_ref-World_Air_Forces_2024_64-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-World_Air_Forces_2024_64-1"><sup><i><b>b</b></i></sup></a> <a href="#cite_ref-World_Air_Forces_2024_64-2"><sup><i><b>c</b></i></sup></a> <a href="#cite_ref-World_Air_Forces_2024_64-3"><sup><i><b>d</b></i></sup></a> <a href="#cite_ref-World_Air_Forces_2024_64-4"><sup><i><b>e</b></i></sup></a> <a href="#cite_ref-World_Air_Forces_2024_64-5"><sup><i><b>f</b></i></sup></a> <a href="#cite_ref-World_Air_Forces_2024_64-6"><sup><i><b>g</b></i></sup></a> <a href="#cite_ref-World_Air_Forces_2024_64-7"><sup><i><b>h</b></i></sup></a> <a href="#cite_ref-World_Air_Forces_2024_64-8"><sup><i><b>i</b></i></sup></a> <a href="#cite_ref-World_Air_Forces_2024_64-9"><sup><i><b>j</b></i></sup></a> <a href="#cite_ref-World_Air_Forces_2024_64-10"><sup><i><b>k</b></i></sup></a></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFHoyle2023" class="citation web cs1">Hoyle, Craig (2023). <a rel="nofollow" class="external text" href="https://www.flightglobal.com/download?ac=98881">"World Air Forces 2024"</a>. <a href="/wiki/FlightGlobal" title="FlightGlobal">FlightGlobal</a><span class="reference-accessdate">. Retrieved <span class="nowrap">27 December</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=World+Air+Forces+2024&amp;rft.pub=FlightGlobal&amp;rft.date=2023&amp;rft.aulast=Hoyle&amp;rft.aufirst=Craig&amp;rft_id=https%3A%2F%2Fwww.flightglobal.com%2Fdownload%3Fac%3D98881&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-65"><span class="mw-cite-backlink"><b><a href="#cite_ref-65">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.janes.com/defence-news/news-detail/indian-navy-reports-crash-of-fifth-mig-29k-in-four-years">"Indian Navy reports crash of fifth MiG-29K in four years"</a>. 13 October 2022<span class="reference-accessdate">. Retrieved <span class="nowrap">21 March</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=Indian+Navy+reports+crash+of+fifth+MiG-29K+in+four+years&amp;rft.date=2022-10-13&amp;rft_id=https%3A%2F%2Fwww.janes.com%2Fdefence-news%2Fnews-detail%2Findian-navy-reports-crash-of-fifth-mig-29k-in-four-years&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-66"><span class="mw-cite-backlink"><b><a href="#cite_ref-66">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://pib.gov.in/PressReleasePage.aspx?PRID=2015025">"MoD signs contract worth over Rs. 2,890 cr with HAL for Mid Life Upgrade of 25 Dornier Aircraft of Indian Navy"</a>. <i>pib.gov.in</i><span class="reference-accessdate">. Retrieved <span class="nowrap">15 March</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=pib.gov.in&amp;rft.atitle=MoD+signs+contract+worth+over+Rs.+2%2C890+cr+with+HAL+for+Mid+Life+Upgrade+of+25+Dornier+Aircraft+of+Indian+Navy&amp;rft_id=https%3A%2F%2Fpib.gov.in%2FPressReleasePage.aspx%3FPRID%3D2015025&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-67"><span class="mw-cite-backlink"><b><a href="#cite_ref-67">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.indiannavy.nic.in/content/dorniers-1">"Dorniers | INAS 550 – The Flying Fish"</a>. <i>www.indiannavy.nic.in</i>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=www.indiannavy.nic.in&amp;rft.atitle=Dorniers+%7C+INAS+550+%E2%80%93+The+Flying+Fish&amp;rft_id=https%3A%2F%2Fwww.indiannavy.nic.in%2Fcontent%2Fdorniers-1&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:5-68"><span class="mw-cite-backlink"><b><a href="#cite_ref-:5_68-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFSentinels" class="citation web cs1">Sentinels, India. <a rel="nofollow" class="external text" href="https://www.indiasentinels.com/navy/lockheed-martin-delivers-6th-mh-60r-romeo-helicopter-to-indian-navy-6070">"Lockheed Martin delivers 6th MH-60R 'Romeo' helicopter to Indian Navy"</a>. <i>www.indiasentinels.com</i><span class="reference-accessdate">. Retrieved <span class="nowrap">15 December</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=www.indiasentinels.com&amp;rft.atitle=Lockheed+Martin+delivers+6th+MH-60R+%27Romeo%27+helicopter+to+Indian+Navy&amp;rft.aulast=Sentinels&amp;rft.aufirst=India&amp;rft_id=https%3A%2F%2Fwww.indiasentinels.com%2Fnavy%2Flockheed-martin-delivers-6th-mh-60r-romeo-helicopter-to-indian-navy-6070&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-69"><span class="mw-cite-backlink"><b><a href="#cite_ref-69">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-romeos-are-coming-to-india-long-wait-for-mh-60r-multi-mission-helicopter-for-indian-navy-is-over-2609515/">"Romeos are coming to India! Long wait for MH-60R multi-mission helicopter for Indian Navy is over"</a>. <i>Financialexpress</i>. 28 July 2022<span class="reference-accessdate">. Retrieved <span class="nowrap">15 December</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Financialexpress&amp;rft.atitle=Romeos+are+coming+to+India%21+Long+wait+for+MH-60R+multi-mission+helicopter+for+Indian+Navy+is+over&amp;rft.date=2022-07-28&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-romeos-are-coming-to-india-long-wait-for-mh-60r-multi-mission-helicopter-for-indian-navy-is-over-2609515%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-hiranandani-70"><span class="mw-cite-backlink"><b><a href="#cite_ref-hiranandani_70-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFHiranandani2005" class="citation book cs1">Hiranandani, G. M. (2005). <a rel="nofollow" class="external text" href="https://books.google.com/books?id=1WxI9TlAxIQC"><i>Transition to Eminence: The Indian Navy 1976-1990</i></a>. Lancer Publishers. p.&#160;99. <a href="/wiki/ISBN_(identifier)" class="mw-redirect" title="ISBN (identifier)">ISBN</a>&#160;<a href="/wiki/Special:BookSources/9788170622666" title="Special:BookSources/9788170622666"><bdi>9788170622666</bdi></a>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=book&amp;rft.btitle=Transition+to+Eminence%3A+The+Indian+Navy+1976-1990&amp;rft.pages=99&amp;rft.pub=Lancer+Publishers&amp;rft.date=2005&amp;rft.isbn=9788170622666&amp;rft.aulast=Hiranandani&amp;rft.aufirst=G.+M.&amp;rft_id=https%3A%2F%2Fbooks.google.com%2Fbooks%3Fid%3D1WxI9TlAxIQC&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-bs-sipri-71"><span class="mw-cite-backlink"><b><a href="#cite_ref-bs-sipri_71-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFMallapur2015" class="citation news cs1">Mallapur, Chaitanya (4 May 2015). <a rel="nofollow" class="external text" href="http://www.business-standard.com/article/specials/india-tops-list-of-drone-importing-nations-115050400136_1.html">"India tops list of drone-importing nations"</a>. <i>IndiaSpend</i>. Business Standard.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=IndiaSpend&amp;rft.atitle=India+tops+list+of+drone-importing+nations&amp;rft.date=2015-05-04&amp;rft.aulast=Mallapur&amp;rft.aufirst=Chaitanya&amp;rft_id=http%3A%2F%2Fwww.business-standard.com%2Farticle%2Fspecials%2Findia-tops-list-of-drone-importing-nations-115050400136_1.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:03-72"><span class="mw-cite-backlink"><b><a href="#cite_ref-:03_72-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-iafs-heron-rpa-crashes-in-jaisalmer-court-of-inquiry-initiated-3468130/">"IAF's 'Heron' RPA crashes in Jaisalmer; Court of Inquiry initiated"</a>. <i>Financialexpress</i>. 25 April 2024<span class="reference-accessdate">. Retrieved <span class="nowrap">26 April</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Financialexpress&amp;rft.atitle=IAF%E2%80%99s+%E2%80%98Heron%E2%80%99+RPA+crashes+in+Jaisalmer%3B+Court+of+Inquiry+initiated&amp;rft.date=2024-04-25&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-iafs-heron-rpa-crashes-in-jaisalmer-court-of-inquiry-initiated-3468130%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-toi-inas-73"><span class="mw-cite-backlink"><b><a href="#cite_ref-toi-inas_73-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://web.archive.org/web/20121104115844/http://articles.timesofindia.indiatimes.com/2011-01-18/ahmedabad/28352057_1_uav-squadron-unmanned-aerial-vehicle-squadron-western-coast">"Eye in the sky to guard Gujarat coast"</a>. <i><a href="/wiki/The_Times_of_India" title="The Times of India">The Times of India</a></i>. 18 January 2011. Archived from <a rel="nofollow" class="external text" href="http://articles.timesofindia.indiatimes.com/2011-01-18/ahmedabad/28352057_1_uav-squadron-unmanned-aerial-vehicle-squadron-western-coast">the original</a> on 4 November 2012<span class="reference-accessdate">. Retrieved <span class="nowrap">3 July</span> 2013</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Times+of+India&amp;rft.atitle=Eye+in+the+sky+to+guard+Gujarat+coast&amp;rft.date=2011-01-18&amp;rft_id=http%3A%2F%2Farticles.timesofindia.indiatimes.com%2F2011-01-18%2Fahmedabad%2F28352057_1_uav-squadron-unmanned-aerial-vehicle-squadron-western-coast&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-74"><span class="mw-cite-backlink"><b><a href="#cite_ref-74">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="http://us.rediff.com/news/2006/jan/06uav.htm?q=np&amp;file=.htm">"Indian Navy commissions first UAV squadron"</a>. Us.rediff.com<span class="reference-accessdate">. Retrieved <span class="nowrap">18 November</span> 2012</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=Indian+Navy+commissions+first+UAV+squadron&amp;rft.pub=Us.rediff.com&amp;rft_id=http%3A%2F%2Fus.rediff.com%2Fnews%2F2006%2Fjan%2F06uav.htm%3Fq%3Dnp%26file%3D.htm&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-75"><span class="mw-cite-backlink"><b><a href="#cite_ref-75">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite id="CITEREFPeri2020" class="citation news cs1">Peri, Dinakar (25 November 2020). <a rel="nofollow" class="external text" href="https://www.thehindu.com/news/national/navy-inducts-two-sea-guardian-drones-on-lease-from-us/article33178519.ece">"Navy inducts two Sea Guardian drones on lease from U.S."</a> <i>The Hindu</i>. <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/0971-751X">0971-751X</a><span class="reference-accessdate">. Retrieved <span class="nowrap">30 November</span> 2020</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Hindu&amp;rft.atitle=Navy+inducts+two+Sea+Guardian+drones+on+lease+from+U.S.&amp;rft.date=2020-11-25&amp;rft.issn=0971-751X&amp;rft.aulast=Peri&amp;rft.aufirst=Dinakar&amp;rft_id=https%3A%2F%2Fwww.thehindu.com%2Fnews%2Fnational%2Fnavy-inducts-two-sea-guardian-drones-on-lease-from-us%2Farticle33178519.ece&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:6-76"><span class="mw-cite-backlink"><b><a href="#cite_ref-:6_76-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.hindustantimes.com/india-news/india-first-indigenously-manufactured-uav-drishti-10-starliner-flagged-off-101704866050985.html">"India's first indigenously manufactured UAV 'Drishti 10 Starliner' flagged off"</a>. <i>Hindustan Times</i>. 10 January 2024<span class="reference-accessdate">. Retrieved <span class="nowrap">10 January</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Hindustan+Times&amp;rft.atitle=India%27s+first+indigenously+manufactured+UAV+%27Drishti+10+Starliner%27+flagged+off&amp;rft.date=2024-01-10&amp;rft_id=https%3A%2F%2Fwww.hindustantimes.com%2Findia-news%2Findia-first-indigenously-manufactured-uav-drishti-10-starliner-flagged-off-101704866050985.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-77"><span class="mw-cite-backlink"><b><a href="#cite_ref-77">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.indiatoday.in/india/story/navy-gets-first-india-made-long-endurance-starliner-drone-2486731-2024-01-10">"Navy gets first India-made long endurance Drishti 10 Starliner drone"</a>. <i>India Today</i><span class="reference-accessdate">. Retrieved <span class="nowrap">10 January</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=India+Today&amp;rft.atitle=Navy+gets+first+India-made+long+endurance+Drishti+10+Starliner+drone&amp;rft_id=https%3A%2F%2Fwww.indiatoday.in%2Findia%2Fstory%2Fnavy-gets-first-india-made-long-endurance-starliner-drone-2486731-2024-01-10&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-thestatesman.com-78"><span class="mw-cite-backlink"><b><a href="#cite_ref-thestatesman.com_78-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://www.thestatesman.com/northeast/indian-coast-guard-to-induct-16-advanced-light-helicopters-2-of-them-for-north-east-1502742438.html">"Indian Coast Guard to induct 16 Advanced Light Helicopters in July, 2 of them for North-East"</a>. <i><a href="/wiki/The_Statesman_(India)" title="The Statesman (India)">The Statesman</a></i>. 2 April 2019.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Statesman&amp;rft.atitle=Indian+Coast+Guard+to+induct+16+Advanced+Light+Helicopters+in+July%2C+2+of+them+for+North-East&amp;rft.date=2019-04-02&amp;rft_id=https%3A%2F%2Fwww.thestatesman.com%2Fnortheast%2Findian-coast-guard-to-induct-16-advanced-light-helicopters-2-of-them-for-north-east-1502742438.html&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-79"><span class="mw-cite-backlink"><b><a href="#cite_ref-79">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://www.financialexpress.com/business/defence-indian-coast-guard-to-get-dornier-aircraft-from-hal-3160424/">"Indian Coast Guard to get Dornier aircraft from HAL"</a>. 7 July 2023<span class="reference-accessdate">. Retrieved <span class="nowrap">8 July</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.atitle=Indian+Coast+Guard+to+get+Dornier+aircraft+from+HAL&amp;rft.date=2023-07-07&amp;rft_id=https%3A%2F%2Fwww.financialexpress.com%2Fbusiness%2Fdefence-indian-coast-guard-to-get-dornier-aircraft-from-hal-3160424%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-80"><span class="mw-cite-backlink"><b><a href="#cite_ref-80">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.ndtv.com/india-news/army-clears-grounded-dhruv-chopper-fleet-for-flight-but-conditions-apply-4080889">"Army Clears Grounded 'Dhruv' Chopper Fleet For Flight, But Conditions Apply"</a>. <i>NDTV.com</i><span class="reference-accessdate">. Retrieved <span class="nowrap">13 August</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=NDTV.com&amp;rft.atitle=Army+Clears+Grounded+%27Dhruv%27+Chopper+Fleet+For+Flight%2C+But+Conditions+Apply&amp;rft_id=https%3A%2F%2Fwww.ndtv.com%2Findia-news%2Farmy-clears-grounded-dhruv-chopper-fleet-for-flight-but-conditions-apply-4080889&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-81"><span class="mw-cite-backlink"><b><a href="#cite_ref-81">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.pib.gov.in/PressReleasePage.aspx?PRID=1880134">"Indian Coast Guard Advanced Light Helicopter Mk-III squadron, 840 Sqn (CG), commissioned in Chennai"</a>. <i>www.pib.gov.in</i><span class="reference-accessdate">. Retrieved <span class="nowrap">13 August</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=www.pib.gov.in&amp;rft.atitle=Indian+Coast+Guard+Advanced+Light+Helicopter+Mk-III+squadron%2C+840+Sqn+%28CG%29%2C+commissioned+in+Chennai&amp;rft_id=https%3A%2F%2Fwww.pib.gov.in%2FPressReleasePage.aspx%3FPRID%3D1880134&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-82"><span class="mw-cite-backlink"><b><a href="#cite_ref-82">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://www.thehindu.com/news/national/indian-coast-guard-looks-for-new-helicopters-rotary-unmanned-aerial-vehicles/article66187739.ece">"Indian Coast Guard looks for new helicopters, rotary Unmanned Aerial Vehicles"</a>. <i>The Hindu</i>. 26 November 2022. <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/0971-751X">0971-751X</a><span class="reference-accessdate">. Retrieved <span class="nowrap">13 August</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Hindu&amp;rft.atitle=Indian+Coast+Guard+looks+for+new+helicopters%2C+rotary+Unmanned+Aerial+Vehicles&amp;rft.date=2022-11-26&amp;rft.issn=0971-751X&amp;rft_id=https%3A%2F%2Fwww.thehindu.com%2Fnews%2Fnational%2Findian-coast-guard-looks-for-new-helicopters-rotary-unmanned-aerial-vehicles%2Farticle66187739.ece&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:022-83"><span class="mw-cite-backlink"><b><a href="#cite_ref-:022_83-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.reuters.com/business/aerospace-defense/indias-defence-ministry-signs-deals-worth-975-mln-indigenous-helicopters-2024-03-13/">"India's defence ministry signs deals worth $975 mln for indigenous helicopters"</a>. <i><a href="/wiki/Reuters" title="Reuters">Reuters</a></i>. 13 March 2024.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=unknown&amp;rft.jtitle=Reuters&amp;rft.atitle=India%27s+defence+ministry+signs+deals+worth+%24975+mln+for+indigenous+helicopters&amp;rft.date=2024-03-13&amp;rft_id=https%3A%2F%2Fwww.reuters.com%2Fbusiness%2Faerospace-defense%2Findias-defence-ministry-signs-deals-worth-975-mln-indigenous-helicopters-2024-03-13%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-84"><span class="mw-cite-backlink"><b><a href="#cite_ref-84">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation news cs1"><a rel="nofollow" class="external text" href="https://economictimes.indiatimes.com/news/defence/cabinet-committee-on-security-clears-34-new-dhruv-choppers-for-indian-coast-guard-army/articleshow/108306276.cms?from=mdr">"Cabinet Committee on Security clears 34 new Dhruv choppers for Indian Coast Guard, Army"</a>. <i>The Economic Times</i>. 7 March 2024. <a href="/wiki/ISSN_(identifier)" class="mw-redirect" title="ISSN (identifier)">ISSN</a>&#160;<a rel="nofollow" class="external text" href="https://search.worldcat.org/issn/0013-0389">0013-0389</a><span class="reference-accessdate">. Retrieved <span class="nowrap">8 March</span> 2024</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.jtitle=The+Economic+Times&amp;rft.atitle=Cabinet+Committee+on+Security+clears+34+new+Dhruv+choppers+for+Indian+Coast+Guard%2C+Army&amp;rft.date=2024-03-07&amp;rft.issn=0013-0389&amp;rft_id=https%3A%2F%2Feconomictimes.indiatimes.com%2Fnews%2Fdefence%2Fcabinet-committee-on-security-clears-34-new-dhruv-choppers-for-indian-coast-guard-army%2Farticleshow%2F108306276.cms%3Ffrom%3Dmdr&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    <li id="cite_note-:0-85"><span class="mw-cite-backlink"><b><a href="#cite_ref-:0_85-0">^</a></b></span> <span class="reference-text"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1238218222"><cite class="citation web cs1"><a rel="nofollow" class="external text" href="https://www.iiss.org/publications/the-military-balance/">"The Military Balance 2023"</a>. <a href="/wiki/International_Institute_for_Strategic_Studies" title="International Institute for Strategic Studies">International Institute for Strategic Studies</a>. p.&#160;252<span class="reference-accessdate">. Retrieved <span class="nowrap">27 December</span> 2023</span>.</cite><span title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=The+Military+Balance+2023&amp;rft.pages=252&amp;rft.pub=International+Institute+for+Strategic+Studies&amp;rft_id=https%3A%2F%2Fwww.iiss.org%2Fpublications%2Fthe-military-balance%2F&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+active+Indian+military+aircraft" class="Z3988"></span></span>
    </li>
    </ol></div>
    <div class="mw-heading mw-heading2"><h2 id="External_links">External links</h2></div>
    <ul><li><a rel="nofollow" class="external text" href="http://indianairforce.nic.in/show_unit_page.php?pg_id=23&amp;cat=F">The Official Home Page of Indian Air Force.</a></li></ul>
    <div class="navbox-styles"><style data-mw-deduplicate="TemplateStyles:r1129693374">.mw-parser-output .hlist dl,.mw-parser-output .hlist ol,.mw-parser-output .hlist ul{margin:0;padding:0}.mw-parser-output .hlist dd,.mw-parser-output .hlist dt,.mw-parser-output .hlist li{margin:0;display:inline}.mw-parser-output .hlist.inline,.mw-parser-output .hlist.inline dl,.mw-parser-output .hlist.inline ol,.mw-parser-output .hlist.inline ul,.mw-parser-output .hlist dl dl,.mw-parser-output .hlist dl ol,.mw-parser-output .hlist dl ul,.mw-parser-output .hlist ol dl,.mw-parser-output .hlist ol ol,.mw-parser-output .hlist ol ul,.mw-parser-output .hlist ul dl,.mw-parser-output .hlist ul ol,.mw-parser-output .hlist ul ul{display:inline}.mw-parser-output .hlist .mw-empty-li{display:none}.mw-parser-output .hlist dt::after{content:": "}.mw-parser-output .hlist dd::after,.mw-parser-output .hlist li::after{content:" · ";font-weight:bold}.mw-parser-output .hlist dd:last-child::after,.mw-parser-output .hlist dt:last-child::after,.mw-parser-output .hlist li:last-child::after{content:none}.mw-parser-output .hlist dd dd:first-child::before,.mw-parser-output .hlist dd dt:first-child::before,.mw-parser-output .hlist dd li:first-child::before,.mw-parser-output .hlist dt dd:first-child::before,.mw-parser-output .hlist dt dt:first-child::before,.mw-parser-output .hlist dt li:first-child::before,.mw-parser-output .hlist li dd:first-child::before,.mw-parser-output .hlist li dt:first-child::before,.mw-parser-output .hlist li li:first-child::before{content:" (";font-weight:normal}.mw-parser-output .hlist dd dd:last-child::after,.mw-parser-output .hlist dd dt:last-child::after,.mw-parser-output .hlist dd li:last-child::after,.mw-parser-output .hlist dt dd:last-child::after,.mw-parser-output .hlist dt dt:last-child::after,.mw-parser-output .hlist dt li:last-child::after,.mw-parser-output .hlist li dd:last-child::after,.mw-parser-output .hlist li dt:last-child::after,.mw-parser-output .hlist li li:last-child::after{content:")";font-weight:normal}.mw-parser-output .hlist ol{counter-reset:listitem}.mw-parser-output .hlist ol>li{counter-increment:listitem}.mw-parser-output .hlist ol>li::before{content:" "counter(listitem)"\a0 "}.mw-parser-output .hlist dd ol>li:first-child::before,.mw-parser-output .hlist dt ol>li:first-child::before,.mw-parser-output .hlist li ol>li:first-child::before{content:" ("counter(listitem)"\a0 "}</style><style data-mw-deduplicate="TemplateStyles:r1236075235">.mw-parser-output .navbox{box-sizing:border-box;border:1px solid #a2a9b1;width:100%;clear:both;font-size:88%;text-align:center;padding:1px;margin:1em auto 0}.mw-parser-output .navbox .navbox{margin-top:0}.mw-parser-output .navbox+.navbox,.mw-parser-output .navbox+.navbox-styles+.navbox{margin-top:-1px}.mw-parser-output .navbox-inner,.mw-parser-output .navbox-subgroup{width:100%}.mw-parser-output .navbox-group,.mw-parser-output .navbox-title,.mw-parser-output .navbox-abovebelow{padding:0.25em 1em;line-height:1.5em;text-align:center}.mw-parser-output .navbox-group{white-space:nowrap;text-align:right}.mw-parser-output .navbox,.mw-parser-output .navbox-subgroup{background-color:#fdfdfd}.mw-parser-output .navbox-list{line-height:1.5em;border-color:#fdfdfd}.mw-parser-output .navbox-list-with-group{text-align:left;border-left-width:2px;border-left-style:solid}.mw-parser-output tr+tr>.navbox-abovebelow,.mw-parser-output tr+tr>.navbox-group,.mw-parser-output tr+tr>.navbox-image,.mw-parser-output tr+tr>.navbox-list{border-top:2px solid #fdfdfd}.mw-parser-output .navbox-title{background-color:#ccf}.mw-parser-output .navbox-abovebelow,.mw-parser-output .navbox-group,.mw-parser-output .navbox-subgroup .navbox-title{background-color:#ddf}.mw-parser-output .navbox-subgroup .navbox-group,.mw-parser-output .navbox-subgroup .navbox-abovebelow{background-color:#e6e6ff}.mw-parser-output .navbox-even{background-color:#f7f7f7}.mw-parser-output .navbox-odd{background-color:transparent}.mw-parser-output .navbox .hlist td dl,.mw-parser-output .navbox .hlist td ol,.mw-parser-output .navbox .hlist td ul,.mw-parser-output .navbox td.hlist dl,.mw-parser-output .navbox td.hlist ol,.mw-parser-output .navbox td.hlist ul{padding:0.125em 0}.mw-parser-output .navbox .navbar{display:block;font-size:100%}.mw-parser-output .navbox-title .navbar{float:left;text-align:left;margin-right:0.5em}body.skin--responsive .mw-parser-output .navbox-image img{max-width:none!important}@media print{body.ns-0 .mw-parser-output .navbox{display:none!important}}</style></div><div role="navigation" class="navbox" aria-labelledby="18px_Indian_Armed_Forces" style=";wide;padding:3px"><table class="nowraplinks hlist mw-collapsible mw-collapsed navbox-inner" style="border-spacing:0;background:transparent;color:inherit"><tbody><tr><th scope="col" class="navbox-title" colspan="2" style="background-color:#C3D6EF;color:inherit;"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1129693374"><style data-mw-deduplicate="TemplateStyles:r1239400231">.mw-parser-output .navbar{display:inline;font-size:88%;font-weight:normal}.mw-parser-output .navbar-collapse{float:left;text-align:left}.mw-parser-output .navbar-boxtext{word-spacing:0}.mw-parser-output .navbar ul{display:inline-block;white-space:nowrap;line-height:inherit}.mw-parser-output .navbar-brackets::before{margin-right:-0.125em;content:"[ "}.mw-parser-output .navbar-brackets::after{margin-left:-0.125em;content:" ]"}.mw-parser-output .navbar li{word-spacing:-0.125em}.mw-parser-output .navbar a>span,.mw-parser-output .navbar a>abbr{text-decoration:inherit}.mw-parser-output .navbar-mini abbr{font-variant:small-caps;border-bottom:none;text-decoration:none;cursor:inherit}.mw-parser-output .navbar-ct-full{font-size:114%;margin:0 7em}.mw-parser-output .navbar-ct-mini{font-size:114%;margin:0 4em}html.skin-theme-clientpref-night .mw-parser-output .navbar li a abbr{color:var(--color-base)!important}@media(prefers-color-scheme:dark){html.skin-theme-clientpref-os .mw-parser-output .navbar li a abbr{color:var(--color-base)!important}}@media print{.mw-parser-output .navbar{display:none!important}}</style><div class="navbar plainlinks hlist navbar-mini"><ul><li class="nv-view"><a href="/wiki/Template:Military_of_India" title="Template:Military of India"><abbr title="View this template" style="color:inherit">v</abbr></a></li><li class="nv-talk"><a href="/wiki/Template_talk:Military_of_India" title="Template talk:Military of India"><abbr title="Discuss this template" style="color:inherit">t</abbr></a></li><li class="nv-edit"><a href="/wiki/Special:EditPage/Template:Military_of_India" title="Special:EditPage/Template:Military of India"><abbr title="Edit this template" style="color:inherit">e</abbr></a></li></ul></div><div id="18px_Indian_Armed_Forces" style="font-size:114%;margin:0 4em"><span typeof="mw:File"><a href="/wiki/File:Indian_Armed_Forces.svg" class="mw-file-description"><img src="//upload.wikimedia.org/wikipedia/commons/thumb/4/4a/Indian_Armed_Forces.svg/18px-Indian_Armed_Forces.svg.png" decoding="async" width="18" height="12" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/4/4a/Indian_Armed_Forces.svg/27px-Indian_Armed_Forces.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/4/4a/Indian_Armed_Forces.svg/36px-Indian_Armed_Forces.svg.png 2x" data-file-width="900" data-file-height="600" /></a></span> <a href="/wiki/Indian_Armed_Forces" title="Indian Armed Forces">Indian Armed Forces</a></div></th></tr><tr><td class="navbox-abovebelow" colspan="2" style="background-color:#DCDCDC;color:inherit;"><div>
    <ul><li><span class="flagicon"><span class="mw-image-border" typeof="mw:File"><span><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/e/ea/Flag_of_Indian_Army.svg/23px-Flag_of_Indian_Army.svg.png" decoding="async" width="23" height="12" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/e/ea/Flag_of_Indian_Army.svg/35px-Flag_of_Indian_Army.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/e/ea/Flag_of_Indian_Army.svg/46px-Flag_of_Indian_Army.svg.png 2x" data-file-width="900" data-file-height="450" /></span></span>&#160;</span><a href="/wiki/Indian_Army" title="Indian Army">Indian Army</a></li>
    <li><span class="flagicon"><span class="mw-image-border" typeof="mw:File"><span><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/3/35/Naval_Ensign_of_India.svg/23px-Naval_Ensign_of_India.svg.png" decoding="async" width="23" height="12" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/3/35/Naval_Ensign_of_India.svg/35px-Naval_Ensign_of_India.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/3/35/Naval_Ensign_of_India.svg/46px-Naval_Ensign_of_India.svg.png 2x" data-file-width="1200" data-file-height="600" /></span></span>&#160;</span><a href="/wiki/Indian_Navy" title="Indian Navy">Indian Navy</a></li>
    <li><span class="flagicon"><span class="mw-image-border" typeof="mw:File"><span><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/8/8e/Air_Force_Ensign_of_India.svg/23px-Air_Force_Ensign_of_India.svg.png" decoding="async" width="23" height="12" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/8/8e/Air_Force_Ensign_of_India.svg/35px-Air_Force_Ensign_of_India.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/8/8e/Air_Force_Ensign_of_India.svg/46px-Air_Force_Ensign_of_India.svg.png 2x" data-file-width="1200" data-file-height="600" /></span></span>&#160;</span><a href="/wiki/Indian_Air_Force" title="Indian Air Force">Indian Air Force</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Leadership</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/President_of_India" title="President of India">President</a></li>
    <li><a href="/wiki/Prime_Minister_of_India" title="Prime Minister of India">Prime Minister</a></li>
    <li><a href="/wiki/Minister_of_Defence_(India)" title="Minister of Defence (India)">Minister of Defence</a></li>
    <li><a href="/wiki/Defence_Secretary_(India)" title="Defence Secretary (India)">Defence Secretary</a></li>
    <li><a href="/wiki/National_Security_Advisor_(India)" title="National Security Advisor (India)">National Security Advisor</a></li>
    <li><a href="/wiki/Chief_of_Defence_Staff_(India)" title="Chief of Defence Staff (India)">Chief of Defence Staff</a> (<a href="/wiki/Chairman_Chiefs_of_Staff_Committee" class="mw-redirect" title="Chairman Chiefs of Staff Committee">Chairman Chiefs of Staff Committee</a>)</li>
    <li><a href="/wiki/Chief_of_the_Army_Staff_(India)" title="Chief of the Army Staff (India)">Chief of the Army Staff</a></li>
    <li><a href="/wiki/Chief_of_the_Naval_Staff_(India)" title="Chief of the Naval Staff (India)">Chief of the Naval Staff</a></li>
    <li><a href="/wiki/Chief_of_the_Air_Staff_(India)" title="Chief of the Air Staff (India)">Chief of the Air Staff</a></li>
    <li><a href="/wiki/Chief_of_Integrated_Defence_Staff" title="Chief of Integrated Defence Staff">Vice Chief of Defence Staff</a></li>
    <li><a href="/wiki/Director_General_Armed_Forces_Medical_Services_(India)" title="Director General Armed Forces Medical Services (India)">Director General Armed Forces Medical Services</a></li>
    <li><a href="/wiki/List_of_serving_generals_of_the_Indian_Army" title="List of serving generals of the Indian Army">Serving generals</a></li>
    <li><a href="/wiki/List_of_serving_admirals_of_the_Indian_Navy" title="List of serving admirals of the Indian Navy">Serving admirals</a></li>
    <li><a href="/wiki/List_of_serving_marshals_of_the_Indian_Air_Force" title="List of serving marshals of the Indian Air Force">Serving marshals</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Organisation</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks navbox-subgroup" style="border-spacing:0;;wide"><tbody><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Ministry and<br />committees/councils</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Ministry_of_Defence_(India)" title="Ministry of Defence (India)">Ministry of Defence</a>
    <ul><li><a href="/wiki/Department_of_Military_Affairs" title="Department of Military Affairs">Department of Military Affairs</a></li>
    <li><a href="/wiki/Defence_Research_and_Development_Organisation" title="Defence Research and Development Organisation">Department of Defence Research and Development</a></li>
    <li><a href="/wiki/Department_of_Ex-servicemen_Welfare" title="Department of Ex-servicemen Welfare">Department of Ex-servicemen Welfare</a></li></ul></li>
    <li><a href="/wiki/National_Security_Council_(India)" title="National Security Council (India)">National Security Council</a></li>
    <li><a href="/wiki/Cabinet_Committee_on_Security" title="Cabinet Committee on Security">Cabinet Committee on Security</a></li>
    <li><a href="/wiki/Standing_Committee_on_Defence_(India)" title="Standing Committee on Defence (India)">Standing Committee on Defence</a></li>
    <li><a href="/wiki/Defence_Planning_Committee" title="Defence Planning Committee">Defence Planning Committee</a></li>
    <li><a href="/wiki/Nuclear_Command_Authority_(India)" title="Nuclear Command Authority (India)">Nuclear Command Authority</a></li>
    <li><a href="/wiki/Integrated_Defence_Staff" title="Integrated Defence Staff">Integrated Defence Staff</a></li>
    <li><a href="/wiki/Defence_Intelligence_Agency_(India)" title="Defence Intelligence Agency (India)">Defence Intelligence Agency</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Commands</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks navbox-subgroup" style="border-spacing:0;;wide"><tbody><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;"><a href="/wiki/Joint_warfare" title="Joint warfare">Joint</a></th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Indian_Armed_Forces_Tri-Service_Commands" class="mw-redirect" title="Indian Armed Forces Tri-Service Commands">Integrated Theatre Commands</a></li>
    <li><a href="/wiki/Andaman_and_Nicobar_Command" title="Andaman and Nicobar Command">Andaman and Nicobar Command</a>
    <ul><li><a href="/wiki/Commander-in-Chief,_Andaman_and_Nicobar_Command" title="Commander-in-Chief, Andaman and Nicobar Command">Commander-in-Chief</a></li></ul></li>
    <li><a href="/wiki/Strategic_Forces_Command" title="Strategic Forces Command">Strategic Forces Command</a>
    <ul><li><a href="/wiki/Commander-in-Chief,_Strategic_Forces_Command" title="Commander-in-Chief, Strategic Forces Command">Commander-in-Chief</a></li></ul></li>
    <li><a href="/wiki/Northern_Theatre_Command_(India)" title="Northern Theatre Command (India)">Northern Theatre Command (India)</a></li>
    <li><a href="/wiki/Western_Theatre_Command_(India)" title="Western Theatre Command (India)">Western Theatre Command (India)</a></li>
    <li><a href="/wiki/Maritime_Theatre_Command" title="Maritime Theatre Command">Maritime Theatre Command</a></li>
    <li><a href="/wiki/Defence_Cyber_Agency" title="Defence Cyber Agency">Defence Cyber Agency</a></li>
    <li><a href="/wiki/Defence_Space_Agency" title="Defence Space Agency">Defence Space Agency</a></li>
    <li><a href="/wiki/Armed_Forces_Special_Operations_Division" title="Armed Forces Special Operations Division">Armed Forces Special Operations Division</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;"><a href="/wiki/Indian_Army" title="Indian Army">Army</a></th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Central_Command_(India)" title="Central Command (India)">Central Command</a></li>
    <li><a href="/wiki/Eastern_Command_(India)" title="Eastern Command (India)">Eastern Command</a></li>
    <li><a href="/wiki/Northern_Command_(India)" title="Northern Command (India)">Northern Command</a></li>
    <li><a href="/wiki/Southern_Command_(India)" title="Southern Command (India)">Southern Command</a></li>
    <li><a href="/wiki/South_Western_Command_(India)" title="South Western Command (India)">South Western Command</a></li>
    <li><a href="/wiki/Western_Command_(India)" title="Western Command (India)">Western Command</a></li>
    <li><a href="/wiki/Army_Training_Command" title="Army Training Command">Army Training Command</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;"><a href="/wiki/Indian_Navy" title="Indian Navy">Navy</a></th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Western_Naval_Command" title="Western Naval Command">Western Naval Command</a></li>
    <li><a href="/wiki/Eastern_Naval_Command" title="Eastern Naval Command">Eastern Naval Command</a></li>
    <li><a href="/wiki/Southern_Naval_Command" title="Southern Naval Command">Southern Naval Command</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;"><a href="/wiki/Indian_Air_Force" title="Indian Air Force">Air Force</a></th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Central_Air_Command_(India)" title="Central Air Command (India)">Central Air Command</a></li>
    <li><a href="/wiki/Eastern_Air_Command_(India)" title="Eastern Air Command (India)">Eastern Air Command</a></li>
    <li><a href="/wiki/Southern_Air_Command_(India)" title="Southern Air Command (India)">Southern Air Command</a></li>
    <li><a href="/wiki/South_Western_Air_Command" title="South Western Air Command">South Western Air Command</a></li>
    <li><a href="/wiki/Western_Air_Command_(India)" title="Western Air Command (India)">Western Air Command</a></li>
    <li><a href="/wiki/Training_Command_(India)" title="Training Command (India)">Training Command</a></li>
    <li><a href="/wiki/Maintenance_Command" title="Maintenance Command">Maintenance Command</a></li></ul>
    </div></td></tr></tbody></table><div></div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Other components</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Indian_Coast_Guard" title="Indian Coast Guard">Indian Coast Guard</a></li>
    <li><a href="/wiki/National_Cadet_Corps_(India)" title="National Cadet Corps (India)">National Cadet Corps</a></li>
    <li><a href="/wiki/Paramilitary_forces_of_India" title="Paramilitary forces of India">Paramilitary forces</a></li>
    <li><a href="/wiki/Special_forces_of_India" title="Special forces of India">Special forces</a></li>
    <li><a href="/wiki/Territorial_Army_(India)" title="Territorial Army (India)">Territorial Army</a></li>
    <li><a href="/wiki/Border_Roads_Organisation" title="Border Roads Organisation">Border Roads Organisation</a></li></ul>
    </div></td></tr></tbody></table><div></div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Personnel</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Military_academies_in_India" title="Military academies in India">Military Academies</a></li>
    <li>Ranks and insignia
    <ul><li><a href="/wiki/Army_ranks_and_insignia_of_India" class="mw-redirect" title="Army ranks and insignia of India">Army</a></li>
    <li><a href="/wiki/Naval_ranks_and_insignia_of_India" class="mw-redirect" title="Naval ranks and insignia of India">Navy</a></li>
    <li><a href="/wiki/Air_Force_ranks_and_insignia_of_India" class="mw-redirect" title="Air Force ranks and insignia of India">Air Force</a></li>
    <li><a href="/wiki/Indian_Coast_Guard#Rank_insignia" title="Indian Coast Guard">Coast Guard</a></li>
    <li><a href="/wiki/Border_Roads_Organisation#Ranks" title="Border Roads Organisation">Border Roads Organisation</a></li>
    <li><a href="/wiki/Paramilitary_forces_of_India#Ranks_and_insignia" title="Paramilitary forces of India">Paramilitary forces</a></li></ul></li>
    <li><a href="/wiki/Awards_and_decorations_of_the_Indian_Armed_Forces" title="Awards and decorations of the Indian Armed Forces">Awards and Decorations</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;"><a href="/wiki/List_of_military_operations_of_India" title="List of military operations of India">Operations</a></th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks navbox-subgroup" style="border-spacing:0;;wide"><tbody><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Wars</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Indo-Pakistani_wars_and_conflicts" title="Indo-Pakistani wars and conflicts">Indo-Pakistani wars</a>
    <ul><li><a href="/wiki/Indo-Pakistani_War_of_1947%E2%80%931948" class="mw-redirect" title="Indo-Pakistani War of 1947–1948">1947–1948</a></li>
    <li><a href="/wiki/Indo-Pakistani_War_of_1965" class="mw-redirect" title="Indo-Pakistani War of 1965">1965</a>
    <ul><li><a href="/wiki/Battle_of_Asal_Uttar" title="Battle of Asal Uttar">Battle of Asal Uttar</a></li>
    <li><a href="/wiki/Battle_of_Chawinda" title="Battle of Chawinda">Battle of Chawinda</a></li></ul></li>
    <li><a href="/wiki/Indo-Pakistani_War_of_1971" class="mw-redirect" title="Indo-Pakistani War of 1971">1971</a>
    <ul><li><a href="/wiki/Indo-Pakistani_Naval_War_of_1971" title="Indo-Pakistani Naval War of 1971">Naval War</a></li>
    <li><a href="/wiki/East_Pakistan_Air_Operations_(1971)" title="East Pakistan Air Operations (1971)">Air War</a></li>
    <li><a href="/wiki/Battle_of_Chamb" class="mw-redirect" title="Battle of Chamb">Battle of Chamb</a></li>
    <li><a href="/wiki/Operation_Trident_(1971)" title="Operation Trident (1971)">Operation <i>Trident</i></a></li>
    <li><a href="/wiki/Operation_Cactus-Lilly" class="mw-redirect" title="Operation Cactus-Lilly">Operation <i>Cactus-Lilly</i></a></li>
    <li><a href="/wiki/Battle_of_Longewala" title="Battle of Longewala">Battle of Longewala</a></li></ul></li>
    <li><a href="/wiki/Kargil_War" title="Kargil War">Kargil War</a></li></ul></li>
    <li><a href="/wiki/Sino-Indian_War" title="Sino-Indian War">Sino-Indian War</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">External <br />conflicts</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Kashmir_conflict" title="Kashmir conflict">Kashmir conflict</a></li>
    <li><a href="/wiki/Korean_War" title="Korean War">Korean War</a></li>
    <li><a href="/wiki/Siachen_conflict" title="Siachen conflict">Siachen conflict</a></li>
    <li><a href="/wiki/Line_of_Control" title="Line of Control">Indo-Pakistani border skirmishes</a>
    <ul><li><a href="/wiki/2001%E2%80%932002_India%E2%80%93Pakistan_standoff" title="2001–2002 India–Pakistan standoff">Operation <i>Parakram</i></a></li>
    <li><a href="/wiki/2011_India%E2%80%93Pakistan_border_skirmish" title="2011 India–Pakistan border skirmish">2011</a></li>
    <li><a href="/wiki/2013_India%E2%80%93Pakistan_border_skirmishes" title="2013 India–Pakistan border skirmishes">2013</a></li>
    <li><a href="/wiki/2014%E2%80%932015_India%E2%80%93Pakistan_border_skirmishes" title="2014–2015 India–Pakistan border skirmishes">2014–2015</a></li>
    <li><a href="/wiki/2016%E2%80%932018_India%E2%80%93Pakistan_border_skirmishes" title="2016–2018 India–Pakistan border skirmishes">2016–2018</a></li>
    <li><a href="/wiki/2019_India%E2%80%93Pakistan_border_skirmishes" title="2019 India–Pakistan border skirmishes">2019</a>
    <ul><li><a href="/wiki/2019_Balakot_airstrike" title="2019 Balakot airstrike">Balakot airstrike</a></li></ul></li></ul></li>
    <li><a href="/wiki/Congo_Crisis" title="Congo Crisis">Congo Crisis</a></li>
    <li><a href="/wiki/Line_of_Actual_Control" title="Line of Actual Control">Sino-Indian border skirmish</a>
    <ul><li><a href="/wiki/Sumdorong_Chu_standoff" title="Sumdorong Chu standoff">1987</a></li>
    <li><a href="/wiki/Nathu_La_and_Cho_La_clashes" title="Nathu La and Cho La clashes">Nathu La and Cho La clashes</a></li>
    <li><a href="/wiki/2017_China%E2%80%93India_border_standoff" title="2017 China–India border standoff">Doklam standoff</a></li>
    <li><a href="/wiki/2020%E2%80%932021_China%E2%80%93India_skirmishes" title="2020–2021 China–India skirmishes">2020</a></li></ul></li>
    <li><a href="/wiki/Indian_intervention_in_the_Sri_Lankan_Civil_War" title="Indian intervention in the Sri Lankan Civil War">Indian intervention in the Sri Lankan Civil War</a></li>
    <li><a href="/wiki/1988_Maldives_coup_d%27%C3%A9tat_attempt" class="mw-redirect" title="1988 Maldives coup d&#39;état attempt">Operation <i>Cactus</i></a></li>
    <li><a href="/wiki/1990_airlift_of_Indians_from_Kuwait" title="1990 airlift of Indians from Kuwait">Evacuation of Indian civilians from Kuwait</a></li>
    <li><a href="/wiki/Piracy_off_the_coast_of_Somalia" title="Piracy off the coast of Somalia">Piracy off the coast of Somalia</a></li>
    <li><a href="/wiki/Operation_Raahat" title="Operation Raahat">Operation <i>Raahat</i></a></li>
    <li><a href="/wiki/Operation_Devi_Shakti" title="Operation Devi Shakti">Operation <i>Devi Shakti</i></a></li>
    <li><a href="/wiki/2015_Indian_counter-insurgency_operation_in_Myanmar" title="2015 Indian counter-insurgency operation in Myanmar">Indo-Myanmar border strike</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Annexations</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Annexation_of_Hyderabad" title="Annexation of Hyderabad">Operation <i>Polo</i> (Hyderabad)</a></li>
    <li><a href="/wiki/Annexation_of_Goa" title="Annexation of Goa">Operation <i>Vijay</i> (Portuguese India -  Goa, Damaon, Silvassa &amp; Diu)</a></li>
    <li><a href="/wiki/Annexation_of_Junagadh" title="Annexation of Junagadh">Junagadh</a></li>
    <li><a href="/wiki/Annexation_of_Dadra_and_Nagar_Haveli" title="Annexation of Dadra and Nagar Haveli">Dadra and Nagar Haveli</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Insurgencies</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Insurgency_in_Northeast_India" title="Insurgency in Northeast India">Northeast India</a></li>
    <li><a href="/wiki/Insurgency_in_Punjab" class="mw-redirect" title="Insurgency in Punjab">Punjab</a>
    <ul><li><a href="/wiki/Operation_Blue_Star" title="Operation Blue Star">Operation <i>Blue Star</i></a></li>
    <li><a href="/wiki/Operation_Woodrose" title="Operation Woodrose">Operation <i>Woodrose</i></a></li></ul></li>
    <li><a href="/wiki/Insurgency_in_Jammu_and_Kashmir" title="Insurgency in Jammu and Kashmir">Kashmir</a>
    <ul><li><a href="/wiki/Indian_Army_operations_in_Jammu_and_Kashmir" title="Indian Army operations in Jammu and Kashmir">Counter-insurgency operations</a></li>
    <li><a href="/wiki/2016_Indian_Line_of_Control_strike" title="2016 Indian Line of Control strike">LOC surgical strike</a></li></ul></li></ul>
    </div></td></tr></tbody></table><div></div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Equipment</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Defence_Research_and_Development_Organisation" title="Defence Research and Development Organisation">Defence Research and Development Organisation</a></li>
    <li><a href="/wiki/Ordnance_Factory_Board" class="mw-redirect" title="Ordnance Factory Board">Ordnance Factory Board</a></li>
    <li><a href="/wiki/List_of_Indian_military_missiles" title="List of Indian military missiles">Ballistic missiles</a></li>
    <li><a href="/wiki/India_and_weapons_of_mass_destruction" title="India and weapons of mass destruction">Weapons of mass destruction</a></li></ul>
    </div><table class="nowraplinks navbox-subgroup" style="border-spacing:0;;wide"><tbody><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Army</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_equipment_of_the_Indian_Army" title="List of equipment of the Indian Army">List of equipment of the Indian Army</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Navy</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_active_Indian_Navy_ships" title="List of active Indian Navy ships">Active Ships</a></li>
    <li><a href="/wiki/List_of_ships_of_the_Indian_Navy" title="List of ships of the Indian Navy">Historical Ships</a></li>
    <li><a href="/wiki/Weapon_systems_of_the_Indian_Navy" title="Weapon systems of the Indian Navy">Weapon Systems</a></li>
    <li><a href="/wiki/Future_of_the_Indian_Navy" title="Future of the Indian Navy">Future</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Air Force</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a class="mw-selflink selflink">Active Aircraft</a></li>
    <li><a href="/wiki/List_of_historical_aircraft_of_the_Indian_Air_Force" title="List of historical aircraft of the Indian Air Force">Historical Aircraft</a></li>
    <li><a href="/wiki/List_of_active_Indian_Air_Force_aircraft_squadrons" title="List of active Indian Air Force aircraft squadrons">Aircraft Squadrons</a></li>
    <li><a href="/wiki/Future_of_the_Indian_Air_Force" title="Future of the Indian Air Force">Future</a></li></ul>
    </div></td></tr></tbody></table><div>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Documents</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Ensuring_Secure_Seas:_Indian_Maritime_Security_Strategy" title="Ensuring Secure Seas: Indian Maritime Security Strategy">Indian Maritime Security Strategy</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%;background-color:#DCDCDC;color:inherit;">Other topics</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/President%27s_fleet_review" title="President&#39;s fleet review">President's fleet review</a></li>
    <li><a href="/wiki/Military_history_of_India" title="Military history of India">History</a></li>
    <li><a href="/wiki/President%27s_Colour_Award" title="President&#39;s Colour Award">President's Colour Award</a></li>
    <li><a href="/wiki/Women_in_the_Indian_Armed_Forces" title="Women in the Indian Armed Forces">Women in the Indian Armed Forces</a></li>
    <li><a href="/wiki/Armed_Forces_Flag_Day" title="Armed Forces Flag Day">Armed Forces Flag Day</a></li>
    <li><a href="/wiki/Armed_Forces_Tribunal" title="Armed Forces Tribunal">Armed Forces Tribunal</a></li>
    <li><a href="/wiki/Indian_Armed_Forces_rank_flags" title="Indian Armed Forces rank flags">Indian Armed Forces rank flags</a></li>
    <li><a href="/wiki/Indian_military_bands" title="Indian military bands">Indian military bands</a></li>
    <li><a href="/wiki/National_War_Memorial_(India)" title="National War Memorial (India)">National War Memorial</a></li>
    <li><a href="/wiki/Amar_Jawan_Jyoti" title="Amar Jawan Jyoti">Amar Jawan Jyoti</a></li></ul>
    </div></td></tr><tr><td class="navbox-abovebelow" colspan="2" style="background-color:#DCDCDC;color:inherit;"><div>
    <ul><li><span class="noviewer" typeof="mw:File"><span title="Category"><img alt="" src="//upload.wikimedia.org/wikipedia/en/thumb/9/96/Symbol_category_class.svg/16px-Symbol_category_class.svg.png" decoding="async" width="16" height="16" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/en/thumb/9/96/Symbol_category_class.svg/23px-Symbol_category_class.svg.png 1.5x, //upload.wikimedia.org/wikipedia/en/thumb/9/96/Symbol_category_class.svg/31px-Symbol_category_class.svg.png 2x" data-file-width="180" data-file-height="185" /></span></span> <a href="/wiki/Category:Military_of_India" title="Category:Military of India">Category</a>
    <ul><li><a href="/wiki/Category:Indian_Army" title="Category:Indian Army">Army</a></li>
    <li><a href="/wiki/Category:Indian_Navy" title="Category:Indian Navy">Navy</a></li>
    <li><a href="/wiki/Category:Indian_Air_Force" title="Category:Indian Air Force">Air Force</a></li></ul></li></ul>
    </div></td></tr></tbody></table></div>
    <div class="navbox-styles"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1129693374"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1236075235"></div><div role="navigation" class="navbox" aria-labelledby="Lists_of_aircraft" style="padding:3px"><table class="nowraplinks mw-collapsible mw-collapsed navbox-inner" style="border-spacing:0;background:transparent;color:inherit"><tbody><tr><th scope="col" class="navbox-title" colspan="2"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1129693374"><link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r1239400231"><div class="navbar plainlinks hlist navbar-mini"><ul><li class="nv-view"><a href="/wiki/Template:Lists_of_aircraft" title="Template:Lists of aircraft"><abbr title="View this template">v</abbr></a></li><li class="nv-talk"><a href="/wiki/Template_talk:Lists_of_aircraft" title="Template talk:Lists of aircraft"><abbr title="Discuss this template">t</abbr></a></li><li class="nv-edit"><a href="/wiki/Special:EditPage/Template:Lists_of_aircraft" title="Special:EditPage/Template:Lists of aircraft"><abbr title="Edit this template">e</abbr></a></li></ul></div><div id="Lists_of_aircraft" style="font-size:114%;margin:0 4em"><a href="/wiki/List_of_aircraft" title="List of aircraft">Lists of aircraft</a></div></th></tr><tr><td colspan="2" class="navbox-list navbox-odd hlist" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks mw-collapsible expanded navbox-subgroup" style="border-spacing:0"><tbody><tr><th scope="col" class="navbox-title" colspan="2"><div id="By_name" style="font-size:114%;margin:0 4em">By name</div></th></tr><tr><td colspan="2" class="navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_aircraft_(pre-1914)" title="List of aircraft (pre-1914)">pre-1914</a></li>
    <li><a href="/wiki/List_of_aircraft_(0-A)" class="mw-redirect" title="List of aircraft (0-A)">0-Ah</a></li>
    <li><a href="/wiki/List_of_aircraft_(Ai-Am)" class="mw-redirect" title="List of aircraft (Ai-Am)">Ai-Am</a></li>
    <li><a href="/wiki/List_of_aircraft_(An-Az)" class="mw-redirect" title="List of aircraft (An-Az)">An-Az</a></li>
    <li><a href="/wiki/List_of_aircraft_(B-Be)" class="mw-redirect" title="List of aircraft (B-Be)">B-Be</a></li>
    <li><a href="/wiki/List_of_aircraft_(Bf-Bo)" class="mw-redirect" title="List of aircraft (Bf-Bo)">Bf-Bo</a></li>
    <li><a href="/wiki/List_of_aircraft_(Br-Bz)" class="mw-redirect" title="List of aircraft (Br-Bz)">Br-Bz</a></li>
    <li><a href="/wiki/List_of_aircraft_(C-Ca)" class="mw-redirect" title="List of aircraft (C-Ca)">C-Ca</a></li>
    <li><a href="/wiki/List_of_aircraft_(Cd-Cn)" class="mw-redirect" title="List of aircraft (Cd-Cn)">Cd-Cn</a></li>
    <li><a href="/wiki/List_of_aircraft_(Co-Cz)" class="mw-redirect" title="List of aircraft (Co-Cz)">Co-Cz</a></li>
    <li><a href="/wiki/List_of_aircraft_(D)" class="mw-redirect" title="List of aircraft (D)">D</a></li>
    <li><a href="/wiki/List_of_aircraft_(E)" title="List of aircraft (E)">E</a></li>
    <li><a href="/wiki/List_of_aircraft_(F)" title="List of aircraft (F)">F</a></li>
    <li><a href="/wiki/List_of_aircraft_(G-Gn)" title="List of aircraft (G-Gn)">G-Gn</a></li>
    <li><a href="/wiki/List_of_aircraft_(Go-Gz)" title="List of aircraft (Go-Gz)">Go-Gz</a></li>
    <li><a href="/wiki/List_of_aircraft_(H)" class="mw-redirect" title="List of aircraft (H)">H</a></li>
    <li><a href="/wiki/List_of_aircraft_(I)" title="List of aircraft (I)">I</a></li>
    <li><a href="/wiki/List_of_aircraft_(J)" title="List of aircraft (J)">J</a></li>
    <li><a href="/wiki/List_of_aircraft_(K)" title="List of aircraft (K)">K</a></li>
    <li><a href="/wiki/List_of_aircraft_(La-Lh)" class="mw-redirect" title="List of aircraft (La-Lh)">La-Lh</a></li>
    <li><a href="/wiki/List_of_aircraft_(Li-Lz)" class="mw-redirect" title="List of aircraft (Li-Lz)">Li-Lz</a></li>
    <li><a href="/wiki/List_of_aircraft_(M)" class="mw-redirect" title="List of aircraft (M)">M</a></li>
    <li><a href="/wiki/List_of_aircraft_(N)" title="List of aircraft (N)">N</a></li>
    <li><a href="/wiki/List_of_aircraft_(O)" title="List of aircraft (O)">O</a></li>
    <li><a href="/wiki/List_of_aircraft_(P)" class="mw-redirect" title="List of aircraft (P)">P</a></li>
    <li><a href="/wiki/List_of_aircraft_(Q)" title="List of aircraft (Q)">Q</a></li>
    <li><a href="/wiki/List_of_aircraft_(R)" title="List of aircraft (R)">R</a></li>
    <li><a href="/wiki/List_of_aircraft_(S)" title="List of aircraft (S)">S</a></li>
    <li><a href="/wiki/List_of_aircraft_(T)" title="List of aircraft (T)">T</a></li>
    <li><a href="/wiki/List_of_aircraft_(U)" title="List of aircraft (U)">U</a></li>
    <li><a href="/wiki/List_of_aircraft_(V)" title="List of aircraft (V)">V</a></li>
    <li><a href="/wiki/List_of_aircraft_(W)" title="List of aircraft (W)">W</a></li>
    <li><a href="/wiki/List_of_aircraft_(X)" title="List of aircraft (X)">X</a></li>
    <li><a href="/wiki/List_of_aircraft_(Y)" title="List of aircraft (Y)">Y</a></li>
    <li><a href="/wiki/List_of_aircraft_(Z)" title="List of aircraft (Z)">Z</a></li>
    <li><a href="/wiki/List_of_gliders" title="List of gliders">Gliders</a></li>
    <li><a href="/wiki/List_of_human-powered_aircraft" title="List of human-powered aircraft">List</a> of <a href="/wiki/Human-powered_aircraft" title="Human-powered aircraft">human-powered aircraft</a></li>
    <li><a href="/wiki/List_of_unmanned_aerial_vehicles" title="List of unmanned aerial vehicles">List</a> of <a href="/wiki/Unmanned_aerial_vehicle" title="Unmanned aerial vehicle">unmanned aerial vehicle</a></li></ul>
    </div></td></tr></tbody></table><div></div></td></tr><tr><td colspan="2" class="navbox-list navbox-odd hlist" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks mw-collapsible mw-collapsed navbox-subgroup" style="border-spacing:0"><tbody><tr><th scope="col" class="navbox-title" colspan="2"><div id="Civil_aircraft" style="font-size:114%;margin:0 4em"><a href="/wiki/List_of_civil_aircraft" title="List of civil aircraft">Civil aircraft</a></div></th></tr><tr><td colspan="2" class="navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks navbox-subgroup" style="border-spacing:0"><tbody><tr><td colspan="2" class="navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks mw-collapsible mw-collapsed navbox-subgroup" style="border-spacing:0"><tbody><tr><th scope="col" class="navbox-title" colspan="2" style="font-size:95%;"><div id="By_characteristic" style="font-size:114%;margin:0 4em">By characteristic</div></th></tr><tr><td colspan="2" class="navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks navbox-subgroup" style="border-spacing:0"><tbody><tr><th scope="row" class="navbox-group" style="width:1%">Type</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_aerobatic_aircraft" title="List of aerobatic aircraft">Aerobatic</a></li>
    <li><a href="/wiki/Bush_plane" title="Bush plane">Bush planes</a></li>
    <li><a href="/wiki/List_of_electric_aircraft" title="List of electric aircraft">Electric aircraft</a></li>
    <li><a href="/wiki/List_of_flying_wings" title="List of flying wings">Flying wings</a></li>
    <li><a href="/wiki/List_of_gliders" title="List of gliders">Gliders</a></li>
    <li><a href="/wiki/List_of_human-powered_aircraft" title="List of human-powered aircraft">Human-powered</a></li>
    <li><a href="/wiki/Prone_pilot#List_of_prone-pilot_aircraft" title="Prone pilot">Prone-pilot</a></li>
    <li><a href="/wiki/List_of_rocket_aircraft" class="mw-redirect" title="List of rocket aircraft">Rocket-powered</a></li>
    <li><a href="/wiki/List_of_flying_boats_and_floatplanes" title="List of flying boats and floatplanes">Flying boats and floatplanes</a></li>
    <li><a href="/wiki/List_of_STOL_aircraft" title="List of STOL aircraft">STOL</a></li>
    <li><a href="/wiki/List_of_supersonic_aircraft" title="List of supersonic aircraft">Supersonic</a></li>
    <li><a href="/wiki/Trimotor" title="Trimotor">Trimotors</a></li>
    <li><a href="/wiki/List_of_triplanes" title="List of triplanes">Triplanes</a></li>
    <li><a href="/wiki/List_of_unmanned_aerial_vehicles" title="List of unmanned aerial vehicles">Unmanned</a></li>
    <li><a href="/wiki/List_of_VTOL_aircraft" title="List of VTOL aircraft">VTOL</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%">Fuselage</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Double-deck_aircraft" title="Double-deck aircraft">Double-deck</a></li>
    <li><a href="/wiki/Narrow-body_aircraft" title="Narrow-body aircraft">Narrow-body</a></li>
    <li><a href="/wiki/Wide-body_aircraft" title="Wide-body aircraft">Wide-body</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%"><div class="hlist"><ul><li>Weight</li><li>Size</li></ul></div></th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_airliners_by_maximum_takeoff_weight" title="List of airliners by maximum takeoff weight">Maximum takeoff weight</a></li>
    <li><a href="/wiki/List_of_current_production_certified_light_aircraft" title="List of current production certified light aircraft">Light aircraft</a>
    <ul><li><a href="/wiki/List_of_very_light_jets" class="mw-redirect" title="List of very light jets">very light jets</a></li></ul></li>
    <li><a href="/wiki/List_of_large_aircraft" title="List of large aircraft">Large aircraft</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%">Manufacturer</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><span class="noviewer" typeof="mw:File"><span title="Template"><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/16px-Symbol_template_class_pink.svg.png" decoding="async" width="16" height="16" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/23px-Symbol_template_class_pink.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/31px-Symbol_template_class_pink.svg.png 2x" data-file-width="180" data-file-height="185" /></span></span>&#160;<a href="/wiki/Template:Airbus_Group_aircraft" class="mw-redirect" title="Template:Airbus Group aircraft">Airbus</a></li>
    <li><span class="noviewer" typeof="mw:File"><span title="Template"><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/16px-Symbol_template_class_pink.svg.png" decoding="async" width="16" height="16" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/23px-Symbol_template_class_pink.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/31px-Symbol_template_class_pink.svg.png 2x" data-file-width="180" data-file-height="185" /></span></span>&#160;<a href="/wiki/Template:Antonov_aircraft" title="Template:Antonov aircraft">Antonov</a></li>
    <li><span class="noviewer" typeof="mw:File"><span title="Template"><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/16px-Symbol_template_class_pink.svg.png" decoding="async" width="16" height="16" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/23px-Symbol_template_class_pink.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/31px-Symbol_template_class_pink.svg.png 2x" data-file-width="180" data-file-height="185" /></span></span>&#160;<a href="/wiki/Template:Boeing_airliners" title="Template:Boeing airliners">Boeing</a></li>
    <li><span class="noviewer" typeof="mw:File"><span title="Template"><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/16px-Symbol_template_class_pink.svg.png" decoding="async" width="16" height="16" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/23px-Symbol_template_class_pink.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/31px-Symbol_template_class_pink.svg.png 2x" data-file-width="180" data-file-height="185" /></span></span>&#160;<a href="/wiki/Template:Bombardier_aircraft" title="Template:Bombardier aircraft">Bombardier</a></li>
    <li><span class="noviewer" typeof="mw:File"><span title="Template"><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/16px-Symbol_template_class_pink.svg.png" decoding="async" width="16" height="16" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/23px-Symbol_template_class_pink.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/31px-Symbol_template_class_pink.svg.png 2x" data-file-width="180" data-file-height="185" /></span></span>&#160;<a href="/wiki/Template:Douglas_airliners" title="Template:Douglas airliners">Douglas&#160;/&#32;McDonnell Douglas</a></li>
    <li><span class="noviewer" typeof="mw:File"><span title="Template"><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/16px-Symbol_template_class_pink.svg.png" decoding="async" width="16" height="16" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/23px-Symbol_template_class_pink.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/31px-Symbol_template_class_pink.svg.png 2x" data-file-width="180" data-file-height="185" /></span></span>&#160;<a href="/wiki/Template:Embraer_aircraft" title="Template:Embraer aircraft">Embraer</a></li>
    <li><span class="noviewer" typeof="mw:File"><span title="Template"><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/16px-Symbol_template_class_pink.svg.png" decoding="async" width="16" height="16" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/23px-Symbol_template_class_pink.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/31px-Symbol_template_class_pink.svg.png 2x" data-file-width="180" data-file-height="185" /></span></span>&#160;<a href="/wiki/Template:Ilyushin_aircraft" title="Template:Ilyushin aircraft">Ilyushin</a></li>
    <li><span class="noviewer" typeof="mw:File"><span title="Template"><img alt="" src="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/16px-Symbol_template_class_pink.svg.png" decoding="async" width="16" height="16" class="mw-file-element" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/23px-Symbol_template_class_pink.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/8/83/Symbol_template_class_pink.svg/31px-Symbol_template_class_pink.svg.png 2x" data-file-width="180" data-file-height="185" /></span></span>&#160;<a href="/wiki/Template:Tupolev_aircraft" title="Template:Tupolev aircraft">Tupolev</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%">Engine number</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Twinjet" title="Twinjet">Twinjets</a></li>
    <li><a href="/wiki/Trijet" title="Trijet">Trijets</a></li>
    <li><a href="/wiki/Trimotor" title="Trimotor">Trimotors</a></li>
    <li><a href="/wiki/Four-engined_jet_aircraft" title="Four-engined jet aircraft">Four-engined jet aircraft</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%">Range</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_jet_airliners" class="mw-redirect" title="List of jet airliners">Jet airliners</a></li>
    <li><a href="/wiki/List_of_regional_airliners" title="List of regional airliners">Regional airliners</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%">Use</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_racing_aircraft" title="List of racing aircraft">Racers</a></li>
    <li><a href="/wiki/Regional_airliner" title="Regional airliner">Regional airliner</a>
    <ul><li><a href="/wiki/Regional_jet" title="Regional jet">regional jet</a></li></ul></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%">Research</th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Early_flying_machines" title="Early flying machines">Early flying machines</a></li>
    <li><a href="/wiki/List_of_experimental_aircraft" title="List of experimental aircraft">Experimental</a></li>
    <li><a href="/wiki/List_of_X-planes" title="List of X-planes">X-planes</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%">Rotor-powered</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_rotorcraft" title="List of rotorcraft">Rotorcraft</a>
    <ul><li><a href="/wiki/List_of_utility_helicopters" class="mw-redirect" title="List of utility helicopters">utility</a></li></ul></li>
    <li><a href="/wiki/Tiltrotor#List_of_tiltrotor_aircraft" title="Tiltrotor">Tiltrotors</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%"><div class="hlist"><ul><li>Executive</li><li>Private</li></ul></div></th><td class="navbox-list-with-group navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/Business_jet" title="Business jet">Business jets</a></li>
    <li><a href="/wiki/Light-sport_aircraft" title="Light-sport aircraft">Light-sport aircraft</a></li>
    <li><a href="/wiki/Flying_car" title="Flying car">Flying car</a></li></ul>
    </div></td></tr></tbody></table><div></div></td></tr></tbody></table><div></div></td></tr><tr><td colspan="2" class="navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks mw-collapsible expanded navbox-subgroup" style="border-spacing:0"><tbody><tr><th scope="col" class="navbox-title" colspan="2" style="font-size:95%;"><div id="Other_lists" style="font-size:114%;margin:0 4em">Other lists</div></th></tr><tr><td colspan="2" class="navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_aircraft_by_date_and_usage_category" title="List of aircraft by date and usage category">By date and usage</a></li>
    <li><a href="/wiki/List_of_aircraft_by_tail_number" title="List of aircraft by tail number">By tail number</a></li>
    <li><a href="/wiki/List_of_most-produced_aircraft" title="List of most-produced aircraft">Most-produced</a></li></ul>
    </div></td></tr></tbody></table><div></div></td></tr></tbody></table><div></div></td></tr></tbody></table><div></div></td></tr><tr><td colspan="2" class="navbox-list navbox-odd hlist" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks mw-collapsible uncollapsed navbox-subgroup" style="border-spacing:0"><tbody><tr><th scope="col" class="navbox-title" colspan="2"><div id="Military_aircraft" style="font-size:114%;margin:0 4em"><a href="/wiki/Military_aircraft" title="Military aircraft">Military aircraft</a></div></th></tr><tr><td colspan="2" class="navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks navbox-subgroup" style="border-spacing:0"><tbody><tr><th scope="row" class="navbox-group" style="width:1%">Role</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_airborne_early_warning_aircraft" title="List of airborne early warning aircraft">AEW</a></li>
    <li><a href="/wiki/List_of_attack_aircraft" title="List of attack aircraft">Attack</a></li>
    <li><a href="/wiki/List_of_bomber_aircraft" title="List of bomber aircraft">Bomber</a>
    <ul><li><a href="/wiki/List_of_torpedo_bombers" title="List of torpedo bombers">Torpedo</a></li></ul></li>
    <li><a href="/wiki/List_of_carrier-based_aircraft" title="List of carrier-based aircraft">Carrier-based</a></li>
    <li><a href="/wiki/List_of_fighter_aircraft" title="List of fighter aircraft">Fighter</a></li>
    <li><a href="/wiki/List_of_maritime_patrol_aircraft" title="List of maritime patrol aircraft">Maritime patrol</a></li>
    <li><a href="/wiki/List_of_submarine-borne_aircraft" title="List of submarine-borne aircraft">Submarine-borne</a></li>
    <li><a href="/wiki/List_of_tanker_aircraft" title="List of tanker aircraft">Tanker</a></li></ul>
    </div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%"><a href="/wiki/Lists_of_military_aircraft_by_nation" title="Lists of military aircraft by nation">Nation</a></th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em"></div><table class="nowraplinks navbox-subgroup" style="border-spacing:0"><tbody><tr><td colspan="2" class="navbox-list navbox-even" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_Afghan_Air_Force_aircraft" title="List of Afghan Air Force aircraft">Afghanistan</a></li>
    <li><a href="/wiki/List_of_Albanian_Air_Force_aircraft" title="List of Albanian Air Force aircraft">Albania</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Argentine_Air_Force" title="List of aircraft of the Argentine Air Force">Argentina</a></li>
    <li><a href="/wiki/List_of_current_Royal_Australian_Air_Force_aircraft" title="List of current Royal Australian Air Force aircraft">Australia</a></li>
    <li><a href="/wiki/List_of_active_Bangladesh_military_aircraft" title="List of active Bangladesh military aircraft">Bangladesh</a></li>
    <li><a href="/wiki/List_of_Belize_Defence_Force_Air_Wing_aircraft" class="mw-redirect" title="List of Belize Defence Force Air Wing aircraft">Belize</a></li>
    <li><a href="/wiki/List_of_active_Brazilian_military_aircraft" title="List of active Brazilian military aircraft">Brazil</a></li>
    <li><a href="/wiki/List_of_active_Bulgarian_military_aircraft" class="mw-redirect" title="List of active Bulgarian military aircraft">Bulgaria</a></li>
    <li><a href="/wiki/List_of_aircraft_of_Canada%27s_air_forces" title="List of aircraft of Canada&#39;s air forces">Canada</a></li>
    <li><a href="/wiki/List_of_active_Chile_military_aircraft" title="List of active Chile military aircraft">Chile</a></li>
    <li><a href="/wiki/List_of_active_People%27s_Liberation_Army_aircraft" title="List of active People&#39;s Liberation Army aircraft">China</a></li>
    <li><a href="/wiki/List_of_military_aircraft_of_the_Czech_Republic" title="List of military aircraft of the Czech Republic">Czech Republic</a></li>
    <li><a href="/wiki/List_of_military_aircraft_of_Denmark" title="List of military aircraft of Denmark">Denmark</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Egyptian_Air_Force" title="List of aircraft of the Egyptian Air Force">Egypt</a></li>
    <li><a href="/wiki/List_of_military_aircraft_of_Finland" title="List of military aircraft of Finland">Finland</a></li>
    <li><a href="/wiki/List_of_military_aircraft_of_France" title="List of military aircraft of France">France</a></li>
    <li><a href="/wiki/List_of_military_aircraft_of_Germany" title="List of military aircraft of Germany">Germany</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Hellenic_Air_Force" class="mw-redirect" title="List of aircraft of the Hellenic Air Force">Greece</a></li>
    <li><a class="mw-selflink selflink">India</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Indonesian_National_Armed_Forces" title="List of aircraft of the Indonesian National Armed Forces">Indonesia</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Iranian_Air_Force" title="List of aircraft of the Iranian Air Force">Iran</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Irish_Air_Corps" title="List of aircraft of the Irish Air Corps">Ireland</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Israeli_Air_Force" title="List of aircraft of the Israeli Air Force">Israel</a></li>
    <li><a href="/wiki/List_of_active_Italian_military_aircraft" title="List of active Italian military aircraft">Italy</a></li>
    <li><a href="/wiki/List_of_military_aircraft_of_Japan" title="List of military aircraft of Japan">Japan</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Malaysian_Armed_Forces" title="List of aircraft of the Malaysian Armed Forces">Malaysia</a></li>
    <li><a href="/wiki/List_of_active_Moroccan_military_aircraft" class="mw-redirect" title="List of active Moroccan military aircraft">Morocco</a></li>
    <li><a href="/wiki/List_of_active_New_Zealand_military_aircraft" class="mw-redirect" title="List of active New Zealand military aircraft">New Zealand</a></li>
    <li><a href="/wiki/List_of_military_aircraft_of_Norway" title="List of military aircraft of Norway">Norway</a></li>
    <li><a href="/wiki/List_of_active_Pakistan_military_aircraft" title="List of active Pakistan military aircraft">Pakistan</a></li>
    <li><a href="/wiki/List_of_active_military_aircraft_of_the_Philippines" title="List of active military aircraft of the Philippines">Philippines</a></li>
    <li><a href="/wiki/List_of_retired_Polish_Air_Force_aircraft" title="List of retired Polish Air Force aircraft">Poland</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Portuguese_Air_Force" class="mw-redirect" title="List of aircraft of the Portuguese Air Force">Portugal</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Romanian_Air_Force" title="List of aircraft of the Romanian Air Force">Romania</a></li>
    <li><a href="/wiki/List_of_currently_active_Russian_military_aircraft" class="mw-redirect" title="List of currently active Russian military aircraft">Russia</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_South_African_Air_Force" title="List of aircraft of the South African Air Force">South Africa</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Spanish_Air_and_Space_Force" class="mw-redirect" title="List of aircraft of the Spanish Air and Space Force">Spain</a></li>
    <li><a href="/wiki/List_of_military_aircraft_of_Sri_Lanka" title="List of military aircraft of Sri Lanka">Sri Lanka</a></li>
    <li><a href="/wiki/List_of_military_aircraft_of_Sweden" title="List of military aircraft of Sweden">Sweden</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Swiss_Air_Force" title="List of aircraft of the Swiss Air Force">Switzerland</a></li>
    <li><a href="/wiki/List_of_aircraft_of_the_Royal_Thai_Air_Force" title="List of aircraft of the Royal Thai Air Force">Thailand</a></li>
    <li><a href="/wiki/List_of_active_Turkish_Air_Force_aircraft" title="List of active Turkish Air Force aircraft">Turkey</a></li>
    <li><a href="/wiki/List_of_active_United_Kingdom_military_aircraft" title="List of active United Kingdom military aircraft">United Kingdom</a></li>
    <li><a href="/wiki/List_of_active_United_States_military_aircraft" title="List of active United States military aircraft">United States</a></li></ul>
    </div></td></tr></tbody></table><div></div></td></tr><tr><th scope="row" class="navbox-group" style="width:1%">Era</th><td class="navbox-list-with-group navbox-list navbox-odd" style="width:100%;padding:0"><div style="padding:0 0.25em">
    <ul><li><a href="/wiki/List_of_World_War_I_Entente_aircraft" title="List of World War I Entente aircraft">WWI Entente</a></li>
    <li><a href="/wiki/List_of_World_War_I_Central_Powers_aircraft" title="List of World War I Central Powers aircraft">WWI Central Powers</a></li>
    <li><a href="/wiki/List_of_interwar_military_aircraft" title="List of interwar military aircraft">Interwar</a></li>
    <li><a href="/wiki/List_of_aircraft_of_World_War_II" title="List of aircraft of World War II">World War II</a></li>
    <li><a href="/wiki/List_of_jet_aircraft_of_World_War_II" title="List of jet aircraft of World War II">World War II jets</a></li></ul>
    </div></td></tr></tbody></table><div></div></td></tr></tbody></table><div></div></td></tr></tbody></table></div>
    <!-- 
    NewPP limit report
    Parsed by mw‐web.codfw.main‐6dfc4fc9cc‐cvgc2
    Cached time: 20241010160229
    Cache expiry: 2592000
    Reduced expiry: false
    Complications: [vary‐revision‐sha1, show‐toc]
    CPU time usage: 0.864 seconds
    Real time usage: 1.113 seconds
    Preprocessor visited node count: 4903/1000000
    Post‐expand include size: 283991/2097152 bytes
    Template argument size: 894/2097152 bytes
    Highest expansion depth: 12/100
    Expensive parser function count: 10/500
    Unstrip recursion depth: 1/20
    Unstrip post‐expand size: 324093/5000000 bytes
    Lua time usage: 0.503/10.000 seconds
    Lua memory usage: 5999431/52428800 bytes
    Number of Wikibase entities loaded: 0/400
    -->
    <!--
    Transclusion expansion time report (%,ms,calls,template)
    100.00%  888.096      1 -total
     50.41%  447.732      1 Template:Reflist
     21.35%  189.599     58 Template:Cite_web
     13.80%  122.599      3 Template:Cite_book
     13.37%  118.754      1 Template:Military_of_India
     12.52%  111.209      1 Template:Pp
      7.82%   69.470     22 Template:Cite_news
      6.78%   60.230      1 Template:Short_description
      6.36%   56.483      2 Template:Navbox_with_collapsible_groups
      4.55%   40.412      1 Template:Lists_of_aircraft
    -->
    
    <!-- Saved in parser cache with key enwiki:pcache:idhash:2192619-0!canonical and timestamp 20241010160229 and revision id 1250455700. Rendering was triggered because: page-view
     -->
    </div><!--esi <esi:include src="/esitest-fa8a495983347898/content" /> --><noscript><img src="https://login.wikimedia.org/wiki/Special:CentralAutoLogin/start?type=1x1" alt="" width="1" height="1" style="border: none; position: absolute;"></noscript>
    <div class="printfooter" data-nosnippet="">Retrieved from "<a dir="ltr" href="https://en.wikipedia.org/w/index.php?title=List_of_active_Indian_military_aircraft&amp;oldid=1250455700">https://en.wikipedia.org/w/index.php?title=List_of_active_Indian_military_aircraft&amp;oldid=1250455700</a>"</div></div>
    					<div id="catlinks" class="catlinks" data-mw="interface"><div id="mw-normal-catlinks" class="mw-normal-catlinks"><a href="/wiki/Help:Category" title="Help:Category">Categories</a>: <ul><li><a href="/wiki/Category:Indian_Air_Force" title="Category:Indian Air Force">Indian Air Force</a></li><li><a href="/wiki/Category:Indian_military_aircraft" title="Category:Indian military aircraft">Indian military aircraft</a></li><li><a href="/wiki/Category:Lists_of_military_aircraft" title="Category:Lists of military aircraft">Lists of military aircraft</a></li><li><a href="/wiki/Category:Indian_military-related_lists" title="Category:Indian military-related lists">Indian military-related lists</a></li><li><a href="/wiki/Category:India_aviation-related_lists" title="Category:India aviation-related lists">India aviation-related lists</a></li></ul></div><div id="mw-hidden-catlinks" class="mw-hidden-catlinks mw-hidden-cats-hidden">Hidden categories: <ul><li><a href="/wiki/Category:Wikipedia_semi-protected_pages" title="Category:Wikipedia semi-protected pages">Wikipedia semi-protected pages</a></li><li><a href="/wiki/Category:Articles_with_short_description" title="Category:Articles with short description">Articles with short description</a></li><li><a href="/wiki/Category:Short_description_is_different_from_Wikidata" title="Category:Short description is different from Wikidata">Short description is different from Wikidata</a></li><li><a href="/wiki/Category:Use_dmy_dates_from_October_2019" title="Category:Use dmy dates from October 2019">Use dmy dates from October 2019</a></li></ul></div></div>
    				</div>
    			</main>
    			
    		</div>
    		<div class="mw-footer-container">
    			
    <footer id="footer" class="mw-footer" >
    	<ul id="footer-info">
    	<li id="footer-info-lastmod"> This page was last edited on 10 October 2024, at 14:30<span class="anonymous-show">&#160;(UTC)</span>.</li>
    	<li id="footer-info-copyright">Text is available under the <a rel="license" href="//en.wikipedia.org/wiki/Wikipedia:Text_of_the_Creative_Commons_Attribution-ShareAlike_4.0_International_License">Creative Commons Attribution-ShareAlike License 4.0</a><a rel="license" href="//en.wikipedia.org/wiki/Wikipedia:Text_of_the_Creative_Commons_Attribution-ShareAlike_4.0_International_License" style="display:none;"></a>;
    additional terms may apply. By using this site, you agree to the <a href="//foundation.wikimedia.org/wiki/Special:MyLanguage/Policy:Terms_of_Use">Terms of Use</a> and <a href="//foundation.wikimedia.org/wiki/Special:MyLanguage/Policy:Privacy_policy">Privacy Policy</a>. Wikipedia® is a registered trademark of the <a href="//wikimediafoundation.org/">Wikimedia Foundation, Inc.</a>, a non-profit organization.</li>
    </ul>
    
    	<ul id="footer-places">
    	<li id="footer-places-privacy"><a href="https://foundation.wikimedia.org/wiki/Special:MyLanguage/Policy:Privacy_policy">Privacy policy</a></li>
    	<li id="footer-places-about"><a href="/wiki/Wikipedia:About">About Wikipedia</a></li>
    	<li id="footer-places-disclaimers"><a href="/wiki/Wikipedia:General_disclaimer">Disclaimers</a></li>
    	<li id="footer-places-contact"><a href="//en.wikipedia.org/wiki/Wikipedia:Contact_us">Contact Wikipedia</a></li>
    	<li id="footer-places-wm-codeofconduct"><a href="https://foundation.wikimedia.org/wiki/Special:MyLanguage/Policy:Universal_Code_of_Conduct">Code of Conduct</a></li>
    	<li id="footer-places-developers"><a href="https://developer.wikimedia.org">Developers</a></li>
    	<li id="footer-places-statslink"><a href="https://stats.wikimedia.org/#/en.wikipedia.org">Statistics</a></li>
    	<li id="footer-places-cookiestatement"><a href="https://foundation.wikimedia.org/wiki/Special:MyLanguage/Policy:Cookie_statement">Cookie statement</a></li>
    	<li id="footer-places-mobileview"><a href="//en.m.wikipedia.org/w/index.php?title=List_of_active_Indian_military_aircraft&amp;mobileaction=toggle_view_mobile" class="noprint stopMobileRedirectToggle">Mobile view</a></li>
    </ul>
    
    	<ul id="footer-icons" class="noprint">
    	<li id="footer-copyrightico"><a href="https://wikimediafoundation.org/" class="cdx-button cdx-button--fake-button cdx-button--size-large cdx-button--fake-button--enabled"><img src="/static/images/footer/wikimedia-button.svg" width="84" height="29" alt="Wikimedia Foundation" loading="lazy"></a></li>
    	<li id="footer-poweredbyico"><a href="https://www.mediawiki.org/" class="cdx-button cdx-button--fake-button cdx-button--size-large cdx-button--fake-button--enabled"><img src="/w/resources/assets/poweredby_mediawiki.svg" alt="Powered by MediaWiki" width="88" height="31" loading="lazy"></a></li>
    </ul>
    
    </footer>
    
    		</div>
    	</div> 
    </div> 
    <div class="vector-settings" id="p-dock-bottom">
    	<ul></ul>
    </div><script>(RLQ=window.RLQ||[]).push(function(){mw.config.set({"wgHostname":"mw-web.codfw.main-6dfc4fc9cc-cvgc2","wgBackendResponseTime":1256,"wgPageParseReport":{"limitreport":{"cputime":"0.864","walltime":"1.113","ppvisitednodes":{"value":4903,"limit":1000000},"postexpandincludesize":{"value":283991,"limit":2097152},"templateargumentsize":{"value":894,"limit":2097152},"expansiondepth":{"value":12,"limit":100},"expensivefunctioncount":{"value":10,"limit":500},"unstrip-depth":{"value":1,"limit":20},"unstrip-size":{"value":324093,"limit":5000000},"entityaccesscount":{"value":0,"limit":400},"timingprofile":["100.00%  888.096      1 -total"," 50.41%  447.732      1 Template:Reflist"," 21.35%  189.599     58 Template:Cite_web"," 13.80%  122.599      3 Template:Cite_book"," 13.37%  118.754      1 Template:Military_of_India"," 12.52%  111.209      1 Template:Pp","  7.82%   69.470     22 Template:Cite_news","  6.78%   60.230      1 Template:Short_description","  6.36%   56.483      2 Template:Navbox_with_collapsible_groups","  4.55%   40.412      1 Template:Lists_of_aircraft"]},"scribunto":{"limitreport-timeusage":{"value":"0.503","limit":"10.000"},"limitreport-memusage":{"value":5999431,"limit":52428800}},"cachereport":{"origin":"mw-web.codfw.main-6dfc4fc9cc-cvgc2","timestamp":"20241010160229","ttl":2592000,"transientcontent":false}}});});</script>
    <script type="application/ld+json">{"@context":"https:\/\/schema.org","@type":"Article","name":"List of active Indian military aircraft","url":"https:\/\/en.wikipedia.org\/wiki\/List_of_active_Indian_military_aircraft","sameAs":"http:\/\/www.wikidata.org\/entity\/Q6604953","mainEntity":"http:\/\/www.wikidata.org\/entity\/Q6604953","author":{"@type":"Organization","name":"Contributors to Wikimedia projects"},"publisher":{"@type":"Organization","name":"Wikimedia Foundation, Inc.","logo":{"@type":"ImageObject","url":"https:\/\/www.wikimedia.org\/static\/images\/wmf-hor-googpub.png"}},"datePublished":"2005-07-08T09:02:01Z","dateModified":"2024-10-10T14:30:41Z","headline":"Wikimedia list article"}</script>
    </body>
    </html>
    


```python
soup = beautifulsoup(url.text,"html.parser")
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    Cell In[13], line 1
    ----> 1 soup = beautifulsoup(url.text,"html.parser")
    

    NameError: name 'beautifulsoup' is not defined



```python
soup=beautifulsoup(url.text,"html.parser")
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    Cell In[15], line 1
    ----> 1 soup=beautifulsoup(url.text,"html.parser")
    

    NameError: name 'beautifulsoup' is not defined



```python
soup=BeautifulSoup(url.text,"html.parser")
```


```python
table=soup.find('table',{class : wikitable})

```


      Cell In[19], line 1
        table=soup.find('table',{class : wikitable})
                                 ^
    SyntaxError: invalid syntax
    



```python
table=soup.find('table',{Class = wikitable})

```


      Cell In[23], line 1
        table=soup.find('table',{Class = wikitable})
                                 ^
    SyntaxError: invalid syntax. Maybe you meant '==' or ':=' instead of '='?
    



```python
table=soup.find('table',{class := wikitable})

```


      Cell In[25], line 1
        table=soup.find('table',{class := wikitable})
                                 ^
    SyntaxError: invalid syntax
    



```python
table=soup.find('table',{'class' : 'wikitable'})

```


```python
table

```




    <table class="wikitable">
    <tbody><tr>
    <th style="text-align:center; background:#acc;">Aircraft
    </th>
    <th style="text-align: center; background:#acc;">Origin
    </th>
    <th style="text-align: center; background:#acc;">Type
    </th>
    <th style="text-align:left; background:#acc;">Variant
    </th>
    <th style="text-align:center; background:#acc;">In service
    </th>
    <th style="text-align: center; background:#acc;">Notes
    </th></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Military_aircraft#Combat_aircraft" title="Military aircraft">Combat Aircraft</a>
    </th></tr>
    <tr>
    <td rowspan="2"><a href="/wiki/Dassault_Rafale" title="Dassault Rafale">Dassault Rafale</a>
    </td>
    <td rowspan="2"><a href="/wiki/France" title="France">France</a>
    </td>
    <td rowspan="2"><a href="/wiki/Multirole_combat_aircraft" title="Multirole combat aircraft">Multirole</a>
    </td>
    <td><a href="/wiki/Dassault_Rafale#Variants" title="Dassault Rafale">DH</a>
    </td>
    <td>8<sup class="reference" id="cite_ref-:1_1-0"><a href="#cite_note-:1-1"><span class="cite-bracket">[</span>1<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Dassault_Rafale#Variants" title="Dassault Rafale">EH</a>
    </td>
    <td>28<sup class="reference" id="cite_ref-:1_1-1"><a href="#cite_note-:1-1"><span class="cite-bracket">[</span>1<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td rowspan="3"><a href="/wiki/HAL_Tejas" title="HAL Tejas">HAL Tejas</a>
    </td>
    <td rowspan="3"><a href="/wiki/India" title="India">India</a>
    </td>
    <td><a href="/wiki/Multirole_combat_aircraft" title="Multirole combat aircraft">Multirole</a>
    </td>
    <td><a href="/wiki/HAL_Tejas#Variants" title="HAL Tejas">Mk.1</a>
    </td>
    <td>31<sup class="reference" id="cite_ref-2"><a href="#cite_note-2"><span class="cite-bracket">[</span>2<span class="cite-bracket">]</span></a></sup><sup class="reference" id="cite_ref-3"><a href="#cite_note-3"><span class="cite-bracket">[</span>3<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Trainer_aircraft#Operational_conversion" title="Trainer aircraft">Conversion trainer</a>
    </td>
    <td><a href="/wiki/HAL_Tejas#Variants" title="HAL Tejas">Mk.1 Trainer</a>
    </td>
    <td>2<sup class="reference" id="cite_ref-4"><a href="#cite_note-4"><span class="cite-bracket">[</span>4<span class="cite-bracket">]</span></a></sup><sup class="reference" id="cite_ref-5"><a href="#cite_note-5"><span class="cite-bracket">[</span>5<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>Used for training; 16 more on order<sup class="reference" id="cite_ref-:11_6-0"><a href="#cite_note-:11-6"><span class="cite-bracket">[</span>6<span class="cite-bracket">]</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Multirole_combat_aircraft" title="Multirole combat aircraft">Multirole</a>
    </td>
    <td><a href="/wiki/HAL_Tejas#Variants" title="HAL Tejas">Mk.1A</a>
    </td>
    <td>
    </td>
    <td>73 on order, 97 more approved<sup class="reference" id="cite_ref-:11_6-1"><a href="#cite_note-:11-6"><span class="cite-bracket">[</span>6<span class="cite-bracket">]</span></a></sup><sup class="reference" id="cite_ref-7"><a href="#cite_note-7"><span class="cite-bracket">[</span>7<span class="cite-bracket">]</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Sukhoi_Su-30MKI" title="Sukhoi Su-30MKI">Sukhoi Su-30MKI</a>
    </td>
    <td><a href="/wiki/Russia" title="Russia">Russia</a>
    </td>
    <td><a href="/wiki/Multirole_combat_aircraft" title="Multirole combat aircraft">Multirole</a>
    </td>
    <td><a href="/wiki/Sukhoi_Su-30#Su-30MKI_and_derivatives" title="Sukhoi Su-30">Su-30MKI Flanker H</a>
    </td>
    <td>259<sup class="reference" id="cite_ref-8"><a href="#cite_note-8"><span class="cite-bracket">[</span>8<span class="cite-bracket">]</span></a></sup><sup class="reference" id="cite_ref-9"><a href="#cite_note-9"><span class="cite-bracket">[</span>9<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>12 more cleared.<sup class="reference" id="cite_ref-10"><a href="#cite_note-10"><span class="cite-bracket">[</span>10<span class="cite-bracket">]</span></a></sup>
    </td></tr>
    <tr>
    <td rowspan="2"><a href="/wiki/Mikoyan_MiG-29" title="Mikoyan MiG-29">Mikoyan MiG-29</a>
    </td>
    <td rowspan="2"><a href="/wiki/Soviet_Union" title="Soviet Union">Soviet Union</a>
    </td>
    <td rowspan="2"><a href="/wiki/Multirole_combat_aircraft" title="Multirole combat aircraft">Multirole</a>
    </td>
    <td><a href="/wiki/Mikoyan_MiG-29#Variants" title="Mikoyan MiG-29">Fulcrum</a>
    </td>
    <td>53<sup class="reference" id="cite_ref-:1_1-2"><a href="#cite_note-:1-1"><span class="cite-bracket">[</span>1<span class="cite-bracket">]</span></a></sup><sup class="reference" id="cite_ref-11"><a href="#cite_note-11"><span class="cite-bracket">[</span>11<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>Including 12 <a href="/wiki/Mikoyan_MiG-29#Variants" title="Mikoyan MiG-29">MiG-29UPG</a>.
    </td></tr>
    <tr>
    <td><a href="/wiki/Mikoyan_MiG-29#Variants" title="Mikoyan MiG-29">Fulcrum B</a>
    </td>
    <td>7<sup class="reference" id="cite_ref-:1_1-3"><a href="#cite_note-:1-1"><span class="cite-bracket">[</span>1<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td rowspan="2"><a href="/wiki/Dassault_Mirage_2000" title="Dassault Mirage 2000">Dassault Mirage 2000</a>
    </td>
    <td rowspan="2"><a href="/wiki/France" title="France">France</a>
    </td>
    <td rowspan="2"><a href="/wiki/Multirole_combat_aircraft" title="Multirole combat aircraft">Multirole</a>
    </td>
    <td><a href="/wiki/Dassault_Mirage_2000#Variants" title="Dassault Mirage 2000">-2000H</a>
    </td>
    <td>37<sup class="reference" id="cite_ref-:1_1-4"><a href="#cite_note-:1-1"><span class="cite-bracket">[</span>1<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Dassault_Mirage_2000#Variants" title="Dassault Mirage 2000">-2000TH</a>
    </td>
    <td>10<sup class="reference" id="cite_ref-:1_1-5"><a href="#cite_note-:1-1"><span class="cite-bracket">[</span>1<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>Used for training.
    </td></tr>
    <tr>
    <td rowspan="3"><a href="/wiki/SEPECAT_Jaguar" title="SEPECAT Jaguar">SEPECAT Jaguar</a>
    </td>
    <td rowspan="3"><a href="/wiki/United_Kingdom" title="United Kingdom">United Kingdom</a>
    </td>
    <td rowspan="3"><a href="/wiki/Attack_aircraft" title="Attack aircraft">Attack</a>
    </td>
    <td><a href="/wiki/SEPECAT_Jaguar#Variants" title="SEPECAT Jaguar">IB</a>
    </td>
    <td>28<sup class="reference" id="cite_ref-:1_1-6"><a href="#cite_note-:1-1"><span class="cite-bracket">[</span>1<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>Used for training.
    </td></tr>
    <tr>
    <td><a href="/wiki/SEPECAT_Jaguar#Variants" title="SEPECAT Jaguar">IS</a>
    </td>
    <td>79<sup class="reference" id="cite_ref-:1_1-7"><a href="#cite_note-:1-1"><span class="cite-bracket">[</span>1<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/SEPECAT_Jaguar#Variants" title="SEPECAT Jaguar">IM</a>
    </td>
    <td>8<sup class="reference" id="cite_ref-:1_1-8"><a href="#cite_note-:1-1"><span class="cite-bracket">[</span>1<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>Maritime strike aircraft carrying <a href="/wiki/Sea_Eagle_(missile)" title="Sea Eagle (missile)">Sea Eagle</a> missile.
    </td></tr>
    <tr>
    <td><a href="/wiki/Mikoyan-Gurevich_MiG-21" title="Mikoyan-Gurevich MiG-21">Mikoyan-Gurevich MiG-21</a>
    </td>
    <td><a href="/wiki/Soviet_Union" title="Soviet Union">Soviet Union</a>
    </td>
    <td><a href="/wiki/Interceptor_aircraft" title="Interceptor aircraft">Interceptor</a>
    </td>
    <td><a href="/wiki/List_of_Mikoyan-Gurevich_MiG-21_variants" title="List of Mikoyan-Gurevich MiG-21 variants">MiG-21 <i>Bison</i></a>
    </td>
    <td>40<sup class="reference" id="cite_ref-12"><a href="#cite_note-12"><span class="cite-bracket">[</span>12<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>Being phased out.<sup class="reference" id="cite_ref-13"><a href="#cite_note-13"><span class="cite-bracket">[</span>13<span class="cite-bracket">]</span></a></sup>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Airborne_early_warning_and_control" title="Airborne early warning and control">AEW&amp;CS</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Embraer_R-99" title="Embraer R-99">Embraer R-99</a>
    </td>
    <td><a href="/wiki/Brazil" title="Brazil">Brazil</a>
    </td>
    <td><a href="/wiki/Airborne_early_warning_and_control" title="Airborne early warning and control">AEW&amp;C</a>
    </td>
    <td><a href="/wiki/DRDO_AEW%26CS#Platforms" title="DRDO AEW&amp;CS">Netra Mk1</a>
    </td>
    <td>3<sup class="reference" id="cite_ref-:12_14-0"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>equipped with a <a href="/wiki/DRDO_AEW%26CS" title="DRDO AEW&amp;CS"> Netra AEW&amp;CS</a>.
    </td></tr>
    <tr>
    <td><a href="/wiki/Beriev_A-50" title="Beriev A-50">Beriev A-50</a>
    </td>
    <td>Soviet Union
    </td>
    <td>AEW&amp;C
    </td>
    <td><a href="/wiki/Beriev_A-50#Variants" title="Beriev A-50">A-50EI</a>
    </td>
    <td>3<sup class="reference" id="cite_ref-:12_14-1"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>equipped with the <a href="/wiki/EL/W-2090" title="EL/W-2090">EL/W-2090</a> radar. 2 more planned.<sup class="reference" id="cite_ref-15"><a href="#cite_note-15"><span class="cite-bracket">[</span>15<span class="cite-bracket">]</span></a></sup><sup class="reference" id="cite_ref-16"><a href="#cite_note-16"><span class="cite-bracket">[</span>16<span class="cite-bracket">]</span></a></sup>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Reconnaissance_aircraft" title="Reconnaissance aircraft">Reconnaissance</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Boeing_707" title="Boeing 707">Boeing 707</a>
    </td>
    <td><a href="/wiki/United_States" title="United States">United States</a>
    </td>
    <td><a href="/wiki/Signals_intelligence" title="Signals intelligence">SIGINT</a> / <a class="mw-redirect" href="/wiki/ELINT" title="ELINT">ELINT</a>
    </td>
    <td>707-337C Phalcon
    </td>
    <td>1<sup class="reference" id="cite_ref-:12_14-2"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td>
    <td rowspan="4">Operated by <a href="/wiki/Aviation_Research_Centre" title="Aviation Research Centre">Aviation Research Centre</a> (ARC) of <a href="/wiki/Research_and_Analysis_Wing" title="Research and Analysis Wing">R&amp;AW</a>.<sup class="reference" id="cite_ref-17"><a href="#cite_note-17"><span class="cite-bracket">[</span>17<span class="cite-bracket">]</span></a></sup><sup class="reference" id="cite_ref-18"><a href="#cite_note-18"><span class="cite-bracket">[</span>18<span class="cite-bracket">]</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Bombardier_Global_Express" title="Bombardier Global Express">Global 5000</a>
    </td>
    <td>United States
    </td>
    <td><a href="/wiki/Signals_intelligence" title="Signals intelligence">SIGINT</a> / <a class="mw-redirect" href="/wiki/ELINT" title="ELINT">ELINT</a>
    </td>
    <td>
    </td>
    <td>2<sup class="reference" id="cite_ref-:12_14-3"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Gulfstream_III" title="Gulfstream III">Gulfstream III</a>
    </td>
    <td>United States
    </td>
    <td><a href="/wiki/Signals_intelligence#Electronic_signals_intelligence" title="Signals intelligence">ELINT</a>
    </td>
    <td><a href="/wiki/Gulfstream_III#Variants" title="Gulfstream III">SRA</a><sup class="reference" id="cite_ref-19"><a href="#cite_note-19"><span class="cite-bracket">[</span>19<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>3<sup class="reference" id="cite_ref-:12_14-4"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Gulfstream_G100" title="Gulfstream G100">Gulfstream G100</a>
    </td>
    <td><a href="/wiki/Israel" title="Israel">Israel</a>
    </td>
    <td><a href="/wiki/Surveillance_aircraft" title="Surveillance aircraft">surveillance</a>
    </td>
    <td><a href="/wiki/Gulfstream_G100#Variants" title="Gulfstream G100">1125 Astra</a>
    </td>
    <td>2<sup class="reference" id="cite_ref-:12_14-5"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Aerial_refueling" title="Aerial refueling">Tanker</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Ilyushin_Il-78" title="Ilyushin Il-78">Ilyushin Il-78</a>
    </td>
    <td>Soviet Union
    </td>
    <td>aerial refuelling
    </td>
    <td><a href="/wiki/Ilyushin_Il-78#Variants" title="Ilyushin Il-78">Il-78MKI</a>
    </td>
    <td>6<sup class="reference" id="cite_ref-:12_14-6"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Military_transport_aircraft" title="Military transport aircraft">Transport</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Boeing_777" title="Boeing 777">Boeing 777</a>
    </td>
    <td>United States
    </td>
    <td>VIP transport
    </td>
    <td><a class="mw-redirect" href="/wiki/777-300ER" title="777-300ER">777-300ER</a>
    </td>
    <td>2<sup class="reference" id="cite_ref-20"><a href="#cite_note-20"><span class="cite-bracket">[</span>20<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>Used as <a href="/wiki/Air_India_One" title="Air India One">Air India One</a> for presidential flight
    </td></tr>
    <tr>
    <td><a href="/wiki/Boeing_737" title="Boeing 737">Boeing 737</a>
    </td>
    <td>United States
    </td>
    <td><a href="/wiki/Air_transports_of_heads_of_state_and_government" title="Air transports of heads of state and government">VIP transport</a>
    </td>
    <td><a href="/wiki/Boeing_737#Boeing_Business_Jet_(BBJ)" title="Boeing 737">737-700</a>
    </td>
    <td>3<sup class="reference" id="cite_ref-21"><a href="#cite_note-21"><span class="cite-bracket">[</span>21<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Embraer_Legacy_600" title="Embraer Legacy 600">Embraer Legacy 600</a>
    </td>
    <td>Brazil
    </td>
    <td><a href="/wiki/Air_transports_of_heads_of_state_and_government" title="Air transports of heads of state and government">VIP transport</a>
    </td>
    <td>
    </td>
    <td>4<sup class="reference" id="cite_ref-22"><a href="#cite_note-22"><span class="cite-bracket">[</span>22<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Boeing_C-17_Globemaster_III" title="Boeing C-17 Globemaster III">Boeing C-17</a>
    </td>
    <td>United States
    </td>
    <td><a class="mw-redirect" href="/wiki/Strategic_airlifter" title="Strategic airlifter">strategic airlifter</a>
    </td>
    <td>
    </td>
    <td>11<sup class="reference" id="cite_ref-:12_14-7"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Ilyushin_Il-76" title="Ilyushin Il-76">Ilyushin Il-76</a>
    </td>
    <td>Soviet Union
    </td>
    <td>strategic airlifter
    </td>
    <td><a href="/wiki/Ilyushin_Il-76#Military_variants" title="Ilyushin Il-76">Il-76MD</a>
    </td>
    <td>17<sup class="reference" id="cite_ref-:12_14-8"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Lockheed_Martin_C-130J_Super_Hercules" title="Lockheed Martin C-130J Super Hercules">C-130J Super Hercules</a>
    </td>
    <td>United States
    </td>
    <td><a href="/wiki/Airlift#Tactical_airlift" title="Airlift">tactical airlifter</a>
    </td>
    <td><a class="mw-redirect" href="/wiki/C-130J#Variants" title="C-130J">C-130J-30</a><sup class="reference" id="cite_ref-23"><a href="#cite_note-23"><span class="cite-bracket">[</span>23<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>12<sup class="reference" id="cite_ref-:12_14-9"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Airbus_A321" title="Airbus A321">Airbus A321</a>
    </td>
    <td><a href="/wiki/Europe" title="Europe">Europe</a>
    </td>
    <td>transport
    </td>
    <td><a class="mw-redirect" href="/wiki/A321-200" title="A321-200">A321-200</a>
    </td>
    <td>4<sup class="reference" id="cite_ref-:12_14-10"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Antonov_An-32" title="Antonov An-32">Antonov An-32</a>
    </td>
    <td>Soviet Union
    </td>
    <td><a href="/wiki/Airlift#Tactical_airlift" title="Airlift">tactical airlifter</a>
    </td>
    <td>
    </td>
    <td>103<sup class="reference" id="cite_ref-:12_14-11"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>53 are the <a href="/wiki/Antonov_An-32#Variants" title="Antonov An-32">32RE</a> variant<sup class="reference" id="cite_ref-fg-27nov15_24-0"><a href="#cite_note-fg-27nov15-24"><span class="cite-bracket">[</span>24<span class="cite-bracket">]</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/EADS_CASA_C-295" title="EADS CASA C-295">EADS CASA C-295</a>
    </td>
    <td><a href="/wiki/Spain" title="Spain">Spain</a>
    </td>
    <td><a href="/wiki/Airlift#Tactical_airlift" title="Airlift">tactical airlifter</a>
    </td>
    <td><a href="/wiki/EADS_CASA_C-295#Variants" title="EADS CASA C-295">C-295MW</a>
    </td>
    <td>5<sup class="reference" id="cite_ref-25"><a href="#cite_note-25"><span class="cite-bracket">[</span>25<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>51 more on order - <a href="/wiki/Hawker_Siddeley_HS_748" title="Hawker Siddeley HS 748">HS 748</a> replacement<sup class="reference" id="cite_ref-26"><a href="#cite_note-26"><span class="cite-bracket">[</span>26<span class="cite-bracket">]</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Hawker_Siddeley_HS_748" title="Hawker Siddeley HS 748">Hawker Siddeley HS 748</a>
    </td>
    <td>United Kingdom
    </td>
    <td><a href="/wiki/Airlift#Tactical_airlift" title="Airlift">tactical airlifter</a>
    </td>
    <td>
    </td>
    <td>57<sup class="reference" id="cite_ref-:12_14-12"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>To be replaced by <a href="/wiki/EADS_CASA_C-295" title="EADS CASA C-295">EADS CASA C-295</a>
    </td></tr>
    <tr>
    <td><a href="/wiki/Dornier_228" title="Dornier 228">Dornier Do 228</a>
    </td>
    <td><a href="/wiki/Germany" title="Germany">Germany</a>
    </td>
    <td><a href="/wiki/Airlift#Tactical_airlift" title="Airlift">tactical airlifter</a>
    </td>
    <td>228-201
    </td>
    <td>58<sup class="reference" id="cite_ref-:12_14-13"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>license built by <a href="/wiki/Hindustan_Aeronautics_Limited" title="Hindustan Aeronautics Limited">HAL</a><sup class="reference" id="cite_ref-jawa-04_27-0"><a href="#cite_note-jawa-04-27"><span class="cite-bracket">[</span>27<span class="cite-bracket">]</span></a></sup>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a class="mw-redirect" href="/wiki/Helicopters" title="Helicopters">Helicopters</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/Boeing_AH-64_Apache" title="Boeing AH-64 Apache">Boeing AH-64</a>
    </td>
    <td><a href="/wiki/United_States" title="United States">United States</a>
    </td>
    <td>attack
    </td>
    <td><a href="/wiki/Boeing_AH-64_Apache#AH-64E" title="Boeing AH-64 Apache">AH-64E</a>
    </td>
    <td>22<sup class="reference" id="cite_ref-:12_14-14"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Mil_Mi-24" title="Mil Mi-24">Mil Mi-24</a>
    </td>
    <td>Russia
    </td>
    <td><a href="/wiki/Attack_helicopter" title="Attack helicopter">attack</a>
    </td>
    <td><a href="/wiki/List_of_Mil_Mi-24_variants" title="List of Mil Mi-24 variants">Mi-24/25/35</a>
    </td>
    <td>15<sup class="reference" id="cite_ref-:12_14-15"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a class="mw-redirect" href="/wiki/HAL_Light_Combat_Helicopter" title="HAL Light Combat Helicopter">HAL Prachand</a>
    </td>
    <td>India
    </td>
    <td>attack
    </td>
    <td>
    </td>
    <td>10<sup class="reference" id="cite_ref-:2_28-0"><a href="#cite_note-:2-28"><span class="cite-bracket">[</span>28<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>66 on order<sup class="reference" id="cite_ref-:3_29-0"><a href="#cite_note-:3-29"><span class="cite-bracket">[</span>29<span class="cite-bracket">]</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Rudra" title="HAL Rudra">HAL Rudra</a>
    </td>
    <td>India
    </td>
    <td>attack
    </td>
    <td>
    </td>
    <td>16
    </td>
    <td>50 on order.<sup class="reference" id="cite_ref-30"><a href="#cite_note-30"><span class="cite-bracket">[</span>30<span class="cite-bracket">]</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Boeing_CH-47_Chinook" title="Boeing CH-47 Chinook">CH-47 Chinook</a>
    </td>
    <td>United States
    </td>
    <td>transport
    </td>
    <td><a href="/wiki/Boeing_CH-47_Chinook#CH-47F" title="Boeing CH-47 Chinook">CH-47F</a>
    </td>
    <td>15<sup class="reference" id="cite_ref-:12_14-16"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Mil_Mi-17" title="Mil Mi-17">Mil Mi-17</a>
    </td>
    <td>Russia
    </td>
    <td>utility
    </td>
    <td><a href="/wiki/Mil_Mi-17#Variants" title="Mil Mi-17">Mi-17V-5</a>
    </td>
    <td>222<sup class="reference" id="cite_ref-:12_14-17"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Dhruv" title="HAL Dhruv">HAL Dhruv</a>
    </td>
    <td>India
    </td>
    <td><a href="/wiki/Utility_helicopter" title="Utility helicopter">utility</a>
    </td>
    <td>
    </td>
    <td>95<sup class="reference" id="cite_ref-:12_14-18"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_Light_Utility_Helicopter" title="HAL Light Utility Helicopter">HAL LUH</a>
    </td>
    <td>India
    </td>
    <td>utility
    </td>
    <td>
    </td>
    <td>
    </td>
    <td>6 on order<sup class="reference" id="cite_ref-31"><a href="#cite_note-31"><span class="cite-bracket">[</span>31<span class="cite-bracket">]</span></a></sup>
    </td></tr>
    <tr>
    <td rowspan="2"><a href="/wiki/A%C3%A9rospatiale_Alouette_III" title="Aérospatiale Alouette III">Alouette III</a>
    </td>
    <td rowspan="2">France/India
    </td>
    <td rowspan="2">liaison
    </td>
    <td><a class="mw-redirect" href="/wiki/HAL_Chetak" title="HAL Chetak">Chetak</a>
    </td>
    <td>77<sup class="reference" id="cite_ref-:12_14-19"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td>
    <td rowspan="3">license-built by <a href="/wiki/Hindustan_Aeronautics_Limited" title="Hindustan Aeronautics Limited">HAL</a>. A fleet of around 120 aircraft.<sup class="reference" id="cite_ref-32"><a href="#cite_note-32"><span class="cite-bracket">[</span>32<span class="cite-bracket">]</span></a></sup>
    </td></tr>
    <tr>
    <td><a class="mw-redirect" href="/wiki/HAL_Cheetal" title="HAL Cheetal">Cheetal</a>
    </td>
    <td>18<sup class="reference" id="cite_ref-33"><a href="#cite_note-33"><span class="cite-bracket">[</span>33<span class="cite-bracket">]</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/A%C3%A9rospatiale_SA_315B_Lama" title="Aérospatiale SA 315B Lama">SA 315B Lama</a>
    </td>
    <td>France/India
    </td>
    <td>utility
    </td>
    <td><a href="/wiki/A%C3%A9rospatiale_SA_315B_Lama#Variants" title="Aérospatiale SA 315B Lama">Cheetah</a>
    </td>
    <td>18<sup class="reference" id="cite_ref-:12_14-20"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a class="mw-redirect" href="/wiki/Trainer_(aircraft)" title="Trainer (aircraft)">Trainer Aircraft</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/BAE_Systems_Hawk" title="BAE Systems Hawk">BAE Hawk</a>
    </td>
    <td>United Kingdom
    </td>
    <td><a href="/wiki/Trainer_aircraft#Advanced_training" title="Trainer aircraft">Advanced trainer</a>
    </td>
    <td><a href="/wiki/BAE_Systems_Hawk#Hawk_132" title="BAE Systems Hawk">Hawk 132</a>
    </td>
    <td>101
    <p><sup class="reference" id="cite_ref-:12_14-21"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup><sup class="reference" id="cite_ref-:8_34-0"><a href="#cite_note-:8-34"><span class="cite-bracket">[</span>34<span class="cite-bracket">]</span></a></sup>
    </p>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a class="mw-redirect" href="/wiki/HAL_Kiran" title="HAL Kiran">HAL Kiran</a>
    </td>
    <td>India
    </td>
    <td><a href="/wiki/Trainer_aircraft" title="Trainer aircraft">Intermediate trainer</a>
    </td>
    <td>
    </td>
    <td>77<sup class="reference" id="cite_ref-:12_14-22"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/HAL_HTT-40" title="HAL HTT-40">HAL HTT-40</a>
    </td>
    <td><a href="/wiki/India" title="India">India</a>
    </td>
    <td><a href="/wiki/Trainer_aircraft#Basic_training" title="Trainer aircraft">Basic trainer</a>
    </td>
    <td>
    </td>
    <td>
    </td>
    <td>70 on order <sup class="reference" id="cite_ref-:12_14-23"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/Pilatus_PC-7" title="Pilatus PC-7">Pilatus PC-7</a>
    </td>
    <td><a href="/wiki/Switzerland" title="Switzerland">Switzerland</a>
    </td>
    <td><a href="/wiki/Trainer_aircraft#Basic_training" title="Trainer aircraft">Basic trainer</a>
    </td>
    <td><a href="/wiki/Pilatus_PC-7#Variants" title="Pilatus PC-7">Mk II</a>
    </td>
    <td>75<sup class="reference" id="cite_ref-:12_14-24"><a href="#cite_note-:12-14"><span class="cite-bracket">[</span>14<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/Pipistrel_Virus" title="Pipistrel Virus">Pipistrel Virus</a>
    </td>
    <td><a href="/wiki/Slovenia" title="Slovenia">Slovenia</a>
    </td>
    <td><a class="mw-redirect" href="/wiki/Ab-initio_trainer" title="Ab-initio trainer">Ab initio trainer</a>
    </td>
    <td>
    </td>
    <td>72<sup class="reference" id="cite_ref-35"><a href="#cite_note-35"><span class="cite-bracket">[</span>35<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <th colspan="6" style="align: center; background: lavender;"><a href="/wiki/Unmanned_aerial_vehicle" title="Unmanned aerial vehicle">UAV</a>
    </th></tr>
    <tr>
    <td><a href="/wiki/IAI_Heron" title="IAI Heron">IAI Heron</a>
    </td>
    <td>Israel
    </td>
    <td><a class="mw-redirect" href="/wiki/Surveillance_drones" title="Surveillance drones">surveillance</a>
    </td>
    <td>Heron 1
    </td>
    <td>47<sup class="reference" id="cite_ref-36"><a href="#cite_note-36"><span class="cite-bracket">[</span>36<span class="cite-bracket">]</span></a></sup>
    </td>
    <td><sup class="reference" id="cite_ref-:06_37-0"><a href="#cite_note-:06-37"><span class="cite-bracket">[</span>37<span class="cite-bracket">]</span></a></sup>
    </td></tr>
    <tr>
    <td><a href="/wiki/IAI_Heron" title="IAI Heron">IAI Heron</a> Mk 2
    </td>
    <td>Israel
    </td>
    <td><a class="mw-redirect" href="/wiki/Surveillance_drones" title="Surveillance drones">surveillance</a>
    </td>
    <td>Mk 2
    </td>
    <td>4<sup class="reference" id="cite_ref-:9_38-0"><a href="#cite_note-:9-38"><span class="cite-bracket">[</span>38<span class="cite-bracket">]</span></a></sup><sup class="reference" id="cite_ref-:10_39-0"><a href="#cite_note-:10-39"><span class="cite-bracket">[</span>39<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a href="/wiki/IAI_Searcher" title="IAI Searcher">IAI Searcher</a>
    </td>
    <td>Israel
    </td>
    <td>surveillance
    </td>
    <td>Mk. I / II
    </td>
    <td><sup class="reference" id="cite_ref-janes-16sep15_40-0"><a href="#cite_note-janes-16sep15-40"><span class="cite-bracket">[</span>40<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td>ALS-50
    </td>
    <td>India
    </td>
    <td><a href="/wiki/Loitering_munition" title="Loitering munition">loitering munition</a>
    </td>
    <td>
    </td>
    <td>100<sup class="reference" id="cite_ref-41"><a href="#cite_note-41"><span class="cite-bracket">[</span>41<span class="cite-bracket">]</span></a></sup>
    </td>
    <td>
    </td></tr>
    <tr>
    <td><a class="external text" href="http://www.kadet-uav.com/" rel="nofollow">Kadet</a> Loitering Aerial Munition
    </td>
    <td>India
    </td>
    <td><a href="/wiki/Loitering_munition" title="Loitering munition">loitering munition</a>
    </td>
    <td>
    </td>
    <td>50+ on order
    </td>
    <td>Developed by <a href="/wiki/Defence_Research_and_Development_Organisation" title="Defence Research and Development Organisation">DRDO</a> and <a class="external text" href="http://www.kadet-uav.com/" rel="nofollow">KDS</a>
    <p>Multiple variants; Weight - 15 to 120 kg; Warhead - 2 to 40 kg; Max. Endurance - 12 hrs; Max. Range - 150 to 300 km; Canister launched and vertical take-off and landing (VTOL) variants<sup class="reference" id="cite_ref-42"><a href="#cite_note-42"><span class="cite-bracket">[</span>42<span class="cite-bracket">]</span></a></sup><sup class="reference" id="cite_ref-43"><a href="#cite_note-43"><span class="cite-bracket">[</span>43<span class="cite-bracket">]</span></a></sup>
    </p>
    </td></tr></tbody></table>




```python
table1=table.find_all('th')
```


```python
headers=[]
for th in table1:
    headers.append(th.text.strip())
```


```python
headers

```




    ['Aircraft',
     'Origin',
     'Type',
     'Variant',
     'In service',
     'Notes',
     'Combat Aircraft',
     'AEW&CS',
     'Reconnaissance',
     'Tanker',
     'Transport',
     'Helicopters',
     'Trainer Aircraft',
     'UAV']




```python
rows=[]
for tr in table.find_all('tr'):
    row=[]
    for td in tr.find_all('td'):
        row.append(td.text.strip())
    if row:
        rows.append(row)
```


```python
import pandas as pd

```


```python
! pip install pandas
```

    Requirement already satisfied: pandas in d:\users\lib\site-packages (2.2.2)
    Requirement already satisfied: numpy>=1.26.0 in d:\users\lib\site-packages (from pandas) (1.26.4)
    Requirement already satisfied: python-dateutil>=2.8.2 in d:\users\lib\site-packages (from pandas) (2.9.0.post0)
    Requirement already satisfied: pytz>=2020.1 in d:\users\lib\site-packages (from pandas) (2024.1)
    Requirement already satisfied: tzdata>=2022.7 in d:\users\lib\site-packages (from pandas) (2023.3)
    Requirement already satisfied: six>=1.5 in d:\users\lib\site-packages (from python-dateutil>=2.8.2->pandas) (1.16.0)
    


```python
import pandas as pd
df= pd.dataframe(rows)
```


    ---------------------------------------------------------------------------

    AttributeError                            Traceback (most recent call last)

    Cell In[57], line 2
          1 import pandas as pd
    ----> 2 df= pd.dataframe(rows)
    

    AttributeError: module 'pandas' has no attribute 'dataframe'



```python
df=pd.dataframe(rows)
```


    ---------------------------------------------------------------------------

    AttributeError                            Traceback (most recent call last)

    Cell In[59], line 1
    ----> 1 df=pd.dataframe(rows)
    

    AttributeError: module 'pandas' has no attribute 'dataframe'



```python
df= pd.DataFrame(rows)
```


```python
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>0</th>
      <th>1</th>
      <th>2</th>
      <th>3</th>
      <th>4</th>
      <th>5</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Dassault Rafale</td>
      <td>France</td>
      <td>Multirole</td>
      <td>DH</td>
      <td>8[1]</td>
      <td></td>
    </tr>
    <tr>
      <th>1</th>
      <td>EH</td>
      <td>28[1]</td>
      <td></td>
      <td>None</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>2</th>
      <td>HAL Tejas</td>
      <td>India</td>
      <td>Multirole</td>
      <td>Mk.1</td>
      <td>31[2][3]</td>
      <td></td>
    </tr>
    <tr>
      <th>3</th>
      <td>Conversion trainer</td>
      <td>Mk.1 Trainer</td>
      <td>2[4][5]</td>
      <td>Used for training; 16 more on order[6]</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Multirole</td>
      <td>Mk.1A</td>
      <td></td>
      <td>73 on order, 97 more approved[6][7]</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Sukhoi Su-30MKI</td>
      <td>Russia</td>
      <td>Multirole</td>
      <td>Su-30MKI Flanker H</td>
      <td>259[8][9]</td>
      <td>12 more cleared.[10]</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Mikoyan MiG-29</td>
      <td>Soviet Union</td>
      <td>Multirole</td>
      <td>Fulcrum</td>
      <td>53[1][11]</td>
      <td>Including 12 MiG-29UPG.</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Fulcrum B</td>
      <td>7[1]</td>
      <td></td>
      <td>None</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Dassault Mirage 2000</td>
      <td>France</td>
      <td>Multirole</td>
      <td>-2000H</td>
      <td>37[1]</td>
      <td></td>
    </tr>
    <tr>
      <th>9</th>
      <td>-2000TH</td>
      <td>10[1]</td>
      <td>Used for training.</td>
      <td>None</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>10</th>
      <td>SEPECAT Jaguar</td>
      <td>United Kingdom</td>
      <td>Attack</td>
      <td>IB</td>
      <td>28[1]</td>
      <td>Used for training.</td>
    </tr>
    <tr>
      <th>11</th>
      <td>IS</td>
      <td>79[1]</td>
      <td></td>
      <td>None</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>12</th>
      <td>IM</td>
      <td>8[1]</td>
      <td>Maritime strike aircraft carrying Sea Eagle mi...</td>
      <td>None</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Mikoyan-Gurevich MiG-21</td>
      <td>Soviet Union</td>
      <td>Interceptor</td>
      <td>MiG-21 Bison</td>
      <td>40[12]</td>
      <td>Being phased out.[13]</td>
    </tr>
    <tr>
      <th>14</th>
      <td>Embraer R-99</td>
      <td>Brazil</td>
      <td>AEW&amp;C</td>
      <td>Netra Mk1</td>
      <td>3[14]</td>
      <td>equipped with a  Netra AEW&amp;CS.</td>
    </tr>
    <tr>
      <th>15</th>
      <td>Beriev A-50</td>
      <td>Soviet Union</td>
      <td>AEW&amp;C</td>
      <td>A-50EI</td>
      <td>3[14]</td>
      <td>equipped with the EL/W-2090 radar. 2 more plan...</td>
    </tr>
    <tr>
      <th>16</th>
      <td>Boeing 707</td>
      <td>United States</td>
      <td>SIGINT / ELINT</td>
      <td>707-337C Phalcon</td>
      <td>1[14]</td>
      <td>Operated by Aviation Research Centre (ARC) of ...</td>
    </tr>
    <tr>
      <th>17</th>
      <td>Global 5000</td>
      <td>United States</td>
      <td>SIGINT / ELINT</td>
      <td></td>
      <td>2[14]</td>
      <td>None</td>
    </tr>
    <tr>
      <th>18</th>
      <td>Gulfstream III</td>
      <td>United States</td>
      <td>ELINT</td>
      <td>SRA[19]</td>
      <td>3[14]</td>
      <td>None</td>
    </tr>
    <tr>
      <th>19</th>
      <td>Gulfstream G100</td>
      <td>Israel</td>
      <td>surveillance</td>
      <td>1125 Astra</td>
      <td>2[14]</td>
      <td>None</td>
    </tr>
    <tr>
      <th>20</th>
      <td>Ilyushin Il-78</td>
      <td>Soviet Union</td>
      <td>aerial refuelling</td>
      <td>Il-78MKI</td>
      <td>6[14]</td>
      <td></td>
    </tr>
    <tr>
      <th>21</th>
      <td>Boeing 777</td>
      <td>United States</td>
      <td>VIP transport</td>
      <td>777-300ER</td>
      <td>2[20]</td>
      <td>Used as Air India One for presidential flight</td>
    </tr>
    <tr>
      <th>22</th>
      <td>Boeing 737</td>
      <td>United States</td>
      <td>VIP transport</td>
      <td>737-700</td>
      <td>3[21]</td>
      <td></td>
    </tr>
    <tr>
      <th>23</th>
      <td>Embraer Legacy 600</td>
      <td>Brazil</td>
      <td>VIP transport</td>
      <td></td>
      <td>4[22]</td>
      <td></td>
    </tr>
    <tr>
      <th>24</th>
      <td>Boeing C-17</td>
      <td>United States</td>
      <td>strategic airlifter</td>
      <td></td>
      <td>11[14]</td>
      <td></td>
    </tr>
    <tr>
      <th>25</th>
      <td>Ilyushin Il-76</td>
      <td>Soviet Union</td>
      <td>strategic airlifter</td>
      <td>Il-76MD</td>
      <td>17[14]</td>
      <td></td>
    </tr>
    <tr>
      <th>26</th>
      <td>C-130J Super Hercules</td>
      <td>United States</td>
      <td>tactical airlifter</td>
      <td>C-130J-30[23]</td>
      <td>12[14]</td>
      <td></td>
    </tr>
    <tr>
      <th>27</th>
      <td>Airbus A321</td>
      <td>Europe</td>
      <td>transport</td>
      <td>A321-200</td>
      <td>4[14]</td>
      <td></td>
    </tr>
    <tr>
      <th>28</th>
      <td>Antonov An-32</td>
      <td>Soviet Union</td>
      <td>tactical airlifter</td>
      <td></td>
      <td>103[14]</td>
      <td>53 are the 32RE variant[24]</td>
    </tr>
    <tr>
      <th>29</th>
      <td>EADS CASA C-295</td>
      <td>Spain</td>
      <td>tactical airlifter</td>
      <td>C-295MW</td>
      <td>5[25]</td>
      <td>51 more on order - HS 748 replacement[26]</td>
    </tr>
    <tr>
      <th>30</th>
      <td>Hawker Siddeley HS 748</td>
      <td>United Kingdom</td>
      <td>tactical airlifter</td>
      <td></td>
      <td>57[14]</td>
      <td>To be replaced by EADS CASA C-295</td>
    </tr>
    <tr>
      <th>31</th>
      <td>Dornier Do 228</td>
      <td>Germany</td>
      <td>tactical airlifter</td>
      <td>228-201</td>
      <td>58[14]</td>
      <td>license built by HAL[27]</td>
    </tr>
    <tr>
      <th>32</th>
      <td>Boeing AH-64</td>
      <td>United States</td>
      <td>attack</td>
      <td>AH-64E</td>
      <td>22[14]</td>
      <td></td>
    </tr>
    <tr>
      <th>33</th>
      <td>Mil Mi-24</td>
      <td>Russia</td>
      <td>attack</td>
      <td>Mi-24/25/35</td>
      <td>15[14]</td>
      <td></td>
    </tr>
    <tr>
      <th>34</th>
      <td>HAL Prachand</td>
      <td>India</td>
      <td>attack</td>
      <td></td>
      <td>10[28]</td>
      <td>66 on order[29]</td>
    </tr>
    <tr>
      <th>35</th>
      <td>HAL Rudra</td>
      <td>India</td>
      <td>attack</td>
      <td></td>
      <td>16</td>
      <td>50 on order.[30]</td>
    </tr>
    <tr>
      <th>36</th>
      <td>CH-47 Chinook</td>
      <td>United States</td>
      <td>transport</td>
      <td>CH-47F</td>
      <td>15[14]</td>
      <td></td>
    </tr>
    <tr>
      <th>37</th>
      <td>Mil Mi-17</td>
      <td>Russia</td>
      <td>utility</td>
      <td>Mi-17V-5</td>
      <td>222[14]</td>
      <td></td>
    </tr>
    <tr>
      <th>38</th>
      <td>HAL Dhruv</td>
      <td>India</td>
      <td>utility</td>
      <td></td>
      <td>95[14]</td>
      <td></td>
    </tr>
    <tr>
      <th>39</th>
      <td>HAL LUH</td>
      <td>India</td>
      <td>utility</td>
      <td></td>
      <td></td>
      <td>6 on order[31]</td>
    </tr>
    <tr>
      <th>40</th>
      <td>Alouette III</td>
      <td>France/India</td>
      <td>liaison</td>
      <td>Chetak</td>
      <td>77[14]</td>
      <td>license-built by HAL. A fleet of around 120 ai...</td>
    </tr>
    <tr>
      <th>41</th>
      <td>Cheetal</td>
      <td>18[33]</td>
      <td>None</td>
      <td>None</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>42</th>
      <td>SA 315B Lama</td>
      <td>France/India</td>
      <td>utility</td>
      <td>Cheetah</td>
      <td>18[14]</td>
      <td>None</td>
    </tr>
    <tr>
      <th>43</th>
      <td>BAE Hawk</td>
      <td>United Kingdom</td>
      <td>Advanced trainer</td>
      <td>Hawk 132</td>
      <td>101\n[14][34]</td>
      <td></td>
    </tr>
    <tr>
      <th>44</th>
      <td>HAL Kiran</td>
      <td>India</td>
      <td>Intermediate trainer</td>
      <td></td>
      <td>77[14]</td>
      <td></td>
    </tr>
    <tr>
      <th>45</th>
      <td>HAL HTT-40</td>
      <td>India</td>
      <td>Basic trainer</td>
      <td></td>
      <td></td>
      <td>70 on order [14]</td>
    </tr>
    <tr>
      <th>46</th>
      <td>Pilatus PC-7</td>
      <td>Switzerland</td>
      <td>Basic trainer</td>
      <td>Mk II</td>
      <td>75[14]</td>
      <td></td>
    </tr>
    <tr>
      <th>47</th>
      <td>Pipistrel Virus</td>
      <td>Slovenia</td>
      <td>Ab initio trainer</td>
      <td></td>
      <td>72[35]</td>
      <td></td>
    </tr>
    <tr>
      <th>48</th>
      <td>IAI Heron</td>
      <td>Israel</td>
      <td>surveillance</td>
      <td>Heron 1</td>
      <td>47[36]</td>
      <td>[37]</td>
    </tr>
    <tr>
      <th>49</th>
      <td>IAI Heron Mk 2</td>
      <td>Israel</td>
      <td>surveillance</td>
      <td>Mk 2</td>
      <td>4[38][39]</td>
      <td></td>
    </tr>
    <tr>
      <th>50</th>
      <td>IAI Searcher</td>
      <td>Israel</td>
      <td>surveillance</td>
      <td>Mk. I / II</td>
      <td>[40]</td>
      <td></td>
    </tr>
    <tr>
      <th>51</th>
      <td>ALS-50</td>
      <td>India</td>
      <td>loitering munition</td>
      <td></td>
      <td>100[41]</td>
      <td></td>
    </tr>
    <tr>
      <th>52</th>
      <td>Kadet Loitering Aerial Munition</td>
      <td>India</td>
      <td>loitering munition</td>
      <td></td>
      <td>50+ on order</td>
      <td>Developed by DRDO and KDS\nMultiple variants; ...</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.TO_CSV("Indian_military_Aircraft")
```


    ---------------------------------------------------------------------------

    AttributeError                            Traceback (most recent call last)

    ~\AppData\Local\Temp\ipykernel_9976\433132280.py in ?()
    ----> 1 df.TO_CSV("Indian_military_Aircraft")
    

    D:\Users\Lib\site-packages\pandas\core\generic.py in ?(self, name)
       6295             and name not in self._accessors
       6296             and self._info_axis._can_hold_identifiers_and_holds_name(name)
       6297         ):
       6298             return self[name]
    -> 6299         return object.__getattribute__(self, name)
    

    AttributeError: 'DataFrame' object has no attribute 'TO_CSV'



```python
df.To_CSV("Indian_military_Aircraft")
```


    ---------------------------------------------------------------------------

    AttributeError                            Traceback (most recent call last)

    ~\AppData\Local\Temp\ipykernel_9976\1721363881.py in ?()
    ----> 1 df.To_CSV("Indian_military_Aircraft")
    

    D:\Users\Lib\site-packages\pandas\core\generic.py in ?(self, name)
       6295             and name not in self._accessors
       6296             and self._info_axis._can_hold_identifiers_and_holds_name(name)
       6297         ):
       6298             return self[name]
    -> 6299         return object.__getattribute__(self, name)
    

    AttributeError: 'DataFrame' object has no attribute 'To_CSV'



```python
df.TO_CSV("Indian_military_Aircraft")
```


    ---------------------------------------------------------------------------

    AttributeError                            Traceback (most recent call last)

    ~\AppData\Local\Temp\ipykernel_9976\433132280.py in ?()
    ----> 1 df.TO_CSV("Indian_military_Aircraft")
    

    D:\Users\Lib\site-packages\pandas\core\generic.py in ?(self, name)
       6295             and name not in self._accessors
       6296             and self._info_axis._can_hold_identifiers_and_holds_name(name)
       6297         ):
       6298             return self[name]
    -> 6299         return object.__getattribute__(self, name)
    

    AttributeError: 'DataFrame' object has no attribute 'TO_CSV'



```python
df.to_CSV("Indian_military_Aircraft")
```


    ---------------------------------------------------------------------------

    AttributeError                            Traceback (most recent call last)

    ~\AppData\Local\Temp\ipykernel_9976\377395478.py in ?()
    ----> 1 df.to_CSV("Indian_military_Aircraft")
    

    D:\Users\Lib\site-packages\pandas\core\generic.py in ?(self, name)
       6295             and name not in self._accessors
       6296             and self._info_axis._can_hold_identifiers_and_holds_name(name)
       6297         ):
       6298             return self[name]
    -> 6299         return object.__getattribute__(self, name)
    

    AttributeError: 'DataFrame' object has no attribute 'to_CSV'



```python
df.to_csv("Indian_military_Aircraft")
```


```python

```
