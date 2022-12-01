---
altLangPage: fr/configurations-communes/en-demande.html
breadcrumbs:
  - title: "About Canada.ca"
    link: "https://www.canada.ca/en/government/about.html"
  - title: "Canada.ca design system"
    link: "/en"
  - title: "Template and pattern library for Canada.ca"
    link: "/en/pattern-library.html"
date: 2022-05-17
dateModified: 2022-12-02
description:
title: Most requested
---
<p class="gc-byline"><strong>From : <a href="https://www.canada.ca/en/treasury-board-secretariat.html">Treasury Board Secretariat of Canada</a></strong></p>

<dl>
	<dt>Name of the pattern</dt>
	<dd data-json-replace="https://wet-boew.github.io/GCWeb/components/gc-most-requested/index.json-ld#/componentName"></dd>
	<dt>State</dt>
	<dd data-json-replace="https://wet-boew.github.io/GCWeb/components/gc-most-requested/index.json-ld#/status"></dd>
	<!--<dt>Examples:</dt>
	<dd>
     <pre>
      <code data-ajax-replace="https://api.github.com/repos/wet-boew/GCWeb/contents/components/gc-most-requested/gc-most-requested-en.html">
      </code>
    </pre>
  <dd> -->
  <dt>Escaped HTML version</dt>
  <dd>
    <div data-wb-jsonmanager='{
      "url": "https://api.github.com/repos/alpha-canada-ca/gcds/contents/_data/ajax/data-ajax-en.html",
      "name": "githubCode",
      "patches": [
        { "op": "wb-decodeUTF8Base64", "path": "/content", "set": "/raw" },
        { "op": "copy", "from": "/raw", "path": "/escape" },
        { "op": "wb-escapeHTML", "path": "/escape" }
      ]
    }'>
    <pre class="prettyprint"><code data-json-append="#[githubCode]/escape"></code></pre>
    </div>
  </dd>
</dl>
<h2>When to use this pattern</h2>
<ul>
	<li>Includes main tasks related to the page they are on. For example, on a topic page or organizational profile, it will list the top tasks related to that topic or organization based on user metrics and research.</li>
</ul>

<h2>How to use this pattern</h2>
<ul>
	<li>It lists the top tasks specific to the page it's on based on page view metrics and user research.</li>
	<li>Ideally, there should be a maximum of 3 links, since people usually don't click on links that follow the first 3.</li>
	<li>There should be no more than 7 links.</li>
	<li>Articles can only be linked to destination content, or to related topic links that are not already displayed on the page.</li>
	<li>Link titles should not include program or publication names unless they are useful to their intended audience.</li>
	<li>The header label is "Most requested".</li>
</ul>

<!-- <h3>Exemple concret</h3>
<ul>
	<li><a href="http://wet-boew.github.io/themes-dist/GCWeb/topic-fr.html">Page de sujet</a></li>
</ul>

<section class="panel panel-primary">
	<header class="panel-heading">
		<h2 class="panel-title">Exemple</h2>
	</header>
	<div class="panel-body">
		<figure class="mrgn-bttm-sm">
			<figcaption class="text-center">
				<b>Modèle des services les plus demandés</b>
			</figcaption>
			<img src="https://www.canada.ca/content/dam/tbs-sct/images/government-communications/canada-content-style-guide/most-requested-pattern-fra.jpg" class="img-responsive center-block" alt="Capture d'écran illustrant le modèle des services les plus demandés dans le site Canada.ca. Plus de détails au sujet de ce graphique se retrouvent dans le texte entourant l'image.">
		</figure>
	</div>
</section>-->
