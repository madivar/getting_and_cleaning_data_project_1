


<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    <meta name="viewport" content="width=1020">
    
    
    <title>coursera-getting-and-cleaning-data-project/CodeBook.md at master · bgentry/coursera-getting-and-cleaning-data-project</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="bgentry/coursera-getting-and-cleaning-data-project" name="twitter:title" /><meta content="coursera-getting-and-cleaning-data-project - course project for Coursera &quot;Getting and Cleaning Data&quot;" name="twitter:description" /><meta content="https://avatars1.githubusercontent.com/u/114033?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars1.githubusercontent.com/u/114033?v=3&amp;s=400" property="og:image" /><meta content="bgentry/coursera-getting-and-cleaning-data-project" property="og:title" /><meta content="https://github.com/bgentry/coursera-getting-and-cleaning-data-project" property="og:url" /><meta content="coursera-getting-and-cleaning-data-project - course project for Coursera &quot;Getting and Cleaning Data&quot;" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/MTM4Mjc0NzU6ODczNzg0NDg4NTYzMTA5NzNkN2YzMjJmNmQzMTgzZmY6ZjExNDk5MjY1Mzg3N2Y4ZDkyMDg4NWQ4NzJkMDFiNGM2NTdmNmQxNjA0MGI1NDZmZWYxOTI5NmMxMzk5OGQ5Nw==--2218d77a55803ae096a99e650d520b0054deee22">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="AE6E2398:7D29:26139034:5628ED46" name="octolytics-dimension-request_id" /><meta content="13827475" name="octolytics-actor-id" /><meta content="madivar" name="octolytics-actor-login" /><meta content="d16920e210846fcbc3a0057430db2cb3fc14d0eec652e1698b0b684d95b90753" name="octolytics-actor-hash" />

<meta content="Rails, view, blob#show" data-pjax-transient="true" name="analytics-event" />


  <meta class="js-ga-set" name="dimension1" content="Logged In">
    <meta class="js-ga-set" name="dimension4" content="Current repo nav">




    <meta name="is-dotcom" content="true">
        <meta name="hostname" content="github.com">
    <meta name="user-login" content="madivar">

      <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

    <meta content="80e0196dd55c99c962caaa0b5b7693f0c20319d8" name="form-nonce" />

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-ce671588d7b6afbb8bc61feba5b37b4acc3341aec654ff7a2405b657922ff0c1.css" integrity="sha256-zmcViNe2r7uLxh/rpbN7SswzQa7GVP96JAW2V5Iv8ME=" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github2-8d66f9bfcef65682f8b799f2330467be836c483d58670c9388d40c9e4c0492a3.css" integrity="sha256-jWb5v872VoL4t5nyMwRnvoNsSD1YZwyTiNQMnkwEkqM=" media="all" rel="stylesheet" />
    
    
    


    <meta http-equiv="x-pjax-version" content="f7a60445478c6154531fdca94f3ffd1b">

      
  <meta name="description" content="coursera-getting-and-cleaning-data-project - course project for Coursera &quot;Getting and Cleaning Data&quot;">
  <meta name="go-import" content="github.com/bgentry/coursera-getting-and-cleaning-data-project git https://github.com/bgentry/coursera-getting-and-cleaning-data-project.git">

  <meta content="114033" name="octolytics-dimension-user_id" /><meta content="bgentry" name="octolytics-dimension-user_login" /><meta content="32694259" name="octolytics-dimension-repository_id" /><meta content="bgentry/coursera-getting-and-cleaning-data-project" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="32694259" name="octolytics-dimension-repository_network_root_id" /><meta content="bgentry/coursera-getting-and-cleaning-data-project" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/bgentry/coursera-getting-and-cleaning-data-project/commits/master.atom" rel="alternate" title="Recent Commits to coursera-getting-and-cleaning-data-project:master" type="application/atom+xml">

  </head>


  <body class="logged_in   env-production windows vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>

    
    
    



      <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/bgentry/coursera-getting-and-cleaning-data-project/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/bgentry/coursera-getting-and-cleaning-data-project/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <label class="js-chromeless-input-container form-control">
    <div class="scope-badge">This repository</div>
    <input type="text"
      class="js-site-search-focus js-site-search-field is-clearable chromeless-input"
      data-hotkey="s"
      name="q"
      placeholder="Search"
      aria-label="Search this repository"
      data-global-scope-placeholder="Search GitHub"
      data-repo-scope-placeholder="Search"
      tabindex="1"
      autocapitalize="off">
  </label>
