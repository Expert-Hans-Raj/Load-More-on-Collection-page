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



# after done these process open theme .liqued & copy my code & paste.
Screenshot:-  https://prnt.sc/Jbp0pzhT1Ciw

#short Code:- 

<script> document.addEventListener("DOMContentLoaded", function() {
          var endlessScroll = new Ajaxinate({
        container: '#product-grid',
        pagination: '.infinite_next',
});
        }); </script>
        
        
        #and then click on save button.

Demo Url:- https://janstowelstore.myshopify.com/collections/all
Demo Url:- https://budayalife.myshopify.com/collections/all
