# cautious-tribble


<html lang="en">
  <head>
  <title>Configuring npm for use with GitHub Packages - GitHub Docs</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="google-site-verification" content="OgdQc0GZfjDI52wDv1bkMT-SLpBUo_h5nn9mI9L22xQ" />
  <meta name="google-site-verification" content="c1kuD-K2HIVF635lypcsWPoD4kilo5-jA_wBFyT4uMY" />
  
  <!-- localized data needed by client-side JS  -->
  <meta name="site.data.ui.search.placeholder" content="Search topics, products...">
  <!-- end localized data -->

  
    <meta name="description" content="You can configure npm to publish packages to GitHub Packages and to use packages stored on GitHub Packages as dependencies in an npm project.">
  

  <!-- hreflangs -->
  
    <link 
      rel="alternate" 
      hreflang="en" 
      href="https://help.github.com/en/packages/using-github-packages-with-your-projects-ecosystem/configuring-npm-for-use-with-github-packages" 
    />
  
    <link 
      rel="alternate" 
      hreflang="zh-Hans" 
      href="https://help.github.com/cn/packages/using-github-packages-with-your-projects-ecosystem/configuring-npm-for-use-with-github-packages" 
    />
  
    <link 
      rel="alternate" 
      hreflang="ja" 
      href="https://help.github.com/ja/packages/using-github-packages-with-your-projects-ecosystem/configuring-npm-for-use-with-github-packages" 
    />
  
    <link 
      rel="alternate" 
      hreflang="es" 
      href="https://help.github.com/es/packages/using-github-packages-with-your-projects-ecosystem/configuring-npm-for-use-with-github-packages" 
    />
  
    <link 
      rel="alternate" 
      hreflang="pt" 
      href="https://help.github.com/pt/packages/using-github-packages-with-your-projects-ecosystem/configuring-npm-for-use-with-github-packages" 
    />
  
    <link 
      rel="alternate" 
      hreflang="de" 
      href="https://help.github.com/de/packages/using-github-packages-with-your-projects-ecosystem/configuring-npm-for-use-with-github-packages" 
    />
  

  <link rel="stylesheet" href="/stylesheets/index.css">
  <link rel="icon" type="image/x-icon" href="/assets/images/site/favicon.ico">
</head>


  <body class="d-lg-flex">
    <!-- product > guide > topic > article -->
<div class="sidebar d-none d-lg-block">

  <div class="d-flex flex-items-center p-4" style="z-index: 3;" id="github-logo">
    <a href="/en" class="text-white">
      <svg height="32" class="octicon octicon-mark-github"
        viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"></path></svg>
    </a>
    <a href="/en" class="h4-mktg text-white no-underline no-wrap pl-2 flex-auto">GitHub Docs</a>
  </div>

    
    <ul class="sidebar-products">
      <!--
  Styling note:

  Guides, Topics, and Articles list items get a class of `active` when they correspond to content
  hierarchy of the current page. If an item's URL is also the same as the current URL, the item
  also gets an `is-current-page` class.
 -->


<li title="Home">
  <a href="/" class="f6 pl-4 pr-5 ml-n1 pb-1">
    <svg xmlns="http://www.w3.org/2000/svg" class="octicon" viewBox="0 0 16 16" width="16" height="16">  <path fill-rule="evenodd" clip-rule="evenodd" d="M7.78033 12.5303C7.48744 12.8232 7.01256 12.8232 6.71967 12.5303L2.46967 8.28033C2.17678 7.98744 2.17678 7.51256 2.46967 7.21967L6.71967 2.96967C7.01256 2.67678 7.48744 2.67678 7.78033 2.96967C8.07322 3.26256 8.07322 3.73744 7.78033 4.03033L4.81066 7L12.25 7C12.6642 7 13 7.33579 13 7.75C13 8.16421 12.6642 8.5 12.25 8.5L4.81066 8.5L7.78033 11.4697C8.07322 11.7626 8.07322 12.2374 7.78033 12.5303Z"></path></svg>
    All products
  </a>
</li>
<li title="GitHub Packages" class="sidebar-product mb-2">
  <a href="/en/packages" class="pl-4 pr-5 pb-1 f4">GitHub Packages</a>
</li>
<ul class="sidebar-guides list-style-none">
  
  

  <li class="sidebar-guide py-1 ">
    <details class="dropdown-withArrow details details-reset" open>
      <summary>
        <div class="d-flex flex-justify-between">
          <a href="/en/packages/publishing-and-managing-packages" class="pl-4 pr-2 py-2 f6 text-uppercase d-block flex-auto mr-3">Publishing and managing packages</a>
          <svg xmlns="http://www.w3.org/2000/svg" class="octicon flex-shrink-0 arrow mr-3" style="margin-top:7px" viewBox="0 0 16 16" width="16" height="16"> <path fill-rule="evenodd" clip-rule="evenodd" d="M12.7803 6.21967C13.0732 6.51256 13.0732 6.98744 12.7803 7.28033L8.53033 11.5303C8.23744 11.8232 7.76256 11.8232 7.46967 11.5303L3.21967 7.28033C2.92678 6.98744 2.92678 6.51256 3.21967 6.21967C3.51256 5.92678 3.98744 5.92678 4.28033 6.21967L8 9.93934L11.7197 6.21967C12.0126 5.92678 12.4874 5.92678 12.7803 6.21967Z"></path></svg>
        </div>
      </summary>
      <!-- some guides have topics with child articles -->
      
      <ul class="sidebar-articles list-style-none">
        
        
        <li class="sidebar-article ">
          <a href="/en/packages/publishing-and-managing-packages/about-github-packages" class="pl-4 pr-5 py-1">About GitHub Packages</a>
        </li>
        
        
        <li class="sidebar-article ">
          <a href="/en/packages/publishing-and-managing-packages/publishing-a-package" class="pl-4 pr-5 py-1">Publishing a package</a>
        </li>
        
        
        <li class="sidebar-article ">
          <a href="/en/packages/publishing-and-managing-packages/viewing-packages" class="pl-4 pr-5 py-1">Viewing packages</a>
        </li>
        
        
        <li class="sidebar-article ">
          <a href="/en/packages/publishing-and-managing-packages/installing-a-package" class="pl-4 pr-5 py-1">Installing a package</a>
        </li>
        
        
        <li class="sidebar-article ">
          <a href="/en/packages/publishing-and-managing-packages/deleting-a-package" class="pl-4 pr-5 py-1 pb-2">Deleting a package</a>
        </li>
        
      </ul>
      
    </details>
  </li>
  
  

  <li class="sidebar-guide py-1 active ">
    <details class="dropdown-withArrow details details-reset" open>
      <summary>
        <div class="d-flex flex-justify-between">
          <a href="/en/packages/using-github-packages-with-your-projects-ecosystem" class="pl-4 pr-2 py-2 f6 text-uppercase d-block flex-auto mr-3">Using GitHub Packages with your project's ecosystem</a>
          <svg xmlns="http://www.w3.org/2000/svg" class="octicon flex-shrink-0 arrow mr-3" style="margin-top:7px" viewBox="0 0 16 16" width="16" height="16"> <path fill-rule="evenodd" clip-rule="evenodd" d="M12.7803 6.21967C13.0732 6.51256 13.0732 6.98744 12.7803 7.28033L8.53033 11.5303C8.23744 11.8232 7.76256 11.8232 7.46967 11.5303L3.21967 7.28033C2.92678 6.98744 2.92678 6.51256 3.21967 6.21967C3.51256 5.92678 3.98744 5.92678 4.28033 6.21967L8 9.93934L11.7197 6.21967C12.0126 5.92678 12.4874 5.92678 12.7803 6.21967Z"></path></svg>
        </div>
      </summary>
      <!-- some guides have topics with child articles -->
      
      <ul class="sidebar-articles list-style-none">
        
        
        <li class="sidebar-article ">
          <a href="/en/packages/using-github-packages-with-your-projects-ecosystem/using-github-packages-with-github-actions" class="pl-4 pr-5 py-1">Using GitHub Packages with GitHub Actions</a>
        </li>
        
        
        <li class="sidebar-article ">
          <a href="/en/packages/using-github-packages-with-your-projects-ecosystem/configuring-docker-for-use-with-github-packages" class="pl-4 pr-5 py-1">Configuring Docker for use with GitHub Packages</a>
        </li>
        
        
        <li class="sidebar-article ">
          <a href="/en/packages/using-github-packages-with-your-projects-ecosystem/configuring-apache-maven-for-use-with-github-packages" class="pl-4 pr-5 py-1">Configuring Apache Maven for use with GitHub Packages</a>
        </li>
        
        
        <li class="sidebar-article ">
          <a href="/en/packages/using-github-packages-with-your-projects-ecosystem/configuring-gradle-for-use-with-github-packages" class="pl-4 pr-5 py-1">Configuring Gradle for use with GitHub Packages</a>
        </li>
        
        
        <li class="sidebar-article active is-current-page">
          <a href="/en/packages/using-github-packages-with-your-projects-ecosystem/configuring-npm-for-use-with-github-packages" class="pl-4 pr-5 py-1">Configuring npm for use with GitHub Packages</a>
        </li>
        
        
        <li class="sidebar-article ">
          <a href="/en/packages/using-github-packages-with-your-projects-ecosystem/configuring-dotnet-cli-for-use-with-github-packages" class="pl-4 pr-5 py-1">Configuring `dotnet` CLI for use with GitHub Packages</a>
        </li>
        
        
        <li class="sidebar-article ">
          <a href="/en/packages/using-github-packages-with-your-projects-ecosystem/configuring-rubygems-for-use-with-github-packages" class="pl-4 pr-5 py-1 pb-2">Configuring RubyGems for use with GitHub Packages</a>
        </li>
        
      </ul>
      
    </details>
  </li>
  