</form>
      </div>

      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item">
          <a href="/pulls" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
            Pull requests
</a>        </li>
        <li class="header-nav-item">
          <a href="/issues" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
            Issues
</a>        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com/" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item">
      <span class="js-socket-channel js-updatable-content"
        data-channel="notification-changed:madivar"
        data-url="/notifications/header">
      <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
          <span class="mail-status all-read"></span>
          <span class="octicon octicon-bell"></span>
</a>  </span>

  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new…"
       data-ga-click="Header, create new, icon:add">
      <span class="octicon octicon-plus left"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>


  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="bgentry/coursera-getting-and-cleaning-data-project">This repository</span>
  </div>
    <a class="dropdown-item" href="/bgentry/coursera-getting-and-cleaning-data-project/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-s js-menu-target" href="/madivar"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@madivar" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/13827475?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu  dropdown-menu-sw">
        <div class=" dropdown-header header-nav-current-user css-truncate">
            Signed in as <strong class="css-truncate-target">madivar</strong>

        </div>


        <div class="dropdown-divider"></div>

          <a class="dropdown-item" href="/madivar" data-ga-click="Header, go to profile, text:your profile">
            Your profile
          </a>
        <a class="dropdown-item" href="/stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a>
        <a class="dropdown-item" href="/explore" data-ga-click="Header, go to explore, text:explore">
          Explore
        </a>
          <a class="dropdown-item" href="/integrations" data-ga-click="Header, go to integrations, text:integrations">
            Integrations
          </a>
        <a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a>

          <div class="dropdown-divider"></div>

          <a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
            Settings
          </a>

          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/logout" class="logout-form" data-form-nonce="80e0196dd55c99c962caaa0b5b7693f0c20319d8" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="TeaibyDblQ4/VPcMAI71/16WoyVXqp22dec9z1v6qqrjhWwwzRCGt4+71/gx3LGysrKcZPttAQBKgD8l/1LA6w==" /></div>
            <button class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
              Sign out
            </button>
</form>
      </div>
    </div>
  </li>
</ul>


    
  </div>
</div>

      

      


    <div id="start-of-content" class="accessibility-aid"></div>

    <div id="js-flash-container">
</div>


    <div role="main" class="main-content">
        <div itemscope itemtype="http://schema.org/WebPage">
    <div class="pagehead repohead instapaper_ignore readability-menu">

      <div class="container">

        <div class="clearfix">
          

