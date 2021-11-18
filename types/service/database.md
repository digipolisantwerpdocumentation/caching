# Service caching met Redis

<img src="../../images/service.png"/>

Een service kan er voor kiezen om eigen (**primaire**) data, of een aggregatie van (**secundaire**) data uit achterliggende services, te cachen. In geval van primaire data kan dit voordelig zijn om de performance te verhogen, of de load op de primaire database te verlagen. In geval van secundaire data, kan dit naast performance ook resiliency en high availability ten goede komen.