</ul>

    </ul>
    
</div>


    <main class="width-full">
      <div class="border-bottom border-gray-light">

  

  

    <header class="container-xl px-3 px-md-6 pt-3 pb-2 position-relative d-flex flex-justify-between width-full">

      <div class="d-flex flex-items-center d-md-none" style="z-index: 3;" id="github-logo-mobile">
        <a href="/en">
          <svg height="32" class="octicon octicon-mark-github" fill="#000000" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"></path></svg>
        </a>
        <a href="/en" class="h4-mktg text-gray-dark no-underline no-wrap pl-2">GitHub Docs</a>
      </div>

      <div class="width-full">
        <div class="d-inline-block width-full d-md-flex" style="z-index: 1;">
          <button class="nav-mobile-burgerIcon float-right mt-1 border-0 d-md-none" type="button" aria-label="Toggle navigation">
            <!-- Hamburger icon added with css -->
          </button>
          <div style="z-index: 2;" class="nav-mobile-dropdown width-full">
            <div class="d-md-flex flex-justify-between flex-items-center">
              <div class="py-2 py-md-0 d-md-inline-block">
                <h4 class="text-mono f5 text-normal text-gray d-md-none">Explore by product</h4>
                <details class="dropdown-withArrow position-relative details details-reset d-md-none close-when-clicked-outside">
                  <summary class="nav-desktop-productDropdownButton text-blue-mktg py-2" role="button" aria-label="Toggle products list">
                    <div id="current-product" class="d-flex flex-items-center flex-justify-between" style="padding-top: 2px;">
                      <!-- Product switcher - GitHub.com, Enterprise Server, etc -->
                      <!-- 404 and 500 error layouts are not real pages so we need to hardcode the name for those -->
                      GitHub Packages
                      <svg class="arrow ml-md-1" width="14px" height="8px" viewBox="0 0 14 8" xml:space="preserve" fill="none" stroke="#1277eb"><path d="M1,1l6.2,6L13,1"></path></svg>
                    </div>
                  </summary>
                  <div id="homepages" class="position-md-absolute nav-desktop-productDropdown p-md-4 left-md-n4 top-md-6" style="z-index: 6;">
                    
                    <a href="/en/github"
                       class="d-block py-2 link-gray-dark no-underline">
                       GitHub.com
                       
                    </a>
                    
                    <a href="/en/enterprise/admin"
                       class="d-block py-2 link-gray-dark no-underline">
                       Enterprise Server
                       
                    </a>
                    
                    <a href="/en/actions"
                       class="d-block py-2 link-gray-dark no-underline">
                       GitHub Actions
                       
                    </a>
                    
                    <a href="/en/packages"
                       class="d-block py-2 text-blue-mktg text-underline active">
                       GitHub Packages
                       
                    </a>
                    
                    <a href="/en/developers"
                       class="d-block py-2 link-gray-dark no-underline">
                       Developers
                       
                    </a>
                    
                    <a href="/en/rest"
                       class="d-block py-2 link-gray-dark no-underline">
                       REST API
                       
                    </a>
                    
                    <a href="/en/graphql"
                       class="d-block py-2 link-gray-dark no-underline">
                       GraphQL API
                       
                    </a>
                    
                    <a href="/en/insights"
                       class="d-block py-2 link-gray-dark no-underline">
                       GitHub Insights
                       
                    </a>
                    
                    <a href="/en/desktop"
                       class="d-block py-2 link-gray-dark no-underline">
                       GitHub Desktop
                       
                    </a>
                    
                    <a href="https://atom.io/docs"
                       class="d-block py-2 link-gray-dark no-underline">
                       Atom
                       
                       <span class="ml-1"><svg width="9" height="10" viewBox="0 0 9 10" fill="none" xmlns="http://www.w3.org/2000/svg"><path stroke="#24292e" d="M.646 8.789l8-8M8.5 9V1M1 .643h8"/></svg></span>
                       
                    </a>
                    
                    <a href="https://electronjs.org/docs"
                       class="d-block py-2 link-gray-dark no-underline">
                       Electron
                       
                       <span class="ml-1"><svg width="9" height="10" viewBox="0 0 9 10" fill="none" xmlns="http://www.w3.org/2000/svg"><path stroke="#24292e" d="M.646 8.789l8-8M8.5 9V1M1 .643h8"/></svg></span>
                       
                    </a>
                    
                  </div>
                </details>
              </div>
              <div class="d-md-inline-block">

                <div class="border-top border-md-top-0 py-2 py-md-0 d-md-inline-block">
                  <details class="dropdown-withArrow position-relative details details-reset mr-md-3 close-when-clicked-outside">
                    <summary class="py-2 text-gray-dark" role="button" aria-label="Toggle languages list">
                      <div class="d-flex flex-items-center flex-justify-between">
                        <!-- Language switcher - 'English', 'Japanese', etc -->
                        
                          English
                        
                        <svg class="arrow ml-md-1" width="14px" height="8px" viewBox="0 0 14 8" xml:space="preserve" fill="none" stroke="#1B1F23"><path d="M1,1l6.2,6L13,1"></path></svg>
                      </div>
                    </summary>
                    <div id="languages-selector" class="position-md-absolute nav-desktop-langDropdown p-md-4 right-md-n4 top-md-6" style="z-index: 6;">
                    
                      
                        <a
                          href="/en/packages/using-github-packages-with-your-projects-ecosystem/configuring-npm-for-use-with-github-packages"
                          class="d-block py-2 no-underline active link-gray"
                          style="white-space: nowrap"
                        >
                          
                            English
                          
                        </a>
                      
                    
                      
                        <a
                          href="/cn/packages/using-github-packages-with-your-projects-ecosystem/configuring-npm-for-use-with-github-packages"
                          class="d-block py-2 no-underline link-gray-dark"
                          style="white-space: nowrap"
                        >
                          
                            简体中文 (Simplified Chinese)
                          
                        </a>
                      
                    
                      
                        <a
                          href="/ja/packages/using-github-packages-with-your-projects-ecosystem/configuring-npm-for-use-with-github-packages"
                          class="d-block py-2 no-underline link-gray-dark"
                          style="white-space: nowrap"
                        >
                          
                            日本語 (Japanese)
                          
                        </a>
                      
                    
                      
                        <a
                          href="/es/packages/using-github-packages-with-your-projects-ecosystem/configuring-npm-for-use-with-github-packages"
                          class="d-block py-2 no-underline link-gray-dark"
                          style="white-space: nowrap"
                        >
                          
                            Español (Spanish)
                          
                        </a>
                      
                    
                      
                        <a
                          href="/pt/packages/using-github-packages-with-your-projects-ecosystem/configuring-npm-for-use-with-github-packages"
                          class="d-block py-2 no-underline link-gray-dark"
                          style="white-space: nowrap"
                        >
                          
                            Português do Brasil (Portuguese)
                          
                        </a>
                      
                    
                      
                    
                    </div>
                  </details>
                </div>

                <!-- GitHub.com homepage has a stylized search; Enterprise homepages do not -->
                
                <div class="pt-3 pt-md-0 d-md-inline-block ml-md-3 border-top border-md-top-0">
                  <!--
  This form is used in two places:

  - On the homepage, front and center
  - On all other pages, in the header
 -->