<ul class="pagehead-actions">

  <li>
      <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-form-nonce="80e0196dd55c99c962caaa0b5b7693f0c20319d8" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="zUYEOtHj0sTfp9FaAw3u/5i/As2KyuKgDizR9XAyLU0I+c8rbjUdwdzIqEbyEUybqrGbOG4q1h34bJcmuNWPjA==" /></div>    <input id="repository_id" name="repository_id" type="hidden" value="32694259" />

      <div class="select-menu js-menu-container js-select-menu">
        <a href="/bgentry/coursera-getting-and-cleaning-data-project/subscription"
          class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
          data-ga-click="Repository, click Watch settings, action:blob#show">
          <span class="js-select-button">
            <span class="octicon octicon-eye"></span>
            Watch
          </span>
        </a>
        <a class="social-count js-social-count" href="/bgentry/coursera-getting-and-cleaning-data-project/watchers">
          0
        </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header">
              <span class="select-menu-title">Notifications</span>
              <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
            </div>

            <div class="select-menu-list js-navigation-container" role="menu">

              <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                  <span class="select-menu-item-heading">Not watching</span>
                  <span class="description">Be notified when participating or @mentioned.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Watch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                  <span class="select-menu-item-heading">Watching</span>
                  <span class="description">Be notified of all conversations.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Unwatch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_ignore" name="do" type="radio" value="ignore" />
                  <span class="select-menu-item-heading">Ignoring</span>
                  <span class="description">Never be notified.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-mute"></span>
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
    
  <div class="js-toggler-container js-social-container starring-container ">

    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/bgentry/coursera-getting-and-cleaning-data-project/unstar" class="js-toggler-form starred js-unstar-button" data-form-nonce="80e0196dd55c99c962caaa0b5b7693f0c20319d8" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="mMU9p/vpqYY1ZvKP7DtuOGHR8DzDvQcSH013R4+h3gDoHdH812+qUjfMa+WNzaGbHv4SEjwDykmXFMfXhYE+UA==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar bgentry/coursera-getting-and-cleaning-data-project"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/bgentry/coursera-getting-and-cleaning-data-project/stargazers">
          2
        </a>
</form>
    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/bgentry/coursera-getting-and-cleaning-data-project/star" class="js-toggler-form unstarred js-star-button" data-form-nonce="80e0196dd55c99c962caaa0b5b7693f0c20319d8" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="RNX4nR7QfNvw7rCmc+LvuFHU+Aw7vo06ctOEmOb4CFj6v1wjKhMQdCK27GDBUhahJ2SCKH2mKXSRKKGvf+u9HA==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star bgentry/coursera-getting-and-cleaning-data-project"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/bgentry/coursera-getting-and-cleaning-data-project/stargazers">
          2
        </a>
</form>  </div>

  </li>

  <li>
          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/bgentry/coursera-getting-and-cleaning-data-project/fork" class="btn-with-count" data-form-nonce="80e0196dd55c99c962caaa0b5b7693f0c20319d8" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="Ws4W4SpnB0xDhvW2SNfbK0MTpXJRqXyEbTx2155Ugn314Sd+WRJgIYG5dfFodPzYvIPhA3riCJAX8Oyhf186rg==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of bgentry/coursera-getting-and-cleaning-data-project to your account"
                aria-label="Fork your own copy of bgentry/coursera-getting-and-cleaning-data-project to your account">
              <span class="octicon octicon-repo-forked"></span>
              Fork
            </button>
</form>
    <a href="/bgentry/coursera-getting-and-cleaning-data-project/network" class="social-count">
      37
    </a>
  </li>
</ul>

          <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public ">
  <span class="mega-octicon octicon-repo"></span>
  <span class="author"><a href="/bgentry" class="url fn" itemprop="url" rel="author"><span itemprop="title">bgentry</span></a></span><!--
--><span class="path-divider">/</span><!--
--><strong><a href="/bgentry/coursera-getting-and-cleaning-data-project" data-pjax="#js-repo-pjax-container">coursera-getting-and-cleaning-data-project</a></strong>

  <span class="page-context-loader">
    <img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
  </span>

</h1>

        </div>
      </div>
    </div>

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline ">
        <div class="repository-sidebar clearfix">
          
<nav class="sunken-menu repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container"
     data-issue-count-url="/bgentry/coursera-getting-and-cleaning-data-project/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/bgentry/coursera-getting-and-cleaning-data-project" aria-label="Code" aria-selected="true" class="js-selected-navigation-item selected sunken-menu-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /bgentry/coursera-getting-and-cleaning-data-project">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Issues">
        <a href="/bgentry/coursera-getting-and-cleaning-data-project/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /bgentry/coursera-getting-and-cleaning-data-project/issues">
          <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
          <span class="js-issue-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

    <li class="tooltipped tooltipped-w" aria-label="Pull requests">
      <a href="/bgentry/coursera-getting-and-cleaning-data-project/pulls" aria-label="Pull requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /bgentry/coursera-getting-and-cleaning-data-project/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull requests</span>
          <span class="js-pull-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Wiki">
        <a href="/bgentry/coursera-getting-and-cleaning-data-project/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g w" data-selected-links="repo_wiki /bgentry/coursera-getting-and-cleaning-data-project/wiki">
          <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>
  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/bgentry/coursera-getting-and-cleaning-data-project/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /bgentry/coursera-getting-and-cleaning-data-project/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/bgentry/coursera-getting-and-cleaning-data-project/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /bgentry/coursera-getting-and-cleaning-data-project/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>
  </ul>


