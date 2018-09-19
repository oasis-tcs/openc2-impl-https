





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://assets-cdn.github.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" media="all" integrity="sha512-1FLfhli3wF1EqKy4+DmsB7My96mQ71ZtDpkmg/2A8RP+5uDgJ0zAT8sRDwSG0p75xQjd9aMIVb58gpjhC//ngA==" rel="stylesheet" href="https://assets-cdn.github.com/assets/frameworks-dcca19dafecb17dea634d2f083dc7f9f.css" />
  <link crossorigin="anonymous" media="all" integrity="sha512-vpSrq3BnToOCBwttDJ4DfqlJHAGNl2JlQLf4kiZjkkRDjb5I/yUbWeW/OEe8NRITeFfr2hfapEgonrFgRkYrTQ==" rel="stylesheet" href="https://assets-cdn.github.com/assets/github-fa8595d654ae3180ab775b436a8d97a2.css" />
  
  
  
  

  <meta name="viewport" content="width=device-width">
  
  <title>openc2-impl-https/oc2-impl-https-v1.0.md at master · oasis-tcs/openc2-impl-https</title>
    <meta name="description" content="OASIS OpenC2 TC: Repository used by TC members to propose and track changes to the OpenC2 HTTPS implementation specification - oasis-tcs/openc2-impl-https">
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    
    <meta property="og:image" content="https://avatars0.githubusercontent.com/u/20116735?s=400&amp;v=4" /><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="object" /><meta property="og:title" content="oasis-tcs/openc2-impl-https" /><meta property="og:url" content="https://github.com/oasis-tcs/openc2-impl-https" /><meta property="og:description" content="OASIS OpenC2 TC: Repository used by TC members to propose and track changes to the OpenC2 HTTPS implementation specification - oasis-tcs/openc2-impl-https" />

  <link rel="assets" href="https://assets-cdn.github.com/">
  <link rel="web-socket" href="wss://live.github.com/_sockets/VjI6MzE5Mjc1MjIwOjNhOWEzZWYyNGNlZGYyOGY1ZWE2YTkzMTI2M2MzOWE4M2UwYzVkM2Y5ZTBiNDkyMzZmMWJjZGYwM2E0YjY4MjI=--b383659f89770c25c171ead8950cc8f382cb1c1a">
  <meta name="pjax-timeout" content="1000">
  <link rel="sudo-modal" href="/sessions/sudo_modal">
  <meta name="request-id" content="304D:1251:F285F3:1AD8232:5BA2A518" data-pjax-transient>


  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

      <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">

  <meta name="octolytics-host" content="collector.githubapp.com" /><meta name="octolytics-app-id" content="github" /><meta name="octolytics-event-url" content="https://collector.githubapp.com/github-external/browser_event" /><meta name="octolytics-dimension-request_id" content="304D:1251:F285F3:1AD8232:5BA2A518" /><meta name="octolytics-dimension-region_edge" content="iad" /><meta name="octolytics-dimension-region_render" content="iad" /><meta name="octolytics-actor-id" content="26066504" /><meta name="octolytics-actor-login" content="dlemire60" /><meta name="octolytics-actor-hash" content="9ef4195fce530f0165001ba0daf8761b0dbe33e607f1a4c93511072f8b81dced" />
<meta name="analytics-location" content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" />



    <meta name="google-analytics" content="UA-3769691-2">

  <meta class="js-ga-set" name="userId" content="f5849a910cbc79e961649d0b5ce9447c" %>

<meta class="js-ga-set" name="dimension1" content="Logged In">



  

      <meta name="hostname" content="github.com">
    <meta name="user-login" content="dlemire60">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="YmQzNjAxYjg5NDZhNmU3YmE3ZGY3NDY1ODc5ZWI4ODJlYjI2YjcyYTBhNDEwYzU2YmQwYjEyMTNiOGM5ZDBkNHx7InJlbW90ZV9hZGRyZXNzIjoiNjMuODguODMuNjgiLCJyZXF1ZXN0X2lkIjoiMzA0RDoxMjUxOkYyODVGMzoxQUQ4MjMyOjVCQTJBNTE4IiwidGltZXN0YW1wIjoxNTM3Mzg1NzU3LCJob3N0IjoiZ2l0aHViLmNvbSJ9">

    <meta name="enabled-features" content="DASHBOARD_V2_LAYOUT_OPT_IN,EXPLORE_DISCOVER_REPOSITORIES,UNIVERSE_BANNER,MARKETPLACE_PLAN_RESTRICTION_EDITOR,MARKETPLACE_RETARGETING,QUOTE_MARKDOWN">

  <meta name="html-safe-nonce" content="f82f728276757884080b0e91ecef970078f97403">

  <meta http-equiv="x-pjax-version" content="4a2a4ce45f06a6118e1b370fa07eea2a">
  

      <link href="https://github.com/oasis-tcs/openc2-impl-https/commits/master.atom" rel="alternate" title="Recent Commits to openc2-impl-https:master" type="application/atom+xml">

  <meta name="go-import" content="github.com/oasis-tcs/openc2-impl-https git https://github.com/oasis-tcs/openc2-impl-https.git">

  <meta name="octolytics-dimension-user_id" content="20116735" /><meta name="octolytics-dimension-user_login" content="oasis-tcs" /><meta name="octolytics-dimension-repository_id" content="136681453" /><meta name="octolytics-dimension-repository_nwo" content="oasis-tcs/openc2-impl-https" /><meta name="octolytics-dimension-repository_public" content="true" /><meta name="octolytics-dimension-repository_is_fork" content="false" /><meta name="octolytics-dimension-repository_network_root_id" content="136681453" /><meta name="octolytics-dimension-repository_network_root_nwo" content="oasis-tcs/openc2-impl-https" /><meta name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" content="false" />


    <link rel="canonical" href="https://github.com/oasis-tcs/openc2-impl-https/blob/master/oc2-impl-https-v1.0.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://assets-cdn.github.com/favicon.ico">

<meta name="theme-color" content="#1e2327">


  <meta name="u2f-support" content="true">

  <link rel="manifest" href="/manifest.json" crossOrigin="use-credentials">

  </head>

  <body class="logged-in env-production page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="p-3 bg-blue text-white show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>

    
    
    



        
<header class="Header  f5" role="banner">
  <div class="d-flex flex-justify-between px-3 container-lg">
    <div class="d-flex flex-justify-between ">
      <div class="">
        <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg height="32" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>

      </div>

    </div>

    <div class="HeaderMenu d-flex flex-justify-between flex-auto">
      <div class="d-flex">
            <div class="">
              <div class="header-search scoped-search site-scoped-search js-site-search position-relative js-jump-to"
  role="combobox"
  aria-owns="jump-to-results"
  aria-label="Search or jump to"
  aria-haspopup="listbox"
  aria-expanded="false"
>
  <div class="position-relative">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-site-search-form" data-scope-type="Repository" data-scope-id="136681453" data-scoped-search-url="/oasis-tcs/openc2-impl-https/search" data-unscoped-search-url="/search" action="/oasis-tcs/openc2-impl-https/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
      <label class="form-control header-search-wrapper header-search-wrapper-jump-to position-relative d-flex flex-justify-between flex-items-center js-chromeless-input-container">
        <input type="text"
          class="form-control header-search-input jump-to-field js-jump-to-field js-site-search-focus js-site-search-field is-clearable"
          data-hotkey="s,/"
          name="q"
          value=""
          placeholder="Search or jump to…"
          data-unscoped-placeholder="Search or jump to…"
          data-scoped-placeholder="Search or jump to…"
          autocapitalize="off"
          aria-autocomplete="list"
          aria-controls="jump-to-results"
          data-jump-to-suggestions-path="/_graphql/GetSuggestedNavigationDestinations#csrf-token=hnxhI9V2/5PNDmCNnPknHgUVd6VW21ORkUKoQKih9astG7pPKyW0FHJ/RX4ZYsgRaAaBcHAUh2DEC3JqaIcQJg=="
          spellcheck="false"
          autocomplete="off"
          >
          <input type="hidden" class="js-site-search-type-field" name="type" >
            <img src="https://assets-cdn.github.com/images/search-shortcut-hint.svg" alt="" class="mr-2 header-search-key-slash">

            <div class="Box position-absolute overflow-hidden d-none jump-to-suggestions js-jump-to-suggestions-container">
              <ul class="d-none js-jump-to-suggestions-template-container">
                <li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item" role="option">
                  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center p-2 jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open" href="">
                    <div class="jump-to-octicon js-jump-to-octicon mr-2 text-center d-none">
                      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
                      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
                      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
                    </div>

                    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

                    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
                    </div>

                    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
                      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
                        In this repository
                      </span>
                      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
                        All GitHub
                      </span>
                      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
                    </div>

                    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
                      Jump to
                      <span class="d-inline-block ml-1 v-align-middle">↵</span>
                    </div>
                  </a>
                </li>
              </ul>
              <ul class="d-none js-jump-to-no-results-template-container">
                <li class="d-flex flex-justify-center flex-items-center p-3 f5 d-none">
                  <span class="text-gray">No suggested jump to results</span>
                </li>
              </ul>

              <ul id="jump-to-results" role="listbox" class="js-navigation-container jump-to-suggestions-results-container js-jump-to-suggestions-results-container" >
                <li class="d-flex flex-justify-center flex-items-center p-0 f5">
                  <img src="https://assets-cdn.github.com/images/spinners/octocat-spinner-128.gif" alt="Octocat Spinner Icon" class="m-2" width="28">
                </li>
              </ul>
            </div>
      </label>
</form>  </div>
</div>

            </div>

          <ul class="d-flex pl-2 flex-items-center text-bold list-style-none" role="navigation">
            <li>
              <a class="js-selected-navigation-item HeaderNavlink px-2" data-hotkey="g p" data-ga-click="Header, click, Nav menu - item:pulls context:user" aria-label="Pull requests you created" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls" href="/pulls">
                Pull requests
</a>            </li>
            <li>
              <a class="js-selected-navigation-item HeaderNavlink px-2" data-hotkey="g i" data-ga-click="Header, click, Nav menu - item:issues context:user" aria-label="Issues you created" data-selected-links="/issues /issues/assigned /issues/mentioned /issues" href="/issues">
                Issues
</a>            </li>
              <li>
                <a class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:marketplace context:user" data-octo-click="marketplace_click" data-octo-dimensions="location:nav_bar" data-selected-links=" /marketplace" href="/marketplace">
                   Marketplace
</a>              </li>
            <li>
              <a class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore" href="/explore">
                Explore
</a>            </li>
          </ul>
      </div>

      <div class="d-flex">
        
<ul class="user-nav d-flex flex-items-center list-style-none" id="user-links">
  <li class="dropdown">
    <span class="d-inline-block  px-2">
      
    <a aria-label="You have unread notifications" class="notification-indicator tooltipped tooltipped-s  js-socket-channel js-notification-indicator" data-hotkey="g n" data-ga-click="Header, go to notifications, icon:unread" data-channel="notification-changed:26066504" href="/notifications">
        <span class="mail-status unread"></span>
        <svg class="octicon octicon-bell" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M13.99 11.991v1H0v-1l.73-.58c.769-.769.809-2.547 1.189-4.416.77-3.767 4.077-4.996 4.077-4.996 0-.55.45-1 .999-1 .55 0 1 .45 1 1 0 0 3.387 1.229 4.156 4.996.38 1.879.42 3.657 1.19 4.417l.659.58h-.01zM6.995 15.99c1.11 0 1.999-.89 1.999-1.999H4.996c0 1.11.89 1.999 1.999 1.999z"/></svg>
