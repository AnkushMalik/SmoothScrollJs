All internal links would scroll Smoothly.

Usage : 

Include the js file
```
<script type="text/javascript" src="smoothScroll.js"></script>
```

Add this script after the body load. Ideally one may add this just before the closing of body tag.

```  
<script type="text/javascript">
        smooth_scroll.init();
</script>
```

If there is a fixed header, pass the id of fixed header as config.

```
<script type="text/javascript">
        smooth_scroll.init({
            header_id : "page-header"
        });
</script>


```