</nav>

            <div class="only-with-full-nav">
                
<div class="js-clone-url clone-url open"
  data-protocol-type="http">
  <h3 class="text-small text-muted"><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini text-small text-muted input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/bgentry/coursera-getting-and-cleaning-data-project.git" readonly="readonly" aria-label="HTTPS clone URL">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="js-clone-url clone-url "
  data-protocol-type="ssh">
  <h3 class="text-small text-muted"><span class="text-emphasized">SSH</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini text-small text-muted input-monospace js-url-field js-zeroclipboard-target"
           value="git@github.com:bgentry/coursera-getting-and-cleaning-data-project.git" readonly="readonly" aria-label="SSH clone URL">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="js-clone-url clone-url "
  data-protocol-type="subversion">
  <h3 class="text-small text-muted"><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini text-small text-muted input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/bgentry/coursera-getting-and-cleaning-data-project" readonly="readonly" aria-label="Subversion checkout URL">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>



<div class="clone-options text-small text-muted">You can clone with
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-form-nonce="80e0196dd55c99c962caaa0b5b7693f0c20319d8" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="qnYCJ3yupSRqpQafX1T2J7HVafTUlteeWV01xOgXEB1zVrg473YNPGY0+PAV6u31nbDaP33EapBZzD26qtEbZQ==" /></div><button class="btn-link js-clone-selector" data-protocol="http" type="submit">HTTPS</button></form>, <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-form-nonce="80e0196dd55c99c962caaa0b5b7693f0c20319d8" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="XoG+flMmiI5JVGZKjN0S/Xlt+NJCMYpEDXIsAbBxGuDr/BvEfmmnT8T95iZUhMdLI3TeYwhVzVWt/R20OOORJA==" /></div><button class="btn-link js-clone-selector" data-protocol="ssh" type="submit">SSH</button></form>, or <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-form-nonce="80e0196dd55c99c962caaa0b5b7693f0c20319d8" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="VNriLCtPLGP9t8gboi/CXojBG+5OetBfXzyATt+d42ibV/LOKLiHkeVXBZGufyK2d0HlEN9B0e/FlLur5Bj1wQ==" /></div><button class="btn-link js-clone-selector" data-protocol="subversion" type="submit">Subversion</button></form>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</div>
  <a href="github-windows://openRepo/https://github.com/bgentry/coursera-getting-and-cleaning-data-project" class="btn btn-sm sidebar-button" title="Save bgentry/coursera-getting-and-cleaning-data-project to your computer and use it in GitHub Desktop." aria-label="Save bgentry/coursera-getting-and-cleaning-data-project to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-desktop-download"></span>
    Clone in Desktop
  </a>

              <a href="/bgentry/coursera-getting-and-cleaning-data-project/archive/master.zip"
                 class="btn btn-sm sidebar-button"
                 aria-label="Download the contents of bgentry/coursera-getting-and-cleaning-data-project as a zip file"
                 title="Download the contents of bgentry/coursera-getting-and-cleaning-data-project as a zip file"
                 rel="nofollow">
                <span class="octicon octicon-cloud-download"></span>
                Download ZIP
              </a>
            </div>
        </div>
        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>

          

<a href="/bgentry/coursera-getting-and-cleaning-data-project/blob/f970ecbd764eaec92c220d8b28c55b44941fa2a6/CodeBook.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:d7bfc3b1e1294b02b7eda99aff5affa9 -->

  <div class="file-navigation js-zeroclipboard-container">
    