<form class="mb-0">
  <div id="search-input-container">
    <!-- Aloglia instantsearch.js will add a search input here -->
  </div>
</form>

                  <div id="search-results-container"></div>
                  <div class="search-overlay-desktop"></div>
                </div>
                

              </div>
            </div>
          </div>
        </div>
      </div>
    </header>
  </div>

      
        <main class="container-xl px-3 px-md-6 my-4 my-lg-4 d-lg-flex">
  <article class="markdown-body width-full">
    


    <div class="article-grid-container">
      <div class="article-grid-toc">
        

      </div>
      <div class="article-grid-body d-flex flex-items-center" style="height: 39px;">
        <nav class="breadcrumbs f5" aria-label="Breadcrumb">
  
  <a title="product: GitHub Packages" href="/en/packages" class="d-inline-block ">
    GitHub Packages</a>
  
  <a title="guide: Using GitHub Packages with your project's ecosystem" href="/en/packages/using-github-packages-with-your-projects-ecosystem" class="d-inline-block ">
    Using GitHub Packages with your project's ecosystem</a>
  
  <a title="article: Configuring npm for use with GitHub Packages" href="/en/packages/using-github-packages-with-your-projects-ecosystem/configuring-npm-for-use-with-github-packages" class="d-inline-block text-gray-light">
    Configuring npm for use with GitHub Packages</a>
  
</nav>

      </div>
    </div>

    <div class="mt-2 article-grid-container">

    <div class="article-grid-head">
      
      <h1 class="border-bottom-0 mt-3">Configuring npm for use with GitHub Packages</h1>
      
      
        <div class="lead-mktg"><p>You can configure npm to publish packages to GitHub Packages and to use packages stored on GitHub Packages as dependencies in an npm project.</p></div>
      

      

      

      
        <div class="product-callout border rounded-1 mb-4 p-3 border-purple bg-purple-light">
        <p>GitHub Packages is available with GitHub Free, GitHub Pro, GitHub Free for organizations, GitHub Team, GitHub Enterprise Cloud, and GitHub One. GitHub Packages is not available for private repositories owned by accounts using legacy per-repository plans. For more information, see "<a href="/articles/github-s-products">GitHub's products</a>."</p>
        </div>
      
    </div>
    <div class="article-grid-toc border-bottom border-xl-0 pb-4 mb-5 pb-xl-0 mb-xl-0">
      <div class="article-grid-toc-content">
        
        <h3 id="in-this-article" class="f5 mb-2"><a class="link-gray-dark" href="#in-this-article">In this article</a></h3>
        <ul class="list-style-none pl-0 f5 mb-0">
          
          <li class="ml-0  mb-2 lh-condensed"><a href="#authenticating-to-github-packages">Authenticating to GitHub Packages</a></li>
          
          <li class="ml-0  mb-2 lh-condensed"><a href="#publishing-a-package">Publishing a package</a></li>
          
          <li class="ml-0  mb-2 lh-condensed"><a href="#publishing-multiple-packages-to-the-same-repository">Publishing multiple packages to the same repository</a></li>
          
          <li class="ml-0  mb-2 lh-condensed"><a href="#installing-a-package">Installing a package</a></li>
          
          <li class="ml-0  mb-2 lh-condensed"><a href="#further-reading">Further reading</a></li>
          
        </ul>
        
      </div>
    </div>
    <div id="article-contents" class="article-grid-body">
      
      <h3 id="authenticating-to-github-packages"><a href="#authenticating-to-github-packages">Authenticating to GitHub Packages</a></h3>
