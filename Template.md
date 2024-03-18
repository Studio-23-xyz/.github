<%- await embed(`example-base-pdf`, {base:"activity, community, repositories"}) %>
___

<%- await embed(`example-languages-pdf`, {languages:true, languages_details:"percentage, bytes-size", config_display:"large"}) %>
___

<%- await embed(`example-isocalendar`, {isocalendar:true, isocalendar_duration:"full-year", config_display:"large"}) %>

___

<%- await include(`partials/activity.ejs`) %>