<div class="select-menu js-menu-container js-select-menu left">
  <button class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    title="master"
    type="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <i>Branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/bgentry/coursera-getting-and-cleaning-data-project/blob/master/CodeBook.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="master">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

    <div class="btn-group right">
      <a href="/bgentry/coursera-getting-and-cleaning-data-project/find/master"
            class="js-show-file-finder btn btn-sm empty-icon tooltipped tooltipped-nw"
            data-pjax
            data-hotkey="t"
            aria-label="Quickly jump between files">
        <span class="octicon octicon-list-unordered"></span>
      </a>
      <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </div>

    <div class="breadcrumb js-zeroclipboard-target">
      <span class="repo-root js-repo-root"><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/bgentry/coursera-getting-and-cleaning-data-project" class="" data-branch="master" data-pjax="true" itemscope="url"><span itemprop="title">coursera-getting-and-cleaning-data-project</span></a></span></span><span class="separator">/</span><strong class="final-path">CodeBook.md</strong>
    </div>
  </div>


  <div class="commit-tease">
      <span class="right">
        <a class="commit-tease-sha" href="/bgentry/coursera-getting-and-cleaning-data-project/commit/f970ecbd764eaec92c220d8b28c55b44941fa2a6" data-pjax>
          f970ecb
        </a>
        <time datetime="2015-03-22T20:36:43Z" is="relative-time">Mar 22, 2015</time>
      </span>
      <div>
        <img alt="@bgentry" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/114033?v=3&amp;s=40" width="20" />
        <a href="/bgentry" class="user-mention" rel="author">bgentry</a>
          <a href="/bgentry/coursera-getting-and-cleaning-data-project/commit/f970ecbd764eaec92c220d8b28c55b44941fa2a6" class="message" data-pjax="true" title="add code book">add code book</a>
      </div>

    <div class="commit-tease-contributors">
      <a class="muted-link contributors-toggle" href="#blob_contributors_box" rel="facebox">
        <strong>1</strong>
         contributor
      </a>
      
    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@bgentry" height="24" src="https://avatars0.githubusercontent.com/u/114033?v=3&amp;s=48" width="24" />
            <a href="/bgentry">bgentry</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
  <div class="file-actions">

    <div class="btn-group">
      <a href="/bgentry/coursera-getting-and-cleaning-data-project/raw/master/CodeBook.md" class="btn btn-sm " id="raw-url">Raw</a>
        <a href="/bgentry/coursera-getting-and-cleaning-data-project/blame/master/CodeBook.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
      <a href="/bgentry/coursera-getting-and-cleaning-data-project/commits/master/CodeBook.md" class="btn btn-sm " rel="nofollow">History</a>
    </div>

      <a class="octicon-btn tooltipped tooltipped-nw"
         href="github-windows://openRepo/https://github.com/bgentry/coursera-getting-and-cleaning-data-project?branch=master&amp;filepath=CodeBook.md"
         aria-label="Open this file in GitHub Desktop"
         data-ga-click="Repository, open with desktop, type:windows">
          <span class="octicon octicon-device-desktop"></span>
      </a>

        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/bgentry/coursera-getting-and-cleaning-data-project/edit/master/CodeBook.md" class="inline-form js-update-url-with-hash" data-form-nonce="80e0196dd55c99c962caaa0b5b7693f0c20319d8" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="fvQwfDnN9NVotLwHh+BuwFz9wOLuFpDc3vqcmjkHZwl3IpI1PE4N3Q266dpvTw1QK8CFc4giTgFrxE7S4hUkUA==" /></div>
          <button class="octicon-btn tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
            <span class="octicon octicon-pencil"></span>
          </button>
