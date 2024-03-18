[Studio-23](http://studio-23.xyz/)   represents the Game team of  [Brainstation-23](https://brainstation-23.com/) 

We joined GitHub on `{{ f.date(REGISTRATION_DATE, {date:true}) }}`.
We contributed to `{{ REPOSITORIES_CONTRIBUTED_TO }}` repositories and made `{{ COMMITS }}` commits.


<%- await embed(`base-pdf`, {base:"activity, community, repositories"}) %>
___

<%- await embed(`languages-pdf`, {languages:true, languages_details:"percentage, bytes-size", config_display:"large"}) %>
___

<%- await embed(`isocalendar`, {isocalendar:true, isocalendar_duration:"full-year", config_display:"large"}) %>


