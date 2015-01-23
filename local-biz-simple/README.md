
###Simple Local Business Chunk

 - http://schema.org/LocalBusiness
 
Chunk Name `schema_local_biz`

```
<div itemscope itemtype="http://schema.org/LocalBusiness">
  <p><span itemprop="name"><strong>[[+name]]</strong></span></p>
  [[+description:notempty=`<span itemprop="description">[[+description]]</span>`]]
  <div itemprop="address" itemscope itemtype="http://schema.org/PostalAddress">
  <p>
	<span itemprop="streetAddress">[[+address]]</span><br>
    <span itemprop="addressLocality">[[+city]]</span>, <span itemprop="addressRegion">[[+state]]</span> [[+zip]]
  </p>	
  </div>
  <p>Phone: <span itemprop="telephone">[[+phone]]</span></p>
</div>
```

Call on page `[[$schema_local_biz@schema_local_biz`]]