</a>
    </span>
  </li>

  <li class="dropdown">
    <details class="details-overlay details-reset d-flex px-2 flex-items-center">
      <summary class="HeaderNavlink"
         aria-label="Create new…"
         data-ga-click="Header, create new, icon:add">
        <svg class="octicon octicon-plus float-left mr-1 mt-1" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 9H7v5H5V9H0V7h5V2h2v5h5v2z"/></svg>
        <span class="dropdown-caret mt-1"></span>
      </summary>
      <details-menu class="dropdown-menu dropdown-menu-sw">
        
<a role="menuitem" class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a role="menuitem" class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>

<a role="menuitem" class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, create new gist">
  New gist
</a>

  <a role="menuitem" class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>


  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="oasis-tcs/openc2-impl-https">This repository</span>
  </div>
    <a role="menuitem" class="dropdown-item" href="/oasis-tcs/openc2-impl-https/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </details-menu>
    </details>
  </li>

  <li class="dropdown">

    <details class="details-overlay details-reset d-flex pl-2 flex-items-center">
      <summary class="HeaderNavlink name mt-1"
        aria-label="View profile and more"
        data-ga-click="Header, show menu, icon:avatar">
        <img alt="@dlemire60" class="avatar float-left mr-1" src="https://avatars3.githubusercontent.com/u/26066504?s=40&amp;v=4" height="20" width="20">
        <span class="dropdown-caret"></span>
      </summary>
      <details-menu class="dropdown-menu dropdown-menu-sw">
        <ul>
          <li class="header-nav-current-user css-truncate"><a role="menuitem" class="no-underline user-profile-link px-3 pt-2 pb-2 mb-n2 mt-n1 d-block" href="/dlemire60" data-ga-click="Header, go to profile, text:Signed in as">Signed in as <strong class="css-truncate-target">dlemire60</strong></a></li>
          <li class="dropdown-divider"></li>
          <li><a role="menuitem" class="dropdown-item" href="/dlemire60" data-ga-click="Header, go to profile, text:your profile">Your profile</a></li>
          <li><a role="menuitem" class="dropdown-item" href="/dlemire60?tab=repositories" data-ga-click="Header, go to repositories, text:your repositories">Your repositories</a></li>
          <li><a role="menuitem" class="dropdown-item" href="/dlemire60?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">Your stars</a></li>
            <li><a role="menuitem" class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, your gists, text:your gists">Your gists</a></li>
          <li class="dropdown-divider"></li>
          <li><a role="menuitem" class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a></li>
          <li><a role="menuitem" class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">Settings</a></li>
          <li>
            <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="logout-form" action="/logout" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="Nwmn35r820WAnufymG72lfw2LViAuZCHUp1JmlsXhV6q8uBqlij7kj3QpA+BOke/fA1k3BpakQ/g3Z+OW/DjOg==" />
              <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout" role="menuitem">
                Sign out
              </button>
</form>          </li>
        </ul>
      </details-menu>
    </details>
  </li>
</ul>



        <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="sr-only right-0" action="/logout" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="s9Gx3hbZYPaWwG5hwKcr8X1yLkqoYGWT9gjyQMaTDlcuKvZrGg1AISuOLZzZ85rb/UlnzjKDZBtESCRUxnRoMw==" />
          <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
</form>      </div>
    </div>
  </div>
</header>

      

  </div>

  <div id="start-of-content" class="show-on-focus"></div>

    <div id="js-flash-container">


</div>



  <div role="main" class="application-main ">
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
    <div id="js-repo-pjax-container" data-pjax-container >
      





  



  <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav  ">
    <div class="repohead-details-container clearfix container">

      <ul class="pagehead-actions">
  <li>
        <!-- '"` --><!-- </textarea></xmp> --></option></form><form data-autosubmit="true" data-remote="true" class="js-social-container" action="/notifications/subscribe" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="/1LMQpR1BfFTcYmUP4hSs2UFEyYK2sOnOIUGS0rL7oaJvYalL4O4EnkXhx8Qf6eU9SY3MIjSICIYUWRaabrN1Q==" />      <input type="hidden" name="repository_id" id="repository_id" value="136681453" class="form-control" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/oasis-tcs/openc2-impl-https/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target"
            role="button"
            aria-haspopup="true"
            aria-expanded="false"
            aria-label="Toggle repository notifications menu"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
                <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                Unwatch
            </span>
          </a>
          <a class="social-count js-social-count"
            href="/oasis-tcs/openc2-impl-https/watchers"
            aria-label="4 users are watching this repository">
            4
          </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content">
            <div class="select-menu-header js-navigation-enable" tabindex="-1">
              <svg class="octicon octicon-x js-menu-close" role="img" aria-label="Close" viewBox="0 0 12 16" version="1.1" width="12" height="16"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
              <span class="select-menu-title">Notifications</span>
            </div>

              <div class="select-menu-list js-navigation-container" role="menu">

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
                  <div class="select-menu-item-text">
                    <input type="radio" name="do" id="do_included" value="included" />
                    <span class="select-menu-item-heading">Not watching</span>
                    <span class="description">Be notified when participating or @mentioned.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                      Watch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                  <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
                  <div class="select-menu-item-text">
                    <input type="radio" name="do" id="do_subscribed" value="subscribed" checked="checked" />
                    <span class="select-menu-item-heading">Watching</span>
                    <span class="description">Be notified of all conversations.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                        Unwatch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
                  <div class="select-menu-item-text">
                    <input type="radio" name="do" id="do_ignore" value="ignore" />
                    <span class="select-menu-item-heading">Ignoring</span>
                    <span class="description">Never be notified.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg class="octicon octicon-mute v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"/></svg>
                        Stop ignoring
                    </span>
                  </div>
                </div>

              </div>

            </div>
          </div>
        </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container on">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="starred js-social-form" action="/oasis-tcs/openc2-impl-https/unstar" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="3B+ZjRtigXV40eHg6VvGrTSmP5p3I9DIJfKNck6RAU7T/MiknLPXfl52pBSsPeSBpbX04eoaqViIaigLFuntxg==" />
      <input type="hidden" name="context" value="repository"></input>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar oasis-tcs/openc2-impl-https"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <svg class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/oasis-tcs/openc2-impl-https/stargazers"
           aria-label="2 users starred this repository">
          2
        </a>
</form>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="unstarred js-social-form" action="/oasis-tcs/openc2-impl-https/star" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="0qXbTbAXrIiAKZ6qvyjaM+yH+ePUPSa5rcVTp6lT/r8x3G0y+XALPZnkfwXyxGmdxiyWlYD+c9s/caP7hROl/g==" />
      <input type="hidden" name="context" value="repository"></input>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star oasis-tcs/openc2-impl-https"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <svg class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>
        Star
      </button>
        <a class="social-count js-social-count" href="/oasis-tcs/openc2-impl-https/stargazers"
           aria-label="2 users starred this repository">
          2
        </a>
</form>  </div>

  </li>

  <li>
          <details class="details-reset details-overlay details-overlay-dark d-inline-block float-left"
            data-deferred-details-content-url="/oasis-tcs/openc2-impl-https/fork?fragment=1">
            <summary class="btn btn-sm btn-with-count"
              title="Fork your own copy of oasis-tcs/openc2-impl-https to your account"
              data-ga-click="Repository, show fork modal, action:blob#show; text:Fork">
              <svg class="octicon octicon-repo-forked v-align-text-bottom" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
              Fork
            </summary>
            <details-dialog class="anim-fade-in fast Box Box--overlay d-flex flex-column">
              <div class="Box-header">
                <button class="Box-btn-octicon btn-octicon float-right" type="button" aria-label="Close dialog" data-close-dialog>
                  <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
                </button>
                <h3 class="Box-title">Where should we fork this repository?</h3>
              </div>
              <div class="Box-body overflow-auto text-center">
                <include-fragment>
                  <div class="octocat-spinner my-3" aria-label="Loading..."></div>
                  <p class="f5 text-gray">If this dialog fails to load, you can visit <a href="/oasis-tcs/openc2-impl-https/fork">the fork page</a> directly.</p>
                </include-fragment>
              </div>
            </details-dialog>
          </details>

    <a href="/oasis-tcs/openc2-impl-https/network/members" class="social-count"
       aria-label="2 users forked this repository">
      2
    </a>
  </li>
</ul>

      <h1 class="public ">
  <svg class="octicon octicon-repo" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a class="url fn" rel="author" href="/oasis-tcs">oasis-tcs</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a data-pjax="#js-repo-pjax-container" href="/oasis-tcs/openc2-impl-https">openc2-impl-https</a></strong>

</h1>

    </div>
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax container"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a class="js-selected-navigation-item selected reponav-item" itemprop="url" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /oasis-tcs/openc2-impl-https" href="/oasis-tcs/openc2-impl-https">
      <svg class="octicon octicon-code" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" data-hotkey="g i" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones /oasis-tcs/openc2-impl-https/issues" href="/oasis-tcs/openc2-impl-https/issues">
        <svg class="octicon octicon-issue-opened" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a data-hotkey="g p" itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /oasis-tcs/openc2-impl-https/pulls" href="/oasis-tcs/openc2-impl-https/pulls">
      <svg class="octicon octicon-git-pull-request" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>

    <a data-hotkey="g b" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /oasis-tcs/openc2-impl-https/projects" href="/oasis-tcs/openc2-impl-https/projects">
      <svg class="octicon octicon-project" viewBox="0 0 15 16" version="1.1" width="15" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      Projects
      <span class="Counter" >0</span>
</a>

    <a class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /oasis-tcs/openc2-impl-https/wiki" href="/oasis-tcs/openc2-impl-https/wiki">
      <svg class="octicon octicon-book" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"/></svg>
      Wiki
</a>
  <a class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse /oasis-tcs/openc2-impl-https/pulse" href="/oasis-tcs/openc2-impl-https/pulse">
    <svg class="octicon octicon-graph" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
    Insights
</a>

</nav>


  </div>

<div class="container new-discussion-timeline experiment-repo-nav  ">
  <div class="repository-content ">

    
  <a class="d-none js-permalink-shortcut" data-hotkey="y" href="/oasis-tcs/openc2-impl-https/blob/4fee41541d36c17c402e81cd3acfe8f0ba49a247/oc2-impl-https-v1.0.md">Permalink</a>

  <!-- blob contrib key: blob_contributors:v21:6dd90afd010296714f82be1142d0cc37 -->

  

  <div class="file-navigation">
    
<div class="select-menu branch-select-menu js-menu-container js-select-menu float-left">
  <button class=" btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    
    type="button" aria-label="Switch branches or tags" aria-expanded="false" aria-haspopup="true">
      <i>Branch:</i>
      <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax>

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg class="octicon octicon-x js-menu-close" role="img" aria-label="Close" viewBox="0 0 12 16" version="1.1" width="12" height="16"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Find or create a branch…" id="context-commitish-filter-field" class="form-control js-filterable-field js-navigation-enable" placeholder="Find or create a branch…">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Find or create a branch…" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/oasis-tcs/openc2-impl-https/blob/WD01/oc2-impl-https-v1.0.md"
               data-name="WD01"
               data-skip-pjax="true"
               rel="nofollow">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                WD01
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/oasis-tcs/openc2-impl-https/blob/master/oc2-impl-https-v1.0.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                master
              </span>
            </a>
        </div>

          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="select-menu-new-item-form js-new-item-form" action="/oasis-tcs/openc2-impl-https/branches" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="Ixy1/whbfCInnRwOxqqSyLDFl8dEr3DWQdj6Mnwuz8pjSYFjJ36mSaqcAhZT7R6d3zhY3q2B3mTC49SM6a6kQw==" />
            <input type="hidden" name="name" id="name" class="js-new-item-value">
            <input type="hidden" name="branch" id="branch" value="master">
            <input type="hidden" name="path" id="path" value="oc2-impl-https-v1.0.md">

            <button type="submit" class="width-full select-menu-item js-navigation-open js-navigation-item">
              <svg class="octicon octicon-git-branch select-menu-item-icon" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M10 5c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v.3c-.02.52-.23.98-.63 1.38-.4.4-.86.61-1.38.63-.83.02-1.48.16-2 .45V4.72a1.993 1.993 0 0 0-1-3.72C.88 1 0 1.89 0 3a2 2 0 0 0 1 1.72v6.56c-.59.35-1 .99-1 1.72 0 1.11.89 2 2 2 1.11 0 2-.89 2-2 0-.53-.2-1-.53-1.36.09-.06.48-.41.59-.47.25-.11.56-.17.94-.17 1.05-.05 1.95-.45 2.75-1.25S8.95 7.77 9 6.73h-.02C9.59 6.37 10 5.73 10 5zM2 1.8c.66 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2C1.35 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2zm0 12.41c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm6-8c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Create branch: <span class="js-new-item-name"></span></span>
                <span class="description">from ‘master’</span>
              </div>
            </button>
