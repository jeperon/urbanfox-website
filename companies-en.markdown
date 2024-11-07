---
layout: page
title: Companies
permalink: companies
lang: en
page_id: companies
---

Below is a list of companies I worked for:

{% for company in site.companies %}
- **[{{ company.name }}]( {{ company.url }} )**
    - **Location:** {{ company.location }}
    - **Industry:** {{ company.industry }}
    - **Website:** [{{ company.website }}]({{ company.website }})
{% endfor %}
