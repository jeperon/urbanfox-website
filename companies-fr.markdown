---
# Disabled while polyglot is not supported by github pages
#layout: page
layout: null
title: Entrepries
permalink: companies
lang: fr
page_id: companies
---

Ci-dessous une liste d'entreprises pour lesquelles j'ai travaillé :

{% for company in site.companies %}
- **[{{ company.name }}]( {{ company.url }} )**
    - **Location:** {{ company.location }}
    - **Industry:** {{ company.industry }}
    - **Website:** [{{ company.website }}]({{ company.website }})
{% endfor %}