</form>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

    <div class="BtnGroup float-right">
      <a href="/oasis-tcs/openc2-impl-https/find/master"
            class="js-pjax-capture-input btn btn-sm BtnGroup-item"
            data-pjax
            data-hotkey="t">
        Find file
      </a>
      <clipboard-copy for="blob-path" class="btn btn-sm BtnGroup-item">
        Copy path
      </clipboard-copy>
    </div>
    <div id="blob-path" class="breadcrumb">
      <span class="repo-root js-repo-root"><span class="js-path-segment"><a data-pjax="true" href="/oasis-tcs/openc2-impl-https"><span>openc2-impl-https</span></a></span></span><span class="separator">/</span><strong class="final-path">oc2-impl-https-v1.0.md</strong>
    </div>
  </div>


  
  <div class="commit-tease">
      <span class="float-right">
        <a class="commit-tease-sha" href="/oasis-tcs/openc2-impl-https/commit/98d20ed725556162eeb2c454d0cace8af5cca9d1" data-pjax>
          98d20ed
        </a>
        <relative-time datetime="2018-09-19T19:25:26Z">Sep 19, 2018</relative-time>
      </span>
      <div>
        <a rel="contributor" data-skip-pjax="true" data-hovercard-user-id="26066504" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/dlemire60"><img class="avatar" src="https://avatars3.githubusercontent.com/u/26066504?s=40&amp;v=4" width="20" height="20" alt="@dlemire60" /></a>
        <a class="user-mention" rel="contributor" data-hovercard-user-id="26066504" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/dlemire60">dlemire60</a>
          <a data-pjax="true" title="Rename oc2-impl-https-v1.0-WD02.md to oc2-impl-https-v1.0.md" class="message" href="/oasis-tcs/openc2-impl-https/commit/98d20ed725556162eeb2c454d0cace8af5cca9d1">Rename oc2-impl-https-v1.0-WD02.md to oc2-impl-https-v1.0.md</a>
      </div>

    <div class="commit-tease-contributors">
      
<details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark float-left mr-2" id="blob_contributors_box">
  <summary class="btn-link" aria-haspopup="dialog"  >
    
    <span><strong>1</strong> contributor</span>
  </summary>
  <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast " aria-label="Users who have contributed to this file">
    <div class="Box-header">
      <button class="Box-btn-octicon btn-octicon float-right" type="button" aria-label="Close dialog" data-close-dialog>
        <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
      </button>
      <h3 class="Box-title">Users who have contributed to this file</h3>
    </div>
    
        <ul class="list-style-none overflow-auto">
            <li class="Box-row">
              <a class="link-gray-dark no-underline" href="/dlemire60">
                <img class="avatar mr-2" alt="" src="https://avatars3.githubusercontent.com/u/26066504?s=40&amp;v=4" width="20" height="20" />
                dlemire60
</a>            </li>
        </ul>

  </details-dialog>
</details>
      
    </div>
  </div>



  <div class="file">
    <div class="file-header">
  <div class="file-actions">

    <div class="BtnGroup">
      <a id="raw-url" class="btn btn-sm BtnGroup-item" href="/oasis-tcs/openc2-impl-https/raw/master/oc2-impl-https-v1.0.md">Raw</a>
        <a class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b" href="/oasis-tcs/openc2-impl-https/blame/master/oc2-impl-https-v1.0.md">Blame</a>
      <a rel="nofollow" class="btn btn-sm BtnGroup-item" href="/oasis-tcs/openc2-impl-https/commits/master/oc2-impl-https-v1.0.md">History</a>
    </div>

        <a class="btn-octicon tooltipped tooltipped-nw"
           href="x-github-client://openRepo/https://github.com/oasis-tcs/openc2-impl-https?branch=master&amp;filepath=oc2-impl-https-v1.0.md"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:windows">
            <svg class="octicon octicon-device-desktop" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
        </a>

          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form js-update-url-with-hash" action="/oasis-tcs/openc2-impl-https/edit/master/oc2-impl-https-v1.0.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="UsMs9gZOywyS9u2315XDlVTXvSNDGZMFgtLIcGlThE1BjH78LjqEdFGDi4kPEbi59sSG6kceBmotmg+31Fo4RA==" />
            <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
              aria-label="Edit this file" data-hotkey="e" data-disable-with>
              <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
            </button>
</form>
        <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form" action="/oasis-tcs/openc2-impl-https/delete/master/oc2-impl-https-v1.0.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="CNvMiAPgQJYIQpNgHXd4pmqpGDEV91rXLR5frtjXjrhPkiheufhd8NCjtIhlKMpeqXx5woVlRXGa+JgsvpnnnQ==" />
          <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Delete this file" data-disable-with>
            <svg class="octicon octicon-trashcan" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
          </button>
</form>  </div>

  <div class="file-info">
      628 lines (435 sloc)
      <span class="file-info-divider"></span>
    43.4 KB
  </div>