<p>You need an access token to publish, install, and delete packages in GitHub Packages. You can use a personal access token to authenticate with your username directly to GitHub Packages or the GitHub API. You can use a <code>GITHUB_TOKEN</code> to authenticate using a GitHub Actions workflow.</p>
<h4 id="authenticating-with-a-personal-access-token"><a href="#authenticating-with-a-personal-access-token">Authenticating with a personal access token</a></h4>
<p>You must use a personal access token with the appropriate scopes to publish and install packages in GitHub Packages. For more information, see &quot;<a href="/en/packages/publishing-and-managing-packages/about-github-packages#about-tokens">About GitHub Packages</a>.&quot;</p>
<p>You can authenticate to GitHub Packages with npm by either editing your per-user <em>~/.npmrc</em> file to include your personal access token or by logging in to npm on the command line using your username and personal access token.</p>
<p>To authenticate by adding your personal access token to your <em>~/.npmrc</em> file, edit the <em>~/.npmrc</em> file for your project to include the following line, replacing <em>TOKEN</em> with your personal access token.  Create a new <em>~/.npmrc</em> file if one doesn&apos;t exist.</p>
<pre><code class="hljs language-shell">//npm.pkg.github.com/:_authToken=<em>TOKEN</em></code></pre>
<p>To authenticate by logging in to npm, use the <code>npm login</code> command, replacing <em>USERNAME</em> with your GitHub username, <em>TOKEN</em> with your personal access token, and <em>PUBLIC-EMAIL-ADDRESS</em> with your email address.</p>
<pre><code class="hljs language-shell">$ npm login --registry=https://npm.pkg.github.com
&gt; Username: <em>USERNAME</em>
&gt; Password: <em>TOKEN</em>
&gt; Email: <em>PUBLIC-EMAIL-ADDRESS</em></code></pre>
<h4 id="authenticating-with-the-github_token"><a href="#authenticating-with-the-github_token">Authenticating with the <code>GITHUB_TOKEN</code></a></h4>
<p>If you are using a GitHub Actions workflow, you can use a <code>GITHUB_TOKEN</code> to publish and consume packages in GitHub Packages without needing to store and manage a personal access token. For more information, see &quot;<a href="/en/actions/automating-your-workflow-with-github-actions/authenticating-with-the-github_token">Authenticating with the <code>GITHUB_TOKEN</code></a>.&quot;</p>
<h3 id="publishing-a-package"><a href="#publishing-a-package">Publishing a package</a></h3>
<p>By default, GitHub Packages publishes a package in the GitHub repository you specify in the name field of the <em>package.json</em> file. For example, you would publish a package named <code>@my-org/test</code> to the <code>my-org/test</code> GitHub repository. You can add a summary for the package listing page by including a <em>README.md</em> file in your package directory. For more information, see &quot;<a href="https://docs.npmjs.com/getting-started/using-a-package.json">Working with package.json</a>&quot; and &quot;<a href="https://docs.npmjs.com/getting-started/creating-node-modules">How to create Node.js Modules</a>&quot; in the npm documentation.</p>
<p>You can publish multiple packages to the same GitHub repository by including a <code>URL</code> field in the <em>package.json</em> file. For more information, see &quot;<a href="#publishing-multiple-packages-to-the-same-repository">Publishing multiple packages to the same repository</a>.&quot;</p>
<p>You can set up the scope mapping for your project using either a local <em>.npmrc</em> file in the project or using the <code>publishConfig</code> option in the <em>package.json</em>. GitHub Packages only supports scoped npm packages. Scoped packages have names with the format of <code>@owner/name</code>. Scoped packages always begin with an <code>@</code> symbol. You may need to update the name in your <em>package.json</em> to use the scoped name. For example, <code>&quot;name&quot;: &quot;@codertocat/hello-world-npm&quot;</code>.</p>
<p>After you publish a package, you can view the package on GitHub. For more information, see &quot;<a href="/en/packages/publishing-and-managing-packages/viewing-packages">Viewing packages</a>.&quot;</p>
<h4 id="publishing-a-package-using-a-local-npmrc-file"><a href="#publishing-a-package-using-a-local-npmrc-file">Publishing a package using a local <em>.npmrc</em> file</a></h4>
<p>You can use an <em>.npmrc</em> file to configure the scope mapping for your project. In the <em>.npmrc</em> file, use the GitHub Packages URL and account owner so GitHub Packages knows where to route package requests. Using an <em>.npmrc</em> file prevents other developers from accidentally publishing the package to npmjs.org instead of GitHub Packages. Because upper case letters aren&apos;t supported, you must use lowercase letters for the repository owner even if the GitHub user or organization name contains uppercase letters.</p>
<ol>
<li>
<p>Authenticate to GitHub Packages. For more information, see &quot;<a href="#authenticating-to-github-packages">Authenticating to GitHub Packages</a>.&quot;</p>
</li>
<li>
<p>In the same directory as your <code>package.json</code> file, create or edit an <code>.npmrc</code> file to include a line specifying GitHub Packages URL and the account owner. Replace <code>OWNER</code> with the name of the user or organization account that owns the repository containing your project.</p>
<pre><code class="hljs language-shell">registry=https://npm.pkg.github.com/<em>OWNER</em></code></pre>
</li>
<li>
<p>Add the <em>.npmrc</em> file to the repository where GitHub Packages can find your project. For more information, see &quot;<a href="/en/github/managing-files-in-a-repository/adding-a-file-to-a-repository-using-the-command-line">Adding a file to a repository using the command line</a>.&quot;</p>
</li>
<li>
<p>Verify the name of your package in your project&apos;s <em>package.json</em>. The <code>name</code> field must contain the scope and the name of the package. For example, if your package is called &quot;test&quot;, and you are publishing to the &quot;My-org&quot; GitHub organization, the <code>name</code> field in your <em>package.json</em> should be <code>@my-org/test</code>.</p>
</li>
<li>
<p>Verify the <code>repository</code> field in your project&apos;s <em>package.json</em>. The <code>repository</code> field must match the URL for your GitHub repository. For example, if your repository URL is <code>github.com/my-org/test</code> then the repository field should be <code>git://github.com/my-org/test.git</code>.</p>
</li>
<li>
<p>Publish the package:</p>
<pre><code class="hljs language-shell">$ npm publish</code></pre>
</li>
</ol>
<h4 id="publishing-a-package-using-publishconfig-in-the-packagejson-file"><a href="#publishing-a-package-using-publishconfig-in-the-packagejson-file">Publishing a package using <code>publishConfig</code> in the <em>package.json</em> file</a></h4>
<p>You can use <code>publishConfig</code> element in the <em>package.json</em> file to specify the registry where you want the package published. For more information, see &quot;<a href="https://docs.npmjs.com/files/package.json#publishconfig">publishConfig</a>&quot; in the npm documentation.</p>
<ol>
<li>
<p>Edit the <em>package.json</em> file for your package and include a <code>publishConfig</code> entry.</p>
<pre><code class="hljs language-json">  <span class="hljs-string">&quot;publishConfig&quot;</span>: {
    <span class="hljs-attr">&quot;registry&quot;</span>:<span class="hljs-string">&quot;https://npm.pkg.github.com/&quot;</span>
  },
</code></pre>
</li>
<li>
<p>Verify the <code>repository</code> field in your project&apos;s <em>package.json</em>. The <code>repository</code> field must match the URL for your GitHub repository. For example, if your repository URL is <code>github.com/my-org/test</code> then the repository field should be <code>git://github.com/my-org/test.git</code>.</p>
</li>
<li>
<p>Publish the package:</p>
<pre><code class="hljs language-shell">$ npm publish</code></pre>
</li>
</ol>
<h3 id="publishing-multiple-packages-to-the-same-repository"><a href="#publishing-multiple-packages-to-the-same-repository">Publishing multiple packages to the same repository</a></h3>
<p>To publish multiple packages to the same repository, you can include the URL of the GitHub repository in the <code>repository</code> field of the <em>package.json</em> file for each package.</p>
<p>To ensure the repository&apos;s URL is correct, replace REPOSITORY with the name of the repository containing the package you want to publish, and OWNER with the name of the user or organization account on GitHub that owns the repository.</p>
<p>GitHub Packages will match the repository based on the URL, instead of based on the package name. If you store the <em>package.json</em> file outside the root directory of your repository, you can use the <code>directory</code> field to specify the location where GitHub Packages can find the <em>package.json</em> files.</p>
<pre><code class="hljs language-shell">&quot;repository&quot; : {
    &quot;type&quot; : &quot;git&quot;,
    &quot;url&quot;: &quot;ssh://git@github.com/<em>OWNER</em>/<em>REPOSITORY</em>.git&quot;,
    &quot;directory&quot;: &quot;packages/name&quot;
  },</code></pre>