</form>        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/bgentry/coursera-getting-and-cleaning-data-project/delete/master/CodeBook.md" class="inline-form" data-form-nonce="80e0196dd55c99c962caaa0b5b7693f0c20319d8" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="osDJHqmjEmPLYawuaMvsjMJVnBv1S+JTol0EyQ+Y3nnUsEOQKrN4oLtwOpvytpkFLgi1H1sWNUIeMt6moxsceQ==" /></div>
          <button class="octicon-btn octicon-btn-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and delete the file" data-disable-with>
            <span class="octicon octicon-trashcan"></span>
          </button>
</form>  </div>

  <div class="file-info">
      100 lines (92 sloc)
      <span class="file-info-divider"></span>
    2.34 KB
  </div>
</div>

  
  <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1><a id="user-content-code-book" class="anchor" href="#code-book" aria-hidden="true"><span class="octicon octicon-link"></span></a>Code Book</h1>

<p>This code book summarizes the resulting data fields in <code>tidy.txt</code>.</p>

<h2><a id="user-content-identifiers" class="anchor" href="#identifiers" aria-hidden="true"><span class="octicon octicon-link"></span></a>Identifiers</h2>

<ul>
<li><code>subject</code> - The ID of the test subject</li>
<li><code>activity</code> - The type of activity performed when the corresponding measurements were taken</li>
</ul>

<h2><a id="user-content-measurements" class="anchor" href="#measurements" aria-hidden="true"><span class="octicon octicon-link"></span></a>Measurements</h2>

<ul>
<li><code>tBodyAccMeanX</code></li>
<li><code>tBodyAccMeanY</code></li>
<li><code>tBodyAccMeanZ</code></li>
<li><code>tBodyAccStdX</code></li>
<li><code>tBodyAccStdY</code></li>
<li><code>tBodyAccStdZ</code></li>
<li><code>tGravityAccMeanX</code></li>
<li><code>tGravityAccMeanY</code></li>
<li><code>tGravityAccMeanZ</code></li>
<li><code>tGravityAccStdX</code></li>
<li><code>tGravityAccStdY</code></li>
<li><code>tGravityAccStdZ</code></li>
<li><code>tBodyAccJerkMeanX</code></li>
<li><code>tBodyAccJerkMeanY</code></li>
<li><code>tBodyAccJerkMeanZ</code></li>
<li><code>tBodyAccJerkStdX</code></li>
<li><code>tBodyAccJerkStdY</code></li>
<li><code>tBodyAccJerkStdZ</code></li>
<li><code>tBodyGyroMeanX</code></li>
<li><code>tBodyGyroMeanY</code></li>
<li><code>tBodyGyroMeanZ</code></li>
<li><code>tBodyGyroStdX</code></li>
<li><code>tBodyGyroStdY</code></li>
<li><code>tBodyGyroStdZ</code></li>
<li><code>tBodyGyroJerkMeanX</code></li>
<li><code>tBodyGyroJerkMeanY</code></li>
<li><code>tBodyGyroJerkMeanZ</code></li>
<li><code>tBodyGyroJerkStdX</code></li>
<li><code>tBodyGyroJerkStdY</code></li>
<li><code>tBodyGyroJerkStdZ</code></li>
<li><code>tBodyAccMagMean</code></li>
<li><code>tBodyAccMagStd</code></li>
<li><code>tGravityAccMagMean</code></li>
<li><code>tGravityAccMagStd</code></li>
<li><code>tBodyAccJerkMagMean</code></li>
<li><code>tBodyAccJerkMagStd</code></li>
<li><code>tBodyGyroMagMean</code></li>
<li><code>tBodyGyroMagStd</code></li>
<li><code>tBodyGyroJerkMagMean</code></li>
<li><code>tBodyGyroJerkMagStd</code></li>
<li><code>fBodyAccMeanX</code></li>
<li><code>fBodyAccMeanY</code></li>
<li><code>fBodyAccMeanZ</code></li>
<li><code>fBodyAccStdX</code></li>
<li><code>fBodyAccStdY</code></li>
<li><code>fBodyAccStdZ</code></li>
<li><code>fBodyAccMeanFreqX</code></li>
<li><code>fBodyAccMeanFreqY</code></li>
<li><code>fBodyAccMeanFreqZ</code></li>
<li><code>fBodyAccJerkMeanX</code></li>
<li><code>fBodyAccJerkMeanY</code></li>
<li><code>fBodyAccJerkMeanZ</code></li>
<li><code>fBodyAccJerkStdX</code></li>
<li><code>fBodyAccJerkStdY</code></li>
<li><code>fBodyAccJerkStdZ</code></li>
<li><code>fBodyAccJerkMeanFreqX</code></li>
<li><code>fBodyAccJerkMeanFreqY</code></li>
<li><code>fBodyAccJerkMeanFreqZ</code></li>
<li><code>fBodyGyroMeanX</code></li>
<li><code>fBodyGyroMeanY</code></li>
<li><code>fBodyGyroMeanZ</code></li>
<li><code>fBodyGyroStdX</code></li>
<li><code>fBodyGyroStdY</code></li>
<li><code>fBodyGyroStdZ</code></li>
<li><code>fBodyGyroMeanFreqX</code></li>
<li><code>fBodyGyroMeanFreqY</code></li>
<li><code>fBodyGyroMeanFreqZ</code></li>
<li><code>fBodyAccMagMean</code></li>
<li><code>fBodyAccMagStd</code></li>
<li><code>fBodyAccMagMeanFreq</code></li>
<li><code>fBodyBodyAccJerkMagMean</code></li>
<li><code>fBodyBodyAccJerkMagStd</code></li>
<li><code>fBodyBodyAccJerkMagMeanFreq</code></li>
<li><code>fBodyBodyGyroMagMean</code></li>
<li><code>fBodyBodyGyroMagStd</code></li>
<li><code>fBodyBodyGyroMagMeanFreq</code></li>
<li><code>fBodyBodyGyroJerkMagMean</code></li>
<li><code>fBodyBodyGyroJerkMagStd</code></li>
<li><code>fBodyBodyGyroJerkMagMeanFreq</code></li>
</ul>