</div>

    
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><p><a target="_blank" rel="noopener noreferrer" href="/oasis-tcs/openc2-impl-https/blob/master/image_0.png"><img src="/oasis-tcs/openc2-impl-https/raw/master/image_0.png" alt="OASIS Logo" style="max-width:100%;"></a></p>
<hr>
<h1><a id="user-content-specification-for-transfer-of-openc2-messages-via-https-version-10" class="anchor" aria-hidden="true" href="#specification-for-transfer-of-openc2-messages-via-https-version-10"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Specification for Transfer of OpenC2 Messages via HTTPS Version 1.0</h1>
<h2><a id="user-content-working-draft-02" class="anchor" aria-hidden="true" href="#working-draft-02"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Working Draft 02</h2>
<h2><a id="user-content-19-september-2018" class="anchor" aria-hidden="true" href="#19-september-2018"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>19 September 2018</h2>
<h4><a id="user-content-specification-uris" class="anchor" aria-hidden="true" href="#specification-uris"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Specification URIs</h4>
<h5><a id="user-content-this-version" class="anchor" aria-hidden="true" href="#this-version"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>This Version:</h5>
<p><a href="http://docs.oasis-open.org/openc2/open-impl-https/v1.0/csd01/open-impl-https-v1.0-csd01.md" rel="nofollow">http://docs.oasis-open.org/openc2/open-impl-https/v1.0/csd01/open-impl-https-v1.0-csd01.md</a> (Authoritative)</p>
<p><a href="http://docs.oasis-open.org/openc2/open-impl-https/v1.0/csd01/open-impl-https-v1.0-csd01.html" rel="nofollow">http://docs.oasis-open.org/openc2/open-impl-https/v1.0/csd01/open-impl-https-v1.0-csd01.html</a></p>
<p><a href="http://docs.oasis-open.org/openc2/open-impl-https/v1.0/csd01/open-impl-https-v1.0-csd01.pdf" rel="nofollow">http://docs.oasis-open.org/openc2/open-impl-https/v1.0/csd01/open-impl-https-v1.0-csd01.pdf</a></p>
<h5><a id="user-content-previous-version" class="anchor" aria-hidden="true" href="#previous-version"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Previous Version:</h5>
<p>N/A</p>
<h5><a id="user-content-latest-version" class="anchor" aria-hidden="true" href="#latest-version"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Latest Version:</h5>
<p><a href="http://docs.oasis-open.org/openc2/open-impl-https/v1.0/open-impl-https-v1.0.md" rel="nofollow">http://docs.oasis-open.org/openc2/open-impl-https/v1.0/open-impl-https-v1.0.md</a> (Authoritative)</p>
<p><a href="http://docs.oasis-open.org/openc2/open-impl-https/v1.0/open-impl-https-v1.0.html" rel="nofollow">http://docs.oasis-open.org/openc2/open-impl-https/v1.0/open-impl-https-v1.0.html</a></p>
<p><a href="http://docs.oasis-open.org/openc2/open-impl-https/v1.0/open-impl-https-v1.0.pdf" rel="nofollow">http://docs.oasis-open.org/openc2/open-impl-https/v1.0/open-impl-https-v1.0.pdf</a></p>
<h5><a id="user-content-technical-committee" class="anchor" aria-hidden="true" href="#technical-committee"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Technical Committee:</h5>
<p><a href="https://www.oasis-open.org/committees/openc2/" rel="nofollow">OASIS Open Command and Control (OpenC2) TC</a></p>
<h5><a id="user-content-chairs" class="anchor" aria-hidden="true" href="#chairs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Chairs:</h5>
<ul>
<li>Joe Brule (<a href="mailto:jmbrule@nsa.gov">jmbrule@nsa.gov</a>), <a href="https://www.nsa.gov/" rel="nofollow">National Security Agency</a></li>
<li>Sounil Yu (<a href="mailto:sounil.yu@bankofamerica.com">sounil.yu@bankofamerica.com</a>), <a href="http://www.bankofamerica.com/" rel="nofollow">Bank of America</a></li>
</ul>
<h5><a id="user-content-editor" class="anchor" aria-hidden="true" href="#editor"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Editor:</h5>
<ul>
<li>David Lemire (<a href="mailto:dave.lemire@g2-inc.com">dave.lemire@g2-inc.com</a>), <a href="http://www.g2-inc.com/" rel="nofollow">G2, Inc.</a>)</li>
</ul>
<h5><a id="user-content-related-work" class="anchor" aria-hidden="true" href="#related-work"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Related work:</h5>
<p>This specification is related to:</p>
<ul>
<li><a href="http://docs.oasis-open.org/openc2/oc2ls/v1.0/oc2ls-v1.0.html" rel="nofollow">OpenC2 Language Specification</a></li>
<li><a href="http://docs.oasis-open.org/openc2/oc2slpf/v1.0/oc2slpf-v1.0.html" rel="nofollow">Stateless Packet Filtering Application Profile</a></li>
</ul>
<h2><a id="user-content-abstract" class="anchor" aria-hidden="true" href="#abstract"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Abstract:</h2>
<p>Open Command and Control (OpenC2) is a concise and extensible language to enable the command and control of cyber defense components, subsystems and/or systems in a manner that is agnostic of the underlying products, technologies, transport mechanisms or other aspects of the implementation. HTTP over TLS is a widely deployed transfer protocol that provides an authenticated, ordered,  lossless delivery of uniquely-identified messages.  This specification describes the use of HTTP over TLS as a transfer mechanism for OpenC2 messages.</p>
<h2><a id="user-content-status" class="anchor" aria-hidden="true" href="#status"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Status:</h2>
<p>This document was last revised or approved by the OASIS Open Command and Control (OpenC2) TC on the above date. The level of approval is also listed above. Check the "Latest version" location noted above for possible later revisions of this document. Any other numbered Versions and other technical work produced by the Technical Committee (TC) are listed at <a href="https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=openc2#technical" rel="nofollow">https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=openc2#technical</a>.</p>
<p>TC members should send comments on this specification to the TC's email list. Others should send comments to the TC's public comment list, after subscribing to it by following the instructions at the "<a href="https://www.oasis-open.org/committees/comments/index.php?wg_abbrev=openc2" rel="nofollow">Send A Comment</a>" button on the TC's web page at <a href="https://www.oasis-open.org/committees/openc2/" rel="nofollow">https://www.oasis-open.org/committees/openc2/</a>.</p>
<p>This specification is provided under the <a href="https://www.oasis-open.org/policies-guidelines/ipr#Non-Assertion-Mode" rel="nofollow">Non-Assertion</a> Mode of the <a href="https://www.oasis-open.org/policies-guidelines/ipr" rel="nofollow">OASIS IPR Policy</a>, the mode chosen when the Technical Committee was established. For information on whether any patents have been disclosed that may be essential to implementing this specification, and any offers of patent licensing terms, please refer to the Intellectual Property Rights section of the TC's web page (<a href="https://www.oasis-open.org/committees/openc2/ipr.php" rel="nofollow">https://www.oasis-open.org/committees/openc2/ipr.php</a>).</p>
<p>Note that any machine-readable content (<a href="https://www.oasis-open.org/policies-guidelines/tc-process#wpComponentsCompLang" rel="nofollow">Computer Language Definitions</a>) declared Normative for this Work Product is provided in separate plain text files. In the event of a discrepancy between any such plain text file and display content in the Work Product's prose narrative document(s), the content in the separate plain text file prevails.</p>
<h3><a id="user-content-citation-format" class="anchor" aria-hidden="true" href="#citation-format"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Citation format:</h3>
<p>When referencing this specification the following citation format should be used:</p>
<p><strong>[OpenC2-HTTPS-v1.0]</strong></p>
<p><em>Specification for Transfer of OpenC2 Messages via HTTPS Version 1.0</em>. Edited by David Lemire. 09 August 2018. OASIS Committee Specification Draft 02. <a href="http://docs.oasis-open.org/openc2/open-impl-https/v1.0/csd01/open-impl-https-v1.0-csd02.html" rel="nofollow">http://docs.oasis-open.org/openc2/open-impl-https/v1.0/csd02/open-impl-https-v1.0-csd02.html</a>.</p>
<p>Latest version: <a href="http://docs.oasis-open.org/openc2/open-impl-https/v1.0/open-impl-https-v1.0.html" rel="nofollow">http://docs.oasis-open.org/openc2/open-impl-https/v1.0/open-impl-https-v1.0.html</a>.</p>
<hr>
<h2><a id="user-content-notices" class="anchor" aria-hidden="true" href="#notices"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Notices</h2>
<p>Copyright © OASIS Open 2018. All Rights Reserved.</p>
<p>All capitalized terms in the following text have the meanings assigned to them in the OASIS Intellectual Property Rights Policy (the "OASIS IPR Policy"). The full <a href="https://www.oasis-open.org/policies-guidelines/ipr" rel="nofollow">Policy</a> may be found at the OASIS website.</p>
<p>This document and translations of it may be copied and furnished to others, and derivative works that comment on or otherwise explain it or assist in its implementation may be prepared, copied, published, and distributed, in whole or in part, without restriction of any kind, provided that the above copyright notice and this section are included on all such copies and derivative works. However, this document itself may not be modified in any way, including by removing the copyright notice or references to OASIS, except as needed for the purpose of developing any document or deliverable produced by an OASIS Technical Committee (in which case the rules applicable to copyrights, as set forth in the OASIS IPR Policy, must be followed) or as required to translate it into languages other than English.</p>
<p>The limited permissions granted above are perpetual and will not be revoked by OASIS or its successors or assigns.</p>
<p>This document and the information contained herein is provided on an "AS IS" basis and OASIS DISCLAIMS ALL WARRANTIES, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ANY WARRANTY THAT THE USE OF THE INFORMATION HEREIN WILL NOT INFRINGE ANY OWNERSHIP RIGHTS OR ANY IMPLIED WARRANTIES OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE.</p>
<p>OASIS requests that any OASIS Party or any other party that believes it has patent claims that would necessarily be infringed by implementations of this OASIS Committee Specification or OASIS Standard, to notify OASIS TC Administrator and provide an indication of its willingness to grant patent licenses to such patent claims in a manner consistent with the IPR Mode of the OASIS Technical Committee that produced this specification.</p>
<p>OASIS invites any party to contact the OASIS TC Administrator if it is aware of a claim of ownership of any patent claims that would necessarily be infringed by implementations of this specification by a patent holder that is not willing to provide a license to such patent claims in a manner consistent with the IPR Mode of the OASIS Technical Committee that produced this specification. OASIS may include such claims on its website, but disclaims any obligation to do so.</p>
<p>OASIS takes no position regarding the validity or scope of any intellectual property or other rights that might be claimed to pertain to the implementation or use of the technology described in this document or the extent to which any license under such rights might or might not be available; neither does it represent that it has made any effort to identify any such rights. Information on OASIS' procedures with respect to rights in any document or deliverable produced by an OASIS Technical Committee can be found on the OASIS website. Copies of claims of rights made available for publication and any assurances of licenses to be made available, or the result of an attempt made to obtain a general license or permission for the use of such proprietary rights by implementers or users of this OASIS Committee Specification or OASIS Standard, can be obtained from the OASIS TC Administrator. OASIS makes no representation that any information or list of intellectual property rights will at any time be complete, or that any claims in such list are, in fact, Essential Claims.</p>
<p>The name "OASIS" is a trademark of <a href="https://www.oasis-open.org/" rel="nofollow">OASIS</a>, the owner and developer of this specification, and should be used only to refer to the organization and its official outputs. OASIS welcomes reference to, and implementation and use of, specifications, while reserving the right to enforce its marks against misleading uses. Please see <a href="https://www.oasis-open.org/policies-guidelines/trademark" rel="nofollow">https://www.oasis-open.org/policies-guidelines/trademark</a> for above guidance.</p>
<hr>
<h2><a id="user-content-table-of-contents" class="anchor" aria-hidden="true" href="#table-of-contents"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Table of Contents</h2>
<p>[[TOC]]</p>
<hr>
<h1><a id="user-content-1-introduction" class="anchor" aria-hidden="true" href="#1-introduction"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1 Introduction</h1>
<p><em>This section in its entirety is non-normative.</em></p>
<p>OpenC2 is a set of specifications to achieve command and control of cyber defense functions.  These specifications include the OpenC2 Language Specification, Actuator Profiles, and Transfer Specifications.  The OpenC2 Language Specification and Actuator Profile(s) specifications focus on the standard at the origin and destination of the command while the transfer specifications focus on the protocols for the commands and responses in transit.</p>
<ul>
<li>The OpenC2 Language Specification [OpenC2-Lang-v1.0] provides the semantics for the essential elements of the language, the structure for commands and responses, and the schema that defines the proper syntax for the language elements that represents the command or response.</li>
<li>OpenC2 Actuator Profiles specify the subset of the OpenC2 language relevant in the context of specific actuator functions. Cyber defense components, devices, systems and/or instances may (in fact are likely) to implement multiple actuator profiles, such as Stateless Packet Filtering.  Actuator profiles extend the language by defining specifiers that identify the actuator to the required level of precision and may define command arguments that are relevant and/or unique to those actuator functions.</li>
<li>OpenC2 Transfer Specifications utilize existing protocols and standards to implement OpenC2 in specific environments. These standards are used for communications and security functions beyond the scope of the language, such as message transfer encoding, authentication, and end-to-end transport of OpenC2 messages.</li>
</ul>
<p>[OpenC2-Lang-v1.0] defines a language used to compose messages for command and control of cyber defense systems and components.  A message consists of a header (defined in this specification) and a payload (<em>defined</em> as a message body in the OpenC2 Language Specification Version 1.0 and <em>specified</em> in one or more actuator profiles). The language defines two payload structures:</p>
<ol>
<li><strong>Command</strong>: An instruction from one system known as the OpenC2 "Producer", to one or more systems, the OpenC2 "Consumer(s)", to act on the content of the command.</li>
<li><strong>Response</strong>: Any information captured or necessary to send back to the OpenC2 Producer  that issued the Command i.e., the OpenC2 Consumer’s response to the OpenC2 Producer.</li>
</ol>
<p>In general, there are two types of participants involved in the exchange of OpenC2 messages:</p>
<ol>
<li><strong>OpenC2 Producers</strong>: An OpenC2 Producer is an entity that creates commands to provide instruction to one or more systems to act in accordance with the content of the command. An OpenC2 Producer may receive and process responses in conjunction with a command.</li>
<li><strong>OpenC2 Consumers</strong>: An OpenC2 Consumer is an entity that receives and acts on an OpenC2 command.  An OpenC2 Consumer may create responses that provide any information captured or necessary to send back to the OpenC2 Producer.</li>
</ol>
<p>OpenC2 implementations integrate the related OpenC2 specifications described above with related industry specifications, protocols, and standards. Figure 1 depicts the relationships among OpenC2 specifications, and their relationships to other industry standards and environment-specific implementations of OpenC2. Note that the layering of implementation aspects in the diagram is notional, and not intended to preclude, e.g., the use of an application-layer message signature function to provide message source authentication and integrity.</p>
<p><a target="_blank" rel="noopener noreferrer" href="/oasis-tcs/openc2-impl-https/blob/master/image_1.png"><img src="/oasis-tcs/openc2-impl-https/raw/master/image_1.png" alt="no alt title" style="max-width:100%;"></a></p>
<p><strong>Figure 1 -- OpenC2 Documentation and Layering Model</strong></p>
<p>This specification defines the procedures and conventions used when employing Hypertext Transfer Protocol (HTTP) and Transport Layer Security (TLS) for the transport of OpenC2 command and response messages between OpenC2 Producers and Consumers. This specification is one of an expected portfolio of transfer specifications; implementers of OpenC2 should select one or more transfer specifications, consistent with the characteristics and requirements of their cyber ecosystem.</p>
<h2><a id="user-content-11-ipr-policy" class="anchor" aria-hidden="true" href="#11-ipr-policy"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.1 IPR Policy</h2>
<p>This specification is provided under the <a href="https://www.oasis-open.org/policies-guidelines/ipr#Non-Assertion-Mode" rel="nofollow">Non-Assertion</a> Mode of the <a href="https://www.oasis-open.org/policies-guidelines/ipr" rel="nofollow">OASIS IPR Policy</a>, the mode chosen when the Technical Committee was established. For information on whether any patents have been disclosed that may be essential to implementing this specification, and any offers of patent licensing terms, please refer to the Intellectual Property Rights section of the TC's web page (<a href="https://www.oasis-open.org/committees/openc2/ipr.php" rel="nofollow">https://www.oasis-open.org/committees/openc2/ipr.php</a>).</p>
<h2><a id="user-content-12-terminology" class="anchor" aria-hidden="true" href="#12-terminology"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.2 Terminology</h2>
<p>A list of acronyms is provided in Annex A.</p>
<h3><a id="user-content-121-requirement-keywords" class="anchor" aria-hidden="true" href="#121-requirement-keywords"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.2.1 Requirement Keywords</h3>
<p>The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [<a href="#RFC2119">RFC2119</a>] and [<a href="#RFC8174">RFC8174</a>] when, and only when, they appear in all capitals, as shown here.</p>
<h3><a id="user-content-122-font-style-and-size" class="anchor" aria-hidden="true" href="#122-font-style-and-size"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.2.2 Font Style and Size</h3>
<p>The following color, font and font style conventions are used in this document:</p>
<ul>
<li>All examples in this document are formatted in fixed font, with straight quotes, black text, a light grey background, and 4-space indentation.</li>
<li>Parts of the example may be omitted for conciseness and clarity. These omitted parts are denoted with an ellipse (...).</li>
</ul>
<p>Example:</p>
<pre><code>HTTP/1.1 200 OK
Date: Day, DD Mon YYYY HH:MM:SS GMT
Content-type: application/openc2-cmd+json;version=1.0
X-Correlation-ID: bf5t2ttrsc8r