<h3 id="installing-a-package"><a href="#installing-a-package">Installing a package</a></h3>
<p>You can install packages from GitHub Packages by adding the packages as dependencies in the <em>package.json</em> file for your project. For more information on using a <em>package.json</em> in your project, see &quot;<a href="https://docs.npmjs.com/getting-started/using-a-package.json">Working with package.json</a>&quot; in the npm documentation.</p>
<p>By default, you can add packages from one organization. For more information, see <a href="#installing-packages-from-other-organizations">Installing packages from other organizations</a></p>
<p>You also need to add the <em>.npmrc</em> file to your project so all requests to install packages will go through GitHub Packages. When you route all package requests through GitHub Packages, you can use both scoped and unscoped packages from <em>npmjs.com</em>. For more information, see &quot;<a href="https://docs.npmjs.com/misc/scope">npm-scope</a>&quot; in the npm documentation.</p>
<ol>
<li>
<p>Authenticate to GitHub Packages. For more information, see &quot;<a href="#authenticating-to-github-packages">Authenticating to GitHub Packages</a>.&quot;</p>
</li>
<li>
<p>In the same directory as your <code>package.json</code> file, create or edit an <code>.npmrc</code> file to include a line specifying GitHub Packages URL and the account owner. Replace <code>OWNER</code> with the name of the user or organization account that owns the repository containing your project.</p>
<pre><code class="hljs language-shell">registry=https://npm.pkg.github.com/<em>OWNER</em></code></pre>
</li>
<li>
<p>Add the <em>.npmrc</em> file to the repository where GitHub Packages can find your project. For more information, see &quot;<a href="/en/github/managing-files-in-a-repository/adding-a-file-to-a-repository-using-the-command-line">Adding a file to a repository using the command line</a>.&quot;</p>
</li>
<li>
<p>Configure <em>package.json</em> in your project to use the package you are installing. To add your package dependencies to the <em>package.json</em> file for GitHub Packages, specify the full-scoped package name, such as <code>@my-org/server</code>. For packages from <em>npmjs.com</em>, specify the full name, such as <code>@babel/core</code> or <code>@lodash</code>. For example, this following <em>package.json</em> uses the <code>@octo-org/octo-app</code> package as a dependency.</p>
<pre><code class="hljs language-json">{
  <span class="hljs-attr">&quot;name&quot;</span>: <span class="hljs-string">&quot;@my-org/server&quot;</span>,
  <span class="hljs-attr">&quot;version&quot;</span>: <span class="hljs-string">&quot;1.0.0&quot;</span>,
  <span class="hljs-attr">&quot;description&quot;</span>: <span class="hljs-string">&quot;Server app that uses the @octo-org/octo-app package&quot;</span>,
  <span class="hljs-attr">&quot;main&quot;</span>: <span class="hljs-string">&quot;index.js&quot;</span>,
  <span class="hljs-attr">&quot;author&quot;</span>: <span class="hljs-string">&quot;&quot;</span>,
  <span class="hljs-attr">&quot;license&quot;</span>: <span class="hljs-string">&quot;MIT&quot;</span>,
  <span class="hljs-attr">&quot;dependencies&quot;</span>: {
    <span class="hljs-attr">&quot;@octo-org/octo-app&quot;</span>: <span class="hljs-string">&quot;1.0.0&quot;</span>
  }
}
</code></pre>
</li>
<li>
<p>Install the package.</p>
<pre><code class="hljs language-shell">$ npm install</code></pre>
</li>
</ol>
<h4 id="installing-packages-from-other-organizations"><a href="#installing-packages-from-other-organizations">Installing packages from other organizations</a></h4>
<p>By default, you can only use GitHub Packages packages from one organization. If you&apos;d like to route package requests to multiple organizations and users, you can add additional lines to your <em>.npmrc</em> file, replacing <em>OWNER</em> with the name of the user or organization account that owns the repository containing your project. Because upper case letters aren&apos;t supported, you must use lowercase letters for the repository owner even if the GitHub user or organization name contains uppercase letters.</p>
<pre><code class="hljs language-shell">registry=https://npm.pkg.github.com/<em>OWNER</em>
@<em>OWNER</em>:registry=https://npm.pkg.github.com
@<em>OWNER</em>:registry=https://npm.pkg.github.com</code></pre>
<h3 id="further-reading"><a href="#further-reading">Further reading</a></h3>
<ul>
<li>&quot;<a href="/en/packages/publishing-and-managing-packages/deleting-a-package">Deleting a package</a>&quot;</li>
</ul>
    </div>
    </div>
  </article>
</main>

      
      <!-- Contact support banner -->
