{% include teste.html %} 
  <body> 
{% capture includeGuts %}
{% include teste.html %} 
{% endcapture %}
{{ includeGuts | replace: '    ', ''}}
</body>
