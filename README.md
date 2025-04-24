# My personal website

This is the source for my personal website at [friesenegger.xyz](https://friesenegger.xyz).

It uses the amazing al-folio jekyll theme, check [here](https://github.com/alshedivat/al-folio) if you want to use it too. It is hosted for free using github-pages.

## My changes to the theme

I modified [\_includes/resume/languages.liquid](_includes/resume/languages.liquid) to be able to use emojis as icons for languages in my resume.

```diff
<div class="list-groups">
  {% for content in data[1] %}
    <div class="list-group col-md-6">
      <table class="table-cv list-group-table">
        <tbody>
          <tr>
            {% if content.icon %}
-              <td class="list-group-category-icon">
-                <i class="{{ content.icon }}"></i>
-              </td>
+              {% if content.icon[0] == 'f' %}
+                <td class="list-group-category-icon">
+                  <i class="{{ content.icon }}"></i>
+                </td>
+              {% else %}
+                <td class="list-group-category-icon">
+                  {{ content.icon }}
+                </td>
+              {% endif %}
            {% else %}
              <td class="list-group-category-icon"></td>
            {% endif %}
```

## How to update to the latest template release

1) Make sure you have synced the local version of your website repo to be up-to-date with Github.
2) Download the latest [al-folio release](https://github.com/alshedivat/al-folio/releases/latest) and unpack it locally.
3) Install [meld](https://meldmerge.org/), start it and select two folders to compare: the local repo and the template folder.
4) Merge template changes into your repo, look out to keep your modifications.
5) Commit your changes and push to origin.
