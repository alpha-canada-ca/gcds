---
altLangPage: /fr
breadcrumbs:
  - title: "About Canada.ca"
    link: "https://www.canada.ca/en/government/about.html"
date: 2021-05-03
dateModified: 2022-09-13
description: Evidence and insights from the Canada.ca team.
indexed: false
title: Canada.ca design system
---
{%- assign locales = site.data.locales.index-pages -%}
<p>{{ locales.intro-home[ page.lang ] }}</p>
<section class="gc-srvinfo">
  <h2 class="wb-inv">{{ locales.most-requested-home[ page.lang ] }}</h2>
  <div class="row wb-eqht gc-drmt">
{%- assign pages = site.pages | where: "lang", page.lang -%}
{%- if pages.size > 0 -%}
  {%- for page in pages -%}
    {%- if page.type == "landing" -%}
    <div class="col-lg-4 col-md-6">
      <section>
        <h3><a href="{{ page.url }}">{{ page.title }}</a></h3>
        <p>{{ page.description }}</p>
      </section>
    </div>
    {%- endif -%}
  {%- endfor -%}
{%- endif -%}
<!--
  <div class="wb-eqht row gc-drmt">
    <div class="col-lg-4 col-md-6">
      <section>
        <h3><a href="pattern-library.html">Template and design pattern library</a></h3>
        <p>User-tested templates, page layouts, design patterns, guidelines, and code samples</p>
      </section>
    </div>
    <div class="col-lg-4 col-md-6">
      <section>
        <h3><a href="https://www.canada.ca/en/treasury-board-secretariat/services/government-communications/canada-content-style-guide.html">Canada.ca Content Style guide</a></h3>
        <p>Writing principles and techniques to make content clear and accessible to all</p>
      </section>
    </div>
    <div class="col-lg-4 col-md-6">
      <section>
        <h3><a href="https://www.canada.ca/en/treasury-board-secretariat/services/government-communications/canada-content-information-architecture-specification.html">Canada.ca Content and Information Architecture Specification</a></h3>
        <p>Who has to use the Canada.ca design system, mandatory elements, how to organize content and design principles</p>
      </section>
    </div>
    <div class="col-lg-4 col-md-6">
      <section>
        <h3><a href="continuous-improvement.html">Continuous improvement of web content</a></h3>
        <p>Choosing what to improve, organizing and preparing your team, research and prototyping, designing content, monitoring and measuring success</p>
      </section>
    </div>
    <div class="col-lg-4 col-md-6">
      <section>
        <h3><a href="./blog/">Canada.ca blog</a></h3>
        <p>Evidence and insights on improving information and services on Canada.ca</p>
      </section>
    </div>
    <div class="col-lg-4 col-md-6">
      <section>
        <h3><a href="latest-changes.html">Latest changes to the Canada.ca design system</a></h3>
        <p>Latest changes to the design system, templates and patterns, style guide and other tools</p>
      </section>
    </div>
    <div class="col-lg-4 col-md-6">
      <section>
        <h3><a href="latest-changes.html">Latest changes to the Canada.ca design system</a></h3>
        <p>Latest changes to the design system, templates and patterns, style guide and other tools</p>
      </section>
    </div>-->
	</div>
	<h2>Find guidance</h2>
	<table class="wb-tables table table-striped " data-wb-tables="{ &quot;paging&quot;: true, &quot;info&quot;: true  }">
		<thead>
			<tr>
				<th>Name</th>
				<th>Source</th>
				<th>Description</th>
			</tr>
		</thead>
	</table>
</section>
