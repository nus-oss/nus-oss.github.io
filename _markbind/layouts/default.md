<head-bottom>
  <link rel="stylesheet" href="{{baseUrl}}/stylesheets/main.css">
</head-bottom>

<header fixed>
  <navbar type="primary">
    <a slot="brand" href="{{baseUrl}}/index.md" title="NUS-OSS Home" class="navbar-brand">[NUS-OSS]</a>
    <li><a href="{{baseUrl}}/index.md" class="nav-link">Home</a></li>
    <li><a href="{{baseUrl}}/pages/iwm.md" class="nav-link">IWM@NUS-OSS</a></li>
    <li slot="right">
      <form class="navbar-form">
        <searchbar :data="searchData" placeholder="Search" :on-hit="searchCallback" menu-align-right></searchbar>
      </form>
    </li>
  </navbar>
</header>

<div id="flex-body">
  <div id="content-wrapper" class="fixed-header-padding">
    {{ content }}
  </div>
  <nav id="page-nav" class="fixed-header-padding">
    <div class="nav-component slim-scroll">
      <page-nav />
    </div>
  </nav>
</div>

<footer>
  <div class="text-center">

[**This site was generated using <img src="https://markbind.org/favicon.ico" width="25"/> {{MarkBind}}** on {{timestamp}}]<br>
    %%<small><small>favicon.ico of this site was made by <a href="https://www.flaticon.com/authors/smashicons" title="Smashicons">Smashicons</a> from <a href="https://www.flaticon.com/"     title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a></small></small>%%
  </div>
</footer>