{	
	"action": "query"
	"target": "command"
}
</code></pre>
<h2><a id="user-content-13-normative-references" class="anchor" aria-hidden="true" href="#13-normative-references"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.3 Normative References</h2>
<p><strong>[RFC2119]</strong></p>
<p>Bradner, S., "Key words for use in RFCs to Indicate Requirement Levels", BCP 14, RFC 2119, DOI 10.17487/RFC2119, March 1997, &lt;<a href="http://www.rfc-editor.org/info/rfc2119" rel="nofollow">http://www.rfc-editor.org/info/rfc2119</a>&gt;.</p>
<p><strong>[RFC2818]</strong></p>
<p>Rescorla, E., "HTTP Over TLS", RFC 2818, DOI 10.17487/RFC2818, May 2000, &lt;<a href="https://www.rfc-editor.org/info/rfc2818" rel="nofollow">https://www.rfc-editor.org/info/rfc2818</a>&gt;.</p>
<p><strong>[RFC5246]</strong></p>
<p>Dierks, T. and E. Rescorla, "The Transport Layer Security (TLS) Protocol Version 1.2", RFC 5246, DOI 10.17487/RFC5246, August 2008, &lt;<a href="https://www.rfc-editor.org/info/rfc5246" rel="nofollow">https://www.rfc-editor.org/info/rfc5246</a>&gt;.</p>
<p><strong>[RFC5280]</strong></p>
<p>Cooper, D., Santesson, S., Farrell, S., Boeyen, S., Housley, R., and W. Polk, "Internet X.509 Public Key Infrastructure Certificate and Certificate Revocation List (CRL) Profile", RFC 5280, DOI 10.17487/RFC5280, May 2008, <a href="https://www.rfc-editor.org/info/rfc5280" rel="nofollow">https://www.rfc-editor.org/info/rfc5280</a>.</p>
<p><strong>[RFC7230]</strong></p>
<p>Fielding, R., Ed., and J. Reschke, Ed., "Hypertext Transfer Protocol (HTTP/1.1): Message Syntax and Routing", RFC 7230, DOI 10.17487/RFC7230, June 2014, <a href="https://www.rfc-editor.org/info/rfc7230" rel="nofollow">https://www.rfc-editor.org/info/rfc7230</a>.</p>
<p><strong>[RFC7231]</strong></p>
<p>Fielding, R., Ed., and J. Reschke, Ed., "Hypertext Transfer Protocol (HTTP/1.1): Semantics and Content", RFC 7231, DOI 10.17487/RFC7231, June 2014, <a href="https://www.rfc-editor.org/info/rfc7231" rel="nofollow">https://www.rfc-editor.org/info/rfc7231</a>.</p>
<p><strong>[RFC7235]</strong></p>
<p>Fielding, R., Ed., and J. Reschke, Ed., "Hypertext Transfer Protocol (HTTP/1.1): Authentication", RFC 7235, DOI 10.17487/RFC7235, June 2014, <a href="https://www.rfc-editor.org/info/rfc7235" rel="nofollow">https://www.rfc-editor.org/info/rfc7235</a>.</p>
<p><strong>[RFC7540]</strong></p>
<p>Belshe, M., Peon, R., and Thompson, M., "Hypertext Transfer Protocol Version 2 (HTTP/2)", RFC 7540, DOI 10.17487/RFC7540, May 2015, &lt;<a href="https://www.rfc-editor.org/info/rfc7540" rel="nofollow">https://www.rfc-editor.org/info/rfc7540</a>&gt;.</p>
<p><strong>[RFC8174]</strong></p>
<p>Leiba, B., "Ambiguity of Uppercase vs Lowercase in RFC 2119 Key Words", BCP 14, RFC 8174, DOI 10.17487/RFC8174, May 2017, &lt;<a href="http://www.rfc-editor.org/info/rfc8174" rel="nofollow">http://www.rfc-editor.org/info/rfc8174</a>&gt;.</p>
<p><strong>[RFC8446]</strong></p>
<p>Recorla, E., "The Transport Layer Security (TLS) Protocol Version 1.3", RFC 8446, DOI 10.17487/RFC8446, August 2018, &lt;<a href="http://www.rfc-editor.org/info/rfc8446" rel="nofollow">http://www.rfc-editor.org/info/rfc8446</a>&gt;</p>
<p><strong>[OpenC2-Lang-v1.0]</strong></p>
<p><em>Open Command and Control (OpenC2) Language Specification Version 1.0</em>.</p>
<p>Edited by Jason Romano and Duncan Sparrell.</p>
<p>xx September 2018. OASIS Working Draft 08. oasis-to-fill-in-link.html.</p>
<p>Latest version: <a href="http://docs.oasis-open.org/openc2/oc2ls/v1.0/oc2ls-v1.0.html" rel="nofollow">http://docs.oasis-open.org/openc2/oc2ls/v1.0/oc2ls-v1.0.html</a>.</p>
<h2><a id="user-content-14-non-normative-references" class="anchor" aria-hidden="true" href="#14-non-normative-references"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.4 Non-Normative References</h2>
<p><strong>[RFC3205]</strong></p>
<p>Moore, K., "On the use of HTTP as a Substrate", BCP 56, RFC 3205, DOI 10.17487/RFC3205, February 2002, <a href="https://www.rfc-editor.org/info/rfc3205" rel="nofollow">https://www.rfc-editor.org/info/rfc3205</a>.</p>
<p><strong>[RFC6546]</strong></p>
<p>Trammell, B., "Transport of Real-time Inter-network Defense (RID) Messages over HTTP/TLS", RFC 6546, DOI 10.17487/RFC6546, April 2012, <a href="https://www.rfc-editor.org/info/rfc6546" rel="nofollow">https://www.rfc-editor.org/info/rfc6546</a>.</p>
<p><strong>[RFC7525]</strong></p>
<p>Sheffer, Y., Holz, R., and P. Saint-Andre, "Recommendations for Secure Use of Transport Layer Security (TLS) and Datagram Transport Layer Security (DTLS)", BCP 195, RFC 7525, DOI 10.17487/RFC7525, May 2015, <a href="https://www.rfc-editor.org/info/rfc7525" rel="nofollow">https://www.rfc-editor.org/info/rfc7525</a>.</p>
<p><strong>[SLPF]</strong></p>
<p><em>Open Command and Control (OpenC2) Profile for Stateless Packet Filtering Version 1.0</em>.</p>
<p>Edited by Joe Brule, Duncan Sparrell and Alex Everett.</p>
<p>xx September 2018. OASIS Working Draft 01. oasis-to-fill-in-link.html.</p>
<p>Latest version: <a href="http://docs.oasis-open.org/openc2/oc2slpf/v1.0/oc2slpf-v1.0.html" rel="nofollow">http://docs.oasis-open.org/openc2/oc2slpf/v1.0/oc2slpf-v1.0.html</a></p>
<h2><a id="user-content-15-overview" class="anchor" aria-hidden="true" href="#15-overview"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.5 Overview</h2>
<p>This document specifies the use of Hypertext Transfer Protocol (HTTP) over Transport Layer Security (TLS) as a transport mechanism for OpenC2 messages; this HTTP/TLS layering is typically referred to as HTTPS [RFC2818]. As described in [RFC3205], HTTP has become a common "substrate" for information transfer for other application-level protocols. The broad availability of HTTP makes it a useful option for OpenC2 message transport in support of prototyping, interoperability testing, and for operational use in environments where appropriate security protections can be provided. Similarly, TLS is a mature and widely-used protocol for securing information transfers in TCP/IP network environments. This specification provides guidance to the OpenC2 implementation community when utilizing HTTPS for OpenC2 message transport. It includes guidance for selection of TLS versions and options suitable for use with OpenC2.</p>
<h2><a id="user-content-16-suitability" class="anchor" aria-hidden="true" href="#16-suitability"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.6 Suitability</h2>
<p>This OpenC2 over HTTPS transfer specification is suitable for operational environments where:</p>
<ul>
<li>Connectivity between OpenC2 producers and OpenC2 consumers is:
<ul>
<li>Highly available, with infrequent network outages</li>
<li>Of sufficient bandwidth that no appreciable message delays or dropped packets are experienced</li>
</ul>
</li>
<li>In-band negotiation of a connection initiated by either producer or consumer is possible without requiring an out-of-band signalling network.</li>
<li>The overhead of HTTPS is acceptable (e.g., multiple OpenC2 command / response exchanges can be passed through a single HTTPS connection).</li>
</ul>
<p>An additional application for this transfer specification is interoperability test environments.</p>
<h1><a id="user-content-2-operating-models" class="anchor" aria-hidden="true" href="#2-operating-models"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2 Operating models</h1>
<p><em>This section in its entirety is non-normative.</em></p>
<p>This section describes the operating models associated with the available assignments of endpoint roles with regard to OpenC2 and HTTP.</p>
<h2><a id="user-content-21-endpoint-definitions" class="anchor" aria-hidden="true" href="#21-endpoint-definitions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.1 	Endpoint Definitions</h2>
<p>Each endpoint of an OpenC2-over-HTTPS interaction has both an OpenC2 role and an HTTP function. Ideally OpenC2 Consumers will be HTTP listeners so that they can accept connections and receive unsolicited commands from OpenC2 Producers. With this approach OpenC2 Producers act as 'HTTP clients' and transmit commands to Consumers.</p>
<p>In some environments, networking considerations may limit or preclude this configuration. For example, if the OpenC2 Consumer is located behind a router that performs network port and/or address translation, it may not be practicable for the Producer to contact an HTTP server listening on behalf of the Consumer. In these cases, each OpenC2 endpoint must act as both an HTTP client and a server.</p>
<p>One example of using HTTP as a substrate, [RFC6546], <em>Transport of Real-time Inter-network Defense (RID) Messages over HTTP/TLS</em>, addresses this situation by specifying an arrangement where each RID server is both an HTTP/TLS server and an HTTP/TLS client. Given the anticipated range of implementation environments for OpenC2, a more flexible approach appears justified, so this specification allows for three implementation configurations:</p>
<ul>
<li>The OpenC2 Consumer is the HTTP server</li>
<li>The OpenC2 Producer is the HTTP server</li>
<li>Both OpenC2 Producer and Consumer are HTTP servers</li>
</ul>
<p>Where possible, the configuration where the OpenC2 Consumer is the HTTP server is preferred, as it aligns OpenC2 command / response messaging with HTTP’s request / response structure.</p>
<p>The following sections briefly summarize each of these operating models. Specifications for how the models are implemented are provided in Section 3 and example interactions are described in Annex B.</p>
<h2><a id="user-content-22-openc2-consumer-as-the-http-server" class="anchor" aria-hidden="true" href="#22-openc2-consumer-as-the-http-server"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.2 OpenC2 Consumer as the HTTP server</h2>
<p>Figure 2 illustrates the configuration where the OpenC2 Consumer operates an HTTP server. In this configuration, a Producer that needs to send OpenC2 commands initiates a TCP connection to the Consumer. Once the TCP connection is created, a TLS session is initiated to authenticate the endpoints and provide connection confidentiality. The Producer can then issue OpenC2 commands by sending HTTP requests using the POST method, with Consumer OpenC2 responses returned in the HTTP response.</p>
<p><a target="_blank" rel="noopener noreferrer" href="/oasis-tcs/openc2-impl-https/blob/master/image_2.png"><img src="/oasis-tcs/openc2-impl-https/raw/master/image_2.png" alt="no alt title" style="max-width:100%;"></a></p>
<p><strong>Figure 2 -- OpenC2 Consumer as HTTP Server</strong></p>
<h2><a id="user-content-23-openc2-producer-as-http-server" class="anchor" aria-hidden="true" href="#23-openc2-producer-as-http-server"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.3 OpenC2 Producer as HTTP server</h2>
<p>Figure 3 illustrates the configuration where the OpenC2 Producer operates an HTTP server. In this configuration, a Consumer that has been configured to request and accept OpenC2 commands from a particular Producer initiates a TCP connection to the Producer. Once the TCP connection is created, a TLS session is initiated to authenticate the endpoints and provide connection confidentiality. In this configuration, the exchange of OpenC2 commands and responses is driven by the Consumer using simple HTTP polling with the Producer.</p>
<p><a target="_blank" rel="noopener noreferrer" href="/oasis-tcs/openc2-impl-https/blob/master/image_3.png"><img src="/oasis-tcs/openc2-impl-https/raw/master/image_3.png" alt="no alt title" style="max-width:100%;"></a></p>
<p><strong>Figure 3 -- OpenC2 Producer as HTTP Server</strong></p>
<h2><a id="user-content-24-producer-and-consumer-as-httptls-servers" class="anchor" aria-hidden="true" href="#24-producer-and-consumer-as-httptls-servers"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.4 Producer and Consumer as HTTP/TLS Servers</h2>
<p>The configuration where both Producer and Consumer operate an HTTP server is operationally similar to the configuration where only the Consumer operates an HTTP server.  In this configuration, a Producer that needs to send OpenC2 commands initiates a TCP connection to the Consumer. Once the TCP connection is created, a TLS session is initiated to authenticate the endpoints and provide connection confidentiality. The Producer can then issue OpenC2 commands by sending HTTP requests using the POST method, with Consumer OpenC2 responses returned in the HTTP response.</p>
<p>When the Consumer needs to send the Producer an OpenC2 response with updated status, it initiates a TCP connection to the Producer. Once the TCP connection is created, a TLS session is initiated to authenticate the endpoints and provide connection confidentiality. The Consumer can then transmit OpenC2 response messages using the HTTP POST method.</p>
<h1><a id="user-content-3-protocol-mappings" class="anchor" aria-hidden="true" href="#3-protocol-mappings"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3 Protocol mappings</h1>
<p>The section defines the requirements for using HTTP and TLS with OpenC2, including general requirements and protocol mappings for the three operating configurations described in Section 2.</p>
<h2><a id="user-content-31-layering-overview" class="anchor" aria-hidden="true" href="#31-layering-overview"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.1 	Layering Overview</h2>
<p><em>This section is non-normative.</em></p>
<p>When using HTTPS for OpenC2 message transfer, the layering model is:</p>
<table>
<thead>
<tr>
<th align="left">Layer</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">OpenC2 Content</td>
<td align="left">The OpenC2 Language Specification defines the overall OpenC2 language, and the Actuator Profile(s) implemented by any particular endpoint scopes the OpenC2 actions, targets, arguments, and specifiers that apply when commanding that type of Actuator.</td>
</tr>
<tr>
<td align="left">Serialization</td>
<td align="left">Serialization converts internal representations of OpenC2 content into a form that can be transmitted and received. The OpenC2 default serialization is JSON.</td>
</tr>
<tr>
<td align="left">Message</td>
<td align="left">The message layer provides a content- and transport-independent mechanism for conveying requests, responses and notifications.   A message consists of content plus a set of meta items such as content type and version, sender, timestamp, and correlation id.  This layer maps the transport-independent definition of each message element to its transport-specific on-the-wire representation.  Note that notification messages are defined here for completeness even though OpenC2 does not currently define any notification content.</td>
</tr>
<tr>
<td align="left">HTTP</td>
<td align="left">The HTTP layer is responsible for conveying request, response, and notification  messages, as described in this specification.</td>
</tr>
<tr>
<td align="left">TLS</td>
<td align="left">The TLS layer is responsible for authentication of connection endpoints and confidentiality and integrity of transferred messages.</td>
</tr>
<tr>
<td align="left">Lower Layer Transport</td>
<td align="left">The lower protocol layers are responsible for end-to-end delivery of messages. TCP/IP is the most common suite of lower layer protocols used with HTTPS.</td>
</tr></tbody></table>
<h2><a id="user-content-32-general-requirements" class="anchor" aria-hidden="true" href="#32-general-requirements"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.2 General Requirements</h2>
<p>This section defines serialization, HTTP, and TLS requirements that apply regardless of operating model.</p>
<h3><a id="user-content-321-serialization-and-content-types" class="anchor" aria-hidden="true" href="#321-serialization-and-content-types"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.2.1 Serialization and Content Types</h3>
<p><em>This section is normative.</em></p>
<p>While the OpenC2 language is agnostic of serialization, when transferring OpenC2 messages over HTTP/TLS as described in this specification, the default JSON verbose serialization described in [OpenC2-Lang-v1.0] is used.</p>
<p>As described in [OpenC2-Lang-v1.0], transfer protocols must convey message elements. Two content types are defined here to support that requirement:</p>
<ul>
<li>OpenC2 Command:
<ul>
<li>msg_type: "request"</li>
<li>Content type: application/openc2-cmd+json;version=1.0</li>
</ul>
</li>
<li>OpenC2 Response:
<ul>
<li>Msg_type: "response"</li>
<li>Content type: application/openc2-rsp+json;version=1.0</li>
</ul>
</li>
</ul>
<h3><a id="user-content-322-http-usage" class="anchor" aria-hidden="true" href="#322-http-usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.2.2 HTTP Usage</h3>
<p><em>This section is normative.</em></p>
<p>OpenC2 Consumers MUST be HTTP listeners, to implement the operating model described in Section 2.2.  OpenC2 Producers SHOULD be HTTP listeners, to support the operating models described in Sections 2.3 and 2.4. OpenC2 Producers and Consumers acting as HTTP listeners SHOULD listen on port 443, the registered port for HTTPS.</p>
<p>OpenC2 endpoints MUST implement all HTTP functionality required by this specification in accordance with HTTP/1.1 ([RFC7230], <em>et. al.</em>). As described in the following table, the only HTTP request methods utilized are GET and POST.</p>
<table>
<thead>
<tr>
<th align="left">HTTP Method</th>
<th align="left">Utilized</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">GET</td>
<td align="left">Yes</td>
</tr>
<tr>
<td align="left">HEAD</td>
<td align="left">No</td>
</tr>
<tr>
<td align="left">POST</td>
<td align="left">Yes</td>
</tr>
<tr>
<td align="left">PUT</td>
<td align="left">No</td>
</tr>
<tr>
<td align="left">DELETE</td>
<td align="left">No</td>
</tr>
<tr>
<td align="left">CONNECT</td>
<td align="left">No</td>
</tr>
<tr>
<td align="left">OPTIONS</td>
<td align="left">No</td>
</tr>
<tr>
<td align="left">TRACE</td>
<td align="left">No</td>
</tr></tbody></table>
<p>Each HTTP message body MUST contain only a single OpenC2 command or response message. This does not preclude a Producer and Consumer exchanging multiple OpenC2 command and response messages over time during a single HTTPS session. Depending on the set-up, a server and client can have multiple connections, but a sequence of OpenC2 interactions can spread over multiple connections. In some cases the connection may drop, but the session remains open (in an idle state).</p>
<p>All HTTP request and response messages containing OpenC2 payloads SHOULD include the "Cache-control:" header with a value of "no-cache".</p>
<h3><a id="user-content-323-tls-usage" class="anchor" aria-hidden="true" href="#323-tls-usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.2.3 TLS Usage</h3>
<p><em>This section is normative.</em></p>
<p>HTTPS, the transmission of HTTP over TLS, is specified in Section 2 of [RFC2818]. OpenC2 endpoints MUST use TLS version 1.2 [RFC5246] or higher for confidentiality, identification, and authentication when sending OpenC2 messages over HTTPS, and SHOULD use TLS Version 1.3 [RFC8446].</p>
<p>OpenC2 endpoints MUST NOT support any version of TLS prior to v1.2 and MUST NOT support any version of Secure Sockets Layer (SSL).</p>
<p>The implementation and use of TLS SHOULD align with the best currently available security guidance, such as that provided in [RFC7525]/BCP 195.</p>
<p>The TLS session MUST use non-NULL ciphersuites for authentication, integrity, and confidentiality.  Sessions MAY be renegotiated within these constraints.</p>
<p>OpenC2 endpoints supporting TLS v1.2 MUST NOT use any of the blacklisted ciphersuites identified in Appendix A of [RFC7540].</p>
<p>OpenC2 endpoints supporting TLS 1.3 MUST NOT implement zero round trip time resumption (0-RTT).</p>
<p>When deployed in an operational environment, OpenC2 endpoints MUST support basic authentication and SHOULD support mutual authentication.  When mutual authentication is used, endpoints MUST perform  full path validation on each certificate, as defined in [RFC5280].</p>
<h2><a id="user-content-33-openc2-consumer-as-httptls-server" class="anchor" aria-hidden="true" href="#33-openc2-consumer-as-httptls-server"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.3 OpenC2 Consumer as HTTP/TLS Server</h2>
<p><em>This section is normative.</em></p>
<p>This section defines HTTP requirements that apply when the OpenC2 consumer is the HTTP server.</p>
<p>When the OpenC2 Consumer is the HTTP server, the Producer is able to initiate a connection to a specific Consumer and directly transmit OpenC2 messages containing commands; the HTTP POST method is used, with the OpenC2 command body contained in the POST body.</p>
<p>The contents of the X-Correlation-ID HTTP header MUST match the command-id in the OpenC2 message that is in the payload body, if one is present in the payload.</p>
<p>The following HTTP request headers MUST be populated when transferring OpenC2 commands:</p>
<ul>
<li>Host:  host name of HTTP server:listening port number (if other than port 443)</li>
<li>Content-type:  application/openc2-cmd+json;version=1.0</li>
<li>Date:  date-time in HTTP-date format as defined by RFC 7231</li>
<li>X-Correlation-ID: contains the OpenC2 command-id</li>
</ul>
<p>The following HTTP response headers MUST be populated when transferring OpenC2 responses:</p>
<ul>
<li>Date: date-time in HTTP-date format as defined by RFC 7231</li>
<li>Content-type: application/openc2-rsp+json;version=1.0</li>
<li>X-Correlation-ID: contains the OpenC2 command-id</li>
</ul>
<p>Example messages can be found in Annex B, section B.1.</p>
<h2><a id="user-content-34-openc2-producer-as-httptls-server" class="anchor" aria-hidden="true" href="#34-openc2-producer-as-httptls-server"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.4 OpenC2 Producer as HTTP/TLS Server</h2>
<p><em>This section is normative.</em></p>
<p>This section defines HTTP requirements that apply when the OpenC2 Producer is the HTTP server.</p>
<p>When the OpenC2 Producer is the HTTP server, the Consumer must poll for commands.  The Consumer checks for commands by polling the Producer with the HTTP GET method. The polling interval is a matter of Consumer configuration. The interval SHOULD be short enough to meet latency requirements, but long enough to avoid excessive load on the server..</p>
<p>Since OpenC2 responses may not always be available immediately, the Producer may be in any of four states with respect to a particular Consumer when that Consumer polls:</p>
<ul>
<li>Producer has both commands and status queries</li>
<li>Producer has commands but no status queries</li>
<li>Producer has status queries but no commands</li>
<li>Producer has neither commands nor status queries</li>
</ul>
<p>The intent is that the Producer is able to transmit all commands and status queries to the Consumer and receive corresponding responses in a contiguous sequence of exchanges. To accomplish this, the Consumer MUST poll the Producer using the HTTP GET method to inquire whether the Producer has traffic for the Consumer. Polling messages sent by a Consumer MUST NOT contain an OpenC2 command-id and MUST NOT populate the HTTP X-Correlation-ID header field.  Polling messages sent by a Consumer SHOULD populate the Accept: header with 'application/openc2-cmd+json;version=1.0'. The Producer will respond to each GET request with an HTTP response with code 200, OK, and a single command or status query in the response body, until the Producer's set of commands and queries is exhausted. The order in which the Producer sends multiple commands and/or status queries is undefined. After each exchange, the Consumer polls again without delay, until it receives an HTTP response with code 204, No Content.</p>
<p>The following HTTP request headers MUST be populated when a Producer responds to a Consumer's polling request with an OpenC2 command:</p>
<ul>
<li>Host:  host name of HTTP server:listening port number (if other than port 443)</li>
<li>Content-type:  application/openc2-cmd+json;version=1.0</li>
<li>Date:  date-time in HTTP-date format as defined by RFC 7231</li>
<li>X-Correlation-ID: contains the OpenC2 command-id</li>
</ul>
<p>When the Producer sends a command in response to a Consumer poll, the Producer MUST  populate the HTTP X-Correlation-ID field with the command-id value the Producer has assigned to the command. When the Producer sends a status query in response to a Consumer poll, the command-id in the X-Correlation-ID field MUST contain the command-id the Producer assigned when the command was originally sent.</p>
<p>The following HTTP response headers MUST be populated by a Consumer when transmitting OpenC2 responses:</p>
<ul>
<li>Date: date-time in HTTP-date format as defined by RFC 7231</li>
<li>Content-type: application/openc2-rsp+json;version=1.0</li>
<li>X-Correlation-ID: contains the OpenC2 command-id of the command to which this response applies</li>
</ul>
<p>Example messages can be found in Annex B, section B.2.</p>
<h2><a id="user-content-35-openc2-producer-and-openc2-consumer-as-httptls-servers" class="anchor" aria-hidden="true" href="#35-openc2-producer-and-openc2-consumer-as-httptls-servers"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.5 OpenC2 Producer and OpenC2 Consumer as HTTP/TLS Servers</h2>
<p><em>This section is normative.</em></p>
<p>When both the Producer and the Consumer act as HTTP servers, the Producer contacts the Consumer to send commands and status queries as described in Section 3.3. If the Consumer needs to send an OpenC2 response to the Producer asynchronously, it uses the process described in Section 3.4, initiating the connection and using the HTTP POST method to send the OpenC2 response message.</p>
<p>Example messages for Producers sending OpenC2 commands can be found in Annex B, section B.1. Example messages for Consumers asynchronously posting response messages can be found in Annex B, section B.2.</p>
<h1><a id="user-content-4-conformance" class="anchor" aria-hidden="true" href="#4-conformance"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4 Conformance</h1>
<p>A conformant implementation of this transfer specification MUST:</p>
<ol>
<li>Support JSON serialization as specified in Section 3.2.1</li>
<li>Transfer OpenC2 messages using the content types defined in Section 3.2.1 appropriately, as specified in Sections 3.3 and 3.4</li>
<li>Listen for HTTPS connections as specified in Section 3.2.2.</li>
<li>Use HTTP GET and POST methods as specified in Sections 3.2.2, 3.3, and 3.4, and no other HTTP methods</li>
<li>Ensure HTTP request and response messages only contain a single OpenC2 message, as specified in Section 3.2.2</li>
<li>Implement TLS in accordance with the requirements and restrictions specified in Sections 3.2.3 and 3.2.3.1</li>
<li>Employ HTTP methods to send and receive OpenC2 messages as specified in Sections 3.3 and 3.4</li>
<li>Employ only the HTTP response codes as specified in Sections 3.3 and 3.4</li>
<li>Instantiate the message elements defined in Table 3.2 of [OpenC2-Lang-v1.0] as follows:</li>
</ol>
<table>
<thead>
<tr>
<th align="left">Name</th>
<th align="left">HTTPS Implementation</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">content</td>
<td align="left">JSON verbose serialization of OpenC2 commands and responses carried in the HTTP message body</td>
</tr>
<tr>
<td align="left">content_type<br>msg_type</td>
<td align="left">Combined and carried in the HTTP Content-type and Accepted headers:<br>    Command:  application/openc2-cmd+json;version=1.0<br>    Response:  application/openc2-rsp+json;version=1.0</td>
</tr>
<tr>
<td align="left">correlation_id</td>
<td align="left">Carried in HTTP X-Correlation-ID header</td>
</tr>
<tr>
<td align="left">created</td>
<td align="left">Carried in the HTTP Date header</td>
</tr>
<tr>
<td align="left">from</td>
<td align="left">Populated with the authenticated identity of the peer entity, consistent with the configured authentication scheme.</td>
</tr>
<tr>
<td align="left">to</td>
<td align="left">Carried in the HTTP Host header</td>
</tr></tbody></table>
<p><strong>Table 4.1 - Message Element Implementation</strong></p>
<h1><a id="user-content-annex-a-acronyms" class="anchor" aria-hidden="true" href="#annex-a-acronyms"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Annex A. Acronyms</h1>
<table>
<thead>
<tr>
<th align="left">Term</th>
<th align="left">Expansion</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">0-RTT</td>
<td align="left">Zero Round Trip Time</td>
</tr>
<tr>
<td align="left">API</td>
<td align="left">Application Programming Interface</td>
</tr>
<tr>
<td align="left">HTTP</td>
<td align="left">Hypertext Transfer Protocol</td>
</tr>
<tr>
<td align="left">HTTPS</td>
<td align="left">HTTP over TLS</td>
</tr>
<tr>
<td align="left">IETF</td>
<td align="left">Internet Engineering Task Force</td>
</tr>
<tr>
<td align="left">IPR</td>
<td align="left">Intellectual Property Rights</td>
</tr>
<tr>
<td align="left">JSON</td>
<td align="left">JavaScript Object Notation</td>
</tr>
<tr>
<td align="left">RFC</td>
<td align="left">Request For Comment</td>
</tr>
<tr>
<td align="left">RID</td>
<td align="left">Real-time Inter-network Defense</td>
</tr>
<tr>
<td align="left">TC</td>
<td align="left">Technical Committee</td>
</tr>
<tr>
<td align="left">TCP</td>
<td align="left">Transmission Control Protocol</td>
</tr>
<tr>
<td align="left">TLS</td>
<td align="left">Transport Layer Security</td>
</tr></tbody></table>
<h1><a id="user-content-annex-b-examples" class="anchor" aria-hidden="true" href="#annex-b-examples"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Annex B. Examples</h1>
<p>OpenC2 commands and responses need to be transmitted with certain relevant head information (i.e., metadata), as described in Section 3.2 of [OpenC2-Lang-v1.0]<strong>.</strong> When sending OpenC2 commands and responses over HTTP/TLS, the OpenC2 message elements are handled as described in Table 4.2.</p>
<p>A Request-URI ending in /openc2 is used in all example HTTP requests.</p>
<h2><a id="user-content-b1-http-request--response-examples-consumer-as-http-server" class="anchor" aria-hidden="true" href="#b1-http-request--response-examples-consumer-as-http-server"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>B.1 HTTP Request / Response Examples: Consumer as HTTP Server</h2>
<p>This section presents the HTTP message structures used when the OpenC2 Consumer acts as the HTTP listener.</p>
<h3><a id="user-content-b11-producer-http-post-with-openc2-command" class="anchor" aria-hidden="true" href="#b11-producer-http-post-with-openc2-command"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>B.1.1 Producer HTTP POST with OpenC2 Command</h3>
<p>Example message:</p>
<pre><code>POST /openc2 HTTP/1.1
Host: oc2consumer.company.net
Content-type: application/openc2-cmd+json;version=1.0
Date: Day, DD Mon YYYY HH:MM:SS GMT
X-Correlation-ID: shq5x2dmgayf

