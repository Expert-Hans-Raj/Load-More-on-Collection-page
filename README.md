# Load-More-on-Collection-page
# Edit theme code & then find "main-collection-product-grid"
and add then dind "<script src="{{ 'facets.js' | asset_url }}" defer="defer"></script>" and add below "ajaxinate file" .<script src="{{ 'ajaxinate.min.js' | asset_url }}" defer="defer"></script>

Screenshot:- https://prnt.sc/KbBrYRArwQiq


#Find "pagination" and comment pagination and copy the shot code & paste here.

# Short Code:- 
<div class="infinite_next">
{% if paginate.next %}
<a href="{{ paginate.next.url }}">Load More...</a>
{% endif %}
</div>


Demo Url:- https://janstowelstore.myshopify.com/collections/all
Demo Url:- https://budayalife.myshopify.com/collections/all