<section class="mt-lg-9 py-7" style="background-color: #fafbfc;">
  <div class="container-xl px-3 px-md-6">
    <div class="gutter gutter-xl-spacious d-md-flex">
      <div class="col-12 col-md-5">
        <h3 class="text-mono f5 text-normal text-gray mb-2">Ask a human</h3>
        <h4 class="h2-mktg mb-3">Can't find what you're looking for?</h4>
        <a id="contact-us" class="btn-mktg" href="https://support.github.com/contact">Contact us</a>
      </div>
      <div class="col-12 col-md-3 ml-md-6 ml-lg-0 position-relative">
        <svg class="position-relative position-md-absolute right-n8 right-lg-8 top-lg-3" width="240px" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 518.6 406.73"><g data-name="Layer 2"><g id="Layer_5" data-name="Layer 5"><ellipse cx="383.17" cy="369.46" rx="135.42" ry="16.07" style="fill:#cacfd6"/><path d="M37.2,399.86c0,2.37-5.37,3.88-11.75,4.2-.8,1.61-8,2.67-11,2.67C4.83,406.73,1,405,1,401.56s7.82-6.2,17.46-6.2S37.2,396.44,37.2,399.86Z" style="fill:#cacfd6"/><path d="M143.92,281.81c1.81,9.57,6.21,49.92,6.47,56.9s8.53,9.05,14.74,7.76,12-8.33,12.4-11.38-14.89-45.84-15.83-51.72S143.92,281.81,143.92,281.81Z" style="fill:#ffd33d"/><path d="M161.7,283.37a2.85,2.85,0,0,0-1.25-1.89c-3.72,7.66,3.41,23.7,4.1,30.94.5,5.19,3.64,7.34,4.91,11.94,1,3.66-.55,6.28.94,10a31.71,31.71,0,0,0,3.88,6.26c1.86-2.07,3.09-4.19,3.25-5.54C177.89,332,162.64,289.25,161.7,283.37Z" style="fill:#f9c513"/><path d="M153.38,344.41a11.86,11.86,0,0,0,5,2.12c-.48-4.14-1-8.27-1.35-12.43-.64-7.93-2.45-14.05-4.37-21.63-2.28-9.06,1.28-22.79-5.76-29.84a2.45,2.45,0,0,1-.72-1.33l-.92.2C149.47,302.17,150.89,323.38,153.38,344.41Z" style="fill:#ffdf5d"/><path d="M159,293a19.71,19.71,0,0,0,4.63-2.76,69.71,69.71,0,0,1-1.91-6.91c-.95-5.89-17.78-1.56-17.78-1.56.45,2.37,1.06,6.62,1.72,11.77C150,293.59,154.58,294.86,159,293Z" style="fill:#dbab09"/><path d="M83.21,191.25c-1.41.23-10.64-3.83-14.89,12.37s19.51,51.52,43.93,66.81c24.66,15.43,40.79,19.51,46.48,15.73,5.1-8.31,4.88-14,4.88-14s-34-14.65-51.68-30.48C93.52,225.21,83.21,191.25,83.21,191.25Z" style="fill:#dbab09;stroke:#ffea7f;stroke-miterlimit:10;stroke-width:2.5px"/><path d="M110.23,258.74c14.48,11.6,35.06,22.76,53.38,22.74,3.62-6.92,0-9.34,0-9.34s-34-14.65-51.68-30.48c-18.41-16.45-28.72-50.41-28.72-50.41-1,.17-6.12-1.9-10.47,3C70.82,220.26,91.37,243.62,110.23,258.74Z" style="fill:#b08800"/><path d="M192.9,23.26s-57.09,34.68-50.3,91.31c6,49.64,36.15,66.44,46.89,77.58,3.08,6.49-.7,19.08,9.17,26.63s32.14,13.23,61.56.51,56.06-29.82,67.6-54.47" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M202,52.3s-10.83-9.67-8.84-37.39a2.22,2.22,0,0,1,1.1-1.76c23.2-13.26,49-10.74,70.16,3.37" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M236.06,5.22C262.59-4,309.23,1.88,337.36,46.34c24.65,39,14.43,77.55,8.32,98.32" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M203.93,19.65s16.43,0,26.13,6.68c11.74,8.09,16.16,20.8,16.16,20.8" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M148.76,74.46s-26.39,9.14-32.15,27.43c7,11.53,21.41,22,27.49,22.16" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M142.48,113.44s3.61,19,22.59,17.05c28.31-7.16,29.24-57.72,68.06-56,37.09,1.62,42.8,51.75,47.11,65.77,3,9.78,16.49,8,22.51,11.73,10.11,6.35,10.11,29.3-8.74,49.35" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M332.09,156.9s15,82.09,14.35,93.44" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M370.63,245.84s-29.95-4.67-38.54,22.2,15.19,42.07,27.64,48.29c6.55,3.28,25.37,10.51,28.26,7.79,5.43-7.16-3.68-24.71-.59-42.84.78-4.54,6-13.45,6-17-13.88-42.95-40.28-125.12-59.87-129.63-7.52-1.73-5.66,16.81-5.66,16.81" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M317,181.44s3.88,25.34,13.06,42.32,16.43,26.58,16.43,26.58" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M321.17,176.08s7.46,25.2,13.42,34.37a145.35,145.35,0,0,1,9.29,16.36" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M320.14,196.63s-1.83,42.27,2.64,49.62" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M329.55,246.25s-26.16,1.83-27.53,26.61S317,301.31,317,301.31s-2.57,12.39,4.33,13.31,5.8-16.72,6.54-20.77a8.56,8.56,0,0,1,3.88-5.43" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M371.09,199.22s29.15,15.41,56,23.24,28.14,23.45,28.78,31.15-4.43,27.15-44.56,50.17" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M327.61,308s4.5,17.47,8,22.9" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M359.73,316.33s5,21.14,9.64,27" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M346.8,329.59a41.34,41.34,0,0,0-14.71,2.83s-16.35,6.6-19.23,27.95" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M313.56,356.51s-13.67-2-14.45,3.86.47,8.93,22.17,10.1,28.29,0,28.29,0" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M403.67,341.35a57.23,57.23,0,0,0-19.94-.39c-34.16,5.05-34.16,27.56-34.16,27.56s-5.69,7.77-.77,12.43a159,159,0,0,0,61.33,3.88c33-4.66,38-9.45,37.65-13.85s-7.93-5.9-7.93-5.9-2.4-10.22-19.23-40.36-11.41-44.27-11.41-44.27" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M353.51,382.15s2.8-12.65,11-12.65,29.87,17.38,40.49,15.95" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M309.49,189.18s-30.69,37.39-47.69,50.94c-15.05,12-60.2,33.28-84.27,32" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M187.77,285.77s.78-8.41-10.24-13.69" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M191.91,315.31c7.18-4.25,15.13-11.53,13.18-18.83-3.16-11.8-23.24-13.83-30.65-10.71-9.22,3.89-10.83,10.72-28.8,7.81" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M127.16,280.45s-9.9,30.5,5.92,45.45c16.14,15.27,61.21,20.63,61.2-27.57" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M175.32,198.57c5.76-.65,15.5-.65,15.5-.65" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><line x1="180.45" y1="208.08" x2="190.82" y2="202.95" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M295.63,139.3c7.55-12.7,22.25-31.34,32-37.48" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M305.37,142.27c5.29-4.87,15.8-14.22,35.78-22.06" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M186.69,325.8c51.66-20.24,113.43-76.49,134.25-123.21" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><ellipse cx="237.8" cy="275.53" rx="27.12" ry="8.66" transform="translate(-117.06 194.69) rotate(-36.37)" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><ellipse cx="287" cy="234.24" rx="22.62" ry="5.51" transform="translate(-76.62 305.08) rotate(-50.24)" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><ellipse cx="211.18" cy="196.36" rx="6.49" ry="3.48" transform="translate(-26.64 33.29) rotate(-8.48)" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M81.8,191.48S77.29,216.79,106.89,247c17.77,18.13,38.66,26.73,55.18,28.42,2.36-10.8,8.36-32.57-41.26-70C98.2,188.35,81.8,191.48,81.8,191.48Z" style="fill:#79b8ff"/><path d="M113.34,233.44a126.89,126.89,0,0,1-17.09-39.58,50.66,50.66,0,0,0-5.58-1.08c1,25,18.7,45.33,32.52,66.28,2.2,1.39,4.4,2.63,6.61,3.8A243.42,243.42,0,0,0,113.34,233.44Z" style="fill:#c8e1ff"/><path d="M87.23,191.32a24.34,24.34,0,0,0-5.43.16s-4.51,25.3,25.09,55.51c1.29,1.32,2.61,2.57,3.93,3.79C99.22,232.1,87.16,213.47,87.23,191.32Z" style="fill:#2188ff"/><path d="M153.93,254.73c-5-8.36-5.32-18.19-10.2-26.44-7.84-13.25-22.34-20-29.67-33.46-1.32-.49-2.61-.93-3.83-1.28,6.64,16,24.93,23.35,31.59,39.39,3.86,9.29,5.26,19,10.11,28a119.75,119.75,0,0,0,7.1,11.4c.9.29,1.78.54,2.67.8A87.18,87.18,0,0,0,153.93,254.73Z" style="fill:#daedff"/><path d="M68.32,203.62l2.8-13.2L96.3,170.55s36.38-3.91,65.6,30.76c25.47,30.22,24.58,44.25,25.64,58,0,0-18.72,24.65-29.89,28.26,7.4-22,10.3-34.8-22.44-66.09S77.83,185.18,68.32,203.62Z" style="fill:#ffea7f"/><path d="M178.75,225.08c.47,10.69,2.66,21.7-2.37,31.37-3.59,6.91-9.84,11.23-12.22,19-1.08,3.53-1.47,7.08-2.82,10.32,11.17-6.71,26.2-26.5,26.2-26.5C186.81,249.78,187,240.13,178.75,225.08Z" style="fill:#ffdf5d"/><path d="M389.9,253.67s4.18-5.22,9.62-7.42" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:3px"/><path d="M159.4,221.29c-7.51-13-18.33-25.17-31.76-32.3s-29.35-9.27-44.5-8.05l-5.23,4.13a51.11,51.11,0,0,1,17.74-.36c9.76,1.31,20.25,4.38,28.34,10.19,11.72,8.42,20.29,20.47,29.33,31.5,8.06,9.83,14.91,21,16.74,33.83a74.77,74.77,0,0,1,0,18.67c2-1.84,3.91-3.81,5.74-5.78C173.39,255,168.53,237.16,159.4,221.29Z" style="fill:#fff5b1"/><path d="M320.08,108a48.4,48.4,0,0,1,7.53-6.17" style="fill:none;stroke:#0366d6;stroke-linecap:round;stroke-miterlimit:10;stroke-width:3px"/><path d="M330.79,124.79c3.38-1.68,6.85-3.2,10.36-4.58" style="fill:none;stroke:#0366d6;stroke-linecap:round;stroke-miterlimit:10;stroke-width:3px"/><path d="M175.32,198.57c1.86-.2,3.72-.32,5.59-.41" style="fill:none;stroke:#0366d6;stroke-linecap:round;stroke-miterlimit:10;stroke-width:3px"/><path d="M180.45,208.08l3.65-1.8" style="fill:none;stroke:#0366d6;stroke-linecap:round;stroke-miterlimit:10;stroke-width:3px"/><ellipse cx="18.39" cy="393.7" rx="11.22" ry="6.17" style="fill:#0366d6"/><path d="M1,401.38c.45-3.84,5.43-5.54,9-5.53" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:2px"/><path d="M21.25,398.3s4.54.9,4.2,7" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:2px"/><path d="M26.67,395.36a10.33,10.33,0,0,1,5.14,1.7,7.12,7.12,0,0,1,3,4.74" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:2px"/><path d="M28.26,392.65s1.13-1.69,5.47-1.41a7.41,7.41,0,0,1,6.05,4.12" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:2px"/><path d="M2.93,393.7a9.52,9.52,0,0,1,4.24-3,13.51,13.51,0,0,1,5.8.2" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:2px"/><path d="M18.27,388.53s-1.53-2.08-3.58-1.7c-1.5.28-1.72,4-1.72,4" style="fill:none;stroke:#0366d6;stroke-miterlimit:10;stroke-width:2px"/></g></g></svg>
      </div>
    </div>
  </div>