<h2><a id="user-content-activity-labels" class="anchor" href="#activity-labels" aria-hidden="true"><span class="octicon octicon-link"></span></a>Activity Labels</h2>

<ul>
<li><code>WALKING</code> (value <code>1</code>): subject was walking during the test</li>
<li><code>WALKING_UPSTAIRS</code> (value <code>2</code>): subject was walking up a staircase during the test</li>
<li><code>WALKING_DOWNSTAIRS</code> (value <code>3</code>): subject was walking down a staircase during the test</li>
<li><code>SITTING</code> (value <code>4</code>): subject was sitting during the test</li>
<li><code>STANDING</code> (value <code>5</code>): subject was standing during the test</li>
<li><code>LAYING</code> (value <code>6</code>): subject was laying down during the test</li>
</ul>
</article>
  </div>

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

        </div>
      </div>
      <div class="modal-backdrop"></div>
    </div>
  </div>


    </div>

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>
        <li><a href="https://github.com/pricing" data-ga-click="Footer, go to pricing, text:pricing">Pricing</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.12256s from github-fe132-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>
  </div>
</div>



    
    
    

    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
        <span class="octicon octicon-x"></span>
      </button>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" integrity="sha256-Fhzsf0y5oYf2bC7Lj1nJCY4q1kRYr5F+xy+dYda4CJs=" src="https://assets-cdn.github.com/assets/frameworks-161cec7f4cb9a187f66c2ecb8f59c9098e2ad64458af917ec72f9d61d6b8089b.js"></script>
      <script async="async" crossorigin="anonymous" integrity="sha256-6GclomzQZhC8tOsFlcV3/1XOAni+DpFzV8KEBX3gDAQ=" src="https://assets-cdn.github.com/assets/github-e86725a26cd06610bcb4eb0595c577ff55ce0278be0e917357c284057de00c04.js"></script>
      
      
    <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner hidden">
      <span class="octicon octicon-alert"></span>
      <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
      <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
    </div>
  </body>
</html>