{	
	"action": ...
	"target": …
	"args": ...
}
</code></pre>
<h3><a id="user-content-b12-consumer-http-response-with-openc2-response" class="anchor" aria-hidden="true" href="#b12-consumer-http-response-with-openc2-response"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>B.1.2 Consumer HTTP Response with OpenC2 Response</h3>
<p>Example message:</p>
<pre><code>HTTP/1.1 200 OK
Date: Day, DD Mon YYYY HH:MM:SS GMT
Content-type: application/openc2-rsp+json;version=1.0
X-Correlation-ID: shq5x2dmgayf

{	
	"id_ref": ...
	"status": 200
	"status_text": ...
	"results": { ...
}
</code></pre>
<h2><a id="user-content-b2-http-request--response-examples-producer-as-http-server" class="anchor" aria-hidden="true" href="#b2-http-request--response-examples-producer-as-http-server"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>B.2 HTTP Request / Response Examples: Producer as HTTP Server</h2>
<p>This section presents the HTTP message structures used when the OpenC2 Producer acts as the HTTP listener.</p>
<h3><a id="user-content-b21-consumer-polls-producer-with-http-get" class="anchor" aria-hidden="true" href="#b21-consumer-polls-producer-with-http-get"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>B.2.1 Consumer Polls Producer with HTTP GET</h3>
<p>Consumers use the HTTP GET method to poll a Producer for available commands and status queries. No message body is required.</p>
<pre><code>GET /openc2 HTTP/1.1
Host: oc2producer.company.net
Accept: application/openc2-cmd+json;version=1.0
Cache-control: no-cache
Date: Day, DD Mon YYYY HH:MM:SS GMT

</code></pre>
<h3><a id="user-content-b22-producer-http-response-with-openc2-command" class="anchor" aria-hidden="true" href="#b22-producer-http-response-with-openc2-command"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>B.2.2 Producer HTTP Response with OpenC2 Command</h3>
<p>If the Producer has commands for the Consumer, the Producer returns HTTP 200, Success and places an OpenC2 message with a command body in the body of the HTTP response. This signals the Consumer to process the command, send an HTTP POST with its OpenC2 response message, and then poll again for additional messages from the Producer.</p>
<pre><code>HTTP/1.1 200 OK
Date: Day, DD Mon YYYY HH:MM:SS GMT
Content-type: application/openc2-cmd+json;version=1.0
X-Correlation-ID: bf5t2ttrsc8r

{	
"action": ...
	"target": ...
	"actuator": ...
	"args": ...
}
</code></pre>
<h3><a id="user-content-b23-producer-http-response-with-openc2-status-query" class="anchor" aria-hidden="true" href="#b23-producer-http-response-with-openc2-status-query"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>B.2.3 Producer HTTP Response with OpenC2 Status Query</h3>
<p>If the Producer has status queries for the Consumer, the Producer returns HTTP 200, Success and places an OpenC2 message with a command to query status in the body of the HTTP response. The id in the OpenC2 message header identifies the command for which updated status is requested. This signals the Consumer to process the status query, send an HTTP POST with its OpenC2 response message, and then poll again for additional messages from the Producer.</p>
<pre><code>HTTP/1.1 200 OK
Date: Day, DD Mon YYYY HH:MM:SS GMT
Content-type: application/openc2-cmd+json;version=1.0
X-Correlation-ID: bf5t2ttrsc8r

{	
	"action": "query"
	"target": "command"
}
</code></pre>
<h3><a id="user-content-b24-producer-http-response-with-no-content" class="anchor" aria-hidden="true" href="#b24-producer-http-response-with-no-content"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>B.2.4 Producer HTTP Response with No Content</h3>
<p>If the Producer has no commands or status queries for the Consumer, the Producer returns HTTP 204, No Content. This signals the Consumer to return to its default polling interval.</p>
<pre><code>HTTP/1.1 204 OK
Date: Day, DD Mon YYYY HH:MM:SS GMT

</code></pre>
<h3><a id="user-content-b25-consumer-http-post-with-openc2-response" class="anchor" aria-hidden="true" href="#b25-consumer-http-post-with-openc2-response"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>B.2.5 Consumer HTTP POST with OpenC2 Response</h3>
<p>Consumers use the HTTP POST method to send OpenC2 response messages to the Producer.</p>
<pre><code>POST /openc2 HTTP/1.1
Host: oc2producer.company.net
Content-type: application/openc2-rsp+json;version=1.0
Date: Day, DD Mon YYYY HH:MM:SS GMT
X-Correlation-ID: bf5t2ttrsc8r

{	
	"id_ref": ...
	"status": 200
	"status_text": ...
	"results": { …
	}
}
</code></pre>
<h1><a id="user-content-annex-c-acknowledgments" class="anchor" aria-hidden="true" href="#annex-c-acknowledgments"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Annex C. Acknowledgments</h1>
<p>The Implementation Considerations Subcommittee was tasked by the OASIS Open Command and Control Technical Committee (OpenC2 TC) which at the time of this submission, had 132 members.  The editor wishes to express their gratitude to the members of the OpenC2 TC.</p>
<p>The following individuals are acknowledged for providing comments, suggested text, and/or participation in CSD ballots or face-to-face meetings:</p>
<ul>
<li>Michelle Barry, AT&amp;T</li>
<li>Brian Berliner, Symantec</li>
<li>Joe Brule, National Security Agency</li>
<li>Trey Darley, New Context Services, Inc.</li>
<li>David Darnell, Systrends</li>
<li>Travis Farral, Anomali</li>
<li>Andy Gray, ForeScout</li>
<li>John-Mark Gurney, New Context Services, Inc.</li>
<li>Pavel Gutin, G2, Inc.</li>
<li>David Hamilton, AT&amp;T</li>
<li>April Jackson, Praxis Engineering</li>
<li>Sridhar Jayanthi, Polylogyx LLC</li>
<li>Bret Jordan, Symantec</li>
<li>Takahiro Kakumaru, NEC Corporation</li>
<li>David Kemp, National Security Agency</li>
<li>Lauri Korts-Pärn, NECAM</li>
<li>Anthony Librera, AT&amp;T</li>
<li>Danny Martinez, G2, Inc.</li>
<li>Lisa Mathews, National Security Agency</li>
<li>Jim Meck, Fireeye</li>
<li>Efrain Ortiz, Symantec Corp.</li>
<li>Daniel Riedel, New Context Services, Inc.</li>
<li>Nirmal Rajarathnam, ForeScout</li>
<li>Chris Ricard, FS-ISAC</li>
<li>Jason Romano, National Security Agency</li>
<li>Philip Royer, Splunk Inc.</li>
<li>Duane Skeen, Northrop Grumman</li>
<li>Duncan Sparrell, sFractal Consulting LLC</li>
<li>Michael Stair, AT&amp;T</li>
<li>Andrew Storms, New Context Services, Inc.</li>
<li>Gerald Stueve, Forenetix</li>
<li>Allan Thomson, LookingGlass Cyber Solutions</li>
<li>Bill Trost, AT&amp;T</li>
<li>Ryan Trost, ThreatQuotient</li>
<li>Drew Varner, NineFX</li>
<li>Jason Webb, LookingGlass Cyber Solutions</li>
<li>Sounil Yu, Bank of America</li>
<li>David Webber, Huawei</li>
</ul>
<h1><a id="user-content-annex-d-revision-history" class="anchor" aria-hidden="true" href="#annex-d-revision-history"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Annex D. Revision History</h1>
<table>
<thead>
<tr>
<th align="left">Revision</th>
<th align="left">Date</th>
<th align="left">Editor</th>
<th align="left">Changes Made</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">v1.0-wd01-wip</td>
<td align="left">6/15/2018</td>
<td align="left">Lemire</td>
<td align="left">Initial working draft</td>
</tr>
<tr>
<td align="left">v1.0-wd01-wip</td>
<td align="left">6/29/2018</td>
<td align="left">Lemire</td>
<td align="left">Added Suitability section (1.6), responded to SC member comments</td>
</tr>
<tr>
<td align="left">v1.0-wd01-wip</td>
<td align="left">7/20/2018</td>
<td align="left">Lemire</td>
<td align="left">Additional responses to member comments; formatting clean-up for easier conversion to Markdown.</td>
</tr>
<tr>
<td align="left">v1.0-wd01-wip</td>
<td align="left">8/9/2018</td>
<td align="left">Lemire</td>
<td align="left">Implementing feedback from the July 2018 face-to-face meeting and resolving other comments to reach WD01 version to submit for CSD ballot.</td>
</tr>
<tr>
<td align="left">v1.0-wd02-wip</td>
<td align="left">8/24/2018</td>
<td align="left">Lemire</td>
<td align="left">Various edits to clarify interactions when the producer is HTTP listener; other edits and cleanup in response to document comments and Slack forum discussions.</td>
</tr>
<tr>
<td align="left">v1.0-wd02-wip</td>
<td align="left">8/29/2018</td>
<td align="left">Lemire</td>
<td align="left">1) Adjustments to content type definitions to distinguish commands and responses; <br>2) Made corresponding adjustments to message flow descriptions and sample messages.<br>3) Added acknowledgements.</td>
</tr>
<tr>
<td align="left">v1.0-wd02-wip</td>
<td align="left">8/30/2018</td>
<td align="left">Lemire</td>
<td align="left">Inserted proposed replacements for sequence diagrams (Figures 2 and 3).</td>
</tr>
<tr>
<td align="left">v1.0-wd02-wip</td>
<td align="left">8/31/2018</td>
<td align="left">Lemire</td>
<td align="left">1) Inserted initial draft conformance language (section 4).<br>2) Revised Section 1 content for greater consistency with related OpenC2 specifications.<br>3) Revised section 2.1 to merge proposed endpoint role descriptions<br>4) General edit for formatting, readability, consistency, etc.</td>
</tr>
<tr>
<td align="left">v1.0-wd02-wip</td>
<td align="left">9/11/2018</td>
<td align="left">Lemire</td>
<td align="left">1) Reviewed and accepted / rejected comments.<br>2) Added placeholders for addressing use of "From" field.<br>3) Added statements about using Cache-control</td>
</tr>
<tr>
<td align="left">v1.0-wd02-wip</td>
<td align="left">9/17/2018</td>
<td align="left">Lemire</td>
<td align="left">1) Added table to conformance section specifying mapping of Language Spec message elements.<br>2) Clarified certificate mutual authentication requirement.<br>3) Removed language about unsolicited responses from Consumers<br>4) Numbered the conformance items</td>
</tr>
<tr>
<td align="left">v1.0-wd02-wip</td>
<td align="left">9/17/2018</td>
<td align="left">Lemire</td>
<td align="left">1) Removed used of the HTTP "From:" field, and mapped the OpenC2 "from" message element to the authenticated identity of the peer entity<br>2) Updated examples to remove HTTP From:</td>
</tr>
<tr>
<td align="left">v1.0-wd02-wip</td>
<td align="left">9/19/2018</td>
<td align="left">Lemire</td>
<td align="left">1) Final clean-up of residual comments and edits to create WD02 package for CSD ballot.<br>2) Renamed document to WD02</td>
</tr></tbody></table>
</article>
  </div>

  </div>

  <details class="details-reset details-overlay details-overlay-dark">
    <summary data-hotkey="l" aria-label="Jump to line"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast linejump" aria-label="Jump to line">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-jump-to-line-form Box-body d-flex" action="" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
        <input class="form-control flex-auto mr-3 linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
        <button type="submit" class="btn" data-close-dialog>Go</button>
