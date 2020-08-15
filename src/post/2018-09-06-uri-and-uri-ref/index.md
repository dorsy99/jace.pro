---
title: "What's the difference between ${URI} and ${URI_REF}"
subtitle: ""
summary: ""
date: 2018-09-06T20:25:56-05:00
---

All this talk about notifications had me poking around and I just
learned about using `${URI_REF}` instead of `${URI}`. It's magical.

-   `${URI_REF}` creates a link to the current record using the records
    display value. So it's essentially... the same as;

    ```js
    var url = 'https://' + gs.getProperty('instance_name') + '.service-now.com/';
    url += current.getLink();
    template.print('<a href="' + url + '">' + current.getDisplayValue() + '</a>');
    ```

-   `${URI}` creates a link to the current record using the text "Link".
