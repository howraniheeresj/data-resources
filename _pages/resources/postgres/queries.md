---
title: Queries
layout: page
navtitle: Postgres Queries
---

There are 4 basic types of queries:

`SELECT` queries read data.

{% highlight sql %}
SELECT * FROM detroit_council_districts  
{% endhighlight %}


`UPDATE` queries change data in a table.

{% highlight sql %}
UPDATE detroit_council_districts
SET council_member = 'Megatron'
WHERE district_number = 2;
{% endhighlight %}


`INSERT` queries add new rows to a table.

{% highlight sql %}
INSERT INTO
detroit_council_districts (district_number, council_member) -- columns
VALUES (8, 'Megatron');                           -- values must match
{% endhighlight %}

`DELETE` queries permanently delete data from a table.

{% highlight sql %}
DELETE FROM detroit_council_districts
WHERE
{% endhighlight %}