</form>    </details-dialog>
  </details>


  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>

    </div>
  </div>

  </div>

        
<div class="footer container-lg px-3" role="contentinfo">
  <div class="position-relative d-flex flex-justify-between pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap ">
      <li class="mr-3">&copy; 2018 <span title="0.27313s from unicorn-66d9647c46-4m9lm">GitHub</span>, Inc.</li>
        <li class="mr-3"><a data-ga-click="Footer, go to terms, text:terms" href="https://github.com/site/terms">Terms</a></li>
        <li class="mr-3"><a data-ga-click="Footer, go to privacy, text:privacy" href="https://github.com/site/privacy">Privacy</a></li>
        <li class="mr-3"><a href="https://help.github.com/articles/github-security/" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li class="mr-3"><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a data-ga-click="Footer, go to help, text:help" href="https://help.github.com">Help</a></li>
    </ul>

    <a aria-label="Homepage" title="GitHub" class="footer-octicon mr-lg-4" href="https://github.com">
      <svg height="24" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
   <ul class="list-style-none d-flex flex-wrap ">
        <li class="mr-3"><a data-ga-click="Footer, go to contact, text:contact" href="https://github.com/contact">Contact GitHub</a></li>
        <li class="mr-3"><a href="https://github.com/pricing" data-ga-click="Footer, go to Pricing, text:Pricing">Pricing</a></li>
      <li class="mr-3"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
        <li class="mr-3"><a href="https://blog.github.com" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>

    </ul>
  </div>
  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 text-gray-light"></span>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 0 0 0 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 0 0 .01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
    </button>
    You can’t perform that action at this time.
  </div>


    
    <script crossorigin="anonymous" integrity="sha512-02xFq2Nht4XIIWBCxxq4VpC55nq5lZckudHhxAt541juEjdWFJ1DzLL+EKFLNfdBswpt4BxqElmnb+JXKx9yZw==" type="application/javascript" src="https://assets-cdn.github.com/assets/frameworks-4d33d091b81d47249e455238d69a1a95.js"></script>
    
    <script crossorigin="anonymous" async="async" integrity="sha512-qfUyw5LpNPTPv/9yViM2A7A4aveGNTGoub9QL3/+8d0v2MoqXYimROvZCbTrY5R71lHnENoE7c8m+G1OhLsG/Q==" type="application/javascript" src="https://assets-cdn.github.com/assets/github-5cb13afb52d05fe3d7a4f79a51a6b3c8.js"></script>
    
    
    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner d-none">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 0 0 0 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 0 0 .01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
    </button>
  </div>
</div>

  <template id="site-details-dialog">
  <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark" open>
    <summary aria-haspopup="dialog" aria-label="Close dialog"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast">
      <button class="Box-btn-octicon m-0 btn-octicon position-absolute right-0 top-0" type="button" aria-label="Close dialog" data-close-dialog>
        <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
      </button>
      <div class="octocat-spinner my-6 js-details-dialog-spinner"></div>
    </details-dialog>
  </details>
</template>

  <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;" tabindex="0">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box box-shadow-large" style="width:360px;">
  </div>
</div>

<div id="hovercard-aria-description" class="sr-only">
  Press h to open a hovercard with more details.
</div>


  </body>
</html>