</section>

      <div class="footer mt-6">
  <div class="container-xl px-3 px-md-6">
    <div class="d-flex flex-wrap py-5 mb-5">
      <div class="col-12 col-lg-4 mb-5">
        <a href="https://github.com/" data-ga-click="Footer, go to home, text:home" class="text-gray-dark" aria-label="Go to GitHub homepage">
          <svg height="30" class="octicon octicon-logo-github" viewBox="0 0 45 16" version="1.1" width="84" aria-hidden="true"><path fill-rule="evenodd" d="M18.53 12.03h-.02c.009 0 .015.01.024.011h.006l-.01-.01zm.004.011c-.093.001-.327.05-.574.05-.78 0-1.05-.36-1.05-.83V8.13h1.59c.09 0 .16-.08.16-.19v-1.7c0-.09-.08-.17-.16-.17h-1.59V3.96c0-.08-.05-.13-.14-.13h-2.16c-.09 0-.14.05-.14.13v2.17s-1.09.27-1.16.28c-.08.02-.13.09-.13.17v1.36c0 .11.08.19.17.19h1.11v3.28c0 2.44 1.7 2.69 2.86 2.69.53 0 1.17-.17 1.27-.22.06-.02.09-.09.09-.16v-1.5a.177.177 0 0 0-.146-.18zM42.23 9.84c0-1.81-.73-2.05-1.5-1.97-.6.04-1.08.34-1.08.34v3.52s.49.34 1.22.36c1.03.03 1.36-.34 1.36-2.25zm2.43-.16c0 3.43-1.11 4.41-3.05 4.41-1.64 0-2.52-.83-2.52-.83s-.04.46-.09.52c-.03.06-.08.08-.14.08h-1.48c-.1 0-.19-.08-.19-.17l.02-11.11c0-.09.08-.17.17-.17h2.13c.09 0 .17.08.17.17v3.77s.82-.53 2.02-.53l-.01-.02c1.2 0 2.97.45 2.97 3.88zm-8.72-3.61h-2.1c-.11 0-.17.08-.17.19v5.44s-.55.39-1.3.39-.97-.34-.97-1.09V6.25c0-.09-.08-.17-.17-.17h-2.14c-.09 0-.17.08-.17.17v5.11c0 2.2 1.23 2.75 2.92 2.75 1.39 0 2.52-.77 2.52-.77s.05.39.08.45c.02.05.09.09.16.09h1.34c.11 0 .17-.08.17-.17l.02-7.47c0-.09-.08-.17-.19-.17zm-23.7-.01h-2.13c-.09 0-.17.09-.17.2v7.34c0 .2.13.27.3.27h1.92c.2 0 .25-.09.25-.27V6.23c0-.09-.08-.17-.17-.17zm-1.05-3.38c-.77 0-1.38.61-1.38 1.38 0 .77.61 1.38 1.38 1.38.75 0 1.36-.61 1.36-1.38 0-.77-.61-1.38-1.36-1.38zm16.49-.25h-2.11c-.09 0-.17.08-.17.17v4.09h-3.31V2.6c0-.09-.08-.17-.17-.17h-2.13c-.09 0-.17.08-.17.17v11.11c0 .09.09.17.17.17h2.13c.09 0 .17-.08.17-.17V8.96h3.31l-.02 4.75c0 .09.08.17.17.17h2.13c.09 0 .17-.08.17-.17V2.6c0-.09-.08-.17-.17-.17zM8.81 7.35v5.74c0 .04-.01.11-.06.13 0 0-1.25.89-3.31.89-2.49 0-5.44-.78-5.44-5.92S2.58 1.99 5.1 2c2.18 0 3.06.49 3.2.58.04.05.06.09.06.14L7.94 4.5c0 .09-.09.2-.2.17-.36-.11-.9-.33-2.17-.33-1.47 0-3.05.42-3.05 3.73s1.5 3.7 2.58 3.7c.92 0 1.25-.11 1.25-.11v-2.3H4.88c-.11 0-.19-.08-.19-.17V7.35c0-.09.08-.17.19-.17h3.74c.11 0 .19.08.19.17z"></path></svg>
        </a>
      </div>
      <div class="col-6 col-sm-3 col-lg-2 mb-6 mb-md-2 pr-3 pr-lg-0 pl-lg-4">
        <h4 class="mb-3 text-mono text-gray-light text-normal">Product</h4>
        <ul class="list-style-none text-gray f5">
          <li class="lh-condensed mb-3"><a href="https://github.com/features" data-ga-click="Footer, go to features, text:features" class="link-gray">Features</a></li>
          <li class="lh-condensed mb-3"><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security" class="link-gray">Security</a></li>
          <li class="lh-condensed mb-3"><a href="https://github.com/enterprise" data-ga-click="Footer, go to enterprise, text:enterprise" class="link-gray">Enterprise</a></li>
          <li class="lh-condensed mb-3"><a href="https://github.com/case-studies?type=customers" data-ga-click="Footer, go to case studies, text:case studies" class="link-gray">Case Studies</a></li>
          <li class="lh-condensed mb-3"><a href="https://github.com/pricing" data-ga-click="Footer, go to pricing, text:pricing" class="link-gray">Pricing</a></li>
          <li class="lh-condensed mb-3"><a href="https://resources.github.com" data-ga-click="Footer, go to resources, text:resources" class="link-gray">Resources</a></li>
        </ul>
      </div>
      <div class="col-6 col-sm-3 col-lg-2 mb-6 mb-md-2 pr-3 pr-md-0 pl-md-4">
        <h4 class="mb-3 text-mono text-gray-light text-normal">Platform</h4>
        <ul class="list-style-none f5">
          <li class="lh-condensed mb-3"><a href="https://developer.github.com/" data-ga-click="Footer, go to api, text:api" class="link-gray">Developer API</a></li>
          <li class="lh-condensed mb-3"><a href="http://partner.github.com/" data-ga-click="Footer, go to partner, text:partner" class="link-gray">Partners</a></li>
          <li class="lh-condensed mb-3"><a href="https://atom.io" data-ga-click="Footer, go to atom, text:atom" class="link-gray">Atom</a></li>
          <li class="lh-condensed mb-3"><a href="http://electron.atom.io/" data-ga-click="Footer, go to electron, text:electron" class="link-gray">Electron</a></li>
          <li class="lh-condensed mb-3"><a href="https://desktop.github.com/" data-ga-click="Footer, go to desktop, text:desktop" class="link-gray">GitHub Desktop</a></li>
        </ul>
      </div>
      <div class="col-6 col-sm-3 col-lg-2 mb-6 mb-md-2 pr-3 pr-md-0 pl-md-4">
        <h4 class="mb-3 text-mono text-gray-light text-normal">Support</h4>
        <ul class="list-style-none f5">
          <li class="lh-condensed mb-3"><a href="/" class="link-gray">Help</a></li>
          <li class="lh-condensed mb-3"><a href="https://github.community" class="link-gray">Community Forum</a></li>
          <li class="lh-condensed mb-3"><a href="https://services.github.com/" class="link-gray">Training</a></li>
          <li class="lh-condensed mb-3"><a href="https://githubstatus.com/" class="link-gray">Status</a></li>
          <li class="lh-condensed mb-3"><a href="https://support.github.com/contact" class="link-gray">Contact GitHub</a></li>
        </ul>
      </div>
      <div class="col-6 col-sm-3 col-lg-2 mb-6 mb-md-2 pr-3 pr-md-0 pl-md-4">
        <h4 class="mb-3 text-mono text-gray-light text-normal">Company</h4>
        <ul class="list-style-none f5">
          <li class="lh-condensed mb-3"><a href="https://github.com/about" class="link-gray">About</a></li>
          <li class="lh-condensed mb-3"><a href="https://github.blog/" class="link-gray">Blog</a></li>
          <li class="lh-condensed mb-3"><a href="https://github.com/about/careers" class="link-gray">Careers</a></li>
          <li class="lh-condensed mb-3"><a href="https://github.com/about/press" class="link-gray">Press</a></li>
          <li class="lh-condensed mb-3"><a href="https://shop.github.com" class="link-gray">Shop</a></li>
        </ul>
      </div>
    </div>
  </div>
  <div class="bg-gray-light">
    <div class="container-xl px-3 px-md-6 f6 py-4 d-sm-flex flex-justify-between flex-row-reverse flex-items-center">
      <ul class="list-style-none d-flex flex-items-center mb-3 mb-sm-0 lh-condensed-ultra">
        <li class="mr-3">
          <a href="https://twitter.com/github" title="GitHub on Twitter" style="color: #959da5;">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 273.5 222.3" class="d-block" height="18"><path d="M273.5 26.3a109.77 109.77 0 0 1-32.2 8.8 56.07 56.07 0 0 0 24.7-31 113.39 113.39 0 0 1-35.7 13.6 56.1 56.1 0 0 0-97 38.4 54 54 0 0 0 1.5 12.8A159.68 159.68 0 0 1 19.1 10.3a56.12 56.12 0 0 0 17.4 74.9 56.06 56.06 0 0 1-25.4-7v.7a56.11 56.11 0 0 0 45 55 55.65 55.65 0 0 1-14.8 2 62.39 62.39 0 0 1-10.6-1 56.24 56.24 0 0 0 52.4 39 112.87 112.87 0 0 1-69.7 24 119 119 0 0 1-13.4-.8 158.83 158.83 0 0 0 86 25.2c103.2 0 159.6-85.5 159.6-159.6 0-2.4-.1-4.9-.2-7.3a114.25 114.25 0 0 0 28.1-29.1" fill="currentColor"></path></svg>
          </a>
        </li>
        <li class="mr-3">
          <a href="https://www.facebook.com/GitHub" title="GitHub on Facebook" style="color: #959da5;">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 15.3 15.4" class="d-block" height="18"><path d="M14.5 0H.8a.88.88 0 0 0-.8.9v13.6a.88.88 0 0 0 .8.9h7.3v-6h-2V7.1h2V5.4a2.87 2.87 0 0 1 2.5-3.1h.5a10.87 10.87 0 0 1 1.8.1v2.1h-1.3c-1 0-1.1.5-1.1 1.1v1.5h2.3l-.3 2.3h-2v5.9h3.9a.88.88 0 0 0 .9-.8V.8a.86.86 0 0 0-.8-.8z" fill="currentColor"></path></svg>
          </a>
        </li>
        <li class="mr-3">
          <a href="https://www.youtube.com/github" title="GitHub on YouTube" style="color: #959da5;">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 19.17 13.6" class="d-block" height="16"><path d="M18.77 2.13A2.4 2.4 0 0 0 17.09.42C15.59 0 9.58 0 9.58 0a57.55 57.55 0 0 0-7.5.4A2.49 2.49 0 0 0 .39 2.13 26.27 26.27 0 0 0 0 6.8a26.15 26.15 0 0 0 .39 4.67 2.43 2.43 0 0 0 1.69 1.71c1.52.42 7.5.42 7.5.42a57.69 57.69 0 0 0 7.51-.4 2.4 2.4 0 0 0 1.68-1.71 25.63 25.63 0 0 0 .4-4.67 24 24 0 0 0-.4-4.69zM7.67 9.71V3.89l5 2.91z" fill="currentColor"></path></svg>
          </a>
        </li>
        <li class="mr-3 flex-self-start">
          <a href="https://www.linkedin.com/company/github" title="GitHub on Linkedin" style="color: #959da5;">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 19 18" class="d-block" height="18"><path d="M3.94 2A2 2 0 1 1 2 0a2 2 0 0 1 1.94 2zM4 5.48H0V18h4zm6.32 0H6.34V18h3.94v-6.57c0-3.66 4.77-4 4.77 0V18H19v-7.93c0-6.17-7.06-5.94-8.72-2.91z" fill="currentColor"></path></svg>
          </a>
        </li>
        <li>
          <a href="https://github.com/github" title="GitHub's organization" style="color: #959da5;">
            <svg height="20" fill="#959da5" class="octicon octicon-mark-github d-block" alt="GitHub" viewBox="0 0 16 16" version="1.1" width="20" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"></path></svg>
          </a>
        </li>
      </ul>
      <ul class="list-style-none d-flex text-gray">
        <li class="mr-3">&copy; 2020 GitHub, Inc.</li>
        <li class="mr-3"><a href="/articles/github-terms-of-service/" class="link-gray">Terms </a></li>
        <li><a href="/articles/github-privacy-statement/" class="link-gray">Privacy </a></li>
      </ul>
    </div>
  </div>
</div>

<script src="/node_modules/algoliasearch/dist/algoliasearch.min.js"></script>
<script src="/node_modules/instantsearch.js/dist/instantsearch.production.min.js"></script>
<script src="/javascripts/index.js"></script>

    </main>
  </body>
</html>
